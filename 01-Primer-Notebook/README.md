# Bloque 1: Creacion del Primer Notebook con Materiales Propios

**Duracion:** 45 minutos
**Objetivo:** Cargar documentos y contenido generado en NotebookLM, organizar las fuentes y realizar las primeras consultas dirigidas.

---

## Que es Google NotebookLM?

Google NotebookLM es un asistente de investigacion impulsado por IA (Gemini) que permite:

- Cargar multiples fuentes de informacion (PDFs, textos, URLs, videos de YouTube, audios)
- Hacer preguntas y obtener respuestas basadas **exclusivamente** en tus fuentes
- Generar informes, cuestionarios, mapas mentales, tarjetas didacticas y mas
- Crear infografias, presentaciones (Slide Deck) y resumenes en video
- Crear podcasts de audio (Audio Overview) a partir de tus fuentes
- Usar Deep Research para completar contexto con fuentes externas
- Organizar informacion en notas estructuradas

**URL de acceso:** `notebooklm.google.com`

---

## Paso 1: Acceder a NotebookLM

1. Abre tu navegador (recomendado: Google Chrome)
2. Ve a **notebooklm.google.com**
3. Inicia sesion con tu cuenta de Google
4. Haz clic en **"Nuevo Notebook"** o **"New Notebook"**

---

## Paso 2: Entender la Interfaz

La interfaz de NotebookLM tiene 3 paneles principales:

```
+------------------+------------------------+------------------+
|                  |                        |                  |
|    FUENTES       |     AREA DE CHAT       |     STUDIO       |
|   (Sources)      |     (Chat / Notes)     |    (Notebook     |
|                  |                        |     Guide)       |
|  - Lista de      |  - Conversacion        |  - Generar       |
|    documentos    |    con la IA           |    contenido     |
|    cargados      |  - Preguntas y         |  - Audio         |
|                  |    respuestas          |    Overview      |
|  - Agregar       |  - Notas guardadas     |  - Resumen       |
|    fuentes       |                        |  - Guia de       |
|                  |                        |    estudio       |
+------------------+------------------------+------------------+
```

### Panel Izquierdo - Fuentes (Sources)
- Aqui se listan todos los documentos cargados
- Puedes agregar nuevas fuentes con el boton "+"
- Cada fuente muestra un resumen automatico al hacer clic

### Panel Central - Chat y Notas
- Aqui interactuas con la IA haciendo preguntas
- Las respuestas se basan SOLO en las fuentes cargadas
- Puedes guardar respuestas como notas
- Las notas se organizan cronologicamente

### Panel Derecho - Studio / Notebook Guide
- Contiene opciones de generacion automatica
- Sugerencias de preguntas basadas en tus fuentes
- Opciones para generar contenido (informes, cuestionario, mapa mental, tarjetas didacticas, etc.)

---

## Paso 3: Cargar Fuentes en el Notebook

### Tipos de fuentes soportadas

| Tipo | Formato | Limite |
|------|---------|--------|
| **Documentos** | PDF, TXT, Markdown | Hasta 500,000 palabras por fuente |
| **Google Docs** | Desde Google Drive | Documentos completos |
| **Google Slides** | Desde Google Drive | Presentaciones completas |
| **URLs / Sitios web** | Cualquier pagina web publica | Contenido de la pagina |
| **Videos de YouTube** | URL del video | Transcripcion del video |
| **Archivos de audio** | MP3, WAV | Transcripcion del audio |
| **Texto copiado** | Copiar y pegar directamente | Hasta 500,000 caracteres |

**Limite total:** Hasta **50 fuentes** por notebook.

### Como cargar fuentes

1. Haz clic en el boton **"+"** en el panel de fuentes
2. Selecciona el tipo de fuente:
   - **Subir archivo** (PDF, TXT)
   - **Google Drive** (Docs, Slides)
   - **Link** (URL de sitio web)
   - **YouTube** (URL del video)
   - **Copiar texto** (pegar directamente)
3. Espera a que NotebookLM procese la fuente (puede tardar unos segundos)
4. Verifica que aparezca en la lista de fuentes

### Ejercicio: Cargar el contenido generado en el Bloque 0

Vamos a cargar los materiales que generamos con las herramientas de IA:

1. **Articulo educativo** -> Subir como PDF o TXT, o pegar como texto
2. **Glosario tecnico** -> Subir como archivo o pegar como texto
3. **URLs de fuentes** -> Agregar como links individuales
4. **Videos de YouTube encontrados** -> Agregar como fuentes de YouTube

---

## Paso 4: Verificar y Organizar las Fuentes

Una vez cargadas las fuentes:

1. **Haz clic en cada fuente** para ver su resumen automatico
2. **Verifica que el contenido se cargo correctamente**
3. **Renombra las fuentes** si es necesario (clic derecho > renombrar)
4. **Elimina fuentes duplicadas o irrelevantes**

### Tip: Seleccion de fuentes activas

> NotebookLM permite **seleccionar/deseleccionar fuentes** individualmente. Esto es muy util para hacer consultas sobre documentos especificos. Si solo seleccionas 2 de 10 fuentes, la IA solo respondera basandose en esas 2.

---

## Paso 5: Primeras Consultas Dirigidas

### Consultas basicas para explorar tus fuentes

Una vez que tienes las fuentes cargadas, prueba estas consultas en el chat:

**Consulta 1 - Resumen general:**
```
Dame un resumen ejecutivo de toda la informacion disponible
en las fuentes. Organiza los puntos principales por temas.
```

**Consulta 2 - Conceptos clave:**
```
Cuales son los 10 conceptos mas importantes que aparecen
en las fuentes? Para cada uno, dame una definicion breve.
```

**Consulta 3 - Relaciones entre temas:**
```
Como se relacionan los diferentes temas tratados en las fuentes?
Describe las conexiones principales entre los conceptos.
```

**Consulta 4 - Vacios de informacion:**
```
Basandote en las fuentes disponibles, que temas importantes
sobre [TEMA] no estan cubiertos o estan poco desarrollados?
```

**Consulta 5 - Resumen por fuente:**
```
Haz un resumen de 3 oraciones para cada fuente cargada,
indicando su aporte principal al tema general.
```

---

## Paso 6: Guardar Notas desde el Chat

Cuando obtengas una respuesta util:

1. Pasa el cursor sobre la respuesta
2. Haz clic en el icono **"Pin"** o **"Guardar como nota"**
3. La nota se guardara en el panel central
4. Puedes editar, renombrar y organizar las notas

### Tip: Notas como material base

> Las notas guardadas se convierten en material de referencia que puedes usar en los siguientes bloques para generar contenido educativo. Guarda las mejores respuestas.

---

## Paso 7: Usar el Notebook Guide (Panel Derecho)

El panel derecho **Studio** ofrece generacion automatica. Explora estas opciones:

| Opcion | Que genera |
|--------|------------|
| **Cuestionario** | Preguntas de comprension, repaso y evaluacion automatica |
| **Mapa mental** | Organizacion visual de conceptos clave y estructura tematica |
| **Tarjetas didacticas** | Flashcards con definiciones rapidas para memorizacion |
| **Informes** | Resumen estructurado y sintesis academica de las fuentes |
| **Infografia** | Resumen visual con bloques, iconos y estructura grafica |
| **Presentacion (Slide Deck)** | Diapositivas listas para presentar o compartir |
| **Audio Overview** | Podcast conversacional sobre el tema |
| **Resumen en video** | Video corto con los puntos principales |
| **Deep Research** | Investigacion adicional con fuentes externas para completar contexto |

### Ejercicio: Genera tu primer recurso automatico

1. Ve al panel derecho (Studio)
2. Haz clic en **"Informes"** para obtener un resumen estructurado
3. Revisa el informe generado y fijate en las **citas numeradas** (al hacer clic te llevan al fragmento original)
4. Si te gusta, guardalo como nota
5. Prueba con **"Cuestionario"** para generar preguntas de estudio
6. Explora **"Mapa mental"** para ver la estructura visual del contenido
7. Genera **"Tarjetas didacticas"** para obtener flashcards de repaso
8. Prueba **"Infografia"** para un resumen visual con bloques y estructura grafica
9. Genera una **"Presentacion"** para obtener diapositivas listas para usar

---

## Ejemplo Practico: Caso IA

### Fuentes cargadas para el caso practico:

1. **Texto generado:** "Fundamentos de la Inteligencia Artificial" (del Bloque 0)
2. **Glosario:** "30 terminos clave de IA" (del Bloque 0)
3. **URL:** Articulo sobre IA de una fuente confiable
4. **YouTube:** Video explicativo sobre como funciona la IA

### Consulta ejemplo:
```
Usando todas las fuentes disponibles, crea una introduccion
de 300 palabras al tema de Inteligencia Artificial que sea
adecuada para estudiantes que no tienen conocimientos previos
en tecnologia. Incluye una analogia cotidiana para explicar
como funciona la IA.
```

---

## Errores Comunes y Como Evitarlos

| Error | Solucion |
|-------|----------|
| "No puedo acceder a esa URL" | Verifica que la pagina sea publica y accesible |
| Fuente no se procesa | Verifica el formato y tamano del archivo |
| Respuestas muy genericas | Selecciona solo las fuentes relevantes para tu pregunta |
| "No encuentro informacion sobre eso" | El tema no esta en tus fuentes; agrega mas fuentes |
| Contenido incompleto | Divide documentos muy largos en partes mas pequenas |

---

## Resumen del Bloque

- [x] Accedimos a NotebookLM y creamos un notebook
- [x] Entendimos la interfaz de 3 paneles
- [x] Cargamos multiples tipos de fuentes
- [x] Realizamos consultas dirigidas
- [x] Guardamos notas utiles
- [x] Exploramos el Notebook Guide

➡️ [Ir al Bloque 2: Transformacion Rapida de Contenido](../02-Transformacion-Contenido/README.md)
