# Trucos y Tips Avanzados de Google NotebookLM

Guia de funcionalidades avanzadas, atajos y tecnicas para sacar el maximo provecho de NotebookLM.

---

## 1. Trucos de Carga de Fuentes

### 1.1 Maximizar la calidad de las fuentes

- **PDFs escaneados:** Si tu PDF es una imagen escaneada, primero pasalo por un OCR (Google Drive lo hace automaticamente al subirlo como Google Doc). Luego carga el Google Doc en NotebookLM.
- **Presentaciones:** Carga Google Slides directamente desde Drive para mantener el contexto de cada diapositiva.
- **Videos de YouTube:** NotebookLM extrae la transcripcion. Funciona mejor con videos que tienen subtitulos (automaticos o manuales).
- **Sitios web:** Si una URL no carga bien, copia el texto manualmente y pegalo con "Copiar texto".

### 1.2 Organizacion estrategica de fuentes

- **Un notebook por tema/proyecto:** No mezcles temas diferentes en un mismo notebook.
- **Nombra tus fuentes descriptivamente:** Renombra cada fuente para que sea facil identificarla.
- **Divide documentos largos:** Si un PDF tiene mas de 100 paginas, dividelo en secciones y cargalas por separado. Esto mejora la precision de las respuestas.

### 1.3 Limite de fuentes

- Maximo **50 fuentes** por notebook
- Maximo **500,000 palabras** por fuente individual
- Si necesitas mas, crea multiples notebooks tematicos

---

## 2. Trucos del Chat

### 2.1 Seleccion selectiva de fuentes

**Este es el truco mas poderoso de NotebookLM:**
- Puedes **seleccionar/deseleccionar fuentes individuales** antes de hacer una pregunta
- Si seleccionas solo 2 de 10 fuentes, la IA SOLO usa esas 2 para responder
- Esto permite hacer consultas super especificas

**Uso practico:**
- Selecciona solo el glosario -> pregunta por definiciones
- Selecciona solo un articulo -> pide resumen de ese articulo
- Selecciona todas -> pide una vision integrada

### 2.2 Cadena de preguntas (Chain Prompting)

Construye respuestas complejas paso a paso:
```
1. "Cuales son los 5 temas principales?"
2. "Del tema 2, dame mas detalles"
3. "Como se relaciona el tema 2 con el tema 4?"
4. "Crea un ejemplo que integre ambos temas"
```

### 2.3 Especificar formato

Siempre dile a NotebookLM COMO quieres la respuesta:
- `"Presentalo en formato de tabla"`
- `"Usa viñetas con sub-viñetas"`
- `"Redactalo como parrafo narrativo"`
- `"Organizalo con subtitulos y secciones"`
- `"Usa formato de lista numerada"`

### 2.4 Pedir citas de fuentes

NotebookLM puede indicar de DONDE saca la informacion:
```
"Para cada punto, indica de que fuente especifica proviene"
```
Las respuestas incluyen numeros de referencia clicables que te llevan al texto exacto en la fuente.

### 2.5 Respuestas mas largas

Si NotebookLM corta la respuesta:
```
"Continua desde donde te quedaste"
"Amplica la seccion [X] con mas detalles"
"Genera la parte 2 del contenido anterior"
```

### 2.6 Control del tono y estilo

```
"Explicalo como si fuera para un niño de 10 anos"
"Redactalo en tono academico formal"
"Hazlo conversacional, como una charla entre colegas"
"Usa analogias deportivas para explicar cada concepto"
```

---

## 3. Trucos del Studio (Panel Derecho)

### 3.1 Opciones del Studio y cuando usarlas

| Opcion | Mejor momento para usar |
|--------|------------------------|
| **Cuestionario** | Para crear preguntas de comprension, repaso y evaluacion automatica |
| **Mapa mental** | Para visualizar la estructura y conceptos clave del contenido |
| **Tarjetas didacticas** | Para generar flashcards de definiciones y memorizacion |
| **Informes** | Cuando acabas de cargar fuentes y quieres un resumen estructurado |
| **Infografia** | Para resumir contenido visualmente con bloques, iconos y estructura grafica |
| **Presentacion (Slide Deck)** | Para generar diapositivas listas para presentar o compartir |
| **Audio Overview** | Para crear contenido de podcast/audio conversacional |
| **Resumen en video** | Para crear un video corto con los puntos principales |
| **Deep Research** | Para ampliar contenido con fuentes externas cuando tus fuentes se quedan cortas |

### 3.2 Audio Overview - Tips avanzados

**Personalizar ANTES de generar:**
- Haz clic en "Customize" antes de "Generate"
- Escribe instrucciones especificas sobre enfoque, tono y contenido

**Instrucciones efectivas:**
```
"Enfocate solo en las aplicaciones practicas, no en la teoria"
"El tono debe ser como un podcast de divulgacion cientifica"
"Asegurate de mencionar estos 5 terminos: [lista]"
"No hablen de historia, solo del presente y futuro"
"Dirigido a adolescentes, usen lenguaje juvenil y ejemplos de redes sociales"
```

**Descargar el audio:**
- Una vez generado, haz clic en los 3 puntos > Descargar
- Se descarga como archivo de audio que puedes compartir

**Usos creativos del Audio Overview:**
- Material para clase invertida (flipped classroom)
- Podcast para distribuir en plataformas
- Audio de repaso antes de examenes
- Material accesible para inclusion

### 3.3 Infografia - Tips avanzados

**Personalizar el estilo:**
- Indica el objetivo: "Resumen", "Mapa mental", "Pasos clave"
- Ajusta el estilo con instrucciones claras

**Instrucciones de estilo que funcionan bien:**
```
"Estilo limpio y minimalista, sin parrafos largos."
"Formato muy visual, con bloques y bullets."
"Tono profesional, jerarquia clara y titulares cortos."
```

**Formatos recomendados:**
- **Vertical:** perfecto para stories y piezas moviles
- **Cuadrado:** ideal para feed y carruseles

**Tip:** El resultado es una base lista para exportar. Llevalo a **Canva** para maquetarlo con tu marca.

### 3.4 Presentacion (Slide Deck) - Tips avanzados

**Dos tipos de presentacion:**
- **Slides del presentador:** visuales, con pocos puntos, pensadas para presentar en directo
- **Presentacion detallada:** mas texto, pensada para enviarla y que se entienda sin explicacion

**Instrucciones de estilo:**
```
"Profesional y ejecutivo, tono corporativo."
"Minimalista, mensajes breves."
"Didactica, con ejemplos claros para estudiantes."
```

**Exportacion:** Descargala en PDF y usala tal cual o como base para maquetar en PowerPoint, Google Slides o Canva.

### 3.5 Resumen en Video

- Genera un video corto con los puntos principales de tus fuentes
- Util para vision general rapida, compartir facilmente y crear piezas educativas
- Ideal para clase invertida (flipped classroom)

### 3.6 Deep Research - Investigacion Adicional

- Si tus fuentes se quedan cortas, Deep Research completa con fuentes externas
- Util para guias, comparativas y documentos con varias perspectivas
- **Importante:** Separa lo que viene de tus fuentes de lo anadido por Deep Research para mantener trazabilidad

### 3.7 Combinar Studio + Chat

1. **Genera con Studio** -> obtienes una primera version automatica
2. **Copia al Chat** -> pide refinamientos especificos
3. **Guarda como Nota** -> conserva la version final

---

## 4. Trucos de Notas

### 4.1 Guardar respuestas como notas

- Pasa el cursor sobre cualquier respuesta del chat
- Haz clic en el icono de "Pin" o "Save to note"
- La nota se guarda en el panel central

### 4.2 Guardar las mejores respuestas como fuentes (Hack)

**Truco avanzado del PDF:** Cuando NotebookLM te de una respuesta muy buena, guardala como nota y **conviertela en fuente**. Asi no se pierde y podras reutilizarla en mapas, infografias y nuevos documentos. Aparecera en la seccion Studio como fuente adicional.

### 4.3 Organizar notas

- Renombra las notas con titulos descriptivos
- Usa notas para organizar tu flujo de trabajo
- Crea una nota "indice" con links a tus otras notas

### 4.4 Exportar notas

- Selecciona el texto de la nota
- Copia y pega en tu herramienta favorita (Word, Google Docs, etc.)
- Mantiene el formato basico (negritas, listas, tablas)

---

## 5. Trucos para Diferentes Tipos de Contenido

### 5.1 Para crear presentaciones

**Opcion rapida (Studio):**
1. Usa **Presentacion (Slide Deck)** del Studio para generar slides automaticamente
2. Descarga en PDF y usala tal cual o como base para maquetar

**Opcion detallada (Chat):**
1. Pide la estructura completa en NotebookLM via Chat
2. Copia cada diapositiva a Google Slides o PowerPoint
3. Usa las notas del presentador como guia
4. Tip: Pide las sugerencias visuales por separado

**Complementa con:**
- **Infografia** del Studio para material visual de apoyo
- **Mapa mental** del Studio para estructura de conceptos

### 5.2 Para crear videos

**Opcion rapida (Studio):**
1. Usa **Resumen en video** del Studio para un video corto automatico
2. Usa **Audio Overview** como version audio del tema

**Opcion detallada (Chat):**
1. Genera el guion completo en NotebookLM via Chat
2. Usa el Audio Overview como referencia del tono
3. Copia el guion a un teleprompter
4. Las indicaciones [VISUAL] te guian en la edicion

### 5.3 Para crear evaluaciones

1. Genera preguntas con el chat
2. Usa Cuestionario y Tarjetas didacticas como complemento
3. Pide siempre la clave de respuestas
4. Genera versiones A y B del mismo examen:
   ```
   "Crea una version alternativa del examen anterior
   con preguntas diferentes pero del mismo nivel
   y cubriendo los mismos temas"
   ```

### 5.4 Para investigacion

1. Carga papers y articulos como fuentes
2. Pide comparaciones entre autores/perspectivas
3. Solicita identificar consensos y controversias
4. Genera bibliografias organizadas

---

## 6. Errores Comunes y Soluciones

| Error | Causa | Solucion |
|-------|-------|----------|
| Respuestas muy genericas | Demasiadas fuentes seleccionadas | Selecciona solo las fuentes relevantes |
| "No encuentro informacion" | El tema no esta en las fuentes | Agrega fuentes sobre ese tema |
| Respuesta cortada | Limite de tokens | Pide "continua" o divide la pregunta |
| Audio Overview no genera | Fuentes insuficientes o muy cortas | Agrega mas contenido a las fuentes |
| URL no se carga | Pagina protegida o dinamica | Copia el texto manualmente |
| Informacion incorrecta | Fuentes con datos erroneos | Revisa y corrige las fuentes |
| Formato no se respeta | Prompt poco especifico | Se mas explicito con el formato deseado |

---

## 7. Flujo de Trabajo Recomendado

```
PREPARACION (con ChatGPT/Gemini/Copilot)
│
├── Generar contenido base con prompts estructurados
├── Recopilar URLs y recursos
└── Organizar en archivos
│
ALIMENTACION (en NotebookLM)
│
├── Crear notebook tematico
├── Cargar fuentes (PDFs, textos, URLs, videos)
├── Verificar que las fuentes se procesaron bien
└── Renombrar fuentes descriptivamente
│
EXPLORACION (Chat de NotebookLM)
│
├── Resumen general (todas las fuentes)
├── Conceptos clave
├── Vacios de informacion
└── Guardar hallazgos como notas
│
TRANSFORMACION (Chat + Studio)
│
├── Resumenes multinivel (Chat)
├── Mapas mentales (Chat)
├── Preguntas de examen (Chat)
├── Tablas comparativas (Chat)
├── Cuestionario (Studio)
├── Mapa mental (Studio)
├── Tarjetas didacticas (Studio)
├── Informes (Studio)
├── Infografia (Studio)
├── Presentacion / Slide Deck (Studio)
├── Audio Overview (Studio)
├── Resumen en video (Studio)
├── Deep Research (Studio)
└── Guardar todo como notas
│
CREACION (Chat de NotebookLM)
│
├── Guiones de video (Chat)
├── Estructuras de presentacion (Chat + Studio Slide Deck)
├── Infografias (Studio)
├── Fichas de aprendizaje (Chat)
├── Hojas de actividades (Chat)
└── Rubricas de evaluacion (Chat)
│
EXPORTACION
│
├── Copiar contenido a herramientas finales
├── Google Slides / PowerPoint
├── Google Docs / Word
├── Descargar audios
└── Compartir notebooks
```

---

## 8. Atajos y Accesos Rapidos

| Accion | Como hacerlo |
|--------|-------------|
| Nuevo notebook | Boton "+" en la pagina principal |
| Agregar fuente | Boton "+" en panel de fuentes |
| Seleccionar/deseleccionar fuente | Clic en el checkbox de la fuente |
| Guardar respuesta como nota | Icono "Pin" en la respuesta |
| Ver resumen de fuente | Clic en el nombre de la fuente |
| Generar Cuestionario | Studio > Cuestionario |
| Generar Mapa mental | Studio > Mapa mental |
| Generar Tarjetas didacticas | Studio > Tarjetas didacticas |
| Generar Informes | Studio > Informes |
| Generar Infografia | Studio > Infografia |
| Generar Presentacion | Studio > Presentacion (Slide Deck) |
| Generar Audio Overview | Studio > Audio Overview > Generate |
| Personalizar Audio | Studio > Audio Overview > Customize |
| Generar Resumen en video | Studio > Resumen en video |
| Usar Deep Research | Studio > Deep Research |
| Compartir notebook | Menu > Share |
| Descargar audio | 3 puntos en Audio Overview > Download |

---

## 9. Integracion con Otras Herramientas

| Herramienta | Como integrar |
|-------------|--------------|
| **Google Slides** | Copia estructura de presentacion o usa Slide Deck del Studio |
| **Google Docs** | Copia contenido generado o usa Informes del Studio |
| **Canva** | Exporta infografias del Studio a Canva para maquetarlas con tu marca |
| **YouTube** | Usa guiones de video del Chat o Resumen en video del Studio |
| **Podcast** | Descarga Audio Overview y publica |
| **LMS (Moodle, Canvas)** | Exporta Cuestionario y preguntas del Chat al LMS |
| **Quizlet/Anki** | Usa Tarjetas didacticas del Studio para crear sets |
| **Gemini** | Adjunta notebooks en Gemini para crear landings, guiones, mini cursos |

---

## 10. Hacks Avanzados de NotebookLM

### 10.1 Usar NotebookLM dentro de Gemini

Adjunta tus notebooks directamente en **Gemini** y pidele cosas como:
- "Crea una landing page"
- "Escribe un guion"
- "Diseña un mini curso"

Gemini usara solo ese cuaderno como fuente.

### 10.2 Guardar respuestas como fuentes

Cuando NotebookLM te de una respuesta muy buena:
1. Guardala como **nota**
2. Conviertela en **fuente**
3. Asi no se pierde y podras reutilizarla en mapas, infografias y nuevos documentos

### 10.3 Crear una persona fija por notebook

Define en cada cuaderno como quieres que responda:
- **Tono:** formal, casual, didactico, tecnico
- **Rol:** profesor, consultor, periodista, divulgador
- **Nivel de detalle:** basico, intermedio, avanzado
- **Tipo de audiencia:** estudiantes, profesionales, ejecutivos

Esas instrucciones se aplican siempre y no tienes que repetir el mismo prompt en cada mensaje.

### 10.4 Ordenar cuadernos en carpetas

Con extensiones como **NotebookLM Tools Extension** puedes:
- Crear carpetas y agrupar notebooks
- Organizar por proyecto, cliente o asignatura
- Evitar perderte en una lista infinita de notebooks

### 10.5 Entrenar con tus propios textos

Crea un notebook solo con tus textos (newsletters, posts, hilos, guiones):
- NotebookLM entendera tu estilo de escritura
- Podra reescribir contenido nuevo sonando mucho mas parecido a ti
- Util para mantener consistencia de marca personal

### 10.6 Verificar siempre las citas

- Cada respuesta de NotebookLM incluye **citas numeradas**
- Al hacer clic, te lleva al **fragmento exacto** de la fuente original
- Esto te permite verificar la informacion y construir materiales solidos
- **NotebookLM no alucina** porque trabaja exclusivamente con las fuentes que subes

### 10.7 Refinar antes de generar (direccion editorial)

Antes de generar cualquier pieza del Studio, dedica un minuto a afinar:
```
"Hazlo mas minimalista y elimina redundancias."
"Tono profesional, como un informe de consultoria."
"Hazlo mas didactico, con ejemplos sencillos."
"Simplifica los terminos tecnicos y anade analogias."
"Incluye datos en tabla si aparecen en la fuente."
```

Piensa en este paso como **direccion editorial**: tu marcas el criterio, la herramienta ejecuta.

---

> **Recuerda:** NotebookLM es tan bueno como las fuentes que le proporcionas. Invierte tiempo en curar fuentes de calidad y los resultados seran significativamente mejores. No trabajes "a ciegas": todo lo que sale esta conectado a un fragmento real de tu material.
