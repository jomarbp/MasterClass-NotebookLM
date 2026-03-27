# Bloque 3: Creacion de Materiales Educativos

**Duracion:** 60 minutos
**Objetivo:** Elaborar recursos pedagogicos completos usando NotebookLM: guiones de video, estructuras de presentacion, fichas de aprendizaje, actividades y mas.

---

## Que vamos a crear en este bloque?

| Material | Uso pedagogico |
|----------|---------------|
| Guion para video educativo | Clases grabadas, tutoriales, YouTube |
| Estructura de presentacion | Clases presenciales, conferencias |
| Ficha de aprendizaje | Material de estudio para alumnos |
| Hoja de actividades | Ejercicios y talleres practicos |
| Tarjetas de estudio (Flashcards) | Repaso rapido de conceptos |
| Rubrica de evaluacion | Criterios de calificacion |

---

## Material 1: Guion para Video Educativo

### Mediante el Chat de NotebookLM

**Prompt para guion de video completo:**
```
Usando la informacion de las fuentes, crea un guion completo
para un video educativo de [DURACION] minutos sobre
"[TEMA_DEL_VIDEO]".

El guion debe incluir:

1. INTRO (30 segundos):
   - Saludo y presentacion del tema
   - Pregunta gancho para captar atencion
   - Adelanto de lo que se aprendera

2. DESARROLLO (dividido en secciones):
   Para cada seccion incluir:
   - [LOCUCION]: Lo que dice el presentador (texto exacto)
   - [VISUAL]: Lo que se muestra en pantalla
   - [GRAFICO]: Graficos, diagramas o textos en pantalla
   - [TRANSICION]: Como se pasa a la siguiente seccion

3. EJEMPLOS PRACTICOS:
   - Al menos 2 ejemplos o demostraciones
   - Paso a paso visual

4. RESUMEN Y CIERRE (30 segundos):
   - Recapitulacion de puntos clave
   - Llamado a la accion
   - Despedida

Estilo: [ESTILO: formal/conversacional/dinamico]
Audiencia: [AUDIENCIA]

Formatea el guion de manera que sea facil de seguir
durante la grabacion.
```

**Ejemplo con caso practico (IA):**
```
[DURACION] = 10
[TEMA_DEL_VIDEO] = Que es la Inteligencia Artificial y como esta cambiando el mundo
[ESTILO] = conversacional y dinamico
[AUDIENCIA] = estudiantes universitarios
```

### Prompt para guion estilo tutorial:
```
Crea un guion para un video tutorial paso a paso sobre
"[TEMA_TUTORIAL]" basandote en las fuentes.

Formato del guion:

MINUTO 0:00 - 0:30 | INTRODUCCION
- Presentador dice: "..."
- En pantalla: [descripcion de lo que se ve]

MINUTO 0:30 - 2:00 | PASO 1: [nombre del paso]
- Presentador dice: "..."
- Demostracion: [describir que se muestra]
- Texto en pantalla: [puntos clave]

[Continuar con cada paso...]

MINUTO X:XX | CIERRE
- Resumen visual de todos los pasos
- Presentador dice: "..."

Incluye al menos 5 pasos y timestamps aproximados.
```

---

## Material 2: Estructura de Presentacion (Slides)

### Prompt para crear estructura de presentacion:
```
Usando las fuentes disponibles, crea la estructura completa
para una presentacion de [CANTIDAD] diapositivas sobre
"[TEMA_PRESENTACION]".

Para CADA diapositiva indica:

DIAPOSITIVA [N]: [TITULO]
- Contenido principal: [texto o puntos clave - maximo 5 puntos]
- Elemento visual sugerido: [tipo de imagen, grafico o diagrama]
- Notas del presentador: [lo que debe decir el presentador]
- Tiempo estimado: [minutos en esta diapositiva]

Estructura sugerida:
- Diapositiva 1: Portada
- Diapositiva 2: Agenda/Indice
- Diapositivas 3-[N-2]: Contenido
- Diapositiva [N-1]: Resumen/Conclusiones
- Diapositiva [N]: Preguntas y contacto

La presentacion es para [AUDIENCIA] con nivel [NIVEL].
Duracion total de la exposicion: [DURACION_TOTAL] minutos.
```

**Ejemplo con caso practico (IA):**
```
[CANTIDAD] = 15
[TEMA_PRESENTACION] = Inteligencia Artificial: Fundamentos y Aplicaciones
[AUDIENCIA] = profesionales de recursos humanos
[NIVEL] = basico
[DURACION_TOTAL] = 30
```

### Prompt para notas del presentador:
```
Para la presentacion sobre "[TEMA_PRESENTACION]", genera notas
detalladas del presentador para cada diapositiva.

Para cada slide incluye:
- Que decir al mostrar la diapositiva (texto completo)
- Una anecdota o dato curioso relacionado
- Una pregunta para interactuar con la audiencia
- Posibles preguntas que el publico podria hacer y sus respuestas
- Tip de como presentar esa diapositiva (tono, enfasis, pausa)

Esto me servira como guia durante la presentacion.
```

---

## Material 3: Fichas de Aprendizaje

### Prompt para ficha de aprendizaje completa:
```
Crea una ficha de aprendizaje sobre "[TEMA_FICHA]" usando
la informacion de las fuentes. La ficha debe tener este formato:

============================================
FICHA DE APRENDIZAJE
Tema: [titulo]
Nivel: [basico/intermedio/avanzado]
Tiempo estimado: [minutos]
============================================

OBJETIVOS DE APRENDIZAJE:
Al completar esta ficha, el estudiante podra:
1. [objetivo 1]
2. [objetivo 2]
3. [objetivo 3]

CONCEPTOS CLAVE:
| Termino | Definicion | Ejemplo |
|---------|------------|---------|
| ... | ... | ... |

CONTENIDO PRINCIPAL:
[Desarrollo del tema en parrafos cortos con subtitulos]

ESQUEMA VISUAL:
[Mapa conceptual o diagrama en formato texto]

EJEMPLO PRACTICO:
[Caso o ejercicio resuelto paso a paso]

ACTIVIDAD DE PRACTICA:
[Ejercicio para que el estudiante resuelva]

AUTOEVALUACION:
1. [Pregunta con respuesta oculta]
2. [Pregunta con respuesta oculta]
3. [Pregunta con respuesta oculta]

PARA PROFUNDIZAR:
[Referencias y recursos adicionales de las fuentes]
============================================
```

### Prompt para fichas rapidas (flashcards):
```
Genera un set de 20 tarjetas de estudio (flashcards) basadas
en las fuentes. Formato:

TARJETA 1
- Frente: [pregunta o termino]
- Reverso: [respuesta o definicion]
- Categoria: [tema o subtema]
- Dificultad: [facil/media/dificil]

Las tarjetas deben cubrir:
- 7 tarjetas de definiciones
- 5 tarjetas de conceptos y relaciones
- 4 tarjetas de aplicacion practica
- 4 tarjetas de datos y hechos importantes

Haz que las preguntas sean especificas y las respuestas concisas.
```

---

## Material 4: Hoja de Actividades

### Prompt para actividad practica:
```
Disenha una hoja de actividades sobre "[TEMA_ACTIVIDAD]" para
[AUDIENCIA]. Usa la informacion de las fuentes.

HOJA DE ACTIVIDADES
====================================
Titulo: [nombre de la actividad]
Materia/Curso: [asignatura]
Duracion: [minutos]
Modalidad: [individual/grupal/mixta]
====================================

INSTRUCCIONES GENERALES:
[instrucciones claras para el estudiante]

ACTIVIDAD 1: Comprension (10 min)
Tipo: [lectura, video, analisis]
Descripcion: [que debe hacer el estudiante]
Entregable: [que debe producir]

ACTIVIDAD 2: Aplicacion (15 min)
Tipo: [ejercicio practico, caso de estudio]
Descripcion: [que debe hacer el estudiante]
Entregable: [que debe producir]

ACTIVIDAD 3: Creacion (15 min)
Tipo: [proyecto, produccion, diseño]
Descripcion: [que debe hacer el estudiante]
Entregable: [que debe producir]

ACTIVIDAD 4: Reflexion (10 min)
Tipo: [debate, escritura reflexiva]
Descripcion: [que debe hacer el estudiante]
Entregable: [que debe producir]

CRITERIOS DE EVALUACION:
| Criterio | Excelente | Bueno | En desarrollo |
|----------|-----------|-------|---------------|
| ... | ... | ... | ... |

RECURSOS NECESARIOS:
[lista de materiales o herramientas necesarias]
```

### Prompt para caso de estudio:
```
Basandote en las fuentes, crea un caso de estudio educativo
sobre "[TEMA_CASO]" con el siguiente formato:

CASO DE ESTUDIO: [Titulo atractivo]

CONTEXTO:
[Situacion o escenario realista - 200 palabras]

DATOS DEL CASO:
[Informacion especifica que el estudiante necesita analizar]

PERSONAJES / ACTORES:
[Quienes estan involucrados y sus roles]

PROBLEMA O DILEMA:
[Cual es el desafio que debe resolverse]

PREGUNTAS DE ANALISIS:
1. [Pregunta que requiere comprension]
2. [Pregunta que requiere analisis]
3. [Pregunta que requiere evaluacion]
4. [Pregunta que requiere propuesta de solucion]

GUIA PARA EL DOCENTE:
[Puntos clave que deberian surgir en la discusion]
[Posibles respuestas y enfoques validos]
```

---

## Material 5: Rubrica de Evaluacion

### Prompt para rubrica:
```
Crea una rubrica de evaluacion para un trabajo/proyecto sobre
"[TEMA_RUBRICA]". Basate en los contenidos de las fuentes.

RUBRICA DE EVALUACION
Trabajo: [nombre del trabajo]
Puntaje total: [puntos]

| Criterio | Excelente (4) | Bueno (3) | Regular (2) | Insuficiente (1) |
|----------|--------------|-----------|-------------|-------------------|
| Contenido | [descripcion] | [descripcion] | [descripcion] | [descripcion] |
| Analisis | [descripcion] | [descripcion] | [descripcion] | [descripcion] |
| Aplicacion | [descripcion] | [descripcion] | [descripcion] | [descripcion] |
| Presentacion | [descripcion] | [descripcion] | [descripcion] | [descripcion] |
| Originalidad | [descripcion] | [descripcion] | [descripcion] | [descripcion] |

PUNTAJE:
- Excelente: 18-20 puntos
- Bueno: 14-17 puntos
- Regular: 10-13 puntos
- Insuficiente: menos de 10 puntos

Cada descripcion debe ser especifica al tema de las fuentes.
```

---

## Usando las Opciones del Studio para Materiales

Ademas del chat, el panel Studio ofrece generacion directa:

### Opciones disponibles y su uso educativo:

| Opcion Studio | Material que genera | Uso educativo |
|--------------|--------------------|----|
| **FAQ** | Preguntas frecuentes | Base para seccion de dudas |
| **Study Guide** | Guia de estudio completa | Material de repaso |
| **Briefing Doc** | Documento ejecutivo | Resumen para docentes |
| **Timeline** | Linea temporal | Contexto historico |
| **Table of Contents** | Indice tematico | Estructura de curso |
| **Audio Overview** | Podcast conversacional | Material auditivo |

### Tip: Combinar Chat + Studio

> 1. Usa el **Studio** para generar la primera version automatica
> 2. Luego usa el **Chat** para refinar, ampliar o ajustar
> 3. **Guarda como nota** cada version final
> 4. Exporta copiando el texto a tu herramienta favorita

---

## Organizacion Didactica: Estructura de un Curso Completo

### Prompt para estructura de curso/clase:
```
Usando las fuentes como base de contenido, disenha la estructura
completa de un [TIPO: curso/taller/seminario/clase] de
[DURACION_TOTAL] sobre "[TEMA_CURSO]".

ESTRUCTURA DEL [TIPO]
================================
Titulo: [nombre]
Duracion total: [horas]
Audiencia: [descripcion]
Prerequisitos: [si aplica]
================================

SESION 1: [Titulo] ([duracion])
- Objetivo: [que lograra el participante]
- Contenidos:
  * [tema 1]
  * [tema 2]
- Actividades:
  * [actividad 1] ([minutos])
  * [actividad 2] ([minutos])
- Recursos: [materiales necesarios]
- Evaluacion: [como se evalua]

[Repetir para cada sesion]

EVALUACION FINAL:
[Descripcion del proyecto/examen final]

RECURSOS GENERALES:
[Lista de todos los materiales del curso]
```

---

## Ejercicio Integrador del Bloque 3

### Mision: Crear un paquete educativo completo

Elige uno de los siguientes y crealo usando NotebookLM:

**Opcion A:** Guion de Video (10 min) + Presentacion (15 slides)
**Opcion B:** Ficha de Aprendizaje + Hoja de Actividades + 20 Flashcards
**Opcion C:** Estructura de Curso Completo + Rubrica de Evaluacion

### Caso practico IA - Resultado esperado:

- Guion de video: "Que es la IA y por que importa" (10 min)
- Presentacion: "IA para profesionales" (15 diapositivas)
- Ficha: "Fundamentos de Machine Learning"
- Actividad: "Explorando herramientas de IA generativa"
- Flashcards: 20 tarjetas sobre conceptos clave de IA
- Rubrica: Para evaluar un proyecto sobre aplicaciones de IA

---

## Resumen del Bloque

- [x] Creamos guiones para videos educativos
- [x] Disenamos estructuras de presentaciones
- [x] Elaboramos fichas de aprendizaje y flashcards
- [x] Creamos hojas de actividades y casos de estudio
- [x] Generamos rubricas de evaluacion
- [x] Combinamos Chat + Studio para producir materiales
- [x] Organizamos didacticamente el contenido

➡️ [Ir al Bloque 4: Proyecto Final](../04-Proyecto-Final/README.md)
