# Bloque 0: Preparacion - Generacion de Contenido con IA

**Duracion:** 30 minutos
**Objetivo:** Aprender a utilizar herramientas de IA (ChatGPT, Gemini, Copilot) para generar y recopilar contenido de calidad que luego alimentara nuestros notebooks en NotebookLM.

---

## Por que empezar con herramientas de IA?

Antes de entrar a NotebookLM, necesitamos **contenido de calidad** para alimentarlo. Las herramientas de IA nos permiten:

- Generar textos estructurados sobre cualquier tema
- Obtener resumenes de temas complejos
- Crear listados de fuentes y referencias
- Producir contenido en diferentes formatos (articulos, guias, glosarios)
- Adaptar el nivel del contenido a nuestra audiencia

---

## Herramientas de IA Disponibles

| Herramienta | URL | Mejor para |
|-------------|-----|------------|
| **ChatGPT** | chat.openai.com | Textos largos, analisis profundo, generacion creativa |
| **Google Gemini** | gemini.google.com | Integracion con Google, busqueda web actualizada |
| **Microsoft Copilot** | copilot.microsoft.com | Busqueda web con fuentes, integracion con Office |

---

## Estrategia de Prompting con Variables

La clave para obtener resultados utiles es usar **prompts estructurados** con variables que puedas personalizar segun tu especialidad.

### Anatomia de un Buen Prompt

```
[ROL] + [CONTEXTO] + [TAREA] + [FORMATO] + [RESTRICCIONES]
```

- **[ROL]:** Quien quieres que sea la IA
- **[CONTEXTO]:** Informacion de fondo
- **[TAREA]:** Que necesitas exactamente
- **[FORMATO]:** Como quieres la respuesta
- **[RESTRICCIONES]:** Limites, longitud, estilo

---

## Prompts Practicos con Variables

### PROMPT 1: Generar un Articulo Educativo Completo

```
Actua como un [ROL_EXPERTO] especializado en [ESPECIALIDAD].

Necesito que generes un articulo educativo completo sobre el tema:
"[TEMA_PRINCIPAL]"

El articulo debe estar dirigido a [AUDIENCIA] con un nivel de
conocimiento [NIVEL: basico/intermedio/avanzado].

Estructura del articulo:
1. Introduccion y contexto (por que es importante este tema)
2. Conceptos fundamentales (definiciones clave)
3. Desarrollo del tema (minimo 5 subtemas relevantes)
4. Aplicaciones practicas o ejemplos reales
5. Tendencias actuales y futuras
6. Conclusion y puntos clave para recordar
7. Glosario de terminos tecnicos

Formato: Usa encabezados claros, parrafos cortos, y listas
cuando sea apropiado. Extension minima: 2000 palabras.
```

**Ejemplo con caso practico (IA):**
- `[ROL_EXPERTO]` = profesor universitario de tecnologia
- `[ESPECIALIDAD]` = Inteligencia Artificial y Machine Learning
- `[TEMA_PRINCIPAL]` = Fundamentos de la Inteligencia Artificial: desde los conceptos basicos hasta las aplicaciones modernas
- `[AUDIENCIA]` = estudiantes universitarios de primer ano
- `[NIVEL]` = basico

---

### PROMPT 2: Generar un Glosario Tecnico

```
Actua como un [ROL_EXPERTO] en [ESPECIALIDAD].

Crea un glosario completo de los [CANTIDAD] terminos mas
importantes relacionados con "[TEMA_PRINCIPAL]".

Para cada termino incluye:
- Definicion clara y concisa (maximo 2 oraciones)
- Un ejemplo practico o analogia sencilla
- Categoria o subtema al que pertenece

Organiza los terminos por categorias tematicas, no alfabeticamente.
El nivel de explicacion debe ser adecuado para [AUDIENCIA].
```

**Ejemplo con caso practico (IA):**
- `[ROL_EXPERTO]` = investigador en IA
- `[ESPECIALIDAD]` = Inteligencia Artificial
- `[CANTIDAD]` = 30
- `[TEMA_PRINCIPAL]` = Inteligencia Artificial y sus ramas
- `[AUDIENCIA]` = profesionales no tecnicos

---

### PROMPT 3: Obtener Fuentes y Referencias Web

```
Actua como un [ROL_EXPERTO] y curador de contenido academico
en [ESPECIALIDAD].

Necesito que me proporciones una lista de [CANTIDAD] fuentes
confiables y actualizadas sobre "[TEMA_PRINCIPAL]" que incluya:

1. **Articulos web:** URLs de articulos relevantes de sitios
   reconocidos (universidades, revistas cientificas, medios
   especializados)
2. **Videos educativos:** Links de YouTube de canales reconocidos
   que expliquen el tema
3. **Documentos PDF:** Referencias a papers, guias o reportes
   descargables
4. **Cursos o tutoriales:** Plataformas con contenido gratuito
   sobre el tema

Para cada fuente indica:
- Titulo
- URL (si es posible)
- Breve descripcion de que cubre
- Nivel de dificultad (basico/intermedio/avanzado)
- Idioma

Prioriza fuentes en [IDIOMA] y que sean de los ultimos [PERIODO] anos.
```

**Ejemplo con caso practico (IA):**
- `[ROL_EXPERTO]` = profesor de tecnologia educativa
- `[ESPECIALIDAD]` = Inteligencia Artificial aplicada a la educacion
- `[CANTIDAD]` = 15
- `[TEMA_PRINCIPAL]` = Inteligencia Artificial: fundamentos, tipos y aplicaciones
- `[IDIOMA]` = espanol e ingles
- `[PERIODO]` = 2

---

### PROMPT 4: Generar Contenido por Subtemas

```
Actua como un [ROL_EXPERTO] en [ESPECIALIDAD].

Voy a crear un curso/clase sobre "[TEMA_PRINCIPAL]".
Necesito que generes contenido detallado para los siguientes
subtemas. Para CADA subtema genera un texto de [EXTENSION]
palabras:

Subtemas:
1. [SUBTEMA_1]
2. [SUBTEMA_2]
3. [SUBTEMA_3]
4. [SUBTEMA_4]
5. [SUBTEMA_5]

Cada texto debe incluir:
- Una introduccion que conecte con el tema principal
- Explicacion clara con ejemplos
- Al menos un caso practico o aplicacion real
- Datos o estadisticas relevantes (si aplica)
- Una pregunta de reflexion al final

El tono debe ser [TONO: academico/conversacional/tecnico]
y dirigido a [AUDIENCIA].
```

**Ejemplo con caso practico (IA):**
- `[ROL_EXPERTO]` = experto en IA
- `[ESPECIALIDAD]` = Inteligencia Artificial
- `[TEMA_PRINCIPAL]` = Inteligencia Artificial en el mundo actual
- `[EXTENSION]` = 500
- `[SUBTEMA_1]` = Que es la IA y como funciona
- `[SUBTEMA_2]` = Machine Learning vs Deep Learning
- `[SUBTEMA_3]` = IA Generativa: ChatGPT, DALL-E, Midjourney
- `[SUBTEMA_4]` = Etica y riesgos de la IA
- `[SUBTEMA_5]` = El futuro de la IA en la educacion
- `[TONO]` = conversacional
- `[AUDIENCIA]` = docentes de educacion superior

---

### PROMPT 5: Generar Preguntas y Respuestas para Estudio

```
Actua como un [ROL_EXPERTO] disenador instruccional
especializado en [ESPECIALIDAD].

Genera un banco de [CANTIDAD] preguntas sobre "[TEMA_PRINCIPAL]"
distribuidas asi:

- [N1] preguntas de opcion multiple (4 opciones, indica la correcta)
- [N2] preguntas de verdadero/falso (con justificacion)
- [N3] preguntas abiertas de desarrollo
- [N4] preguntas de aplicacion practica (casos o escenarios)

Nivel de dificultad: [NIVEL]
Audiencia: [AUDIENCIA]

Para cada pregunta incluye:
- La pregunta claramente formulada
- La respuesta correcta
- Una breve explicacion de por que es correcta

Organiza las preguntas por subtema o unidad tematica.
```

**Ejemplo con caso practico (IA):**
- `[ROL_EXPERTO]` = docente universitario
- `[ESPECIALIDAD]` = Inteligencia Artificial
- `[CANTIDAD]` = 20
- `[TEMA_PRINCIPAL]` = Fundamentos de Inteligencia Artificial
- `[N1]` = 8, `[N2]` = 4, `[N3]` = 4, `[N4]` = 4
- `[NIVEL]` = intermedio
- `[AUDIENCIA]` = estudiantes de ingenieria

---

## Ejercicio Practico del Bloque 0

### Paso a paso:

1. **Elige tu herramienta de IA** (ChatGPT, Gemini o Copilot)
2. **Copia el Prompt 1** y reemplaza las variables con tu especialidad
3. **Genera el articulo** y revisalo brevemente
4. **Copia el Prompt 2** y genera el glosario de tu tema
5. **Usa el Prompt 3** para obtener fuentes y enlaces
6. **Guarda todo el contenido generado** en archivos separados:
   - `articulo-[tu-tema].txt`
   - `glosario-[tu-tema].txt`
   - `fuentes-[tu-tema].txt`

### Tip importante:
> Guarda el contenido generado en archivos `.txt`, `.pdf` o `.docx` porque estos son los formatos que NotebookLM acepta como fuentes. Tambien puedes copiar URLs directamente.

---

## Que sigue?

Con el contenido generado, estamos listos para ir al **Bloque 1** donde cargaremos todo en Google NotebookLM y comenzaremos a crear nuestro primer notebook.

➡️ [Ir al Bloque 1: Creacion del Primer Notebook](../01-Primer-Notebook/README.md)
