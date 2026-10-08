---
name: divulgacion
description: Crea guiones de divulgación (ciencia, tecnología, software, matemáticas o cualquier tema complejo explicado a público general) para video corto (TikTok, Reels, Shorts) y largo (YouTube), además de ganchos, títulos, estructuras y revisiones de guion. Usa esta skill siempre que alguien quiera explicar un tema técnico de forma interesante, escribir o mejorar un guion educativo, idear el gancho o el título de un video de divulgación, convertir un paper, una noticia o un tutorial en contenido para redes, o planear una serie de contenido educativo, aunque no diga "divulgación" ni "guion". También sirve para charlas, talleres y posts que expliquen tecnología a personas no expertas.
---

# Divulgación: guiones que hacen entender y querer saber más

Divulgar es acercar a alguien a un conocimiento que no entendería solo, de forma que se quede con ganas de más. No se busca el subidón (adrenalina, miedo, estímulo vacío). Se busca la **recompensa ganada**: el momento "¡ya entendí!". La estructura narrativa es la misma que la del entretenimiento épico; lo que cambia es el combustible: la tensión es **"¿cómo es posible?"** y no "¿lo conseguirá?".

Esta skill sale del análisis de más de 50 videos (Jaime Altozano, Veritasium, 3Blue1Brown, Fireship, Nate Gentile, Mark Rober, Sebastian Lague, Branch Education, Kurzgesagt, divulgadores de TikTok con métricas reales) y de marcos de storytelling (ABT de Randy Olson, "But/Therefore" de Trey Parker, el manual de MrBeast y la investigación de Derek Muller sobre aprendizaje con video). La evidencia detallada está en `references/`.

## Flujo de trabajo

### 1. Brief (no escribas antes de tenerlo)
Averigua o deduce lo siguiente. Pregunta solo lo que de verdad falte y propón valores por defecto razonables:
- **Tema** y qué debe entender el espectador al final (una frase).
- **Público:** quién es, qué sabe ya y qué le preocupa. Si hay varios segmentos, elige uno principal para este video.
- **Formato:** corto (15–90 s), medio (3–8 min) o largo (8–40 min). Plataforma.
- **Perfil de voz/marca:** si el usuario tiene un perfil en `perfiles/` (o en su proyecto), léelo y respétalo. Si no, pregunta por el tono o usa uno cercano, claro y apasionado sin exagerar.
- **Material fuente:** papers, notas, código, enlaces. Si no hay, investiga y anota las fuentes.

### 2. Encuentra el ángulo (lo más importante)
Antes de estructurar, contesta por escrito:
1. **¿Cuál es la pregunta "¿cómo es posible?"** que hace interesante el tema? (Shazam reconoce una canción entre millones en segundos. ¿Cómo?)
2. **¿Por qué es difícil?** La dificultad del problema es lo que hace que la respuesta se sienta grandiosa. Sin dificultad no hay recompensa.
3. **¿Cuál es el error común** o la intuición equivocada del público? Muller demostró que una explicación clara pero que no toca el error previo no enseña: el espectador se siente seguro y no aprende.
4. **¿Por qué le importa a este espectador, hoy, en su vida?** Si el gancho habla de ti, de tu institución o de tu proyecto en lugar del espectador, el video no despega (en los datos, las cuentas institucionales bien producidas obtuvieron cientos de vistas frente a millones de las que hablaban desde el espectador).
5. **La frase ABT:** "[Contexto] Y [contexto], PERO [problema o misterio], POR LO TANTO [lo que vamos a descubrir]". Si no puedes escribir esta frase, todavía no tienes historia; tienes una lista de datos.

Propón 2–3 ángulos distintos cuando el tema lo permita y recomienda uno.

### 3. Elige la estructura
- **Corto (15–90 s):** lee `references/formato-corto.md`. Una sola idea, un mecanismo, una analogía.
- **Medio o largo:** lee `references/formato-largo.md`. Una cadena de preguntas con escalera de tensión y momentos para recuperar la atención.
- Para el gancho, consulta `references/ganchos.md` (tipos con ejemplos reales y métricas).
- Si el tema pide una forma particular (historia de una persona, sin conflicto, inspiracional), consulta `references/marcos-storytelling.md`.
- Si el usuario pide "al estilo de" un creador o necesitas un modelo concreto (diario de programación, historia de un inventor, desmontar un aparato), consulta `references/referentes.md`.
- El gancho sensacional y accesible es la **puerta de entrada**, no todo el contenido. Entra por lo que el público ya busca y llévalo a un mundo más grande (Johnny Harris: "meter las verduras").

### 4. Escribe el guion
Usa la plantilla de `assets/plantilla-guion.md`. Para cada bloque, indica **qué se dice**, **qué se ve** y **para qué está** (su función). Principios de escritura:

- **Densidad, no velocidad.** Los divulgadores exitosos hablan a unas 190–210 palabras/min tanto en TikTok como en YouTube. La velocidad no distingue los videos que funcionan; lo que distingue es que **no hay relleno**: ni saludo, ni "en este video vamos a ver", ni frases que no cambien lo que el espectador entiende. Une las ideas con "pero" y "por lo tanto", no con "y además".
- **Demuestra antes de explicar.** Primero el fenómeno (el sonido, el código ejecutándose, el objeto, la gráfica) y después el porqué.
- **Una analogía cotidiana por cada concepto difícil:** la huella dactilar para el audio, el quarterback que lanza a donde estará el receptor, las capas de una cebolla. Si la analogía tiene límites, dilo.
- **Personas, no solo datos.** Quién tuvo el problema, qué intentó, dónde se frustró (Wang de Shazam pensó que no podría lograrlo).
- **Pasión específica.** Señala el detalle exacto que te emociona ("la pieza dura 4 minutos y tiene **un solo acorde**"), en lugar de entusiasmo genérico ("¡esto es increíble!"). El cringe aparece cuando la emoción actuada es más grande que lo que se está contando.
- **Rigor visible.** Datos con fuente. Lo aproximado se dice como aproximado ("los diagramas son aproximaciones", como hace Branch Education). Nunca inventes cifras, estudios ni citas: si un dato hace falta y no está verificado, márcalo `[VERIFICAR: …]`.
- **El humor baja la tensión, no la sustituye.** Úsalo en apartes, entre subidas.

### 5. Revisa
Pasa el guion por `references/checklist.md`. Lee cada frase y pregúntate qué cambia en la cabeza del espectador; si la respuesta es nada, córtala. Comprueba que el gancho cumple lo que promete el título y que el video da **más** de lo que promete ("reality must beat expectations").

### 6. Entrega
Presenta, en este orden:
1. **El ángulo elegido** y la frase ABT.
2. **El guion** con la plantilla.
3. **3 opciones de título o gancho** honestas ("legitbait": atractivas pero verdaderas; el problema en el título, no la jerga).
4. **Notas de producción** breves: visuales clave, demostraciones, recursos libres.
5. **Fuentes y datos por verificar.**
6. **Qué medir:** guardados y compartidos (utilidad y conexión) en corto; porcentaje del video visto en largo.

Si el usuario solo pide una parte (un gancho, una revisión, ideas para una serie), entrega esa parte aplicando los mismos principios. No hace falta el paquete completo.

## Perfiles de voz y marca
La skill es general. La voz, los públicos, los valores y las líneas rojas de cada creador viven en un archivo de perfil (ver `perfiles/_plantilla.md` y el ejemplo `perfiles/ejemplo-canal-tecnologia.md`; cada creador agrega el suyo como `perfiles/<su-marca>.md`). Cuando exista un perfil:
- Adapta los ejemplos y analogías al mundo del público del perfil.
- Respeta sus "no es" (por ejemplo, no alarmista, no consumista).
- Los valores se notan en el **porqué** y el **para quién** del video ("para ayudar a tus papás", "para servir a tu comunidad"), no en jerga interna ni en temas que solo entiende el grupo. En los datos, el mismo creador obtuvo 834K vistas con un tema universal y 8K con un tema interno explicado con jerga.

## Cuándo romper las reglas
Estas son heurísticas basadas en evidencia, no leyes. Tom Scott retiene sin edición; tecnitips llegó a 1.1M casi sin cortes; Sebastian Lague empieza con "Hello everyone" y es excelente. Lo que nunca se negocia es: el espectador en el centro, densidad, rigor y una recompensa real al final.
