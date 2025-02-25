# GROK 3

Grok es el nombre del modelo de inteligencia artificial de xAI, la empresa de IA de Elon Musk. Es un modelo de IA como los [Gemini](https://www.xataka.com/basics/google-gemini-que-como-funciona-diferencias-gpt-cuando-podras-usar-este-modelo-inteligencia-artificial) de Google o [GPT](https://www.xataka.com/basics/chatgpt-que-como-usarlo-que-puedes-hacer-este-chat-inteligencia-artificial) de OpenAI. En el caso de Grok, es el modelo que utiliza el chatbot Grok vinculado a la red social X, tanto que para poder utilizarlo necesitas tener una cuenta en esta red social.

### Modelos Grok 3 y diferencias con otros modelos

Con el razonamiento desactivado, Grok 3 ofrece respuestas instantáneas de alta calidad. Grok 3 ofrece los mejores resultados en diversas pruebas académicas entre los modelos de no razonamiento, incluyendo: conocimiento científico a nivel de posgrado (GPQA), conocimiento general (MMLU-Pro), problemas de competición matemática (AIME). Grok 3 también destaca en tareas de comprensión de imágenes (MMMU) y de vídeo (EgoSchema).

| Benchmark   |      | Grok 3 Beta | Grok 3 mini Beta | GPT-4o | Gemini 2.0 Pro | DeepSeek-V3 | Claude 3.5 Sonnet |
| :---------- | ---: | ----------: | ---------------: | -----: | -------------: | ----------: | ----------------: |
| AIME’24     |      |       52.2% |            39.7% |   9.3% |              — |       39.2% |             16.0% |
| GPQA        |      |       75.4% |            66.2% |  53.6% |          64.7% |       59.1% |             65.0% |
| LCB         |      |       57.0% |            41.5% |  32.3% |          36.0% |       33.1% |             40.2% |
| MMLU-pro    |      |       79.9% |            78.9% |  72.6% |          79.1% |       75.9% |             78.0% |
| LOFT (128k) |      |       83.3% |            83.1% |  78.0% |          75.6% |           — |             69.9% |
| SimpleQA    |      |       43.6% |            21.7% |  38.2% |          44.3% |       24.9% |             28.4% |
| MMMU        |      |       73.2% |            69.4% |  69.1% |          72.7% |           — |             70.4% |
| EgoSchema   |      |       74.5% |            74.3% |  72.2% |          71.9% |           — |                 — |

Con una ventana de contexto de 1 millón de tokens (8 veces mayor que nuestros modelos anteriores), Grok 3 puede procesar documentos extensos y manejar instrucciones complejas sin perder precisión en el seguimiento de instrucciones. En la prueba de referencia LOFT (128k), que se centra en casos de uso de RAG de contexto largo, Grok 3 alcanzó una precisión de vanguardia (promedio de 12 tareas distintas), lo que demuestra sus potentes capacidades de recuperación de información.

Grok 3 también demuestra una mayor precisión factual y un mayor control estilístico. Bajo el nombre en clave de «chocolate», una versión temprana de Grok 3 encabezó la clasificación de LMArena Chatbot Arena, superando a todos los competidores en puntuaciones Elo en todas las categorías. A medida que seguimos creciendo, nos preparamos para entrenar modelos aún mayores en nuestro clúster de 200.000 GPU.



![Chatbot Arena Score](https://x.ai/grok-3/arena.webp)



### Glosario Terminos desconocidos

1. **Razonamiento desactivado**: Modo en el que el modelo responde de forma rápida sin aplicar un análisis profundo o desglosar su lógica paso a paso. Es útil para respuestas instantáneas.
2. **Modelo de no razonamiento**: Un tipo de IA que genera respuestas sin realizar múltiples pasos de pensamiento lógico o análisis profundo.
3. **GPQA (Graduate-Level Physics Question Answering)**: Una prueba que mide el conocimiento de física a nivel de posgrado (universidad avanzada).
4. **MMLU-Pro (Massive Multitask Language Understanding - Professional Level)**: Un conjunto de pruebas que evalúa el conocimiento general y la comprensión de textos en diversas disciplinas a nivel profesional.
5. **AIME (American Invitational Mathematics Examination)**: Un examen de matemáticas de alto nivel utilizado en competencias internacionales. Evalúa la capacidad de resolver problemas matemáticos complejos.
6. **MMMU (MultiModal Multitask Understanding)**: Una prueba diseñada para evaluar la capacidad de una IA en comprender y analizar información combinada de texto e imágenes.
7. **EgoSchema**: Una evaluación que mide cómo un modelo de IA entiende y analiza vídeos desde una perspectiva en primera persona (como si viera a través de los ojos de alguien).
8. **Ventana de contexto**: La cantidad de información que una IA puede recordar y procesar en una sola interacción. Un millón de tokens equivale a leer y comprender miles de páginas de texto de una vez.
9. **Tokens**: Fragmentos de texto en los que la IA divide las palabras y frases para procesarlas. Por ejemplo, "inteligencia artificial" puede ser dos o tres tokens.
10. **RAG (Retrieval-Augmented Generation)**: Técnica de IA que combina generación de texto con recuperación de información externa para mejorar la precisión de las respuestas.
11. **LOFT (Long-Form Task Benchmark)**: Una prueba diseñada para evaluar cómo los modelos de IA manejan textos largos y siguen instrucciones detalladas.
12. **Clasificación de LMArena Chatbot Arena**: Un ranking que compara modelos de IA en base a la evaluación de usuarios y pruebas estandarizadas.
13. **Puntuaciones Elo**: Sistema de calificación utilizado en ajedrez y otras competencias para clasificar la habilidad de diferentes jugadores o, en este caso, modelos de IA.
14. **"Chocolate" (nombre en clave)**: Un alias interno para una versión temprana de Grok 3 utilizada en pruebas de rendimiento antes de su lanzamiento oficial.
15. **Cluster de 200,000 GPU**: Un conjunto de **200,000 unidades de procesamiento gráfico (GPU)** utilizadas para entrenar Grok 3. Estas GPUs permiten realizar cálculos masivos en paralelo, acelerando el aprendizaje del modelo.



### API Grok 3

Desde la pagina oficial de grok, se menciona que en las proximas semanas se hara un lanxamiento de su API platform, ofreciendo acceso a los modelos estandar y a los modelos de tazonamiento, ademas de que DeepSearch sera lanzado para empresas aliadas via API.

Actualmente, la **API de Grok 3** está en fase de desarrollo y se espera que esté disponible para integraciones empresariales en el **segundo trimestre de 2025**. El acceso anticipado para socios seleccionados comenzará en marzo de 2025. Los precios estarán basados en el volumen de uso, con una tarifa estimada de **0,0035 USD por cada 1.000 tokens** procesados. 

Grok 3: 

In the coming weeks, we will release Grok 3 and Grok 3 mini via our API platform, offering access to both the standard and reasoning models. `DeepSearch` will also be released to Enterprise partners via our API.



### Precios Grok 3

Grok 3, el modelo de inteligencia artificial desarrollado por xAI, está disponible principalmente a través de suscripciones en la plataforma X (anteriormente conocida como Twitter). A continuación, se detallan los costos asociados y su rentabilidad en entornos empresariales.

## Costos de Suscripción

- **X Premium+**: Para acceder a las funciones avanzadas de Grok 3, como sus capacidades de razonamiento y la herramienta DeepSearch, es necesario suscribirse al plan X Premium+. Este plan ha experimentado incrementos recientes en su tarifa mensual en Estados Unidos:

  - **Diciembre de 2024**: de $16 a $22 mensuales.

  - Febrero de 2025

    : de $22 a $50 mensuales. 

    [Europa Press](https://www.europapress.es/portaltic/socialmedia/noticia-aumenta-precio-suscripcion-premium-50-dolares-mensuales-estados-unidos-20250218101327.html?utm_source=chatgpt.com)

- **SuperGrok**: xAI ha introducido un nuevo plan de suscripción llamado SuperGrok, que ofrece las capacidades más avanzadas de Grok 3 y acceso anticipado a nuevas funciones. Este plan tiene un costo de $30 mensuales o $300 anuales, lo que representa un ahorro del 16.6% en comparación con el pago mensual. 

  [Xpert](https://xpert.digital/es/super-grok/?utm_source=chatgpt.com)

Actualmente, **Grok 3** está disponible para los suscriptores de **X Premium+** y **SuperGrok**. Estas suscripciones permiten a los usuarios interactuar con Grok 3 a través de la plataforma X (anteriormente Twitter) y la aplicación Grok. Sin embargo, este acceso se limita a la interfaz proporcionada por estas plataformas y no incluye la capacidad de integrar Grok 3 directamente en aplicaciones propias mediante código o API.



## Usar Grok 3 de forma gratuita

En caso de tener curiosidad de cara a conocer todo lo que puede ofrecer Grok 3, lo único necesario para probar este nuevo modelo de lenguaje de IA es **contar con una cuenta en X**. Sí, es imprescindible tener un perfil en la red social que antes era conocida como Twitter para poder acceder a todas las ventajas de Grok.

Teniendo un perfil en la red social, lo siguiente es visitar el siguiente [enlace](https://x.com/i/grok) que sirve como acceso directo a Grok. Eso sí, también se puede acceder desde la propia red social de tal forma que se encuentra entre los iconos de mensajes directos y listas de X. Una vez dentro de Grok hay que realizar un par de cambios.

Entre estos cambios se encuentra seleccionar el modelo de Grok a utilizar. Es posible que al entrar por primera vez a la IA de xAI la versión que aparezca no sea Grok 3. En caso de que esta sea tu situación, solo hará falta **seleccionar Grok 3** que aparece en su versión beta dentro de este apartado. Esto sería todo de cara a configurar este nuevo modelo de lenguaje.

**No queda claro cuánto tiempo estará disponible Grok 3 de forma gratuita**, aunque puede que sea un periodo lo suficientemente extendido como para que los usuarios puedan probar todas las capacidades de este nuevo modelo de lenguaje. Habrá que esperar para ver la respuesta del resto de empresas a esta propuesta por parte de xAI.