# Banco de Prompts con Variables

Coleccion completa de prompts listos para usar con **[VARIABLES]** personalizables. Copia el prompt, reemplaza las variables entre corchetes con tu informacion y pegalo en la herramienta de IA correspondiente.

---

## Indice

1. [Prompts para Generar Contenido (usar en ChatGPT/Gemini/Copilot)](#1-prompts-para-generar-contenido)
2. [Prompts para NotebookLM - Consultas y Analisis](#2-prompts-para-notebooklm---consultas-y-analisis)
3. [Prompts para NotebookLM - Materiales Educativos](#3-prompts-para-notebooklm---materiales-educativos)
4. [Prompts para NotebookLM - Audio Overview](#4-prompts-para-audio-overview)

---

## 1. Prompts para Generar Contenido

> Usar en: **ChatGPT, Gemini o Copilot** - ANTES de ir a NotebookLM

### 1.1 Articulo Educativo Completo

```
Actua como un [ROL_EXPERTO] especializado en [ESPECIALIDAD].

Genera un articulo educativo completo sobre "[TEMA_PRINCIPAL]"
dirigido a [AUDIENCIA] con nivel [NIVEL: basico/intermedio/avanzado].

Estructura:
1. Introduccion (por que importa este tema)
2. Conceptos fundamentales (definiciones clave)
3. Desarrollo (minimo 5 subtemas)
4. Aplicaciones practicas con ejemplos reales
5. Tendencias actuales y futuras
6. Conclusion y puntos clave
7. Glosario de terminos

Extension: minimo 2000 palabras.
Formato: Encabezados claros, parrafos cortos, listas cuando sea apropiado.
```

### 1.2 Glosario Tecnico Categorizado

```
Actua como un [ROL_EXPERTO] en [ESPECIALIDAD].

Crea un glosario de [CANTIDAD] terminos sobre "[TEMA_PRINCIPAL]".

Para cada termino:
- Definicion clara (maximo 2 oraciones)
- Ejemplo practico o analogia sencilla
- Categoria tematica

Organiza por categorias, no alfabeticamente.
Nivel: adecuado para [AUDIENCIA].
```

### 1.3 Recopilacion de Fuentes Web

```
Actua como un [ROL_EXPERTO] y curador de contenido en [ESPECIALIDAD].

Lista [CANTIDAD] fuentes confiables sobre "[TEMA_PRINCIPAL]":

1. Articulos web (universidades, revistas, medios especializados)
2. Videos de YouTube de canales reconocidos
3. PDFs o papers descargables
4. Cursos o tutoriales gratuitos

Para cada fuente: titulo, URL, descripcion breve, nivel, idioma.
Prioriza fuentes en [IDIOMA] de los ultimos [PERIODO] anhos.
```

### 1.4 Contenido por Subtemas

```
Actua como un [ROL_EXPERTO] en [ESPECIALIDAD].

Genera contenido de [EXTENSION] palabras para cada subtema
de "[TEMA_PRINCIPAL]":

1. [SUBTEMA_1]
2. [SUBTEMA_2]
3. [SUBTEMA_3]
4. [SUBTEMA_4]
5. [SUBTEMA_5]

Cada texto debe incluir: introduccion, explicacion con ejemplos,
caso practico, datos relevantes y pregunta de reflexion.

Tono: [TONO: academico/conversacional/tecnico]
Audiencia: [AUDIENCIA]
```

### 1.5 Banco de Preguntas

```
Actua como un [ROL_EXPERTO] en [ESPECIALIDAD].

Genera [CANTIDAD] preguntas sobre "[TEMA_PRINCIPAL]":
- [N1] de opcion multiple (4 opciones, marca la correcta)
- [N2] de verdadero/falso (con justificacion)
- [N3] abiertas de desarrollo
- [N4] de aplicacion practica (escenarios)

Nivel: [NIVEL] | Audiencia: [AUDIENCIA]
Incluye respuesta correcta y explicacion para cada una.
```

### 1.6 Esquema de Curso Completo

```
Actua como un [ROL_EXPERTO] disenador instruccional en [ESPECIALIDAD].

Disenha un [TIPO: curso/taller/seminario] de [DURACION_TOTAL]
sobre "[TEMA_PRINCIPAL]" para [AUDIENCIA].

Para cada sesion incluye:
- Titulo y duracion
- Objetivos de aprendizaje
- Contenidos principales
- Actividades con tiempos
- Recursos necesarios
- Forma de evaluacion

Incluye evaluacion final y lista de recursos generales.
```

### 1.7 Resumen Ejecutivo para Docentes

```
Actua como un [ROL_EXPERTO] en [ESPECIALIDAD].

Crea un resumen ejecutivo de 1 pagina sobre "[TEMA_PRINCIPAL]"
pensado para que un [AUDIENCIA] pueda:
1. Entender el tema en 5 minutos
2. Identificar los 5 puntos mas importantes
3. Conocer 3 aplicaciones practicas inmediatas
4. Tener 3 datos/estadisticas de impacto
5. Saber donde profundizar (3 recursos clave)

Formato: conciso, con viñetas y negritas en los puntos clave.
```

---

## 2. Prompts para NotebookLM - Consultas y Analisis

> Usar directamente en: **el chat de NotebookLM**

### 2.1 Resumen General

```
Dame un resumen estructurado de toda la informacion en las fuentes.
Organiza por temas con subtitulos. Cada seccion: 100-200 palabras.
```

### 2.2 Resumen Multinivel

```
Genera 3 versiones del resumen de las fuentes:
1. BASICO (150 palabras): Para novatos, lenguaje cotidiano
2. INTERMEDIO (300 palabras): Terminologia tecnica con explicaciones
3. AVANZADO (500 palabras): Para profesionales, detalles tecnicos
```

### 2.3 Conceptos Clave

```
Lista los 20 conceptos mas importantes de las fuentes.
Para cada uno: termino, definicion (2 oraciones), ejemplo,
relevancia. Ordena de fundamental a avanzado.
```

### 2.4 Mapa Mental

```
Crea un mapa mental jerarquico del contenido de las fuentes:

TEMA CENTRAL
├── Rama 1
│   ├── Sub-rama 1.1
│   │   └── Detalle
│   └── Sub-rama 1.2
├── Rama 2
└── Rama 3

Minimo 5 ramas principales, 2-3 sub-ramas cada una.
Indica 5 relaciones cruzadas entre ramas.
```

### 2.5 Tabla Comparativa

```
Crea una tabla comparativa de los principales conceptos/herramientas/
enfoques de las fuentes.

| Aspecto | Elemento 1 | Elemento 2 | Elemento 3 |
|---------|-----------|-----------|-----------|
| Definicion | | | |
| Ventajas | | | |
| Desventajas | | | |
| Uso principal | | | |
| Ejemplo | | | |

Identifica tu los elementos mas relevantes para comparar.
```

### 2.6 Vacios de Informacion

```
Analiza las fuentes e identifica:
1. Que temas estan bien cubiertos
2. Que temas estan poco desarrollados
3. Que temas importantes faltan completamente
4. Que contradicciones existen entre fuentes
5. Que fuentes adicionales recomendarias agregar
```

### 2.7 Relaciones entre Conceptos

```
Identifica y explica las 10 relaciones mas importantes entre
los conceptos de las fuentes. Para cada relacion:
- Concepto A y Concepto B
- Tipo de relacion (causa-efecto, parte-todo, comparacion, etc.)
- Explicacion de la relacion
- Por que es importante entender esta conexion
```

### 2.8 Cronologia / Linea de Tiempo

```
Crea una linea de tiempo detallada basada en las fuentes:
[Anho/Periodo] | [Evento/Hito] | [Descripcion] | [Impacto]
Ordena cronologicamente. Si no hay fechas exactas, usa aproximaciones.
```

---

## 3. Prompts para NotebookLM - Materiales Educativos

> Usar directamente en: **el chat de NotebookLM**

### 3.1 Guion de Video Educativo

```
Crea un guion de video educativo de [DURACION] minutos sobre
"[TEMA]" basado en las fuentes.

Para cada segmento incluye:
- [LOCUCION]: Texto exacto del presentador
- [VISUAL]: Que se ve en pantalla
- [GRAFICO]: Textos o graficos superpuestos

Estructura: Intro (30s) + Desarrollo (3 secciones) + Cierre (30s)
Estilo: [ESTILO] | Audiencia: [AUDIENCIA]
```

### 3.2 Presentacion de Diapositivas

```
Crea una presentacion de [CANTIDAD] diapositivas sobre "[TEMA]".

Para cada diapositiva:
- Titulo
- 3-5 puntos de contenido
- Elemento visual sugerido
- Notas del presentador
- Tiempo estimado

Duracion total: [DURACION] minutos. Audiencia: [AUDIENCIA]
```

### 3.3 Ficha de Aprendizaje

```
Crea una ficha de aprendizaje sobre "[TEMA]":

- Objetivos de aprendizaje (3 medibles)
- Conceptos clave (tabla: termino, definicion, ejemplo)
- Contenido principal resumido
- Esquema visual (formato texto)
- Ejemplo practico resuelto
- 3 actividades de practica
- 5 preguntas de autoevaluacion con respuestas
- Recursos complementarios

Nivel: [NIVEL] | Audiencia: [AUDIENCIA]
```

### 3.4 Flashcards / Tarjetas de Estudio

```
Genera 20 flashcards basadas en las fuentes:

TARJETA N
- Frente: [pregunta o termino]
- Reverso: [respuesta o definicion]
- Categoria: [subtema]
- Dificultad: [facil/media/dificil]

Distribucion: 7 definiciones, 5 relaciones, 4 aplicacion, 4 datos.
```

### 3.5 Hoja de Actividades

```
Crea una hoja de actividades sobre "[TEMA]" para [AUDIENCIA]:

- Actividad 1 - Comprension (10 min): [tipo y descripcion]
- Actividad 2 - Analisis (15 min): [tipo y descripcion]
- Actividad 3 - Aplicacion (15 min): [tipo y descripcion]
- Actividad 4 - Reflexion (10 min): [tipo y descripcion]

Incluye instrucciones, entregables y criterios de evaluacion.
```

### 3.6 Caso de Estudio

```
Crea un caso de estudio educativo sobre "[TEMA]":
- Contexto (situacion realista, 200 palabras)
- Datos del caso
- Personajes/actores involucrados
- Problema o dilema
- 4 preguntas de analisis progresivas
- Guia para el docente con respuestas esperadas
```

### 3.7 Rubrica de Evaluacion

```
Crea una rubrica para evaluar un trabajo sobre "[TEMA]":

| Criterio | Excelente (4) | Bueno (3) | Regular (2) | Insuficiente (1) |
Criterios: Contenido, Analisis, Aplicacion, Presentacion, Originalidad.
Incluye escalas de puntaje y descripcion especifica por nivel.
```

### 3.8 Preguntas de Examen Completo

```
Genera un examen completo sobre el contenido de las fuentes:

Seccion A: 10 preguntas de opcion multiple (4 opciones c/u)
Seccion B: 5 verdadero/falso con justificacion
Seccion C: 3 preguntas de desarrollo
Seccion D: 1 caso practico con 3 sub-preguntas

Incluye clave de respuestas al final.
Nivel: [NIVEL] | Duracion estimada: [MINUTOS] minutos
```

---

## 4. Prompts para Audio Overview

> Usar en: **campo "Customize" del Audio Overview en NotebookLM Studio**

### 4.1 Podcast Introductorio

```
Crea una conversacion amigable que explique los conceptos basicos
del tema. Usa analogias cotidianas y un tono accesible. Dirigido
a personas que no conocen nada del tema.
```

### 4.2 Podcast de Debate

```
Discutan las diferentes perspectivas y controversias del tema.
Uno tome una postura y el otro la contraria. Incluyan argumentos
basados en las fuentes.
```

### 4.3 Podcast de Aplicacion Practica

```
Enfoquense en las aplicaciones practicas y casos reales del tema.
Den consejos actionables que la audiencia pueda implementar
inmediatamente. Incluyan ejemplos concretos.
```

### 4.4 Podcast de Resumen Rapido

```
Hagan un resumen rapido y energico de los 5 puntos mas importantes
del tema. Sean directos y concisos. Ideal para escuchar en 5 minutos.
```

### 4.5 Podcast para Docentes

```
Discutan como un educador puede usar este contenido en sus clases.
Den ideas de actividades, estrategias de ensenanza y formas de
evaluar. El tono debe ser de colegas compartiendo experiencias.
```

---

## Como usar estos prompts

1. **Identifica tu necesidad** (generar contenido, analizar, crear material)
2. **Copia el prompt** que mejor se ajuste
3. **Reemplaza las [VARIABLES]** con tu informacion especifica
4. **Pega el prompt** en la herramienta correspondiente
5. **Revisa y refina** la respuesta obtenida

### Tabla de referencia rapida

| Variable | Que poner | Ejemplos |
|----------|-----------|----------|
| `[ROL_EXPERTO]` | Rol profesional | profesor, investigador, ingeniero |
| `[ESPECIALIDAD]` | Tu area de conocimiento | medicina, derecho, ingenieria |
| `[TEMA_PRINCIPAL]` | El tema especifico | "Anatomia del corazon", "Derecho penal" |
| `[AUDIENCIA]` | A quien va dirigido | estudiantes de 1er anho, profesionales |
| `[NIVEL]` | Complejidad | basico, intermedio, avanzado |
| `[CANTIDAD]` | Numero de items | 10, 20, 30 |
| `[DURACION]` | Tiempo en minutos | 5, 10, 15, 30 |
| `[TONO]` | Estilo de comunicacion | academico, conversacional, tecnico |
| `[IDIOMA]` | Idioma preferido | espanol, ingles |
| `[ESTILO]` | Estilo del material | formal, dinamico, interactivo |
