
<p align="center">
  <img src="resources/images/upc_logo.png" alt="UPC Logo" width="200">
</p>



<h3 align="center"> Universidad Peruana de Ciencias Aplicadas</h3>



<h4 align="center"> Ingeniería de Software  </h4>

<h4 align="center"> Desarrollo de Soluciones IOT </h4>

<h4 align="center"> Informe de Trabajo Final </h4>
<h4 align="center">Ciclo: VII </h4>
<h5 align="center">Sección: WS71</h5>

<h5 align="center">Profesor: Angel Augusto Velasquez Nuñez</h5>


<h3 align="center">Startup: "Castores Rabiosos"</h2>
  
<h4 align="center">Producto: TransportApp</h3>

  


| Integrantes                        | Codigo     |
| ---------------------------------- | ---------- |
| Abanto Vicente, Edery Renzo        | U201822832 |
| Castro Soto, Sebastian Enrique     | U20181C241 |
| Conde Isla, Camila Alessandra      | U202114309 |
| Portales Ortiz, Diego Alejandro    | U202123501 |
| Sabino Ramírez, Rodrigo Alexander  | U20201B801 |



<h4 align="center">Agosto, 2024</h3>


---

# Registro de Versiones del Informe

| Versión | Fecha    | Autor                | Descripción de modificación                             |
| ------- | -------- | -------------------- | ------------------------------------------------------- |
| 1.0     | 27/08/24 | - Rodrigo Sabino<br> | Se creó el archivo README.md con la estructura inicial. |

---

# Contenido
- [Student Outcome](#student-outcome)
- [Capítulo I: Introducción](#capítulo-i-introducción)
  - [1.1. Startup Profile](#11-startup-profile)
    - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
    - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  - [1.2. Solution Profile](#12-solution-profile)
    - [1.2.1. Antecedentes y Problemática](#121-antecedentes-y-problemática)
    - [1.2.2. Lean UX Process](#122-lean-ux-process)
        - [1.2.2.1.  Lean UX Problem Statements](#1221-lean-ux-problem-statements)
        - [1.2.2.2 Lean UX Assumptions](#1222-lean-ux-assumptions)
        - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
        - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
  - [1.3. Segmentos Objetivo](#13-segmentos-objetivo)
- [Capítulo II: Requirements Elicitation & Analysis](#capítulo-ii-requirements-elicitation--analysis)
  - [2.1. Competidores](#211-competidores)
    - [2.1.1. Análisis Competitivo](#211-análisis-competitivo)
    - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
  - [2.2. Entrevistas](#22-entrevistas)
    - [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
    - [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
    - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
  - [2.3. Needfinding](#23-needfinding)
    - [2.3.1. User Personas](#231-user-personas)
    - [2.3.2. User Task Matrix](#232-user-task-matrix)
    - [2.3.3. User Journey Mapping](#233-user-journey-mapping)
    - [2.3.4. Empathy Mapping](#234-empathy-mapping)
    - [2.3.5. As-is Scenario Mapping](#235-as-is-scenario-mapping)
  - [2.4. Ubiquitous Language](#24-ubiquitous-language)
- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
  - [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
  - [3.2. User Stories](#32-user-stories)
  - [3.3. Impact Mapping](#33-impact-mapping)
  - [3.4. Product Backlog](#34-product-backlog)
- [Capítulo IV: Solution Software Design](#capítulo-iv-solution-software-design)
  - [4.1. Strategic-Level Domain-Driven Design](#41-strategic-level-domain-driven-design)
	- [4.1.1. EventStorming](#411-eventstorming)
		- [4.1.1.1. Candidate Context Discovery](#4111-candidate-context-discovery)
		- [4.1.1.2 Domain Message Flows Modeling](#4112-domain-message-flows-modeling)
		- [4.1.1.3 Bounded Context Canvases](#4113-bounded-context-canvases)
	- [4.1.2 Context Mapping](#412-context-mapping)
	- [4.1.3. Software Architecture](#413-software-architecture)
		- [4.3.1. Software Architecture System Landscape Diagram](#431-software-architecture-system-landscape-diagram)
		- [4.3.2. Software Architecture Context Level Diagrams](#432-software-architecture-context-level-diagrams)
		- [4.3.3 Software Architecture Container Level Diagrams](#433-software-architecture-container-level-diagrams)
		- [4.3.4 Software Architecture Deployment Diagrams](#434-software-architecture-deployment-diagrams)

---
# Student Outcome

| Criterio específico                                                                             | Acciones realizadas                                                                                                       | Conclusiones |
| ----------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------- | ------------ |
| Trabaja en equipo para proporcionar liderazgo en forma conjunta                                 | **Rodrigo Sabino**<br><br>**Edery Abanto** <br><br>**Sebastian Castro**<br><br>**Camila Conde**<br><br>**Diego Portales** |              |
| Crea un entorno colaborativo e inclusivo, establece metas, planifica tareas y cumple objetivos. | **Rodrigo Sabino**<br><br>**Edery Abanto** <br><br>**Sebastian Castro**<br><br>**Camila Conde**<br><br>**Diego Portales** | <br>         |

---

# Capítulo I: Introducción

## 1.1. Startup Profile

### 1.1.1. Descripción de la Startup