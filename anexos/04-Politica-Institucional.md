
### Anexo 04: Política Institucional de IA (Propuesta Marco)

Subtítulo: Plantilla de Gobernanza para el Sector Público)

#### Introducción: De la Guía a la Política

Esta es una plantilla marco de política institucional, diseñada para el sector público. No es un documento final, sino un punto de partida que debe ser adaptado al contexto legal y misional específico de cada institución.

Sintetiza los principios de gobernanza, ética y estrategia de esta obra (especialmente las Guías 07, 10 y 12\) con los fundamentos legales (como la Ley N° 19.628 de Chile) y los conceptos de "Licencia Social" y "Opacidad" discutidos en la "Guía Ética" (BID/UAI).

---

### Política Institucional de Uso Responsable de Inteligencia Artificial

**Servicio Público de Chile**

#### 1. Propósito

Esta política establece los principios, normas y procedimientos que regulan el uso responsable, seguro y ético de la Inteligencia Artificial (IA) en el Servicio. Su objetivo es garantizar que su aplicación se oriente al interés público, la eficiencia institucional, la protección de los derechos fundamentales y la confianza ciudadana, asegurando que la IA se utilice para **aumentar** la capacidad humana, no para **abdicar** la responsabilidad.

#### 2. Alcance

Aplica a todas las unidades y funcionarios, así como a terceros que desarrollen o utilicen herramientas de IA en el marco de las funciones del Servicio.

**Definición de "Sistema de IA"** 

Para efectos de esta política, definimos un Sistema de IA como "cualquier tecnología que usa datos para hacer inferencias y generar resultados como predicciones, recomendaciones o decisiones con un grado de autonomía".  
* **Esto incluye, pero no se limita a:** Modelos de machine learning, herramientas de IA Generativa, sistemas de análisis predictivo y chatbots que generan sus propias respuestas.  
* **Esto excluye explícitamente:** Fórmulas estándar de hojas de cálculo, automatizaciones basadas en reglas (como macros "if-then") y dashboards de Business Intelligence tradicionales.  

Esta política regula tanto sistemas de soporte de decisión (que informan a un humano) como sistemas de toma de decisión (automatizados), y establece los controles para el uso de herramientas no aprobadas (IA en la Sombra).

#### 3. Principios Rectores

Todo uso de la IA en el Servicio se regirá por:

1. **Legalidad y Proporcionalidad:** El uso de IA debe cumplir con el marco normativo vigente (ej. Ley 19.628, Ley 20.285) y ser **proporcional** al problema, evaluando siempre si la IA es la herramienta idónea y necesaria.  
2. **Principio de Criterio Humano (Delegar, No Abdicar):** La IA es una herramienta para **aumentar** la capacidad humana. Toda decisión de impacto requerirá supervisión humana significativa, reteniendo el funcionario el 100% de la responsabilidad final.  
3. **Gobernanza de la Fuente (Basura Entra, Basura Sale):** La calidad de un agente de IA es inseparable de la calidad de sus datos. El Servicio se compromete a una **Gobernanza de Datos**  activa para asegurar que los sistemas se alimenten de "combustible limpio": datos curados, verificados y actualizados.  
4. **Transparencia y Licencia Social:** El funcionamiento de los algoritmos será transparente y documentado. Se debe informar a la ciudadanía sobre su uso y beneficios para obtener y mantener la **"Licencia Social"** (aceptación pública).  
5. **Equidad y No Discriminación:** Los algoritmos serán diseñados y auditados para evitar sesgos y resultados que constituyan una **discriminación arbitraria**, según lo define la Ley N° 20.609.  
6. **Gobernanza Financiera y de Seguridad:** Se utilizarán controles automáticos para prevenir riesgos financieros como **Bucles de Costos** (procesos que se repiten indefinidamente generando costos excesivos inesperados), y riesgos de seguridad como **Inyección de Prompts** (intentos de un usuario malintencionado de manipular el sistema con instrucciones ocultas).
7. **Privacidad desde el Diseño:** La protección de datos (Ley 19.628) se integrará desde la formulación inicial del proyecto, aplicando principios de minimización y proporcionalidad.

#### 4. Directriz Central: Uso de IA Generativa y Agentes Autónomos

Esta sección regula el uso de IA Generativa (capaz de crear contenido) y Agentes (capaces de actuar).

**4.1 Finalidad Permitida (El Marco S1/S2)**

La finalidad principal de la IA es automatizar o asistir en tareas de **"Sistema 1"** (tácticas, repetitivas, de bajo juicio) para liberar el tiempo del funcionario para el trabajo de **"Sistema 2"** (criterio, estrategia, empatía y juicio ético).

**4.2 Principios Específicos de Criterio**

1. **Gestión del Riesgo ("Basura Elocuente"):** Se debe asumir que el principal riesgo de la IA generativa es la **"Basura Elocuente"**: respuestas que son fluidas, convincentes y *totalmente incorrectas*. La confianza ciega en un LLM es un error de principiante.  
2. **La Validación como Habilidad Clave:** El valor del funcionario ya no reside en "saber la respuesta", sino en **"validarla"**. Se debe aplicar escepticismo crítico y verificar las fuentes, especialmente de sistemas RAG.  
3. **De "Pedir" a "Instruir":** El uso eficaz requiere pasar de "pedir" (tratar a la IA como un oráculo) a "instruir" (tratarla como un asistente sin criterio), usando técnicas de **Ingeniería de Prompts**.  
4. **Prohibición de Datos Sensibles:** Queda estrictamente prohibido ingresar datos personales sensibles, reservados o confidenciales en herramientas de IA públicas o de terceros que no estén validadas por el Comité de Gobernanza.  
5. **Transparencia Obligatoria:** Todo *chatbot* o asistente virtual debe identificarse claramente como una IA. Todo documento oficial generado con asistencia sustancial de IA deberá declararlo.

#### 5. Gobernanza, Roles y Procedimientos

Para asegurar la gobernanza efectiva, se establecen los siguientes roles y procedimientos:

**5.1 Roles y Responsabilidades Clave**

Se establecen roles granulares para asegurar la separación de deberes y la rendición de cuentas (accountability):
* **Dueño de la Política (Policy Owner):** Un líder senior designado (ej. Jefe de Servicio) que es el responsable final de mantener y patrocinar esta política.  
* **Comité de Gobernanza de IA:** Actúa como el punto de escalamiento para revisar y aprobar sistemas de "alto riesgo" identificados en el Triage.  
* **Dueño del Sistema de IA (System Owner):** Por cada sistema de IA aprobado, se debe designar un "Dueño de Sistema" específico. Esta persona es responsable del ciclo de vida de ese sistema, su cumplimiento con esta política y sus resultados.  
* **Monitor de Cumplimiento (Compliance Monitor):** Un rol (ej. Auditoría Interna) responsable de verificar y auditar el cumplimiento de esta política, revisando que los proyectos hayan completado su Triage y que el Registro de IA esté actualizado.  
* **Unidad de Tecnologías de la Información:** Implementa la Observabilidad (el "Dashboard de Gobernanza") para monitorear métricas de costo, seguridad y calidad de los sistemas en producción.
* **Funcionarios (Usuarios Finales):** Asumen los roles de "Validadores" y "Entrenadores", cumpliendo con esta política y reportando cualquier incidente.  

**5.2 Procedimiento para Nuevos Casos de Uso (Triage y Aprobación)**

Todo proyecto o adquisición de un nuevo Sistema de IA debe seguir este procedimiento antes de su implementación:  
1. **Screening (Triage) Obligatorio:** El "Dueño del Sistema" propuesto debe presentar el caso de uso para un "screening" o "triage" inicial.  
2. **Clasificación de Riesgo:** Este "screening" clasifica el proyecto (ej. "Riesgo Normal", "Riesgo Elevado", "Riesgo Prohibido").  
3. **Gobernanza Proporcional:** El resultado del "triage" determina el nivel de gobernanza requerido:  
   * Los casos de "Riesgo Normal" pueden ser aprobados por el "Dueño de la Política".
   * Los casos de "Riesgo Elevado" (ej. que afecten derechos, manejen datos sensibles) deben ser escalados al **Comité de Gobernanza de Datos e IA** para su revisión y aprobación explícita.  

**5.3 Registro Central de IA (AI Register)**

Todo Sistema de IA que haya sido aprobado mediante el procedimiento de Triage debe ser inscrito en el **"Registro Central de IA"** de la institución.
* Este registro es el inventario central y la "fuente única de verdad" sobre qué sistemas de IA están en uso y quién es el "Dueño de Sistema" responsable de cada uno.
* Este registro es la herramienta principal de transparencia para el "Monitor de Cumplimiento" y la gobernanza interna.  

#### 6. Cumplimiento y Sanciones

El incumplimiento de esta política podrá constituir una falta a la probidad administrativa (Ley N° 18.575). Adicionalmente, la **"Abdicación"** del criterio profesional, es decir, el uso de "respuestas crudas" de IA sin la validación humana obligatoria en decisiones de impacto, será considerada una falta al deber de diligencia.

#### 7. Revisión y Vigencia de la Política

Esta política será revisada formalmente una vez al año para asegurar que se mantiene actualizada y efectiva.  

Adicionalmente, una **revisión extraordinaria (ad-hoc)** será gatillada por uno de los siguientes eventos:  
* Un incidente significativo relacionado con la IA en la organización.  
* La emergencia de nuevas tecnologías de IA que impacten significativamente nuestros riesgos u operaciones.  
* Cambios en las leyes, regulaciones o estándares de la industria.  

El proceso de revisión será liderado por el **Comité de Gobernanza de Datos e IA**.



---
  <div style="display: flex; justify-content: space-between; font-size: 0.9em; padding-top: 10px;">
    <div>
      <a href="./03-Plantillas-Recursos.html">« Anexo Anterior</a>
    </div>
    <div>
      <a href="../">Volver al Índice</a>
    </div>
    <div>
      <a href="./05-Modelos-Mercado.html">Siguiente Anexo »</a>
    </div>
  </div>