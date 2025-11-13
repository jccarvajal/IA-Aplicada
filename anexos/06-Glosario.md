### Anexo 06: Glosario Unificado

#### Introducción: Un Lenguaje Común

Este anexo es el léxico centralizado de "Inteligencia Artificial Aplicada". La terminología en este campo es precisa, y un malentendido conceptual puede llevar a errores de arquitectura. Este glosario no es solo una lista de definiciones; es un mapa de referencia cruzada que conecta los conceptos clave con las guías donde se exploran en profundidad. Úsalo para solidificar tu comprensión y asegurar que todo el equipo hable el mismo idioma.

---

#### Léxico de "Inteligencia Artificial Aplicada"

**Abdicación vs. Aumento (Abdication vs. Augmentation)**

* **Definición:** El dilema central de la sinergia. **Abdicación** es la tendencia humana a confiar ciegamente en la IA, dejando de pensar y convirtiéndose en un "pulsador de botones". **Aumento** es el uso de la IA para eliminar el trabajo de "Sistema 1" y liberar al humano para que se enfoque en el "Sistema 2" (criterio, estrategia).  
* **Referencia Principal:** Guía 10 (Humanidad, Ética y Confianza).

**Agente (Agent)**

* **Definición:** Un sistema de IA que va más allá de la simple respuesta. Un agente puede razonar, planificar, descomponer tareas complejas y utilizar "herramientas" (como APIs o bases de datos) para ejecutar acciones de forma autónoma.  
* **Referencia Principal:** Guía 04 (Ingeniería de Agentes), Guía 05 (Diseño de Sistemas Cognitivos).

**Agente Enrutador (Router Agent)**

* **Definición:** Un tipo de agente "gerente" (o de metacognición) cuyo único trabajo es analizar una solicitud y dirigirla al agente especialista o al modelo de IA (LLM) más adecuado para esa tarea específica (ej: enviar tareas analíticas a Claude 3 Opus y tareas simples a Haiku).  
* **Referencia Principal:** Guía 05 (Diseño de Sistemas Cognitivos), Anexo 05 (Modelos y Mercado LLM).

**Agentes-como-Servicio (AaaS)**

* **Definición:** Una estrategia de adquisición (Anexo 05) donde se "contrata al especialista". Es un producto de IA terminado (ej. Perplexity, Copilot) que se consume vía suscripción, ofreciendo rápida implementación a cambio de baja flexibilidad técnica.
* **Referencia Principal:** Anexo 05 (Modelos y Mercado LLM).

**Ajuste Fino (Fine-Tuning)**

* **Definición:** El proceso de re-entrenar un modelo de IA preexistente (como Llama 3\) usando un conjunto de datos más pequeño y específico. No le enseña nuevo conocimiento, sino que ajusta su comportamiento, tono, estilo o su habilidad para realizar una tarea muy específica.  
* **Referencia Principal:** Anexo 01 (Ajuste Fino y Adaptación de Modelos).

**Alucinación (Hallucination)**

* **Definición:** Un riesgo operacional crítico donde el LLM genera información que es factualmente incorrecta, inventada o contradictoria, pero la presenta con total confianza y elocuencia. Es una "mentira" no intencional.  
* **Referencia Principal:** Guía 07 (Gobernanza de IA), Guía 08 (Evaluación, Calidad y Validación de IA).

**Amnesia Estática (Static Amnesia)**

* **Definición:** Un término conceptual (basado en la "amnesia anterógrada" de la investigación) para describir la limitación fundamental de la arquitectura Transformer. Es la incapacidad estructural del modelo para consolidar nueva información (aprendida de las interacciones) en su memoria a largo plazo (los pesos del modelo) después de que finaliza su entrenamiento.
* **Referencia Principal:** Guía 02 (Ingeniería de Contexto y Memoria), Guía 13 (Perspectivas y Futuro de la IA).

**Aprendizaje Anidado (Nested Learning)**

* **Definición:** Un paradigma de arquitectura de IA que se perfila como el sucesor del Transformer. Propuesto por Google Research (NeurIPS 2025), abandona las "capas de cómputo" estáticas por "capas de cognición" que operan y se actualizan a múltiples frecuencias (escalas de tiempo).
* **Referencia Principal:** Guía 13 (Perspectivas y Futuro de la IA).

**Aprendizaje Continuo (Continual Learning)**

* **Definición:** El objetivo de las arquitecturas de próxima generación (como "Nested Learning"). Es la capacidad de un modelo de IA para aprender continuamente de nuevas interacciones y datos sin sufrir un "olvido catastrófico" (olvidar lo que sabía antes). Es la solución a la "Amnesia Estática".
* **Referencia Principal:** Guía 13 (Perspectivas y Futuro de la IA).

**Auto-Modificable (Self-Modifying)**

* **Definición:** Una característica clave de los modelos de Aprendizaje Anidado. Es la capacidad del sistema para aprender y modificar su propio algoritmo de actualización, en lugar de depender de una regla de aprendizaje fija.
* **Referencia Principal:** Guía 13 (Perspectivas y Futuro de la IA).

**Basura Elocuente (Eloquent Bullshit)**

* **Definición:** El principal producto de riesgo de la IA. Es el resultado de combinar una "basura cognitiva" (un prompt vago, sin criterio o mal formulado) con un LLM potente. La IA produce una respuesta fluida, profesional y convincente que es fundamentalmente incorrecta o inútil.  
* **Referencia Principal:** Guía 11 (Aprender a Pensar con IA).

**Benchmark (o Golden Set)**

* **Definición:** Un conjunto de datos de evaluación (el "Set Dorado") que contiene ejemplos de preguntas (prompts) y sus respuestas ideales validadas por humanos. Se utiliza como la "pista de pruebas" estándar para medir la calidad y el rendimiento de un sistema de IA de forma objetiva.  
* **Referencia Principal:** Guía 08 (Evaluación, Calidad y Validación de IA).

**Blueprint**

* **Definición:** Un caso de estudio práctico y un plano de arquitectura. Es la plantilla que conecta la teoría de las Guías y la técnica de los Anexos para resolver un problema de negocio específico, detallando los ingredientes, el flujo y la sinergia resultante.  
* **Referencia Principal:** Anexo 02 (Lecciones de Implementación).

**Brecha de Aprendizaje (Learning Gap)**

* **Definición:** El concepto central de la obra. Describe por qué la mayoría de los pilotos de IA fracasan (el 95%). Se debe a que las herramientas genéricas son "tontas" y operan sin memoria, lo que se manifiesta en tres fallos: no recuerdan el contexto, no aprenden del feedback y no se adaptan al flujo de trabajo.
* **Referencia Principal:** Guía 02 (Ingeniería de Contexto y Memoria).

**Brecha GenAI (GenAI Divide)**

* **Definición:** Término de la industria (2025) que describe la amplia brecha entre la alta experimentación con IA Generativa (la mayoría de las organizaciones) y el bajo retorno de inversión tangible (el 5% que logra impacto real en el negocio ). También se le conoce como la "Brecha de Escalamiento" (Scaling Gap), ya que los sondeos muestran que la mayoría de las empresas (62%) están atascadas en fases de "Experimentación" o "Pilotaje" y no logran escalar el valor a nivel empresarial.  
* **Referencia Principal:** Guía 12 (Estrategia y Valor en la Era de la IA).

**Bucle de Costos (Cost Loop)**

* **Definición:** Un riesgo operacional crítico donde un agente autónomo, usualmente operando en un ciclo ReAct, entra en un bucle (loop) infinito. Esto causa que el agente ejecute miles de llamadas a la API sin control, generando un gasto masivo e imprevisto.
* **Referencia Principal:** Guía 07 (Gobernanza de IA), Guía 05 (Diseño de Sistemas Cognitivos).

**Chain-of-Thought (CoT)**

* **Definición:** Una técnica de *prompting* (Guía 01) y un patrón de razonamiento (Guía 05). Consiste en forzar al modelo a explicar su razonamiento "paso a paso" antes de dar la respuesta final, lo que aumenta la precisión en tareas lógicas.
* **Referencia Principal:** Guía 01 (Ingeniería de Prompts), Guía 05 (Diseño de Sistemas Cognitivos).

**Co-Piloto Estratégico**

* **Definición:** El rol humano evolucionado en la sinergia Humano-IA. El Co-Piloto no es un "usuario" pasivo que "pide" tareas, sino un "operador" activo que "instruye", "valida" y "audita" a la IA, usando su criterio de "Sistema 2" para dirigir la herramienta. Ver también "Prosumer".  
* **Referencia Principal:** Guía 11 (Aprender a Pensar con IA).

**Compactación (de Contexto)**

* **Definición:** Una estrategia de ingeniería de contexto donde, en una conversación larga, el sistema usa un LLM para resumir automáticamente el historial de chat anterior, preservando el contexto clave sin exceder la Ventana de Contexto.  
* **Referencia Principal:** Guía 02 (Ingeniería de Contexto y Memoria).

**Costo Cuadrático (Quadratic Cost)**

* **Definición:** La principal limitación de costo y rendimiento de la arquitectura Transformer. Se refiere al hecho de que el costo computacional y el uso de memoria crecen exponencialmente ($O(n^2)$) con la longitud de la Ventana de Contexto, haciendo que procesar secuencias muy largas sea extremadamente costoso.
* **Referencia Principal:** Guía 02 (Ingeniería de Contexto y Memoria).

**Datos Sintéticos (Synthetic Data)**

* **Definición:** Una táctica de Estrategia de Datos donde se utiliza un modelo de IA potente para generar un gran volumen de ejemplos de entrenamiento de alta calidad. Es la fuente de datos clave para el Ajuste Fino.
* **Referencia Principal:** Guía 03 (Estrategia de Datos), Anexo 01 (Ajuste Fino).

**Estrategia de Datos (Data Strategy)**

* **Definición:** El plan maestro para la adquisición, almacenamiento, limpieza, seguridad y (crucialmente) vectorización de los datos propietarios de una organización. Define el "combustible" que alimentará a los sistemas RAG y de Ajuste Fino.  
* **Referencia Principal:** Guía 03 (Estrategia de Datos).

**Foso Competitivo (Moat)**

* **Definición:** La ventaja estratégica defendible que una empresa construye con IA. El glosario argumenta que el "foso" no es el modelo LLM (que es un commodity), sino los datos propietarios (para RAG), los datos de juicio humano (para Ajuste Fino) y la eficiencia de la Gobernanza (Guía 07 y Guía 09).  
* **Referencia Principal:** Guía 12 (Estrategia y Valor en la Era de la IA).

**Framework PPP (Productividad, Proactividad y Personalización)**

* **Definición:** Un *framework* de Gobernanza y Evaluación (introducido en la Guía 07), basado en investigaciones de 2025 (Sun, et al.), para medir la calidad de un agente de IA. Establece que el éxito de un agente no solo depende de la **Productividad** (completar la tarea), sino también de la **Proactividad** (gestionar la ambigüedad) y la **Personalización** (adaptarse al usuario).
* **Referencia Principal:** Guía 07 (Gobernanza de IA).

**Gobernanza de Datos (Data Governance)**

* **Definición:** El "Pre-Juego" de la Gobernanza de IA. Es el marco de políticas para controlar la *fuente* de datos (el "combustible"). Incluye la Catalogación (metadata), el Control de Acceso (seguridad) y la Gestión del Ciclo de Vida (archivar datos obsoletos).
* **Referencia Principal:** Guía 03 (Estrategia de Datos).

**Gobernanza de IA (AI Governance)**

* **Definición:** El marco de políticas, procesos y controles técnicos para gestionar la IA de forma segura, ética y eficiente. Su objetivo es maximizar el valor mientras se mitigan los riesgos clave (alucinaciones, fugas de datos, inyección de prompts, costos).  
* **Referencia Principal:** Guía 07 (Gobernanza de IA).

**Hiper-Personalización**

* **Definición:** Un modelo de negocio habilitado por la IA. Es la capacidad de usar agentes para ofrecer un servicio de "conserje" personalizado a millones de clientes simultáneamente, un servicio que antes era económicamente inviable y se reservaba solo para clientes "premium".  
* **Referencia Principal:** Guía 12 (Estrategia y Valor en la Era de la IA).

**Humano-en-el-Bucle (Human-in-the-Loop)**

* **Definición:** Un control de Gobernanza (Guía 07) y Sinergia (Guía 10). Es un punto de control obligatorio donde un agente autónomo debe detenerse y pedir validación a un humano antes de ejecutar una acción crítica o peligrosa (ej. enviar un email, gastar dinero).
* **Referencia Principal:** Guía 06 (Prototipado y Experimentación), Guía 05 (Diseño de Sistemas Cognitivos), Guía 10 (Humanidad, Ética y Confianza).

**IA Corpórea (Embodied AI)**

* **Definición:** Una perspectiva futura de la IA donde los "agentes" salen de la pantalla y se integran con la robótica. Es la fusión de los LLM (para entender el lenguaje natural) con cuerpos robóticos (para ejecutar acciones físicas en el mundo real).  
* **Referencia Principal:** Guía 13 (Perspectivas y Futuro de la IA).

**IA en la Sombra (Shadow AI)**

* **Definición:** Término de la industria (2025) para el uso no autorizado de herramientas de IA públicas (ej. ChatGPT personal) por parte de empleados para tareas laborales. Es un riesgo de gobernanza principal por la fuga de datos sensibles.  
* **Referencia Principal:** Guía 07 (Gobernanza de IA).

**Industrialización (Industrialization)**

* **Definición:** El proceso de llevar un prototipo de IA funcional (Guía 06\) a un sistema de nivel de producción: escalable, confiable, monitoreado y mantenible. Ver LLM-Ops.  
* **Referencia Principal:** Guía 09 (Industrialización de IA).

**Ingeniería de Prompts (Prompt Engineering)**

* **Definición:** La disciplina de diseñar y estructurar instrucciones (prompts) de manera clara, contextualizada y precisa para obtener respuestas controladas, predecibles y de alta calidad por parte de un LLM.  
* **Referencia Principal:** Guía 01 (Ingeniería de Prompts).

**Inyección de Prompts (Prompt Injection)**

* **Definición:** El principal riesgo de seguridad de los LLM. Ocurre cuando un usuario malicioso introduce instrucciones ocultas dentro de un prompt legítimo (ej: en un documento que el RAG va a leer) para secuestrar el comportamiento del agente y forzarlo a ignorar sus directrices originales.  
* **Referencia Principal:** Guía 07 (Gobernanza de IA).

**Latencia (Latency)**

* **Definición:** Una métrica de rendimiento (eficiencia). Es el tiempo total que tarda el sistema de IA en procesar una solicitud y entregar la respuesta final al usuario.  
* **Referencia Principal:** Guía 08 (Evaluación, Calidad y Validación de IA).

**Licencia Social (Social License)**

* **Definición:** La aceptación, aprobación y confianza continua que la sociedad (usuarios, clientes, ciudadanos) otorga a un proyecto de IA. Es un "permiso" ético e informal, distinto del legal, que se gana demostrando justicia, transparencia y operación responsable.
* **Referencia Principal:** Guía 10 (Humanidad, Ética y Confianza).

**LLM (Large Language Model)**

* **Definición:** Un modelo de IA entrenado con un volumen masivo de texto. Su función es predecir la siguiente palabra más probable en una secuencia basándose en el contexto proporcionado. No "piensa", sino que calcula probabilidades.
* **Referencia Principal:** Guía 01 (Ingeniería de Prompts).

**LLM-como-Juez (LLM-as-a-judge)**

* **Definición:** Una táctica de Evaluación (Guía 08). Consiste en usar un LLM de máxima potencia (ej. GPT-4o) como un "robot de QA". Se le entrega la Rúbrica de Evaluación (Anexo 03) como prompt para que califique de forma rápida y escalable las respuestas del agente.
* **Referencia Principal:** Guía 08 (Evaluación, Calidad y Validación de IA).

**LLM-Ops (Large Language Model Operations)**

* **Definición:** Una especialización de DevOps. Es el conjunto de prácticas de ingeniería para gestionar el ciclo de vida completo de las aplicaciones de LLM, incluyendo la gestión de datos, el versionado de prompts, la evaluación (QA) y el monitoreo de costos y rendimiento en producción.  
* **Referencia Principal:** Guía 09 (Industrialización de IA).

**LoRA / QLoRA**

* **Definición:** (Low-Rank Adaptation) La técnica de ingeniería clave para el Ajuste Fino eficiente. En lugar de re-entrenar el modelo completo (miles de millones de parámetros), "congela" el modelo base e inserta una pequeña "capa adaptadora" que es la única que se entrena. QLoRA es una versión aún más eficiente en memoria.  
* **Referencia Principal:** Anexo 01 (Ajuste Fino y Adaptación de Modelos).

**Memoria Continua (Continuum Memory)**

* **Definición:** Un sistema de memoria que generaliza la visión tradicional de memoria "a corto/largo plazo". Permite al modelo un acceso y consolidación fluidos a través de múltiples escalas de tiempo (corta, media y larga).
* **Referencia Principal:** Guía 13 (Perspectivas y Futuro de la IA).

**Metacognición (Metacognition)**

* **Definición:** Literalmente, "pensar sobre el pensamiento". En IA, se refiere a la capacidad de un sistema (usualmente un Agente Enrutador) para analizar una tarea, descomponerla y decidir qué proceso o agente especialista es el mejor para resolverla.  
* **Referencia Principal:** Guía 05 (Diseño de Sistemas Cognitivos).

**Modelos Open-Source (Ejecución Local)**

* **Definición:** Una estrategia de adquisición (Anexo 05) donde se "compra la máquina". El modelo (ej. Llama, Mistral) se ejecuta en infraestructura propia, dando **Control** y **Soberanía de Datos** total. Es clave para el Ajuste Fino.
* **Referencia Principal:** Anexo 05 (Modelos y Mercado LLM).

**Modelos Pequeños (SLMs)**

* **Definición:** (Small Language Models). Una tendencia clave (Guía 13) de modelos (ej. Phi-3, Llama 4-8B) diseñados para ejecutarse localmente en dispositivos (On-Device). Ofrecen Privacidad Total y Latencia Cero, revolucionando el **Control** y el **Costo**.
* **Referencia Principal:** Guía 13 (Perspectivas y Futuro de la IA).

**Modelos Propietarios (APIs)**

* **Definición:** Una estrategia de adquisición (Anexo 05) donde se "arrienda el cerebro". Se accede al modelo (ej. GPT, Claude) a través de una API, pagando por token. Prioriza el **Rendimiento** sobre el **Control**.
* **Referencia Principal:** Anexo 05 (Modelos y Mercado LLM).

**Multimodalidad (Multimodality)**

* **Definición:** La capacidad de los LLM modernos (Guía 13) de procesar múltiples tipos de *input* (modalidades) más allá del texto, incluyendo imágenes, audio y video.
* **Referencia Principal:** Guía 13 (Perspectivas y Futuro de la IA), Guía 02 (Ingeniería de Contexto y Memoria).

**Observabilidad (Observability)**

* **Definición:** Un pilar de la Gobernanza (Guía 07). Es la capacidad de ver lo que está sucediendo dentro del sistema de IA en tiempo real: qué prompts recibe, qué respuestas genera, cuántos tokens consume, qué tan seguido alucina. No puedes gobernar lo que no puedes ver.  
* **Referencia Principal:** Guía 07 (Gobernanza de IA), Guía 08 (Evaluación, Calidad y Validación de IA).

**Patrones de Razonamiento (Reasoning Patterns)**

* **Definición:** Estructuras de pensamiento algorítmico que se diseñan para los agentes. Ejemplos incluyen Chain of Thought (pensar paso a paso), ReAct (razonar y luego actuar) y Tree of Thoughts (explorar múltiples caminos).  
* **Referencia Principal:** Guía 05 (Diseño de Sistemas Cognitivos).

**Pensamiento Algorítmico**

* **Definición:** Una habilidad cognitiva humana clave (Guía 11). Es la capacidad de descomponer un problema complejo del mundo real en una secuencia de pasos lógicos (un algoritmo) que pueden ser ejecutados por un Co-Piloto de IA.  
* **Referencia Principal:** Guía 11 (Aprender a Pensar con IA).

**Personalización (dentro del Framework PPP)**

* **Definición:** En el contexto del **Framework PPP** (Guía 07), la 'Personalización' es la métrica de calidad de interacción que mide la habilidad del agente para reducir la fricción adaptando su estilo (tono, formato, etc.) a las preferencias del usuario.
* **Referencia Principal:** Guía 07 (Gobernanza de IA), Guía 10 (Humanidad, Ética y Confianza).

**Proactividad (dentro del Framework PPP)**

* **Definición:** En el contexto del **Framework PPP** (Guía 07), la 'Proactividad' es la métrica de calidad de interacción que mide la habilidad del agente para gestionar la ambigüedad. Un agente proactivo identifica instrucciones vagas y solicita aclaraciones estratégicas ("preguntas de bajo esfuerzo").
* **Referencia Principal:** Guía 07 (Gobernanza de IA).

**Productividad (dentro del Framework PPP)**

* **Definición:** En el contexto del **Framework PPP** (Guía 07), la 'Productividad' es la métrica *baseline* que mide la eficacia del agente, es decir, su Tasa de Éxito en la Tarea (Task Success Rate). Es la métrica que se mide en la Guía 08 (Evaluación).
* **Referencia Principal:** Guía 07 (Gobernanza de IA), Guía 08 (Evaluación, Calidad y Validación de IA).

**Prosumer**

* **Definición:** Término de la industria (2025) para un "productor" y "consumidor" experto de IA. Es el "power user" (usuario avanzado) que, a menudo usando "Shadow AI", desarrolla un alto nivel de alfabetización cognitiva y se convierte en un "Co-Piloto Estratégico", impulsando la adopción y los casos de uso prácticos.  
* **Referencia Principal:** Guía 11 (Aprender a Pensar con IA).

**Prompt**

* **Definición:** La instrucción o conjunto de instrucciones (texto, imágenes) que el usuario proporciona al LLM para iniciar una tarea. Es la entrada fundamental del sistema.  
* **Referencia Principal:** Guía 01 (Ingeniería de Prompts).

**Prototipado (Prototyping)**

* **Definición:** El proceso rápido y de bajo costo para validar una hipótesis de IA. Su objetivo no es construir un sistema robusto, sino "matar malas ideas rápidamente" y aprender sobre la viabilidad de un agente, un prompt o un flujo de datos antes de invertir en la Industrialización (Guía 09).  
* **Referencia Principal:** Guía 06 (Prototipado y Experimentación).

**Quick Win (Victoria Rápida)**

* **Definición:** El objetivo central del Prototipado (Guía 06). Es un caso de uso piloto que busca el **Máximo Valor de Negocio** con el **Mínimo Riesgo Técnico y de Seguridad**, para demostrar valor sin "hervir el océano".
* **Referencia Principal:** Guía 06 (Prototipado y Experimentación).

**RAG (Retrieval-Augmented Generation)**

* **Definición:** La arquitectura de sistema más común para dar "memoria" a largo plazo a un LLM. El sistema **Recupera (Retrieves)** información relevante de una base de datos externa (usualmente vectorizada) y la **Aumenta (Augments)**, inyectándola en el prompt del LLM como contexto justo a tiempo.  
* **Referencia Principal:** Guía 02 (Ingeniería de Contexto y Memoria).

**ReAct (Reason + Act)**

* **Definición:** El "motor" o patrón de razonamiento fundamental de un Agente (Guía 04). El agente opera en un bucle (loop) donde genera un **Razonamiento** (el plan) y luego una **Acción** (el uso de una herramienta) para alcanzar un objetivo.
* **Referencia Principal:** Guía 04 (Ingeniería de Agentes), Guía 05 (Diseño de Sistemas Cognitivos).

**Reflexión (Reflection)**

* **Definición:** Un patrón de razonamiento (Guía 05) donde un agente genera un primer borrador y luego invoca a un "agente crítico" (o a sí mismo en un rol de auditor) para que revise, critique y corrija su propio trabajo, mejorando la fiabilidad.
* **Referencia Principal:** Guía 05 (Diseño de Sistemas Cognitivos).

**Rotura de Contexto (Context Rot)**

* **Definición:** Un problema operacional (Guía 02) que ocurre cuando la Ventana de Contexto (la "pizarra") se sobrecarga de tokens. Causa que la IA "olvide" instrucciones clave (el "Punto Ciego") o se confunda por el "Ruido".
* **Referencia Principal:** Guía 02 (Ingeniería de Contexto y Memoria).

**Rúbrica de Evaluación (Evaluation Rubric)**

* **Definición:** Una plantilla de calificación (Anexo 03) usada en la Evaluación (Guía 08) para medir objetivamente la calidad de la respuesta de un agente. Incluye métricas clave como Facticidad, Relevancia, Tono y Seguridad.
* **Referencia Principal:** Guía 08 (Evaluación, Calidad y Validación de IA), Anexo 03 (Plantillas y Recursos).

**Sinergia Humano-IA (Human-AI Synergy)**

* **Definición:** La arquitectura de trabajo donde la IA y los humanos se fusionan en un solo flujo. Se basa en dividir el trabajo: la IA ejecuta el "Sistema 1" (tareas tácticas, rápidas, de bajo juicio) y el humano se enfoca en el "Sistema 2" (estrategia, validación, empatía, criterio).  
* **Referencia Principal:** Guía 10 (Humanidad, Ética y Confianza).

**Sistema 1 / Sistema 2**

* **Definición:** Un modelo de la psicología humana usado para definir la Sinergia Humano-IA. **Sistema 1** es el pensamiento rápido, automático e instintivo (perfecto para delegar a la IA). **Sistema 2** es el pensamiento lento, analítico y deliberado (el nuevo rol del humano).  
* **Referencia Principal:** Guía 10 (Humanidad, Ética y Confianza).

**Sistema Cognitivo (Cognitive System)**

* **Definición:** Un sistema de IA que no solo responde, sino que también razona, planifica, usa herramientas y aprende (o se adapta) de sus interacciones, imitando un proceso de pensamiento estructurado.  
* **Referencia Principal:** Guía 05 (Diseño de Sistemas Cognitivos).

**Token**

* **Definición:** La unidad fundamental de procesamiento de un LLM. Un token no es una palabra; es una "pieza" de palabra (ej: "Gobernanza" pueden ser 3: "Gob", "er", "nanza"). Los costos y la Ventana de Contexto se miden en tokens.  
* **Referencia Principal:** Guía 02 (Ingeniería de Contexto y Memoria).

**Transformer**

* **Definición:** La arquitectura de IA fundamental que define la generación actual de LLMs (GPT, Llama, Gemini, etc.). Su mecanismo clave es la "auto-atención". Sus limitaciones estratégicas son el **Costo Cuadrático** (un problema de contexto) y la **Amnesia Estática** (un problema de memoria).
* **Referencia Principal:** Guía 02 (Ingeniería de Contexto y Memoria), Anexo 05 (Modelos y Mercado LLM).

**Tree of Thoughts (ToT)**

* **Definición:** Un patrón de razonamiento avanzado donde el agente explora múltiples caminos de razonamiento en paralelo (como un "Comité de Estrategia"), evalúa los pros y contras de cada uno, y descarta los callejones sin salida.
* **Referencia Principal:** Guía 05 (Diseño de Sistemas Cognitivos).

**Vectorización (Vectorization)**

* **Definición:** El proceso técnico de convertir datos no estructurados (como texto) en una representación numérica (un "vector") que captura su significado semántico. Esto permite que las bases de datos vectoriales realicen búsquedas por concepto en lugar de por palabra clave. Es el motor de RAG.  
* **Referencia Principal:** Guía 03 (Estrategia de Datos), Guía 02 (Ingeniería de Contexto y Memoria).

**Ventana de Contexto (Context Window)**

* **Definición:** La limitación de memoria más importante de un LLM. Es la cantidad máxima de información (medida en tokens) que el modelo puede "recordar" o procesar en una sola conversación. Todo lo que queda fuera de esta "pizarra blanca" se olvida instantáneamente.  
* **Referencia Principal:** Guía 02 (Ingeniería de Contexto y Memoria).

**Vigilante Estratégico**

* **Definición:** El rol permanente del arquitecto de IA después de construir la fábrica. Es la función de escanear el horizonte en busca de la próxima disrupción tecnológica, no por curiosidad, sino como una función de negocio para anticipar la obsolescencia de la fábrica actual.  
* **Referencia Principal:** Guía 13 (Perspectivas y Futuro de la IA).

**Web Agéntica (Agentic Web)**

* **Definición:** Concepto de la industria (mencionado en informes del MIT de 2025) que describe la siguiente evolución de la IA, más allá de los agentes individuales. Es una red persistente e interconectada de agentes autónomos que pueden colaborar, negociar y coordinar tareas entre sí a través de diferentes plataformas, dominios y organizaciones, utilizando protocolos de interoperabilidad (como NANDA, MCP o A2A ).
* **Referencia Principal:** Guía 13 (Perspectivas y Futuro de la IA) .

---
  <div style="display: flex; justify-content: space-between; font-size: 0.9em; padding-top: 10px;">
    <div>
      <a href="./05-Modelos-Mercado.html">« Anexo Anterior</a>
    </div>
    <div>
      <a href="../">Volver al Índice</a>
    </div>
    <div>
      <a href="./07-Bibliografia.html">Siguiente Anexo »</a>
    </div>
  </div>