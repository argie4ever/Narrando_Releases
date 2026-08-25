# Manual de Usuario Oficial — Narrando v0.5
### Guía Integral de Creación, Estructura, Guion y Preproducción Cinematográfica

Bienvenido a **Narrando (v0.5)**, el entorno de autoría cinematográfica y diseño narrativo concebido para dar soporte a todo el ciclo de vida de una historia: desde el primer chispazo de una idea hasta la entrega del guion literario definitivo y el desglose ejecutivo de preproducción.

Este manual ha sido redactado pensando en **guionistas, novelistas, showrunners, directores y productores**. A lo largo de sus páginas descubrirá cómo articular el universo de su obra, modular el ritmo y la tensión del relato, escribir de forma continua y fluida, y auditar con precisión quirúrgica cada elemento dramático y logístico de su proyecto.

---

# PARTE I: FUNDAMENTOS Y ENTORNO DE TRABAJO

---

## 1. La Filosofía Narrando: SER, DEVENIR y MANUSCRITO

La mayoría de las herramientas de escritura obligan al autor a elegir entre dos extremos limitantes: un documento de texto rígido donde la visión de conjunto se pierde, o un tablero de tarjetas aisladas donde se disuelve la fluidez literaria. 

**Narrando** resuelve esta fragmentación mediante una trinidad creativa sustentada en el paradigma de **Sincronización Suave**:

* **🌌 EL SER (Dominio de la Existencia — Ontología & Lore):** El mapa conceptual y atemporal del universo narrativo. Aquí residen los personajes, las locaciones, los objetos clave, las facciones y las dinámicas vinculares.
* **⚡ EL DEVENIR (Dominio de la Secuencia — Tablero Causal 2D):** El espacio temporal donde los hechos ocurren cronológicamente. Gobierna el encadenamiento causa-efecto, la escaleta, la estructura de Actos y Secuencias, y la modulación de la curva de tensión.
* **✍️ EL MANUSCRITO (Dominio de la Escritura — Lienzo Central 1D):** La redacción literaria continua en tipografía cinematográfica estándar. Permite escribir diálogos, acciones y sluglines con fluidez y foco.

> 📌 **Nota — El Principio de Sincronización Suave:** Lo que escribe en el Manuscrito informa automáticamente a la Escaleta; lo que reorganiza en el Tablero Causal reordena el Manuscrito; y las entidades creadas en el mundo quedan inmediatamente disponibles para ser invocadas durante la redacción. Ninguna capa entorpece a la otra.

### 1.1. EL SER: El Dominio de la Existencia (Ontología y Worldbuilding)
El dominio del **SER** es el mapa conceptual de su universo, libre de la tiranía del orden cronológico. Aquí es donde habitan sus personajes, las locaciones, los objetos clave, las facciones políticas y las dinámicas vinculares. 
* En este espacio, las entidades existen por sí mismas y se entrelazan mediante relaciones lógicas (familiares, jerárquicas, geográficas o emocionales).
* Le permite diseñar la "Biblia" de su proyecto antes, durante o después de estructurar la trama.

### 1.2. EL DEVENIR: El Dominio de la Secuencia Temporal y la Causalidad
El dominio del **DEVENIR** es el espacio donde los acontecimientos ocurren en el tiempo.
* Gobierna el encadenamiento causa-efecto: cómo una decisión en la escena inicial desencadena una crisis en el clímax.
* Es el territorio de la **escaleta**, la distribución en **Actos y Secuencias**, y la modulación de la **Curva de Tensión Dramática**.
* Cada elemento aquí es una **Acción**: la unidad mínima de transformación dramática.

### 1.3. EL MANUSCRITO: El Dominio de la Escritura Literaria Continua
El **MANUSCRITO** es el lienzo donde la historia se lee y se siente como obra terminada.
* Ofrece un entorno de redacción pura con tipografía cinematográfica profesional basada en estándares industriales.
* Permite concentrarse en la poesía de la acción, la cadencia de los diálogos y la atmósfera de las escenas, mientras el sistema mantiene sincronizada la estructura de fondo.

---

## 2. El Portal de Proyectos y Configuración Inicial

El acceso y administración de sus proyectos se realiza a través de la pantalla de bienvenida o **Portal de Proyectos**, diseñado para garantizar la seguridad, autonomía e integridad de sus archivos.

El portal se organiza en dos columnas claras y un selector de idioma superior:

1. **Columna de Creación (Nuevo Proyecto):**
   * Formulario para registrar el **Título del Proyecto** y el **Autor / Creador**.
   * Al pulsar **Crear Proyecto**, el explorador de archivos le permite elegir la ubicación en su disco para guardar el archivo maestro **`.escx`**.
   * El sistema inicializa un proyecto limpio y registra automáticamente una instantánea segura llamada **Génesis** en la Bóveda del Tiempo.

2. **Columna de Gestión (Proyectos Existentes y Recientes):**
   * **Abrir Archivo Local:** Abre cualquier archivo `.escx` existente en su equipo. Narrando no requiere conexión obligatoria a internet ni almacena sus guiones en servidores externos; su obra reside 100% en su máquina.
   * **Historial de Proyectos Recientes:** Lista de acceso directo a los últimos trabajos editados.
   * **Duplicar Proyecto (📋):** Opción de acción rápida junto a cada proyecto reciente que crea una copia física exacta en disco con su nombre interno actualizado, ideal para crear versiones alternativas antes de grandes reescrituras.

3. **Selector de Idioma:**
   * Menú en la esquina superior derecha para alternar instantáneamente toda la interfaz entre **Español (🇪🇸 ES)** e **Inglés (🇺🇸 EN)**.

---

## 3. Anatomía de la Interfaz: Barra Superior y Navegación

La barra de herramientas superior (**Toolbar**) cruza horizontalmente la parte superior de la pantalla y centraliza todos los comandos de navegación y control organizados en tres bloques funcionales:

### 3.1. Bloque Izquierdo: Estado y Búsqueda
* **LED de Persistencia Silenciosa (`● IDLE` / `● SAVE`):** Muestra **IDLE** en verde cuando todos sus cambios están a salvo en el disco, y **SAVE** en ámbar de forma intermitente cuando está guardando silenciosamente en segundo plano sin interrumpir su trabajo.
* **Buscador Universal (`Ctrl + F`):** Filtra en tiempo real todas las acciones, escenas y menciones de personajes en cualquiera de los lienzos activos.

### 3.2. Bloque Central: Espacios de Trabajo y Visibilidad
* **Conmutador de Vistas Principales (Workspace Switcher):**
  - **MANUSCRITO:** Vista prioritaria de texto continuo para redacción literaria.
  - **TABLERO (DEVENIR):** Lienzo espacial 2D de acciones, conexiones causales y escaleta.
  - **ONTOLOGÍA (SER):** Lienzo relacional de worldbuilding, personajes y locaciones.
  - **DUAL:** División de pantalla horizontal para trabajar en paralelo (Tablero arriba, Ontología abajo) con divisor arrastrable.
* **Interruptores de Paneles Auxiliares:**
  - Botones de acceso rápido para mostrar u ocultar el **Editor Lineal** (panel izquierdo), el **Inspector** (panel derecho) y la **Línea de Tiempo** (panel inferior).

### 3.3. Bloque Derecho: Control, IA, Producción y Ajustes
* **Historial y Rayos X (`X-Ray`):** Flechas de **Deshacer (`Ctrl + Z`)** y **Rehacer (`Ctrl + Shift + Z`)**, acompañadas del menú **X-Ray** para retroceder con precisión a micro-operaciones específicas.
* **Bóveda del Tiempo (`⏱ Time Machine`):** Centro de versiones, puntos de control e instantáneas protegidas.
* **Asistentes de IA:** Acceso directo a **🩺 Script Doctor** (auditoría de tensión) y **✨ Desglose Asistido**.
* **Machina Analytica (`📊`):** Panel de estadísticas, sábanas de desglose y planillas de rodaje.
* **Asistente de Exportación (`📥 Exportar`):** Exportador guiado en 3 pasos para formatos estándar de la industria.
* **Interruptor de Ayuda (`💡 Tooltips`):** Activa o desactiva las tarjetas explicativas contextuales en toda la interfaz.

---

## 4. El Sistema Quad-Dock: Paneles Modulares y Widgets

A los laterales de la pantalla, Narrando incorpora el sistema **Quad-Dock**: cuatro cuadrantes modulares configurables (izquierdo superior/inferior y derecho superior/inferior) que le permiten adaptar su mesa de trabajo exactamente a la tarea que esté realizando.

Cada cuadrante dispone de un selector desplegable en su cabecera para intercambiar instantáneamente su herramienta activa entre los siguientes **8 Widgets Especializados**:

| Widget | Función Primaria | Caso de Uso Ideal |
|---|---|---|
| **Marginalia & Notas** | Scratchpad de notas al margen acausales y atemporales. | Apuntar ideas repentinas, recordatorios de reescritura o comentarios de producción sin alterar la escaleta ni la duración. |
| **Inspector Lite** | Vista compacta de propiedades de la acción o escena seleccionada. | Ajustar el valor de tensión dramática (0 a 100) y asignar personajes de forma rápida mientras se redacta. |
| **Editor Lineal** | Lista vertical continua de escenas y acciones con tiradores de arrastre. | Reordenar la cronología general del relato arrastrando y soltando bloques verticalmente. |
| **Librería de Entidades** | Catálogo organizado de personajes, locaciones, objetos y facciones. | Consultar biografías y arrastrar elementos hacia el tablero o el manuscrito. |
| **Machina Analytica** | Telemetría en tiempo real de proporciones, densidad y balance Día/Noche. | Evaluar el ritmo de la escena activa mientras se escribe. |
| **Script Doctor Widget** | Panel de advertencias cualitativas y cuantitativas de la IA. | Ver avisos de caídas de tensión y hacer clic en *"Enfocar"* para ir directamente a la escena en cuestión. |
| **Texto Original (Fossil)** | Visor de solo lectura del texto fuente original importado. | Consultar el material original de una escena adaptada y restaurarlo con un clic si se descarta una versión. |
| **Sandbox (Boneyard)** | Repositorio de acciones apartadas o en pausa de la escena activa. | Conservar descartes y variantes de una escena sin que afecten la línea de tiempo. |

> 💡 **Consejo:** Cada lateral del Quad-Dock cuenta con una pestaña exterior que permite colapsar o expandir el panel completo con un solo clic o atajo, liberando el 100% del ancho de pantalla para la escritura inmersiva.

---

# PARTE II: LOS TRES LIENZOS CREATIVOS

---

## 5. El Tablero Causal (DEVENIR)

El **Tablero Causal (DEVENIR)** es el lienzo bidimensional infinito donde se articulan y visualizan los acontecimientos de su historia. En este espacio, la narrativa se comporta como una estructura plástica y relacional.

Cada tarjeta en el tablero representa una **Acción Dramática**, mostrando su número correlativo de escena, su sinopsis o cuerpo de texto, su nivel de **Tensión Dramática (0 a 100)** y su botón de **Modo Sandbox (⏸)**. Las tarjetas se conectan mediante líneas causales direccionales que trazan las cadenas de consecuencias del relato.

### 5.1. La Unidad Atómica: La Acción
Una **Acción** es la unidad mínima de transformación dramática en Narrando. No es un mero bloque de texto, sino un acontecimiento con carga dramática, duración estimada y consecuencias sobre el resto del relato.

Existen tres formas directas de crear una Acción:
1. **Botón "+ Acción" de la barra superior:** Inserta una nueva acción en la primera posición disponible de la escaleta cronológica.
2. **Menú Contextual (Clic derecho sobre el lienzo):**
   * **Crear en Sandbox:** Genera una acción libre y flotante, ideal para anotar ideas que aún no tienen un lugar definido en la cronología.
   * **Crear Ordenado:** Inserta una acción directamente integrada a la escaleta en la coordenada espacial donde hizo clic.
3. **Atajo de Teclado (`Ctrl + N`):** Invoca instantáneamente una nueva acción subordinada a la escena activa.

### 5.2. El Modo Sandbox (Acciones en Pausa y Variantes)
Cada tarjeta de acción cuenta en su cabecera con el botón **Sandbox (⏸)**. Al activarlo:
* La acción pasa al estado "libre" o "en pausa": se desvincula temporalmente de la escaleta secuencial, desaparece de la Curva de Tensión en la Línea de Tiempo y no se incluye en el conteo de duración del guion.
* **Casos de Uso del Sandbox:**
  - Preservar diálogos o giros alternativos sin borrarlos.
  - Guardar escenas tentativas durante sesiones de lluvia de ideas.
  - Dejar en reserva subtramas que requieren maduración.
* **Reincorporación:** Para devolver una acción del Sandbox al flujo activo, basta con pulsar nuevamente el botón **Sandbox**; el sistema la reinsertará de forma automática en la posición cronológica que le corresponda por su ubicación en el tablero.

### 5.3. La Ley de Expansión Natural
Para evitar el desorden visual y la superposición caótica de tarjetas cuando una historia crece a decenas o cientos de escenas, el motor espacial de Narrando aplica la **Ley de Expansión Natural**:
* Al arrastrar o agrandar una tarjeta de acción verticalmente en una columna, el sistema detecta de forma automática si colisionará con elementos inferiores.
* Si existe riesgo de contacto, **empuja suavemente hacia abajo** a todas las acciones y grupos ubicados por debajo de esa coordenada.
* Este empuje es estrictamente unidireccional (hacia abajo, en el eje Y positivo) y en cascada, garantizando que sus columnas nunca colapsen ni se encimen, preservando siempre un espacio limpio para nuevas inserciones.

### 5.4. Conexiones Causales y Relaciones de Trama
En el Tablero Causal, los acontecimientos se conectan arrastrando líneas desde los conectores circulares (*handles*) situados en los bordes de cada tarjeta:
* **Trazado de Aristas:** Conecte la tarjeta A con la tarjeta B para indicar que el suceso A es el detonante causal del suceso B.
* **Inspector Flotante de Relaciones:** Al hacer clic sobre cualquier línea de conexión, se despliega un popover arrastrable donde podrá:
  - Asignar una etiqueta descriptiva (ej. *"Detonante"*, *"Consecuencia directa"*, *"Ironía dramática"*, *"Subtrama paralela"*).
  - Modificar el color de la línea para codificar visualmente diferentes líneas argumentales o arcos de personajes.
  - Eliminar el enlace sin alterar las tarjetas conectadas.

### 5.5. Grupos de Escenas y Selección Múltiple
Al seleccionar múltiples acciones (mediante recuadro de arrastre o `Shift + Clic`) y hacer clic derecho, accederá a herramientas colectivas:
* **Agrupar:** Envuelve las acciones seleccionadas en un contenedor visual con marco sombreado y título editable. Al mover el grupo desde su cabecera, todas sus acciones hijas se desplazan solidariamente.
* **Categorización por Color:** Asigna simultáneamente uno de los 8 colores de la paleta del proyecto a todas las tarjetas seleccionadas.
* **Eliminación Unificada:** Permite elegir entre *Desagrupar* (mantener las acciones intactas en su posición eliminando solo el marco) o *Eliminar* (borrar el conjunto de la escaleta).

---

## 6. El Lienzo de Ontología (SER)

El dominio del **SER** es el espacio donde reside la construcción de mundo (*worldbuilding*), la red relacional y la mitología de su historia.

En este lienzo, los elementos del universo (personajes, locaciones, objetos clave, facciones y conceptos) se representan como nodos interactivos conectados mediante relaciones lógicas y vínculos temáticos.

### 6.1. Entidades y Arquetipos
En el Lienzo de Ontología, los componentes de su universo se presentan como tarjetas interconectadas clasificadas bajo 5 grandes arquetipos:
* **👤 Personajes:** Protagonistas, antagonistas, secundarios y figuras del coro dramático.
* **📍 Locaciones:** Sets principales, escenarios ficticios, interiores y exteriores.
* **📦 Objetos:** Elementos narrativos clave (*MacGuffins*, armas, documentos, reliquias).
* **🏛️ Facciones:** Organizaciones, familias, corporaciones o clanes.
* **🏷️ Conceptos / Etiquetas:** Temas centrales, arcos emocionales o códigos simbólicos.

### 6.2. La Ficha de Entidad Inmersiva
Al hacer doble clic sobre cualquier entidad (en el lienzo o en la biblioteca lateral), se despliega la **Ficha de Entidad**, un espacio exhaustivo de diseño y caracterización:
* **Títulos Polimórficos:** El panel descriptivo adapta su lenguaje automáticamente al tipo de elemento (*"Biografía"* para Personajes, *"Descripción del Entorno"* para Locaciones, *"Características Físicas"* para Objetos).
* **Aliases y Sobrenombres:** Registro de nombres alternativos (ej. *"El Forastero"*, *"Doc"*, *"Comisaría Central"*) que el sistema utilizará para reconocer a la entidad en el autocompletado y en los análisis automáticos de texto.
* **Atributos Personalizados:** Campos clave/valor dinámicos para consignar edad, profesión, objetivos, debilidades o coordenadas.
* **Registro de Apariciones Cruzadas:** Muestra la lista completa de escenas donde participa la entidad. Si una escena no tiene título, el sistema genera una referencia descriptiva inteligente basada en su primera acción.

### 6.3. Hiper-Navegación Espacial
Narrando elimina las barreras entre el diseño del universo y la redacción:
* Al hacer clic sobre cualquiera de las escenas listadas en la sección de **Apariciones** de la Ficha de Entidad, el modal se cierra y la cámara **vuela de forma animada** para centrar y enfocar esa escena exacta en el Tablero Causal o en el Manuscrito.
* Si se encuentra en la vista de Ontología pura, el sistema activará automáticamente el modo **DUAL** para que pueda ver la escena en el tiempo sin perder de vista la perspectiva relacional.

### 6.4. Fusión de Entidades (Resolución de Duplicados)
Si durante la escritura o importación se crearon entidades redundantes (ej. *"Víktor"* y *"Víktor Petrov"*):
1. Seleccione las entidades a unificar en la biblioteca o lienzo y pulse **Fusionar Entidades**.
2. Designe cuál será la **Entidad Principal**. Ésta conservará su nombre, arquetipo y descripción.
3. El sistema transferirá todas las apariciones, diálogos y conexiones causales de las entidades secundarias hacia la principal, eliminando los duplicados de forma completamente segura.

### 6.5. Gestor de Taxonomía de Colores
Accesible desde la barra de herramientas del SER, el **Gestor de Etiquetas de Color** le permite renombrar y redefinir el significado narrativo de los 8 colores del sistema (por ejemplo, asignar el Azul a *"Subtrama Romántica"*, el Rojo a *"Peligro/Conflicto"* o el Verde a *"Facciones del Norte"*).

---

## 7. El Lienzo de Manuscrito

El **Lienzo de Manuscrito** es el corazón literario de Narrando: un espacio de escritura continua donde el guion se desenvuelve como un documento profesional con tipografía cinematográfica estándar.

En la cabecera del editor, una barra flotante reúne las herramientas de enfoque literario: el selector de numeración de escenas (`# Escenas`), el filtro de **Foco Léxico**, el selector de **Aislamiento de Elenco (Cast Focus)** y el contador dinámico de escenas y acciones.

### 7.1. Tipografía y Estándares Cinematográficos
El manuscrito opera bajo la sintaxis y tipografía estándar de la industria cinematográfica internacional (Courier Prime de ancho fijo). Cada elemento estructural (encabezados de escena, descripciones de acción, nombres de personaje, acotaciones parentéticas, diálogos y transiciones) se formatea con sangrías y márgenes automáticos.

### 7.2. Autocompletado Inteligente (IntelliSense)
Mientras redacta, Narrando asiste su velocidad de escritura sin necesidad de tocar el ratón:
* **Sluglines Automáticos:** Al escribir las primeras letras de una línea, el sistema sugiere prefijos de encabezado (`INT.`, `EXT.`, `INT/EXT.`, `EST.`). Presionar **Tab** autocompleta el prefijo de inmediato.
* **Términos Temporales:** Tras definir la locación y tipear un guion, el sistema despliega términos canónicos (`DÍA`, `NOCHE`, `AMANECER`, `ATARDECER`, `CONTINUO`).
* **Ingesta Silenciosa de Términos:** Si escribe un término temporal no convencional (ej. *"MADRUGADA"*, *"HORA DORADA"*), el sistema lo incorpora automáticamente al Diccionario del Proyecto para reconocerlo en las siguientes escenas.
* **Personajes en Diálogo:** Al escribir en mayúsculas el nombre de un personaje existente, el autocompletado lo sugiere; presionar **Enter** centra el cursor en la posición exacta del diálogo.

### 7.3. Foco Léxico (Filtros Estructurales de Lectura)
En la barra de herramientas del Manuscrito, el selector de **Foco Léxico** permite aislar visualmente capas específicas del guion:
* **Documento Completo:** Muestra la totalidad de la obra.
* **Solo Diálogos:** Oculta las descripciones de acción, permitiendo al guionista auditar el subtexto, la voz y el ritmo conversacional de corrido.
* **Solo Acción:** Oculta los diálogos para evaluar la fluidez visual, la progresión física y las imágenes de la historia.
* **Solo Encabezados:** Muestra únicamente la estructura de locaciones y tiempos (vista esqueleto).

### 7.4. Aislamiento de Elenco (Cast Focus)
Junto al foco léxico, el menú **Cast Focus** le permite seleccionar a un personaje específico (ej. *"JOHN"*).
* El manuscrito atenuará o filtrará las escenas donde el personaje no interviene y resaltará con nitidez cada una de sus líneas y acciones.
* Es una herramienta fundamental para lecturas de elenco, ensayos con actores y auditorías de coherencia en los arcos de personajes.

### 7.5. Bubble Menu Flotante (Creación de Entidades al Vuelo)
Al seleccionar cualquier palabra o frase en el cuerpo del manuscrito (por ejemplo, el nombre de un objeto nuevo como *"EL RELOJ DE BOLSILLO"*), aparecerá un menú flotante con el botón **+ Entidad**. Al pulsarlo, el sistema abrirá la ventana de creación para catalogar el elemento en el SER sin necesidad de salir del manuscrito ni interrumpir el flujo creativo.

---

# PARTE III: INTELIGENCIA Y TELEMETRÍA NARRATIVA

---

## 8. Asistentes de Inteligencia Artificial

Narrando integra asistentes de procesamiento de lenguaje natural concebidos no como generadores de texto genérico, sino como **auditores de ritmo dramático y aceleradores de tareas mecánicas**.

### 8.1. Script Doctor (Auditoría de Tensión Narrativa)
El **Script Doctor** analiza la progresión dramática completa de la obra. Al activarlo desde el botón **🩺** de la barra superior:
* Lee la secuencia de acciones cronológicas y calcula el índice de conflicto y carga emocional de cada una en una escala de 0 a 100.
* Traza de forma automática la **Curva de Tensión Dramática** en la Timeline.
* Genera un informe cualitativo y cuantitativo estructurado con observaciones sobre el ritmo del relato.
* **Streaming de Progreso y Control Total:** Durante el análisis, una ventana muestra el avance escena por escena. Si desea detener el proceso, puede pulsar **Cancelar** en cualquier momento; el sistema recuperará la interfaz al instante conservando todo el análisis completado hasta ese punto.

### 8.2. Desglose Asistido de Escenas
Al seleccionar una escena o bloque de texto complejo y presionar **Desglosar**:
* La IA segmenta los párrafos largos en múltiples acciones atómicas basadas en el principio de causa-efecto.
* Permite elegir entre tres enfoques:
  - **Modo Estructural:** Mantiene un enfoque macro ideal para resúmenes de escaleta.
  - **Modo Atómico:** Fragmentación máxima en unidades de acción puras (un verbo de transformación por tarjeta).
  - **Modo Personalizado:** Permite inyectar directivas específicas al asistente.

### 8.3. Extracción Masiva de Entidades
Al importar guiones o novelas externas, el asistente de extracción escanea el texto completo y detecta personajes, locaciones y objetos:
* **Previsualización de Coincidencias:** Muestra una lista clara de cuántas veces aparece cada término sugerido.
* **Asignación Global Inteligente:** Permite enlazar automáticamente a los personajes en todas las tarjetas de la historia donde sean mencionados, unificando mayúsculas, minúsculas y variantes sin tildes.

### 8.4. Configuración Multi-Proveedor y Privacidad
Desde el panel **Configuración de IA**:
* **Proveedores Compatibles:** Conexión nativa con Google Gemini, OpenAI, Anthropic Claude y modelos locales totalmente privados y sin conexión a internet mediante **Ollama**.
* **Seguridad:** Sus claves de API se guardan de forma encriptada en su equipo local y nunca se envían a servidores de terceros.

---

## 9. Machina Analytica & Métricas Dramáticas

El panel **Machina Analytica (📊)** proporciona una radiografía cuantitativa y estructural de su relato sin interferir en su flujo de trabajo creativo.

| Dimensión de Análisis | Indicadores Clave | Utilidad Práctica para el Autor / Productor |
|---|---|---|
| **Volumen de Obra** | Total de acciones, volumen de palabras, duración estimada. | Control de tiempos de metraje y longitud del manuscrito. |
| **Balance Ambiental** | Porcentaje de Interiores vs. Exteriores. | Evaluación de variedad visual y presupuestación de sets. |
| **Balance Temporal** | Proporción de escenas de Día vs. Noche. | Planificación de jornadas de rodaje y planes de iluminación. |
| **Curva de Conflicto** | Tensión promedio, picos máximos y valles. | Diagnóstico del ritmo y progresión dramática del argumento. |
| **Densidad de Elenco** | Presencia global, cuota relativa y foco específico. | Medición del peso real de cada personaje y balance de protagonismo. |

### 9.1. La Curva de Tensión Continua (Timeline)
Ubicada en la base de la pantalla, representa la dinámica de conflicto en coordenadas continuas:
* **Eje X (Horizontal):** El transcurso secuencial de la historia.
* **Eje Y (Vertical):** La intensidad dramática (0 a 100).
* **Bandas de Actos y Secuencias:** Franjas superiores que delimitan los grandes bloques de la obra. Al arrastrar los bordes laterales de cualquier banda con el ratón, el alcance del Acto o Secuencia se reajusta elásticamente, reasignando las escenas de su interior de forma automática.

### 9.2. Modo Termográfico (Heatmap)
Al activar el icono **🔥**, las tarjetas del Tablero Causal adoptan un degradado de color según su nivel de tensión (desde verdes fríos para momentos de descompresión hasta rojos ardientes para el clímax). Permite detectar anomalías de ritmo simplemente alejando la cámara del tablero.

### 9.3. Métricas de Densidad e Impacto
Calcula con exactitud el peso de cada elemento en la obra:
* **Presencia Global:** Porcentaje de escenas en las que participa una entidad sobre el total del guion.
* **Cuota Relativa:** Porcentaje de relevancia dentro de su propia categoría (ej. el protagonismo de un personaje secundario respecto a los demás secundarios).
* **Foco Específico:** Nivel de dominancia de la entidad en aquellas escenas donde está presente.

---

## 10. Herramientas de Producción Avanzadas

Para los equipos de producción, directores de producción y primeros asistentes de dirección (1st AD), Narrando integra herramientas que transforman el guion literario en un plan de rodaje cuantificable.

### 10.1. Sábana de Desglose (Breakdown Sheet)
Una cuadrícula exhaustiva organizada por escenas que clasifica automáticamente todos los requerimientos de producción:
* **Talento (Cast Principal):** Personajes con diálogo o acción clave.
* **Extras / Atmósfera:** Figuración y grupos de fondo.
* **Utilería (Props):** Objetos manipulados por actores.
* **Ambientación (Set Dressing):** Elementos escenográficos destacados.
* **Vestuario y Maquillaje / Pelo:** Necesidades específicas de caracterización.
* **SFX / VFX:** Efectos especiales físicos y efectos visuales digitales.
* **Sonido y Música:** Requerimientos sonoros y temas diegéticos.
* **Equipamiento Especial:** Grúas, cámaras submarinas, vehículos de escena o dobles de acción.

### 10.2. Planilla de Rodaje Day-out-of-Days (DOOD)
La matriz estándar de la industria cinematográfica para auditar las jornadas de trabajo de cada actor:
* Muestra un cronograma visual donde cada celda indica si el personaje se encuentra en día de inicio (**HOLD / WORK / DROP**).
* Permite detectar jornadas muertas entre llamados y optimizar los costos de contratación de elenco.
* Dispone de botón de **Descarga directa en CSV (⬇ CSV)** para abrir en cualquier planilla de cálculo de producción.

### 10.3. Carga de Trabajo y Tiempos de Rodaje (Workload View)
* Calcula automáticamente el número de **Páginas y Octavos de Página** por escena.
* Estima la duración de pantalla y las jornadas de rodaje recomendadas en base a la complejidad de locaciones y tamaño del elenco.

---

# PARTE IV: CONTROL DEL TIEMPO, EXPORTACIÓN Y ENTREGA

---

## 11. La Bóveda del Tiempo (Time Machine) y Persistencia

Narrando incorpora un sistema de preservación histórica diseñado para eliminar para siempre el miedo a perder trabajo o corromper una versión previa durante sesiones intensivas de reescritura.

| Estado / Tipo | Fecha y Hora | Descripción / Hito Histórico | Acción Disponible |
|---|---|---|---|
| 📌 **Protegido** | 22/08/2026 - 14:30 | Corte de Producción v1.0 | Restaurar / Renombrar |
| ⏱ **Automático** | 22/08/2026 - 11:15 | Desglose de Escenas por IA | Restaurar / Fijar con Pin |
| 📌 **Protegido** | 21/08/2026 - 18:00 | Escaleta Aprobada por Showrunner | Restaurar / Renombrar |
| ⏱ **Automático** | 20/08/2026 - 09:00 | Génesis (Punto de Partida Inicial) | Restaurar / Fijar con Pin |

### 11.1. Instantáneas Integrales (Snapshots)
A diferencia de los editores convencionales que guardan solo cambios parciales de texto, la **Bóveda del Tiempo** captura **instantáneas completas e independientes** de todo el universo del proyecto:
* Cada instantánea contiene el estado exacto del Manuscrito, el Tablero Causal, el mapa de Ontología, las notas de Marginalia y la Curva de Tensión.
* Esto garantiza que saltar a una versión previa no desincronice jamás los personajes del mundo con las escenas del relato.

### 11.2. Disparo de Instantáneas
El sistema registra instantáneas en momentos clave:
1. **Génesis:** Al crear cualquier proyecto nuevo.
2. **Hitos Estructurales:** Tras ejecutar operaciones complejas como el análisis de Script Doctor, importaciones masivas o fusiones de entidades.
3. **Guardado Manual (`Ctrl + S`):** Cuando usted decide conscientemente crear un punto de control.

### 11.3. Gestión de la Bóveda: Renombrar y Fijar (Pin)
Dentro del modal de la Bóveda (`⏱`):
* **Renombrar:** Haga clic en cualquier nombre de instantánea para asignarle una descripción clara (ej. *"Final Alternativo con Muerte del Protagonista"* o *"Versión para Fondos Concursables"*).
* **Fijar con Pin (📌):** Al marcar una instantánea con el pin, queda protegida de forma permanente contra las rutinas automáticas de limpieza de historial.

### 11.4. El Visor de Rayos X (X-Ray)
Ubicado en el Toolbar junto a las flechas de Deshacer y Rehacer, el menú **X-Ray** despliega un historial cronológico de las últimas micro-operaciones realizadas (ej. *"Cambiar título de escena"*, *"Asignar color a grupo"*, *"Vincular arista causal"*). Permite retroceder en el tiempo con precisión milimétrica a cualquier segundo previo de la sesión de trabajo.

---

## 12. El Asistente de Exportación en 3 Pasos

El **Asistente de Exportación (`📥 Exportar`)** consolida todas las vías de salida del proyecto en un proceso guiado y flexible:

> **Pipeline:** `Paso 1: Intención Dramática ➔ Paso 2: Alcance y Formato ➔ Paso 3: Metadatos y Carátula`

### 12.1. Paso 1: Selección de la Intención
Defina el objetivo principal del documento a generar:
1. **🎬 Guion Literario:** Exporta el manuscrito formateado bajo convenciones industriales estándar.
2. **📋 Escaleta Estructural:** Exporta la secuencia de escenas, sinopsis de acciones y divisiones de actos para reuniones de desarrollo.
3. **📊 Sábana de Desglose:** Genera matrices tabulares completas con todas las entidades y requerimientos para el equipo de producción.
4. **🌌 Biblia / Universo:** Exporta la enciclopedia de personajes, locaciones y facciones con esquemas de relaciones estructurados.
5. **📈 Dossier Analítico:** Genera un reporte ejecutivo con la curva de tensión, telemetría dramática y métricas de ritmo.

### 12.2. Paso 2: Alcance y Formato
* **Alcance:** Elija entre exportar la **Obra Completa** o únicamente la **Selección Actual** (ideal para imprimir solo una secuencia o un acto específico).
* **Formatos Disponibles por Intención:**
  - *Final Draft (.fdx)*: Compatible con toda la industria audiovisual.
  - *Fountain (.fountain)*: Texto plano universal para guionistas.
  - *PDF de Alta Calidad*: Listo para impresión con tipografía Courier Prime.
  - *Markdown (.md)*: Documento estructurado con esquemas de relaciones.
  - *JSON Canvas (.canvas)*: Mapeo espacial para Obsidian y herramientas de diagramación.
  - *Planillas CSV y Paquete Relacional ZIP*: Tablas estructuradas para hojas de cálculo.
  - *Gráficos PNG y SVG*: Capturas vectoriales en alta resolución de los lienzos.

### 12.3. Paso 3: Afinación de Metadatos
Personalice la presentación profesional de su entrega:
* **Carátula Profesional (Title Page):** Título, autor, borrador, fecha e información de contacto.
* **Configuración de Página:** Formato estándar A4 o Carta (*US Letter*).
* **Opciones Estructurales:** Incluir o excluir numeración de escenas, encabezados de grupo y bandas de actos/secuencias.

---

# PARTE V: GUÍAS DE MISIÓN — FLUJOS DE TRABAJO DE EXTREMO A EXTREMO

---

## 13. Flujo 1: Génesis Creativa (De la Idea en Blanco al Guion Literario)

> **Pipeline:** `1. Brainstorming en Sandbox ➔ 2. Escaleta Causal 2D ➔ 3. Worldbuilding DUAL ➔ 4. Manuscrito Fountain ➔ 5. Script Doctoring ➔ 6. Exportación FDX/PDF`

### Objetivo:
Crear una obra cinematográfica desde cero, transitando de forma natural desde el torbellino de ideas inicial hasta el guion definitivo listo para rodaje.

### Paso a Paso:
1. **Lluvia de Ideas en Sandbox:**
   - Abra un nuevo proyecto y diríjase al **Tablero Causal (DEVENIR)**.
   - Cree múltiples acciones con la opción **Crear en Sandbox**. Escriba ideas sueltas, giros de trama y escenas clave sin preocuparse por el orden cronológico.
2. **Estructuración y Enlace Causal:**
   - Desactive el modo Sandbox en las acciones a medida que encuentre su lugar en el relato.
   - Trace líneas de conexión causal para definir qué acontecimientos detonan las siguientes escenas.
   - Cree **Actos y Secuencias** en la Timeline inferior para establecer el ritmo clásico en 3 o 5 actos.
3. **Worldbuilding en Modo DUAL:**
   - Cambie a la vista **DUAL**. En el panel inferior (Ontología), cree las fichas de los personajes y locaciones que van apareciendo en la escaleta.
4. **Redacción Continua en el Manuscrito:**
   - Conmute a la vista **MANUSCRITO**. Active en el Quad-Dock izquierdo el widget **Editor Lineal** para navegar entre escenas.
   - Redacte las escenas utilizando el autocompletado *IntelliSense* para saltar rápidamente entre sluglines, personajes y diálogos.
5. **Auditoría de Tensión con Script Doctor:**
   - Ejecute el **Script Doctor (🩺)**. Examine la Curva de Tensión para asegurar que el clímax tenga la intensidad adecuada y no existan baches de ritmo en el segundo acto.
6. **Entrega Profesional:**
   - Abra el Asistente de Exportación, seleccione **Guion Literario**, active la **Carátula Profesional** y genere su archivo **.fdx** y **.pdf**.

---

## 14. Flujo 2: Migración desde Mapas Conceptuales (Obsidian / JSON Canvas)

> **Pipeline:** `1. Ingesta de .canvas ➔ 2. Enrutamiento Híbrido ➔ 3. Consolidación Ontológica ➔ 4. Escaleta & Guion FDX`

### Objetivo:
Transformar un mapa mental o tablero de notas existente en una obra estructurada y lista para redactar.

### Paso a Paso:
1. **Ingesta Directa:**
   - Arrastre su archivo `.canvas` desde su explorador de archivos directamente sobre el lienzo de Narrando.
2. **Selección de Estrategia de Enrutamiento:**
   - Elija **Ingesta Híbrida Inteligente** para que el sistema envíe los personajes y locaciones al **SER** y las tarjetas de acontecimientos al **DEVENIR**.
3. **Consolidación en el Lienzo de Ontología:**
   - Conmute a la vista **SER**. Asigne arquetipos a las entidades importadas y utilice la herramienta **Fusionar Entidades** para limpiar duplicados.
4. **Organización en la Escaleta:**
   - Conmute a la vista **DEVENIR**. Agrupe las acciones en Escenas y defina los límites de Secuencias.
5. **Exportación de la Biblia:**
   - Genere un documento **Markdown Wiki con esquemas relacionales** para documentar el universo antes de escribir el guion.

---

## 15. Flujo 3: Adaptación Literaria (De Novela o Tratamiento a Guion)

> **Pipeline:** `1. Ingesta de Prosa ➔ 2. Desglose Atómico con IA ➔ 3. Extracción de Entidades ➔ 4. Redacción con Fossil ➔ 5. Escaleta y Guion`

### Objetivo:
Convertir una obra en prosa extensa (novela, cuento o biografía) en un guion audiovisual estructurado.

### Paso a Paso:
1. **Ingesta de Prosa:**
   - Arrastre el archivo `.docx`, `.pdf` o `.txt` y seleccione la estrategia **Prosa (Contenedor Maestro)**.
2. **Desglose Atómico Asistido por IA:**
   - Seleccione los capítulos y pulse **Desglosar (✨)** en modo atómico. La IA fragmentará la narración en acciones dramáticas con verbos de transformación.
3. **Extracción Global de Entidades:**
   - Active la **Extracción de Entidades con Asignación Global** para catalogar a todos los personajes mencionados en la novela y vincularlos a sus respectivas escenas.
4. **Cotejo en Vivo con Fossil (Texto Original):**
   - Mientras redacta los diálogos en el Manuscrito, active en el Quad-Dock el widget **Texto Original (Fossil)** para consultar en todo momento el texto fuente de la novela en modo solo lectura.
5. **Exportación de la Escaleta de Adaptación:**
   - Exporte una **Escaleta Estructural en PDF** para contrastar la adaptación con los titulares de los derechos de la obra.

---

## 16. Flujo 4: Consultoría Dramática y Script Doctoring (Auditoría y Reescritura)

> **Pipeline:** `1. Ingesta FDX/Fountain ➔ 2. Diagnóstico IA de Tensión ➔ 3. Foco Léxico & Cast Focus ➔ 4. Reescritura ➔ 5. Dossier Analítico`

### Objetivo:
Evaluar el ritmo, la curva emocional y la coherencia de un guion ajeno o propio en fase de reescritura.

### Paso a Paso:
1. **Carga de Fricción Cero:**
   - Arrastre el archivo `.fdx` o `.fountain`. El guion se inyecta en caliente en la memoria de Narrando.
2. **Ejecución del Script Doctor:**
   - Inicie la auditoría. El sistema calculará la tensión de cada acción y emitirá un reporte cualitativo.
3. **Detección de Valles en Heatmap y Timeline:**
   - Active el **Modo Termográfico (🔥)** para identificar secuencias planas (en verde/azul) que requieran mayor conflicto.
4. **Reescritura Focalizada:**
   - Active en el Manuscrito el **Foco Léxico (Solo Diálogos)** para auditar el subtexto de las conversaciones.
   - Utilice **Cast Focus** para seguir exclusivamente al antagonista y verificar que sus motivaciones sean sólidas.
   - Deje notas de revisión en el widget **Marginalia** de cada escena.
5. **Entrega del Diagnóstico:**
   - Exporte el **Dossier Analítico Ejecutivo** con las gráficas de tensión y recomendaciones para los productores.

---

## 17. Flujo 5: Preproducción y Desglose Industrial (Línea de Producción)

> **Pipeline:** `1. Carga de Guion Aprobado ➔ 2. Sábana de Desglose ➔ 3. Matriz DOOD ➔ 4. Carga de Trabajo (Workload) ➔ 5. Descarga CSV/ZIP`

### Objetivo:
Transformar un guion aprobado en un plan de rodaje cuantificado y optimizado en costos.

### Paso a Paso:
1. **Verificación Ontológica:**
   - Abra el Lienzo de Ontología y verifique que todas las locaciones, vehículos y objetos especiales estén debidamente clasificados.
2. **Generación de la Sábana de Desglose:**
   - Abra **Machina Analytica (📊)** y navegue a la pestaña **Sábana de Desglose (Breakdown Sheet)**.
   - Revise los requerimientos departamento por departamento (Talento, Extras, Utilería, SFX/VFX, Maquillaje).
3. **Auditoría Day-out-of-Days (DOOD):**
   - Abra la matriz **DOOD** para revisar los días de inicio, trabajo y retención (*Hold*) de cada actor.
   - Detecte jornadas muertas y reorganice el orden tentativo de rodaje para optimizar el presupuesto de elenco.
4. **Evaluación de Carga de Trabajo:**
   - Revise la vista **Workload** para auditar el balance Día/Noche y el total de páginas y octavos por escena.
5. **Exportación de Producción:**
   - Descargue la **Sábana de Desglose en CSV** y el **Paquete Relacional ZIP** para el departamento de producción.

---

## 18. Flujo 6: Cuarto de Guionistas y Desarrollo de Series (Writers' Room)

> **Pipeline:** `1. Biblia de Lore (SER) ➔ 2. Escaleta de Temporada en DEVENIR ➔ 3. Snapshots en Bóveda ➔ 4. Pitch Deck Doc`

### Objetivo:
Diseñar la biblia de lore de una serie de televisión y estructurar los arcos dramáticos de una temporada completa.

### Paso a Paso:
1. **Construcción de la Biblia en el SER:**
   - Mapee las facciones políticas, relaciones familiares y dinámicas de poder en el Lienzo de Ontología.
   - Defina arquetipos y complete las biografías y secretos en las Fichas de Entidad.
2. **Estructura de Temporada en el DEVENIR:**
   - Cree un **Grupo de Escenas** para cada episodio (ej. *"Episodio 101 - Piloto"*, *"Episodio 102"*).
   - Trace líneas de conexión causal para marcar tramas continuas (Arco A) y subtramas episódicas (Arco B / Arco C).
3. **Control de Versiones de Sala:**
   - Al final de cada jornada de sala de guionistas, cree una **Instantánea Protegida (📌)** en la Bóveda del Tiempo con el nombre de la versión (ej. *"Parrilla de Temporada - Sesión 14"*).
4. **Exportación del Pitch Deck:**
   - Exporte la **Biblia / Universo en Markdown Wiki con esquemas relacionales** para presentar la serie a cadenas y plataformas.

---

# APÉNDICE

---

## A. Tabla Maestra de Atajos de Teclado

### Navegación y Vistas
| Atajo | Acción |
|---|---|
| **Ctrl + F** | Enfocar el buscador universal de la barra superior. |
| **Ctrl + 1** | Cambiar a vista **Manuscrito**. |
| **Ctrl + 2** | Cambiar a vista **Tablero Causal (DEVENIR)**. |
| **Ctrl + 3** | Cambiar a vista **Ontología (SER)**. |
| **Ctrl + 4** | Cambiar a vista **DUAL**. |
| **Escape** | Deseleccionar todo / Cerrar popovers flotantes activos. |

### Edición y Manuscrito
| Atajo | Acción |
|---|---|
| **Tab** | Autocompletar sluglines (`INT.`, `EXT.`) o términos temporales. |
| **Enter** | Confirmar selección de autocompletado de personaje o crear siguiente acción. |
| **Ctrl + Enter** | Dividir (*Split*) la acción actual en la posición del cursor de texto. |
| **Ctrl + A** | Seleccionar todas las tarjetas del lienzo activo. |

### Tablero Causal y Estructura
| Atajo | Acción |
|---|---|
| **Ctrl + N** | Crear una nueva Acción subordinada en la escaleta. |
| **Ctrl + D** | Duplicar la acción o grupo seleccionado. |
| **Supr / Delete** | Abrir diálogo de eliminación unificada (remover de lienzo o destruir). |
| **Shift + Arrastre** | Selección múltiple de tarjetas en recuadro elástico. |

### Historial y Persistencia
| Atajo | Acción |
|---|---|
| **Ctrl + S** | Guardar en caliente y registrar instantánea manual en la Bóveda. |
| **Ctrl + Z** | Deshacer última operación (*Undo*). |
| **Ctrl + Shift + Z** / **Ctrl + Y** | Rehacer última operación deshecha (*Redo*). |

---

## B. Glosario Canónico de Términos Narrando

* **Acción:** La unidad mínima atómica de transformación dramática y causal en el relato.
* **Bóveda del Tiempo (Time Machine):** Repositorio histórico de instantáneas completas del proyecto para control de versiones y recuperación segura.
* **Cast Focus:** Modo de visualización selectiva en el Manuscrito que aísla las líneas y escenas de un actor o personaje específico.
* **DEVENIR:** El dominio del tiempo, la cronología, la escaleta causal y la modulación de tensión.
* **DOOD (Day-out-of-Days):** Matriz de rodaje que audita las jornadas de inicio, trabajo y retención de cada personaje del elenco.
* **Entidad:** Cualquier elemento persistente del universo narrativo (Personaje, Locación, Objeto, Facción o Concepto).
* **Foco Léxico:** Filtro estructural del Manuscrito para auditar exclusivamente Diálogos, Acción pura o Encabezados de escena.
* **Fossil (Texto Original):** Widget del Quad-Dock que preserva en modo solo lectura el texto fuente original importado para cotejo de adaptaciones.
* **Heatmap (Modo Termográfico):** Capa visual que tiñe las tarjetas del tablero según su carga dramática (de verde a rojo).
* **IntelliSense:** Motor de autocompletado contextual en tiempo real para sluglines, términos de tiempo y personajes.
* **Ley de Expansión Natural:** Regla física del tablero que empuja automáticamente hacia abajo los elementos inferiores al agrandar o mover tarjetas, evitando colisiones.
* **MANUSCRITO:** El lienzo de redacción literaria continua en tipografía cinematográfica Courier Prime.
* **Marginalia:** Sistema de notas al margen atemporales y acausales asociadas a cada bloque o escena sin alterar la duración del guion.
* **Quad-Dock:** Sistema modular de 4 paneles acoplables para personalizar el entorno de trabajo con 8 widgets diferentes.
* **Sandbox (Boneyard):** Espacio de pausa donde las acciones flotan libremente sin afectar la cronología ni la curva de tensión.
* **SER:** El dominio de la ontología, el worldbuilding y la red relacional de la historia.
* **Sincronización Suave (Soft Sync):** Paradigma que garantiza la coexistencia armónica y en tiempo real entre la libertad 2D del tablero y la verdad 1D del manuscrito.
* **Script Doctor:** Asistente de inteligencia artificial que audita la tensión narrativa y detecta baches de ritmo en el guion.
