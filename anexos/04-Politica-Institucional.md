
### **Anexo 04: Política Institucional de IA (Propuesta Marco)**

**(Subtítulo: Plantilla de Gobernanza para el Sector Público)**

#### **Propósito**

Esta es una plantilla marco de política institucional, diseñada para el sector público. No es un documento final, sino un punto de partida que debe ser adaptado al contexto legal y misional específico de cada institución.

Sintetiza los principios de gobernanza, ética y estrategia de esta obra (especialmente las Guías 07, 10 y 12\) con los fundamentos legales (como la Ley N° 19.628 de Chile) y los conceptos de "Licencia Social" y "Opacidad" discutidos en la "Guía Ética" (BID/UAI).

---

### **Política Institucional de Uso Responsable de Inteligencia Artificial** 

**Servicio Público de Chile**

#### **1\. Propósito**

Esta política establece los principios, normas y procedimientos que regulan el uso responsable, seguro y ético de la Inteligencia Artificial (IA) en el Servicio. Su objetivo es garantizar que su aplicación se oriente al interés público, la eficiencia institucional, la protección de los derechos fundamentales y la confianza ciudadana, asegurando que la IA se utilice para **aumentar** la capacidad humana, no para **abdicar** la responsabilidad.

#### **2\. Alcance**

Aplica a todas las unidades y funcionarios, así como a terceros que desarrollen o utilicen herramientas de IA en el marco de las funciones del Servicio, incluyendo tanto sistemas de **soporte de decisión** (que informan a un humano) como sistemas de **toma de decisión** (automatizados).

#### **3\. Principios Rectores**

Todo uso de la IA en el Servicio se regirá por:

1. **Legalidad y Proporcionalidad:** El uso de IA debe cumplir con el marco normativo vigente (ej. Ley 19.628, Ley 20.285) y ser **proporcional** al problema, evaluando siempre si la IA es la herramienta idónea y necesaria.  
2. **Principio de Criterio Humano (Delegar, No Abdicar):** La IA es una herramienta para **aumentar** la capacidad humana. Toda decisión de impacto requerirá supervisión humana significativa, reteniendo el funcionario el 100% de la responsabilidad final.  
3. **Gobernanza de la Fuente (Basura Entra, Basura Sale):** La calidad de un agente de IA es inseparable de la calidad de sus datos. El Servicio se compromete a una **Gobernanza de Datos**  activa para asegurar que los sistemas se alimenten de "combustible limpio": datos curados, verificados y actualizados.  
4. **Transparencia y Licencia Social:** El funcionamiento de los algoritmos será transparente y documentado. Se debe informar a la ciudadanía sobre su uso y beneficios para obtener y mantener la **"Licencia Social"** (aceptación pública).  
5. **Equidad y No Discriminación:** Los algoritmos serán diseñados y auditados para evitar sesgos y resultados que constituyan una **discriminación arbitraria**, según lo define la Ley N° 20.609.  
6. **Gobernanza Financiera y de Seguridad:** Se implementarán controles técnicos (como "Interruptores Automáticos") para prevenir **Bucles de Costos** y riesgos de seguridad, como la **Inyección de Prompts**.  
7. **Privacidad desde el Diseño:** La protección de datos (Ley 19.628) se integrará desde la formulación inicial del proyecto, aplicando principios de minimización y proporcionalidad.

#### **4\. Directriz Central: Uso de IA Generativa y Agentes Autónomos**

Esta sección regula el uso de IA Generativa (capaz de crear contenido) y Agentes (capaces de actuar).

**4.1 Finalidad Permitida (El Marco S1/S2)**

La finalidad principal de la IA es automatizar o asistir en tareas de **"Sistema 1"** (tácticas, repetitivas, de bajo juicio) para liberar el tiempo del funcionario para el trabajo de **"Sistema 2"** (criterio, estrategia, empatía y juicio ético).

**4.2 Principios Específicos de Criterio**

1. **Gestión del Riesgo ("Basura Elocuente"):** Se debe asumir que el principal riesgo de la IA generativa es la **"Basura Elocuente"**: respuestas que son fluidas, convincentes y *totalmente incorrectas*. La confianza ciega en un LLM es un error de principiante.  
2. **La Validación como Habilidad Clave:** El valor del funcionario ya no reside en "saber la respuesta", sino en **"validarla"**. Se debe aplicar escepticismo crítico y verificar las fuentes, especialmente de sistemas RAG.  
3. **De "Pedir" a "Instruir":** El uso eficaz requiere pasar de "pedir" (tratar a la IA como un oráculo) a "instruir" (tratarla como un asistente sin criterio), usando técnicas de **Ingeniería de Prompts**.  
4. **Prohibición de Datos Sensibles:** Queda estrictamente prohibido ingresar datos personales sensibles, reservados o confidenciales en herramientas de IA públicas o de terceros que no estén validadas por el Comité de Gobernanza.  
5. **Transparencia Obligatoria:** Todo *chatbot* o asistente virtual debe identificarse claramente como una IA. Todo documento oficial generado con asistencia sustancial de IA deberá declararlo.

#### **5\. Gobernanza y Responsabilidades**

1. **Comité de Gobernanza de Datos e IA:** Supervisará esta política, aprobará proyectos de alto riesgo y auditará el cumplimiento.  
2. **Unidad de Tecnologías de la Información:** Implementará la **Observabilidad** (el "Dashboard de Gobernanza") para monitorear métricas de costo, seguridad (ej. Inyecciones de Prompt bloqueadas) y calidad (ej. tasa de alucinación).  
3. **Funcionarios (Evolución de Rol):** Asumen los nuevos roles de **"Validadores"** y **"Entrenadores de Agentes"**. Son la primera línea de defensa de la calidad y la principal fuente de retroalimentación para la mejora del sistema.

#### **6\. Cumplimiento y Sanciones**

El incumplimiento de esta política podrá constituir una falta a la probidad administrativa (Ley N° 18.575). Adicionalmente, la **"Abdicación"** del criterio profesional —es decir, el uso de "respuestas crudas" de IA sin la validación humana obligatoria en decisiones de impacto— será considerada una falta al deber de diligencia.