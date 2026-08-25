# Changelog
Todos los cambios notables en este proyecto serán documentados en este archivo.

El formato está basado en [Keep a Changelog](https://keepachangelog.com/es-ES/1.0.0/) y este proyecto se adhiere a [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.5.2] - 2026-08-24

### Motor de Ingesta Léxica y Normalización Heurística de Guiones (v2.3)
- **Normalizador Heurístico Inteligente (`ScreenplayHeuristicNormalizer`):** Pre-procesador de alto rendimiento para texto plano, PDF y archivos de guion. Auto-corrige encabezados de escena rotos o en minúsculas (ej. `int. habitacion - noche` $\to$ `INT. HABITACION - NOCHE`), transiciones inline sin salto de línea (`CORTE A: INT. ...`), saltos de línea de personajes no canónicos y diálogos comprimidos antes de la tokenización léxica.
- **Triaje Ontológico Zero-Shot & Extracción IA (`useAIExtraction` / `AIExtractionModal`):** Extracción semántica automática de personajes y locaciones desde encabezados y cuerpos de escena en la importación masiva. Modal interactivo de triaje con selección, fusión y aprobación de entidades previa a la inserción en memoria (`entityOrchestrator`), con bypass transparente en tests y modo silencioso.
- **Detección Dinámica de Marcadores Temporales:** Identificación y almacenamiento de marcadores de tiempo desconocidos en sluglines (`uiStore.pendingTimeTerms`) para catalogación y triage contextual.
- **Soporte Drag & Drop Multi-Formato:** Integración de arrastrar y soltar nativo en Tauri para `.fdx`, `.fountain`, `.canvas` y `.txt` con feedback visual interactivo de estado de procesamiento (`processingStrategy`).

### Pipeline Unificado de Exportación Profesional (PDF, FDX, Fountain, Markdown, CSV)
- **Compilador PDF Cinematográfico (`pdfExporter.ts`):** Generación de PDFs con portada profesional configurable (`TitlePageModel`: título, autor, crédito, fecha, datos de contacto y copyright), tipografía estándar Courier 12pt con interlineado estricto de 4.3mm, márgenes reglamentarios de 1 pulgada y numeración de escenas/páginas.
- **Exportadores Especializados de Guion y Producción:** Emisión estructurada en Final Draft FDX (`fdxExporter.ts`), Fountain canónico (`fountainExporter.ts`), Markdown (`markdownExporter.ts`) y hojas de cálculo CSV (`csvExporter.ts` / `csvBreakdownExporter.ts`).
- **Asistente de Exportación Multi-Paso (`ExportWizard`):** UI optimizada con previsualización contextual de portada, opciones de numeración, soporte bilingüe i18n (es/en) y discriminación inteligente de intención de exportación (`ExportIntent`).

### Estabilización de Tipado, Concurrencia y Linter (Zero Errors / Zero Warnings)
- **Corrección de Ejecutores de Promesas:** Eliminación del error de linter `no-async-promise-executor` en ejecutores de `new Promise` en `beatActions.ts`.
- **Tipado Estricto de Ingesta y Triaje:** Tipado exhaustivo con `ScriptImportInput`, `ScriptImportStructure`, `FountainStructure` y `AIExtractionTriageEntity`, suprimiendo todos los casteos `any` en la capa de acciones, modales y stores.
- **Configuración Limpia de Linter:** Reglas de `@typescript-eslint/no-unused-vars` configuradas con `argsIgnorePattern: "^_"` y `varsIgnorePattern: "^_"` y purga de directivas `eslint-disable` redundantes.
- **Suite de Pruebas Unitarias:** 100% de tests unitarios (57/57) pasando en Vitest y compilación TypeScript limpia (`tsc --noEmit` exit code 0).

---

## [0.5.1] - 2026-08-23

### Restauración de Texto Original y Bulldozer Espacial 2D
- **Módulo Canónico de Restauración (`restoreSceneOriginalText`):** Unificación bajo el principio DRY de la lógica de restauración de escenas en `beatActions.ts`, erradicando duplicaciones previas entre `SceneInspector.tsx` y `FossilWidget.tsx`.
- **Marea Cronológica y Herencia de Posición 2D:** Al restaurar una escena ("Mega-Acción"), la nueva acción hereda con precisión la posición espacial del primer hijo desglosado. Se dispara automáticamente el motor `applyBulldozer` en coordenadas `(x, y)` para empujar físicamente y de forma determinista cualquier acción circundante o en Sandbox, erradicando superposiciones en el lienzo 2D.
- **Filtrado Determinista y Despacho Atómico O(K):** Reemplazo de anti-patrones de comparación por marcas de tiempo por una heurística de filtrado determinista basada en el desplazamiento real de coordenadas `(x, y)`, garantizando un payload mínimo y seguro en `applyStructuralChange`.
- **Topología 1D y Sincronización Inmediata del Manuscrito:** Inyección estricta del nuevo identificador en `store.blockIds` (`reorder`) respetando la pureza reactiva 1D, garantizando que el editor y el manuscrito rendericen la acción restaurada instantáneamente sin requerir ciclos de recarga o Undo/Redo.

### Sincronización Manuscrito / Editor y Prevención de Pérdida de Desgloses IA
- **Guardia de Diffing de Eliminación (`isDocDirty`):** Incorporación del flag de control `{ isDocDirty }` en `reconcileTiptapToZustand` (`reconciliationEngine.ts`). Previene que interacciones pasivas o eventos de desenfoque (`blur`) eliminen accidentalmente acciones de la memoria Zustand (tales como acciones recién desglosadas por la IA o añadidas externamente).
- **Heurística de Diffing Híbrido O(N) y Echo Cancellation:** Refactorización de `ScriptWorkspace.tsx` para comparar simultáneamente la topología de IDs (`storeIds` vs `tiptapIdsStr`) y el contenido textual (`storeText` vs `currentText`), suprimiendo ciclos de renderizado redundantes y preservando el frame budget.
- **Atomicidad en el Historial de Edición:** Corrección en el pipeline de Undo/Redo en el manuscrito mediante la captura estructurada de snapshots (`captureStructuralSnapshot`) previa a la mutación en Zustand (`reconcile` y `reconcile_blur`), garantizando un historial de deshacer cronológicamente consistente.

### Pipeline de Ingesta Léxica (Fountain y Final Draft FDX)
- **Unificación y Saneamiento de Modelos de Ingesta:** Eliminación de la acumulación manual y redundante de `actionLines` en `fountainService.ts` y `fdxParser.ts`. Ahora `buildFountainTextForScene` actúa como SSOT generando directamente el texto de la escena (`fountainText`), consumido unificadamente por el bloque 1D (manuscrito) y el contenido base 2D (acciones).
- **Normalización de Sinopsis y Metadatos:** Saneamiento en `importScriptMegabeats` y `fountainExtractorAction.ts` para extraer texto sin prefijos no deseados (`=`), actualizando asimismo la suite de pruebas unitarias (`fdxImport.test.ts` y `fountainService.test.ts`).

### Soporte de Modelos de Razonamiento IA
- **Detección Dinámica de Reasoning Models (OpenAI `o1` / `o3`):** En `discoveryService.ts` y `generator.ts`, se implementó la discriminación automática de modelos de razonamiento (`isReasoningModel`), suprimiendo el parámetro no soportado `temperature` en llamadas a modelos `o1` y `o3` para evitar excepciones de API y brindar compatibilidad total.

---

## [0.5.0] - 2026-08-22

### Arquitectura Narrando: Trinidad Creativa y Sincronización Suave (Soft Sync)
- **Lienzo Central de Manuscrito 1D (`ScriptWorkspace`):** Entorno de redacción literaria continua en tipografía cinematográfica estándar (Ghost Zinc / Courier Prime) basado en Tiptap/Prosemirror, con reconciliación bidireccional en tiempo real con el estado de la aplicación.
- **Tablero Causal 2D (Escaleta Espacial):** Espacio bidimensional para la secuenciación dramática, modulación de la curva de tensión, estructuración en Actos/Secuencias y encadenamiento causal entre acciones.
- **Lienzo Ontológico (El SER):** Modelado conceptual atemporal de universos narrativos, personajes, locaciones, facciones, arquetipos y grafos de relaciones.
- **Paradigma Soft Sync (Sincronización Suave):** Coexistencia armónica entre la dimensión 1D y el espacio 2D sin bloqueos mutuos; la verdad narrativa temporal reside en el manuscrito (`fountainText`) y la verdad causal/dramática en las acciones espaciales vinculadas por topología (`parentId`).

### Sistema Quad-Dock de Paneles Modulares
- **Paneles Acoplables de Productividad:** Integración de interfaz de 4 puertos modulares (Norte, Sur, Este, Oeste) que alojan el **Inspector de Escena**, **Fossil Widget** (visualizador y restaurador de texto original 1D), **Script Doctor** (diagnóstico asistido) y **Scratchpad** (notas marginales acausales).
- **IntelliSense y Autocompletado:** Detección contextual de encabezados de escena (sluglines), personajes y entidades durante la escritura.

### Motor Léxico e Ingesta de Formatos Estándar
- **Ingesta Nativa Fountain y Final Draft (.fdx):** Parser léxico para extracción y traducción de jerarquías de guion hacia la arquitectura relacional de Narrando, preservando notas, boneyard y formato original.
- **Zero-Shot Ontology Extraction:** Extracción semántica automática de entidades y locaciones a partir de los encabezados de escena durante la importación.

### Asistencia Narrativa con IA (Vercel AI SDK)
- **Script Doctor y Desglose Inteligente:** Análisis macroestructural y microestructural de escenas, evaluación de curvas de tensión y sugerencias narrativas mediante integración multi-proveedor (OpenAI, Anthropic, Google Gemini).
- **Backpressure y Streaming Seguro:** Manejo de flujo asíncrono con control de concurrencia y sin bloqueo de UI.

### Persistencia y Motor de Estado
- **Paradigma RAM-First y Shadow Writer (SQLite WAL):** Estado reactivo en memoria (Zustand) sincronizado de forma asíncrona hacia SQLite mediante colas no bloqueantes y serialización transaccional.
- **Time Machine (Historial Multinivel):** Captura atómica de snapshots estructurales (`captureStructuralSnapshot`) con soporte completo de Undo/Redo bidireccional.
