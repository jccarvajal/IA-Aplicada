### Anexo 05: Modelos y Mercado LLM

Subtítulo: Del "Jefe de Adquisiciones" al "Arquitecto de Portafolio"

#### Introducción: Del Gobierno al Portafolio

En guías anteriores aprendimos a diseñar y **gobernar** —es decir, controlar de forma segura— los sistemas de IA. Este anexo es el manual de adquisiciones. Su objetivo no es señalar al "mejor" modelo, sino entregar una metodología para construir un ecosistema de portafolio. El rol estratégico no es elegir un solo motor, sino diseñar un portafolio flexible que combine modelos de manera inteligente.

---

#### Parte 1. El Panorama 2025-2026: Los Tres Ecosistemas

Como "Jefes de Adquisiciones" de nuestra fábrica de IA, el mercado de "motores" (LLMs) se ha consolidado en tres ecosistemas claros. Ya no elegimos un modelo; elegimos una estrategia de suministro.

**A. Modelos Propietarios (APIs) \- "Arrendar el Cerebro"**

* **Qué es:** Arriendas el poder de cómputo y el modelo a un proveedor.  
* **Proveedores:** Google (Gemini), OpenAI (GPT), Anthropic (Claude).  
* **Fortaleza:** Acceso inmediato a la máxima potencia y a ventanas de contexto gigantescas (1M+ tokens). Ideal para tareas cognitivas complejas.  
* **Riesgo:** Dependencia tecnológica y exposición de datos al proveedor (los datos viajan a su nube). El costo operacional es alto por token.

**B. Modelos Open-Source (Ejecución Local) \- "Comprar la Máquina"**

* **Qué es:** Descargas y ejecutas el modelo en tu propia infraestructura (on-premise o nube privada).  
* **Proyectos:** Llama (Meta), Mistral/Mixtral, Qwen.  
* **Fortaleza:** Soberanía total de los datos (ideal para entornos regulados). Máximo control y personalización (incluyendo el **Ajuste Fino**, la técnica para especializar el "cerebro" del modelo).  
* **Riesgo:** Alto costo inicial (Hardware GPU) y requiere un equipo especializado en infraestructura e **Industrialización** (el proceso de escalar prototipos a producción).

**C. Agentes-como-Servicio (AaaS) \- "Contratar al Especialista"**

* **Qué es:** Consumes un producto terminado que encapsula el modelo y la arquitectura (como la **Generación Aumentada por Recuperación (RAG)**, el sistema de recuperación de conocimiento).  
* **Ejemplos:** Perplexity, Microsoft Copilot, ChatGPT Enterprise.  
* **Fortaleza:** Implementación en tiempo récord y soluciones enfocadas (ej. ofimática, investigación). Costo inicial bajo (suscripción).  
* **Riesgo:** Flexibilidad técnica baja ("caja negra"). La **Gobernanza** (el control de seguridad y datos) depende 100% del contrato con el proveedor.

---

#### Parte 2. El "Triángulo de Adquisición" (Revisado)

Como "Jefe de Adquisiciones", no puedes tenerlo todo. Cada decisión equilibra tres fuerzas. Hemos reemplazado "Capacidad" por "Control", un término más robusto y estratégico.

1. **Rendimiento (Potencia):** La inteligencia "cruda". Su capacidad para razonar (usando un ciclo de **ReAct** o Razonar-Actuar), escribir código complejo y pasar benchmarks (pruebas de **Evaluación** de calidad).  
2. **Control (Soberanía):** ¿Qué tanto gobierno tienes sobre el proceso? Esto incluye:  
   * **Soberanía de Datos:** ¿Dónde residen los datos? ¿Salen de tu nube?  
   * **Auditoría:** ¿Puedes trazar las decisiones y los logs?  
   * **Personalización:** ¿Puedes hacer Ajuste Fino al modelo?  
   * **Seguridad:** ¿Cómo se manejan los riesgos de Gobernanza?  
3. **Costo (Economía):** El costo total, no solo el precio por token. Incluye el costo de infraestructura (GPUs), licencias y el costo de personal (Industrialización).

---

#### Parte 3. La Solución Estratégica: El "Agente Enrutador"

El panorama 2025-2026 demuestra que la estrategia ganadora no es elegir un motor, sino construir un portafolio y usar el motor adecuado para cada tarea.

¿Cómo se implementa esto? Con la arquitectura de **Diseño Cognitivo** más avanzada: el **Agente Enrutador**.

El "Agente Enrutador" (que puede ser un "Agente Director") es un "cerebro" metacognitivo que gestiona el portafolio.

1. **Llega una Tarea:** "Resume este email de 2 líneas."  
2. **Agente Enrutador (Razona):** "Esto es una tarea 'simple' y 'corta'. No necesito al caro GPT-4o. Usaré un modelo del Ecosistema B (Open-Source) o una API barata (Haiku)."  
3. **Agente Enrutador (Actúa):** Llama al motor más eficiente y económico.  
4. **Llega otra Tarea:** "Analiza las implicaciones de este contrato sensible de 500 páginas."  
5. **Agente Enrutador (Razona):** "Esto es 'complejo' y de 'contexto largo'. Además, los datos son 'sensibles'. Necesito 'Control' total."  
6. **Agente Enrutador (Actúa):** Llama al modelo Open-Source (Ecosistema B) hosteado localmente para garantizar la soberanía de los datos.  
* **Beneficio:** Obtienes el máximo Rendimiento cuando lo necesitas y el máximo Control y Costo-eficiencia cuando no. Has optimizado el "Triángulo de Adquisición".  
* **Validación de Mercado (2025):** Esta estrategia de portafolio ("Comprar" o "Arrendar" en lugar de "Construir" todo desde cero) no es solo teórica. Informes de la industria de 2025 (como el "State of AI in Business" del MIT) revelan que las iniciativas de "Comprar" (asociaciones estratégicas) tienen el **doble de tasa de éxito** (aprox. 66%) que las de "Construir" (desarrollo interno) (aprox. 33%).

---

#### Parte 4. Metodología Práctica de Selección (Checklist)

Para diseñar tu portafolio, usa este proceso:

1. **Definir el Caso de Uso:** ¿Qué problema resuelve? (Precisión, latencia).  
2. **Clasificar por Riesgo/Sensibilidad:** ¿Los datos son públicos, internos o confidenciales (salud, jurídicos, seguridad)?  
3. **Asignar el Tipo de Modelo:** Usa la matriz de decisión y el checklist de abajo.  
4. **Pilotar con Métricas:** Implementa un **prototipo** (la versión v1 de prueba) y mide con la guía de **Evaluación** (QA).  
5. **Monitorear y Revisar:** Implementa logs (parte de la **Industrialización**) y revisa el portafolio cada 3-6 meses.

**Matriz de Decisión Estratégica**

| Dimensión | Propietario (API) | Open-Source (Local) | AaaS (Producto) |
| :---- | :---- | :---- | :---- |
| **Gobernanza de Datos** | Limitada: los datos viajan a la nube del proveedor. | Total: Control local. Ideal para regulación. | Depende del proveedor y del contrato. |
| **Costo Inicial** | Bajo. | Alto (Hardware GPU, equipo). | Bajo (Suscripción). |
| **Costo Operacional** | Alto (Pago por token a escala). | Medio (Infraestructura, soporte). | Fijo/Variable (Licencia). |
| **Flexibilidad Técnica** | Media (Prompting, RAG). | Alta (Ajuste Fino, RAG, modificación). | Baja ("Caja negra"). |

**Checklist Rápido de Decisión**

| Pregunta Clave | Si | No | Comentarios / Acción Requerida (Ejemplos) |
| :---- | :---- | :---- | :---- |
| ¿Los datos son sensibles (salud, seguridad, jurídico)? | \[ \] | \[ \] | (Si es SÍ: Priorizar Open-Source Local) |
| ¿Requiere auditoría y trazabilidad completa? | \[ \] | \[ \] | (Si es SÍ: Priorizar Open-Source o API con cláusulas de logs) |
| ¿Necesitamos customización profunda (Ajuste Fino)? | \[ \] | \[ \] | (Si es SÍ: Requerir Open-Source) |
| ¿Tenemos capacidad de Industrialización interna? | \[ \] | \[ \] | (Si es NO: Priorizar API o AaaS, o planificar contratación) |

---

#### Parte 5. Enfoque Especial: Sector Público y Entornos Regulados

Para instituciones públicas o reguladas (finanzas, salud), el factor **Control** (Soberanía de Datos, Auditoría) debe superar casi siempre al Rendimiento.

1. **Priorizar Soberanía de Datos:** Favorecer soluciones locales (Open-Source) para cualquier información crítica o sensible.  
2. **Exigir Transparencia y Auditoría:** Exigir documentación técnica clara y la capacidad de auditar los procesos y los logs.  
3. **Contratar con Cláusulas de Gobernanza:** Al usar APIs (Ecosistema A) o AaaS (Ecosistema C), incluir cláusulas contractuales específicas sobre residencia de datos, trazabilidad y retención de logs.

#### Conclusión: De Gobernador a Arquitecto de Portafolio

La maestría no reside en saber qué LLM es "mejor", sino en tener el juicio de ingeniería para diseñar un ecosistema flexible: rendimiento donde importa, Control donde hay riesgo, y Costo donde la escala lo exige. El rol final no es solo gobernar una fábrica; es ser el "Arquitecto del Portafolio de IA".

---
  <div style="display: flex; justify-content: space-between; font-size: 0.9em; padding-top: 10px;">
    <div>
      <a href="./04-Politica-Institucional.html">« Anexo Anterior</a>
    </div>
    <div>
      <a href="../">Volver al Índice</a>
    </div>
    <div>
      <a href="./06-Glosario.html">Siguiente Anexo »</a>
    </div>
  </div>