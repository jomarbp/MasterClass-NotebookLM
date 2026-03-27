# Bloque 2: Transformacion Rapida de Contenido

**Duracion:** 60 minutos
**Objetivo:** Aplicar funciones de analisis y sintesis de NotebookLM para generar mapas mentales, resumenes, preguntas de examen, conceptos clave y mas.

---

## Que vamos a crear en este bloque?

A partir de las fuentes ya cargadas, vamos a transformar la informacion en:

1. Resumenes tematicos estructurados
2. Mapas mentales y esquemas conceptuales
3. Preguntas tipo examen
4. Listados de conceptos clave
5. Tablas comparativas
6. Lineas de tiempo
7. Audio Overview (Podcast)

---

## Seccion 1: Resumenes Tematicos

### Mediante el Chat de NotebookLM

**Prompt para resumen general:**
```
Genera un resumen completo y estructurado de toda la informacion
disponible en las fuentes. Organiza el contenido en secciones
tematicas con subtitulos claros. Cada seccion debe tener entre
100 y 200 palabras.
```

**Prompt para resumen ejecutivo:**
```
Crea un resumen ejecutivo de maximo 500 palabras que capture
los puntos mas importantes de las fuentes. Usa viñetas para
los hallazgos clave. Incluye al final 3 conclusiones principales.
```

**Prompt para resumen por niveles:**
```
Genera 3 versiones de resumen del contenido de las fuentes:

1. VERSION BASICA (150 palabras): Para alguien que no sabe nada
   del tema. Usa lenguaje cotidiano y analogias simples.

2. VERSION INTERMEDIA (300 palabras): Para alguien con conocimientos
   generales. Incluye terminologia tecnica con explicaciones.

3. VERSION AVANZADA (500 palabras): Para un profesional del area.
   Incluye detalles tecnicos, datos y referencias a las fuentes.
```

### Mediante el Studio (Panel Derecho)

1. Haz clic en **"Informes"** en el panel Studio
2. NotebookLM generara un resumen/informe automatico
3. Puedes personalizar haciendo clic en **"Customize"**
4. Guarda como nota para usar despues

---

## Seccion 2: Mapas Mentales y Esquemas

NotebookLM puede generar estructuras que luego puedes llevar a herramientas de mapas mentales.

### Prompt para mapa mental en texto:
```
Crea un mapa mental en formato de texto jerarquico sobre
el contenido de las fuentes. Usa la siguiente estructura:

TEMA CENTRAL
├── Rama 1
│   ├── Sub-rama 1.1
│   │   ├── Detalle
│   │   └── Detalle
│   └── Sub-rama 1.2
├── Rama 2
│   ├── Sub-rama 2.1
│   └── Sub-rama 2.2
└── Rama 3
    ├── Sub-rama 3.1
    └── Sub-rama 3.2

Incluye al menos 4 ramas principales con 2-3 sub-ramas cada una.
```

### Prompt para mapa mental con conexiones:
```
Analiza las fuentes y crea un esquema conceptual que muestre:

1. Los 5 conceptos principales del tema
2. Como se relacionan entre si (indica el tipo de relacion)
3. Que subtemas dependen de cada concepto
4. Cuales son los prerequisitos para entender cada concepto

Presentalo en formato de lista jerarquica con flechas que
indiquen las relaciones.
```

### Prompt para diagrama de flujo textual:
```
Crea un diagrama de flujo en formato de texto que muestre
el proceso o la logica principal del tema tratado en las fuentes.
Usa el formato:

[Paso 1: Descripcion] --> [Paso 2: Descripcion] --> [Decision?]
   |-- SI --> [Paso 3A]
   |-- NO --> [Paso 3B]

Incluye al menos 6 pasos y 2 puntos de decision.
```

### Tip: Exportar a herramientas de mapas mentales

> Copia el mapa mental generado y pegalo en herramientas como:
> - **Miro** (miro.com) - Pizarra colaborativa
> - **Canva** (canva.com) - Mapas mentales visuales
> - **MindMeister** (mindmeister.com) - Mapas mentales online
> - **Whimsical** (whimsical.com) - Diagramas y flowcharts
> - Tambien puedes pedirle a ChatGPT/Gemini que convierta el texto a formato Mermaid para diagramas automaticos

---

## Seccion 3: Preguntas Tipo Examen

### Prompt para preguntas de opcion multiple:
```
Basandote en las fuentes cargadas, genera 10 preguntas de
opcion multiple sobre el contenido. Para cada pregunta:

- Formula la pregunta de manera clara
- Proporciona 4 opciones (a, b, c, d)
- Marca la respuesta correcta con *
- Agrega una breve explicacion de por que es correcta
- Indica de que fuente proviene la informacion

Nivel de dificultad: intermedio
Asegurate de cubrir diferentes temas de las fuentes.
```

### Prompt para preguntas verdadero/falso:
```
Genera 10 afirmaciones de verdadero/falso basadas en las fuentes.
Para cada una:

- Escribe la afirmacion
- Indica si es VERDADERO o FALSO
- Explica por que en 1-2 oraciones
- Cita la fuente especifica

Incluye 5 verdaderas y 5 falsas, en orden aleatorio.
Haz que las falsas sean suficientemente sutiles para que
no sean obvias.
```

### Prompt para preguntas de desarrollo:
```
Crea 5 preguntas abiertas de desarrollo que requieran
pensamiento critico y analisis basado en las fuentes.

Para cada pregunta incluye:
- La pregunta (que requiera una respuesta de al menos 200 palabras)
- Una guia de respuesta con los puntos clave que deberia cubrir
- Los criterios de evaluacion (que se espera en una buena respuesta)

Las preguntas deben ir de menor a mayor complejidad.
```

### Mediante el Studio

1. Haz clic en **"Cuestionario"** en el panel Studio
2. NotebookLM genera automaticamente preguntas de comprension, repaso y evaluacion
3. Revisa y ajusta las preguntas generadas
4. Guarda como nota
5. Complementa con **"Tarjetas didacticas"** para generar flashcards automaticas

---

## Seccion 4: Conceptos Clave y Glosarios

### Prompt para listado de conceptos:
```
Identifica y lista los 20 conceptos mas importantes que
aparecen en las fuentes. Para cada concepto:

1. **Termino:** [nombre del concepto]
2. **Definicion:** [definicion en maximo 2 oraciones]
3. **Ejemplo:** [un ejemplo practico]
4. **Relevancia:** [por que es importante en el contexto del tema]

Ordenalos de mas fundamental a mas avanzado.
```

### Prompt para tabla comparativa:
```
Crea una tabla comparativa de los principales conceptos,
herramientas o enfoques mencionados en las fuentes.

Usa el siguiente formato:

| Aspecto | [Elemento 1] | [Elemento 2] | [Elemento 3] |
|---------|-------------|-------------|-------------|
| Definicion | ... | ... | ... |
| Ventajas | ... | ... | ... |
| Desventajas | ... | ... | ... |
| Uso principal | ... | ... | ... |
| Ejemplo | ... | ... | ... |

Identifica tu mismo cuales son los elementos mas relevantes
para comparar basandote en las fuentes.
```

---

## Seccion 5: Linea de Tiempo

### Prompt para cronologia:
```
Basandote en las fuentes, crea una linea de tiempo que muestre
la evolucion del tema. Incluye:

- Fechas o periodos clave
- Eventos importantes
- Hitos o descubrimientos relevantes
- Personas o instituciones involucradas

Formato:
[Ano/Periodo] - [Evento] - [Descripcion breve] - [Impacto]

Ordena de mas antiguo a mas reciente. Si no hay fechas exactas,
usa periodos aproximados.
```

### Mediante el Studio

Puedes solicitar lineas de tiempo directamente desde el **chat** de NotebookLM usando los prompts anteriores. Complementa con la opcion **"Mapa mental"** del Studio para visualizar la estructura temporal del contenido.

---

## Seccion 6: Audio Overview (Podcast)

Una de las funciones mas poderosas de NotebookLM.

### Como generar un Audio Overview:

1. Ve al panel **Studio** (derecho)
2. Busca la opcion **"Audio Overview"**
3. Haz clic en **"Generate"**
4. **(Opcional)** Antes de generar, haz clic en **"Customize"** para dar instrucciones:
   ```
   Enfocate en explicar los conceptos basicos de manera
   sencilla. Usa analogias cotidianas. El tono debe ser
   como una conversacion entre dos profesores amigos
   que explican el tema de forma accesible.
   ```
5. Espera la generacion (puede tardar 2-5 minutos)
6. Escucha el resultado
7. Puedes **descargar el audio** como archivo

### Tip: Personalizar el Audio Overview

> Usa el campo "Customize" para controlar:
> - **El enfoque:** "Enfocate solo en las aplicaciones practicas"
> - **El tono:** "Hazlo divertido y con humor"
> - **La audiencia:** "Explicalo como si fuera para adolescentes"
> - **Lo que incluir:** "Asegurate de mencionar los 5 terminos clave"
> - **Lo que excluir:** "No hables de la historia, solo del presente y futuro"

### Usos del Audio Overview:

- Material de estudio en formato podcast
- Contenido para clases invertidas (flipped classroom)
- Repaso auditivo antes de examenes
- Material accesible para estudiantes con discapacidad visual
- Contenido para publicar en plataformas de podcast

---

## Seccion 7: Tecnicas para Optimizar Consultas

### 1. Seleccion de fuentes especificas

Antes de hacer una consulta, **selecciona solo las fuentes relevantes**:
- Desmarca las fuentes que no necesitas
- Esto hace las respuestas mas precisas y enfocadas

### 2. Preguntas en cadena (Chain Prompting)

Haz preguntas que construyan una sobre la otra:
```
Pregunta 1: "Cuales son los conceptos principales del tema?"
Pregunta 2: "Del concepto X que mencionaste, dame mas detalles"
Pregunta 3: "Como se relaciona el concepto X con el concepto Y?"
Pregunta 4: "Crea un ejemplo practico que integre ambos conceptos"
```

### 3. Especificar formato de salida

Siempre indica como quieres la respuesta:
```
"... presentalo en formato de tabla"
"... usa viñetas y sub-viñetas"
"... redactalo como un parrafo narrativo"
"... organizalo en secciones con subtitulos"
```

### 4. Pedir citas y referencias

NotebookLM puede citar las fuentes especificas:
```
"Para cada punto que menciones, indica de que fuente
proviene la informacion con una referencia."
```

### 5. Iterar y refinar

Si la respuesta no es perfecta:
```
"Amplica el punto 3 con mas detalles"
"Simplifica la explicacion del concepto X"
"Agrega un ejemplo practico para cada punto"
"Reformula esto para una audiencia mas joven"
```

---

## Ejercicio Integrador del Bloque 2

### Mision: Transformar tus fuentes sobre [TU TEMA]

Usando las fuentes que cargaste en el Bloque 1:

1. **Genera un resumen en 3 niveles** (basico, intermedio, avanzado)
2. **Crea un mapa mental** con al menos 4 ramas principales
3. **Genera 10 preguntas de opcion multiple** con respuestas
4. **Extrae los 15 conceptos clave** con definiciones
5. **Crea una tabla comparativa** de al menos 3 elementos
6. **Genera un Audio Overview** personalizado
7. **Guarda todo como notas** en el notebook

### Caso practico IA - Resultado esperado:

- Resumen en 3 niveles sobre Inteligencia Artificial
- Mapa mental: IA > ML > DL > IA Generativa > Etica
- 10 preguntas sobre fundamentos de IA
- 15 conceptos clave (IA, ML, DL, NLP, etc.)
- Tabla: ChatGPT vs Gemini vs Copilot
- Audio Overview sobre "IA para principiantes"

---

## Resumen del Bloque

- [x] Generamos resumenes en multiples formatos y niveles
- [x] Creamos mapas mentales y esquemas conceptuales
- [x] Produjimos bancos de preguntas tipo examen
- [x] Extrajimos conceptos clave y glosarios
- [x] Creamos lineas de tiempo
- [x] Generamos un Audio Overview (podcast)
- [x] Aprendimos tecnicas para optimizar consultas

➡️ [Ir al Bloque 3: Creacion de Materiales Educativos](../03-Materiales-Educativos/README.md)
