# Metodología de Análisis - Evaluación 2: Rediseño de Procesos y Modelado de Requerimientos

## 📝 Resumen del Proyecto

Esta evaluación consiste en el **rediseño de los diagramas de procesos de negocio AS-IS** a la versión **TO-BE** aplicando mejores prácticas de Business Process Management (BPM), y el posterior **modelado de requerimientos** para uno de los procesos rediseñados.

El objetivo principal es demostrar la capacidad de aplicar principios de rediseño de procesos y de traducir los procesos mejorados en modelos de software (Diagramas de Casos de Uso y Modelo de Dominio) y sus especificaciones.

---

## 🚀 Entregables y Criterios de Evaluación

Los entregables serán evaluados según la rúbrica oficial, que considera las siguientes secciones:

### 1. Corrección de Diagramas Anteriores

Corresponde a la corrección de los diagramas de la Evaluación 1, que son:
* [cite_start]Diagrama de **dependencias estratégicas**[cite: 2].
* [cite_start]Diagrama de **racionalidad estratégica**[cite: 2].
* [cite_start]Diagrama de modelos de **proceso de negocio AS-IS**[cite: 2].

[cite_start]El diagrama AS-IS debe tener indicadas las actividades manuales que se automatizarán o soportarán con tecnología en el proceso rediseñado[cite: 3].

| Dimensión de Calidad | Criterio Clave |
| :--- | :--- |
| **Comprensibilidad** (Pragmática) | [cite_start]La información extraída de los modelos es correcta[cite: 4]. |
| **Correctitud** (Sintáctica) | [cite_start]La notación utilizada en los modelos es correcta[cite: 4]. |
| **Representación Precisa** (Semántica) | [cite_start]Lo representado en los tres modelos es consistente con la realidad y entre ellos[cite: 4]. |

---

### 2. BPMN TO-BE (Rediseño de Procesos)

[cite_start]Se debe realizar el **modelo de procesos de negocio mejorado** (BPMN TO-BE) para los **tres procesos** de negocio, aplicando mejores prácticas de rediseño[cite: 6].

**Instrucciones de Modelado:**
* [cite_start]Utilizar **códigos de color** en el diagrama[cite: 7]:
    * [cite_start]Elementos **nuevos**: Naranjo 🟠[cite: 7].
    * [cite_start]Elementos **modificados**: Amarillo 🟡[cite: 7].
* [cite_start]Si hay elementos eliminados, se debe poner una **nota** en el diagrama[cite: 8].

| Dimensión de Calidad | Criterio Clave |
| :--- | :--- |
| **Rediseño** (Semántica) | [cite_start]Aplicación de buenas prácticas de rediseño y explicación clara del cambio AS-IS a TO-BE[cite: 9]. |
| **Mejoras** | [cite_start]Incorporación de tareas de usuario, servicios u otras tareas que generen **requerimientos de software**[cite: 9]. |
| **Correctitud** (Sintáctica) | [cite_start]Uso correcto de la notación para Tasks, Eventos, Gateways, Pools y Lanes[cite: 9, 10]. |
| **Comprensibilidad** (Pragmática) | [cite_start]El diagrama no presenta complejidad que impida extraer información (procesos complejos subdivididos en subprocesos)[cite: 10]. |

---

### 3. Requerimientos (Modelado UML)

[cite_start]Se debe realizar el modelado de requerimientos para **uno de los procesos** BPMN TO-BE[cite: 13].

#### A. Diagrama de Casos de Uso
| Criterio Clave |
| :--- |
| [cite_start]Notación de actores, casos de uso y relaciones usada correctamente[cite: 12]. |
| [cite_start]Los casos de uso corresponden a las **tareas con soporte de tecnología** del BPMN TO-BE, y los actores son consistentes[cite: 12]. |

#### B. Especificación de Caso de Uso
[cite_start]Se debe seleccionar y especificar el **caso de uso más importante** del diagrama de casos de uso[cite: 12].

| Criterio Clave |
| :--- |
| [cite_start]Especifica **lógica de negocio relevante** y/o **cambios de estado** de entidades principales[cite: 12]. |
| [cite_start]El flujo normal de eventos indica claramente la **interacción entre actor y sistema** y completa la tarea del BPMN TO-BE[cite: 12]. |
| [cite_start]Considera **todos los flujos alternativos** de eventos[cite: 12]. |
| [cite_start]Se identifican todos los **flujos de excepción**, indicando los mensajes al usuario consistentemente[cite: 12]. |

#### C. Modelo de Dominio
| Criterio Clave |
| :--- |
| [cite_start]Considera todas las entidades y atributos descritos en la especificación de casos de uso y los requeridos por los casos de uso del diagrama[cite: 12]. |
| [cite_start]Los atributos de las entidades corresponden **solo a tipos básicos de datos**[cite: 14]. |
| [cite_start]Las relaciones (**asociación, agregación, composición** y cardinalidad) son correctamente modeladas[cite: 14]. |
| [cite_start]Las relaciones de **herencia** (de existir) están justificadas por los casos de uso[cite: 14]. |
| [cite_start]Se identifican al menos las **operaciones más relevantes** para la funcionalidad del caso de uso especificado[cite: 14]. |

---

## 💾 Estructura del Repositorio y Subida de Archivos

El repositorio debe contener los archivos organizados en los siguientes *issues* de GitHub:

### **Issue 1: BPMN TO-BE**
| Contenido | Herramienta Sugerida |
| :--- | :--- |
| **Imágenes** de los diagramas BPMN TO-BE (para los 3 procesos). | |
| **Archivos fuente** de los diagramas BPMN. | BPMN.io |

### **Issue 2: Modelado UML**
| Contenido | Herramienta Sugerida |
| :--- | :--- |
| **Diagrama de Casos de Uso**. | Visual Paradigm |
| **Modelo de Dominio**. | Visual Paradigm |
| **Archivo de proyecto** de Visual Paradigm (Nota: NO debe incluir la especificación de caso de uso) | Visual Paradigm |

### **Issue 3: Especificación de Caso de Uso**
| Contenido | Herramienta Sugerida |
| :--- | :--- |
| **Especificación detallada** del caso de uso seleccionado (incluyendo flujos normal, alternativos y de excepción). | Documento Word o similar |

---
