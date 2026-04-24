<div align="center">
<img src="assets/UPC_logo_transparente.png"></img><br>


<h3>Universidad Peruana de Ciencias Aplicadas</h3>
<h4>Facultad de Ingeniería</h4>
<h4>Carrera de Ingeniería de Software</h4>
<h4>Ciclo 202610</h4>
<h4>1ASI0729 Desarrollo de Aplicaciones Open Source</h4>
<h4>NRC 11863</h4>
<h4>Docente: Ivan Robles Fernández</h4>
<h4>Informe del Trabajo Final</h4>
<h4>Startup: Co-Designers</h4>
<h4>Producto: PetCare </h4>

#### Relación de integrantes 
| **Código** | **Apellidos y Nombres**               |
| :--------: | :------------------------------------ |
| U202414313 | Campoblanco Guzman, Diego Roberto |
| U20201E781 | Huaman De La Cruz, Jean Pool   |
| U20241E242 | Mauricio Silva, Ghiou Justinn     |
| U20221A118 | Mejia Aliaga, Katherine Maryory     |
| U20241E107 | Tuncar Vila, Ghorghet Saul|

</div>

<br><div align="center"><h3>Abril 2026</h3></div><br>
<div style="text-align: justify;">

<br><br>

## Registro de Versiones del Informe

<div align="justify">
  
| Versión |  Fecha   |                                       Autor                                        |                                                  Descripción de modificación                                                   |
| :-----: | :------: | :--------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------------------------------------------: |
|   TB1   | 22/04/2026 | Todos | Avance del trabajo: Completando el contenido del Documento |
|   TP1   |            |       |                                                            |
|   TB2   |            |       |                                                            |
|   TF1   |            |       |                                                            |

<div style="page-break-after: always;"></div>

## Project Report Collaboration Insights
URL de Organización de GITHUB del equipo Co-Designers: https://github.com/Co-Designers  
URL de Repositorio del Project Report: https://github.com/Co-Designers/PetCare

<strong>*Entrega TB1:*</strong> 

# Contenido

## Índice

- [Registro de versiones del informe](#registro-de-versiones-del-informe)

- [Project Report Collaboration Insights](#project-report-collaboration-insights)

- [Contenido](#contenido)

- [Student Outcome](#student-outcome-1)

- [Capítulo I: Introducción](#capitulo-i-introduccion)
  - [1.1. StartUp Profile](#11-startup-profile)
    - [1.1.1. Descripción de la StartUp](#111-descripción-de-la-startup)
    - [1.1.2. Perfiles de Integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  - [1.2. Solution Profile](#12-solution-profile)
    - [1.2.1. Antecedentes y Problemática](#121-antecedentes-y-problemática)
    - [1.2.2. Lean UX Process](#122-lean-ux-process)
      - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
      - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
      - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hyphotesis-statements)
      - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
  - [1.3. Segmentos objetivo](#13-segmentos-objetivo)
- [Capítulo II: Requirements Elicitation & Analysis]()
  - [2.1. Competidores](#21-competidores)
    - [2.1.1. Análisis competitivo](#211-análisis-competitivo)
    - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
  - [2.2. Entrevistas](#22-entrevistas)
    - [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
    - [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
    - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
  - [2.3. Needfinding](#23-needfinding)
    - [2.3.1. User Persona](#231-user-persona)
    - [2.3.2. User Task Matrix](#232-user-task-matrix)
    - [2.3.3. User Journey Mapping](#233-user-journey-mapping)
    - [2.3.4. Empathy Mapping](#234-empathy-mapping)
  - [2.4 Big Picture Event Storming](#24-big-picture-event-storming)
  - [2.5 Ubiquitous Language](#25-ubiquitous-language)
- [Capítulo III: Requirements Specification]()
  - [3.1. User Stories](#31-user-stories)
  - [3.2. Impact Mapping](#32-impact-mapping)
  - [3.3. Product Backlog](#33-product-backlog)
- [Capítulo IV: Product Design]()
  - [4.1. Style Guidelines](#41-style-guidelines)
    - [4.1.1. General Style Guidelines](#411-general-style-guidelines)
    - [4.1.2. Web Style Guidelines](#412-web-style-guidelines)
  - [4.2. Information Architecture](#42-information-architecture)
    - [4.2.1. Organization Systems](#421-organization-systems)
    - [4.2.2. Labeling Systems](#422-labeling-systems)
    - [4.2.3. SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
    - [4.2.4. Searching Systems](#424-searching-systems)
    - [4.2.5. Navigation Systems](#425-navigation-systems)
  - [4.3. Landing Page UI Design](#43-landing-page-ui-design)
    - [4.3.1. Landing Page Wireframe](#431-landing-page-wireframe)
    - [4.3.2. Landing Page Mock-up](#432-landing-page-mock-up)
  - [4.4. Web Applications UX/UI Design](#44-web-applications-uxui-design)
    - [4.4.1. Web Applications Wireframes](#441-web-applications-wireframes)
    - [4.4.2. Web Applications Wireflow Diagrams](#442-web-applications-wireflow-diagrams)
    - [4.4.3. Web Applications Mock-ups](#443-web-applications-mock-ups)
    - [4.4.4. Web Applications User Flow Diagrams](#444-web-applications-user-flow-diagrams)
  - [4.5. Web Applications Prototyping](#45-web-applications-prototyping)
  - [4.6. Domain-Driven Software Architecture](#46-domain-driven-software-architecture)
    - [4.6.1. Design-Level Event Storming](#461-design-level-event-storming)
    - [4.6.2. Software Architecture Context Diagram](#462-software-architecture-context-diagram)
    - [4.6.3. Software Architecture Container Diagrams](#463-software-architecture-container-diagrams)
    - [4.6.4. Software Architecture Components Diagrams](#464-software-architecture-components-diagrams)
  - [4.7. Software Object-Oriented Design](#47-software-object-oriented-design)
    - [4.7.1. Class Diagrams](#471-class-diagrams)
  - [4.8. Database Design](#48-database-design)
    - [4.8.1. Database Diagram](#481-database-diagram)
- [Capítulo V: Product Implementation, Validation & Deployment]()
  - [5.1. Software Configuration Management](#51-software-configuration-management)
    - [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
    - [5.1.2. Source Code Management](#512-source-code-management)
    - [5.1.3. Source Code Style Guide & Conventions](#513-source-code-style-guide--conventions)
    - [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
  - [5.2. Landing Page, Services & Applications Implementation](#52-landing-page-services--applications-implementation)
    - [5.2.1. Sprint 1](#521-sprint-1)
      - [5.2.1.1. Sprint Planning 1](#5211-sprint-planning-1)
      - [5.2.1.2. Aspect Leaders and Collaborators](#5212-aspect-leaders-and-collaborators)
      - [5.2.1.3. Sprint Backlog 1](#5213-sprint-backlog-1)
      - [5.2.1.4. Development Evidence for Sprint Review](#5214-development-evidence-for-sprint-review)
      - [5.2.1.5. Execution Evidence for Sprint Review](#5215-execution-evidence-for-sprint-review)
      - [5.2.1.6. Services Documentation Evidence for Sprint Review](#5216-services-documentation-evidence-for-sprint-review)
      - [5.2.1.7. Software Deployment Evidence for Sprint Review](#5217-software-deployment-evidence-for-sprint-review)
      - [5.2.1.8. Team Collaboration Insights during Sprint](#5218-team-collaboration-insights-during-sprint)
    - [5.2.2. Sprint 2](#522-sprint-2)
      - [5.2.2.1. Sprint Planning 2](#5221-sprint-planning-2)
      - [5.2.2.2. Aspect Leaders and Collaborators](#5222-aspect-leaders-and-collaborators)
      - [5.2.2.3. Sprint Backlog 2](#5223-sprint-backlog-2)
      - [5.2.2.4. Development Evidence for Sprint Review](#5224-development-evidence-for-sprint-review)
      - [5.2.2.5. Execution Evidence for Sprint Review](#5225-execution-evidence-for-sprint-review)
      - [5.2.2.6. Services Documentation Evidence for Sprint Review](#5226-services-documentation-evidence-for-sprint-review)
      - [5.2.2.7. Software Deployment Evidence for Sprint Review](#5227-software-deployment-evidence-for-sprint-review)
      - [5.2.2.8. Team Collaboration Insights during Sprint](#5228-team-collaboration-insights-during-sprint)
    - [5.2.3. Sprint 3](#523-sprint-3)
      - [5.2.3.1. Sprint Planning 3](#5231-sprint-planning-3)
      - [5.2.3.2. Aspect Leaders and Collaborators](#5232-aspect-leaders-and-collaborators)
      - [5.2.3.3. Sprint Backlog 3](#5233-sprint-backlog-3)
      - [5.2.3.4. Development Evidence for Sprint Review](#5234-development-evidence-for-sprint-review)
      - [5.2.3.5. Execution Evidence for Sprint Review](#5235-execution-evidence-for-sprint-review)
      - [5.2.3.6. Services Documentation Evidence for Sprint Review](#5236-services-documentation-evidence-for-sprint-review)
      - [5.2.3.7. Software Deployment Evidence for Sprint Review](#5237-software-deployment-evidence-for-sprint-review)
      - [5.2.3.8. Team Collaboration Insights during Sprint](#5238-team-collaboration-insights-during-sprint)
    - [5.2.4. Sprint 4](#524-sprint-4)
      - [5.2.4.1. Sprint Planning 4](#5241-sprint-planning-4)
      - [5.2.4.2. Aspect Leaders and Collaborators](#5242-aspect-leaders-and-collaborators)
      - [5.2.4.3. Sprint Backlog 4](#5243-sprint-backlog-4)
      - [5.2.4.4. Development Evidence for Sprint Review](#5244-development-evidence-for-sprint-review)
      - [5.2.4.5. Execution Evidence for Sprint Review](#5245-execution-evidence-for-sprint-review)
      - [5.2.4.6. Services Documentation Evidence for Sprint Review](#5246-services-documentation-evidence-for-sprint-review)
      - [5.2.4.7. Software Deployment Evidence for Sprint Review](#5247-software-deployment-evidence-for-sprint-review)
      - [5.2.4.8. Team Collaboration Insights during Sprint](#5248-team-collaboration-insights-during-sprint)
  - [5.3. Validation Interviews]()
    - [5.3.1. Diseño de Entrevistas](#531-diseño-de-entrevistas)
    - [5.3.2. Registro de Entrevistas](#532-registro-de-entrevistas)
    - [5.3.3. Evaluaciones según heuristicas](#533-evaluaciones-segun-heuristicas)
  - [5.4. Video About-the-Product](#54-video-about-the-product)
- [Conclusiones](#conclusiones)
  - [Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)
- [Bibliografía](#bibliografía)
- [Anexos](#anexos)

<div style="page-break-after: always;"></div>

## Student Outcome

Objetivo general, ABET – EAC - Student Outcome 3: Capacidad de comunicarse efectivamente con un rango de audiencias.

| Criterio Específico | Acciones realizadas | Conclusiones |
|---|---|---|
| Comunica oralmente con efectividad a diferentes rangos de audiencia. | Diego Roberto <br>AV1: Realice la entrevista con Carolina Guzman, en donde hice uso de un lenguaje sencillo y a la vez empático para entender sus frustraciones, mientras que en la coordinación técnica con los miembros de mi equipo, utilicé terminología de ingeniería como 'Arquitectura de Microservicios' e 'IoT'.<br>TB1:<br>AV2:<br>TB2:<br><br>Jean Pool <br>AV1: Participé en la realización de entrevistas a dueños de mascotas para la definición de los segmentos objetivo, donde utilicé un lenguaje claro y empático para comprender sus necesidades y problemas. Asimismo, durante las reuniones de equipo, comuniqué ideas relacionadas a Ubiquitous Language y Domain-Driven Design, adaptando mi forma de expresión según el nivel técnico de los integrantes. Además, participé en las sesiones de Event Storming, explicando los eventos del dominio y el flujo del sistema de manera comprensible para todo el equipo. <br>TB1:<br>AV2:<br>TB2:<br><br>Ghiou Justinn <br>AV1: Participé en la realización de entrevistas a dueños de mascotas, donde utilicé un lenguaje claro y empático para comprender sus necesidades y experiencias. Asimismo, durante las reuniones de equipo, comuniqué ideas relacionadas a la definición de User Stories, Impact Mapping y Product Backlog, adaptando mi forma de expresión según el contexto, explicando los puntos de manera sencilla para el equipo y asegurando una correcta comprensión de la información obtenida.<br>TB1:<br>AV2:<br>TB2:<br><br>Katherine Maryory <br>AV1: Participé en las entrevistas a profundidad con dueños de mascotas y especialistas (veterinarios), adaptando mi lenguaje para extraer necesidades críticas sin usar tecnicismos. Asimismo, colaboré en las sesiones de Event Storming, comunicando ideas técnicas de forma clara para consensuar el flujo del negocio con el equipo. <br>TB1:<br>AV2:<br>TB2:<br><br>Ghorghet Saul <br>AV1:Realice una entrevista para el segmento uno, la entrevistada es Keidy Maquera, utilizando un lenguaje claro para facilitar una comunicación fluida. Además, participé en el Big Picture Event Storming, una actividad realizada en conjunto con el equipo, donde también se mantuvo un lenguaje claro y colaborativo. Finalmente, en la reunión grupal, se llegó a acuerdos importantes que ayudaron a la toma de decisiones del proyecto para el informe.<br>TB1:<br>AV2:<br>TB2: | |
| Comunica por escrito con efectividad a diferentes rangos de audiencia. | Diego Roberto <br>AV1: Desarrolle el documento haciendo uso del lenguaje Markdown para una lectura clara en la web. De igual manera el desarrollo de los diagramas Empathy Maps y Matrices de Tareas complementan el texto escrito para facilitar la comprensión de audiencias no técnicas al buscar representar de forma simple a los usuarios ideales y las tareas que estos cumplen de manera que cualquier persona tenga una idea clara de nuestro segmento objetivo.<br>TB1:<br>AV2:<br>TB2:<br><br>Jean Pool <br>AV1: Elaboré documentación clave del proyecto, incluyendo los segmentos objetivo y el Ubiquitous Language, redactados de manera clara y estructurada para su comprensión por audiencias no técnicas. Además, desarrollé la documentación de la arquitectura de software basada en Domain-Driven Design, incluyendo diagramas de contexto, contenedores y componentes, utilizando un lenguaje organizado que permite tanto a stakeholders como al equipo técnico comprender el sistema. Asimismo, documenté los resultados del Event Storming y las evidencias del Sprint Review, asegurando una comunicación escrita clara y ordenada.   <br>TB1:<br>AV2:<br>TB2:<br><br>Ghiou Justinn <br>AV1: Elaboré diversos entregables clave del proyecto, incluyendo el análisis competitivo, estrategias frente a competidores y la propuesta de diferenciación del producto, redactados de manera estructurada y comprensible para audiencias no técnicas. Además, desarrollé el capítulo de requisitos funcionales, que incluye el Product Backlog, Impact Mapping, User Stories y el Diagrama de Clases, utilizando un lenguaje claro y organizado que permite tanto a stakeholders como al equipo técnico comprender fácilmente el funcionamiento y la propuesta del sistema.<br>TB1:<br>AV2:<br>TB2:<br><br>Katherine Maryory <br>AV1: Redacté la documentación técnica de la arquitectura (C4 y Context Mapping) y definí los User Stories, asegurando que los requerimientos fueran claros para el equipo de desarrollo. Además, elaboré los Style Guidelines y diseñé secciones de la Landing Page, comunicando visual y textualmente la identidad de la marca hacia los futuros usuarios.<br>TB1:<br>AV2:<br>TB2:<br><br>Ghorghet Saul <br>AV1: Me conunique por escrito de manera efectiva a lo largo del proyecto. Aplique el proceso de Lean UX y participe en el Big Picture Event Storming para el análisis colaborativo del sistema. Además, implemente wireframes para versión mobile, mockups de interfaz y el user flow diagram para desktop. También realize la grabación del flujo del user flow y elabore el diagrama entidad–relación (ERD) para la base de datos del sistema.<br>TB1:<br>AV2:<br>TB2: | |


# Capitulo I: Introducción

## 1.1. StartUp Profile
  
### 1.1.1. Descripción de la StartUp

La startup CO-Designers es un equipo conformado por estudiantes de la carrera de Ingeniería de Software. Tenemos como objetivo principal desarrollar una solución tecnológica escalable que transforme el cuidado de la salud animal. Mediante la plataforma PetCare, se busca integrar IA para mejorar el sistema de búsqueda, analizar historiales clínicos y recomendaciones personalizadas, junto con dispositivos IoT para el monitoreo preventivo de signos vitales. Esta Integración permite a los dueños detectar anomalías a tiempo y gestionar servicios veterinarios de manera eficiente, promoviendo una cultura de prevención y bienestar animal. 

### Misión

Optimizar el cuidado de las mascotas mediante una plataforma integral que combiene IA e IoT para facilitar el acceso a servicios veterinarios y permitir el monitoreo preventivo de la salud animal.

### Visión

Ser la plataforma referente en el ámbito de la salud veterinaria digital en el Perú, destacando por la innovación en medicina preventiva y el uso de tecnologías de código abierto para mejorar la calidad de vida de las mascotas.

### 1.1.2. Perfiles de integrantes del equipo
| **Nombre Completo del integrante**    |	**Descripcion de la carrera** | **Fotografia** | **Conocimientos y habilidades**
| :------------------------------------ |:------------------------------------ |:------------------------------------ |:------------------------------------ |
| Campoblanco Guzman, Diego Roberto   |Ingeniería de Software Universidad Peruana de Ciencias Aplicadas| <img src="assets/Foto.jpg"> | Mi nombre es diego Roberto Campoblanco Guzman, tengo 19 años y estoy cursando la carrera de Ingenieria de Software, actualmente estoy en el 5to ciclo y cuento con conocimientos de programacion en los lenguajes de C++, HTML, JavaScript, python y CSS. Me gusta jugar videojuegos en mis ratos libres. además de conocer nueva gente y dar mi mejor esfuerzo en los trabajos en equipo. Además me gusta aprender nuevas cosas cada dia desarrollando de esta forma mi capacidad profesional.
| Huaman De La Cruz, Jean Pool |Ingeniería de Software Universidad Peruana de Ciencias Aplicadas| <img src="assets/members/Jean.png" alt="Jean"> | Soy Jean Pool, tengo 23 años y estudio Ingeniería de Software en la UPC. Cuento con conocimientos en programación en lenguajes como Python, C++, Java, así como en desarrollo web utilizando HTML y CSS. Me caracterizo por ser una persona comprometida, responsable y orientada a la mejora continua, siempre enfocado en aprender nuevas tecnologías y fortalecer mis habilidades profesionales. Además, mantengo una actitud proactiva en el trabajo en equipo, aportando ideas, comunicándome de manera efectiva y contribuyendo al cumplimiento de los objetivos. |    
| Mauricio Silva, Ghiou Justinn |Ingeniería de Software Universidad Peruana de Ciencias Aplicadas| <img src="assets/JustinnOP.jpeg"> | Soy Ghiou Justinn Mauricio Silva, tengo 19 años y curso el  5to ciclo de la carrera de Ingeniería de Software.  Me caracterizo por ser una persona responsable y comprometida con mis actividades académicas, manteniendo siempre una actitud proactiva dentro del trabajo en equipo. Me caracterizo por ser una persona responsable y comprometida con mis actividades académicas, mantengo una actitud proactiva en el trabajo en grupo, además de tener conocimientos en programación en C++, desarrollo web (HTML, CSS y JavaScript). Entre mis principales fortalezas destaca mi capacidad para colaborar eficazmente en entornos grupales, aportando soluciones y manteniendo una comunicación adecuada con los integrantes del equipo. Mi enfoque se centra en el aprendizaje continuo y en la adquisición de nuevos conocimientos, con el objetivo de seguir formándome y consolidarme como un profesional competente en el ámbito de la ingeniería de software.
| Mejia Aliaga, Katherine Mejia |Ingeniería de Software Universidad Peruana de Ciencias Aplicadas| <img src="assets/fotokatherine.png"> | Mi nombre es Katherine Mejia, tengo 21 años, curso el sexto ciclo de la carrera de ingeniería de software, Tengo conocimientos en C++, Phyton y HTML. Me gusta trabajar en equipo y a la vez sacar lo mejor de mis compañeros para hacer un buen trabajo. Además, tengo capacidad y aptitud para generar nuevas e innovadoras ideas y siempre estoy dispuesta a adquirir nuevas habilidades y conocimientos.
| Tuncar Vila, Ghorghet Saul|Ingeniería de Software Universidad Peruana de Ciencias Aplicadas| <img src="assets/Ghorghet.png"> | Soy Ghorghet Saul Tuncar Vila, tengo 20 años de edad, estudio ingeniería de software en la UPC y estoy comprometido a seguir aprendiendo tecnologías que me ayuden en mi crecimiento como profesional. Me considero una persona empática, responsable, organizada y perfeccionista. Me apasiona aprender cada tema a profundidad y disfruto ayudando a los demás mientras doy lo mejor de mi en cada actividad.


## 1.2 *Solution Profile*
### 1.2.1 Antecedentes y problemática
### Antecedentes
En los últimos años, el cuidado de los animales de compañía ha experimentado una transformación significativa, impulsada por la tendencia global de considerarlos miembros fundamentales de la familia. Es por esta razón que la gestión de la salud veterinaria sigue siendo fundamental para los dueños de mascotas. El historial clínico suele manejarse de forma aislada en cada clínica, muchas veces en formato físico o en sistemas cerrados, lo que dificulta a los dueños el seguimiento de vacunas, cirugías y tratamientos, resultando en un modelo de atención que reacciona ante la enfermedad en lugar de prevenirla.

Diversas iniciativas han buscado digitalizar este sector mediante soluciones de software. En el ámbito de las startups y proyectos académicos recientes, se han desarrollado aplicaciones móviles y directorios web que permiten buscar veterinarias cercanas y, en algunos casos, agendar citas. Aunque estos sistemas han permitido dar un paso importante en la digitalización del rubro, suelen operar de manera estática y limitarse a ser un canal de comunicación, sin capacidad para analizar datos complejos o personalizar las opciones según el presupuesto y el historial específico del usuario.

Más recientemente, a nivel internacional, el avance del Internet de las Cosas (IoT) ha introducido dispositivos portátiles para mascotas, como collares y sensores inteligentes. Iniciativas comerciales como FitBark o Whistle han popularizado el monitoreo en animales, pero se han centrado casi exclusivamente en el rastreo GPS y la medición de la actividad física general. La evolución hacia dispositivos enfocados netamente en la biometría preventiva, como la medición de variaciones de temperatura o frecuencia cardíaca, y su sincronización automática con plataformas médicas sigue siendo un área con muy poca explotación en nuestro entorno.

Por otro lado, si bien tecnologías como la Inteligencia Artificial ya se aplican con éxito en plataformas de salud humana para la clasificación de pacientes según la gravedad de su estado y la derivación de los mismos, su integración en aplicaciones veterinarias de uso cotidiano es aún muy incipiente. Las herramientas actuales no tienen la capacidad de cruzar de manera inteligente el historial clínico del animal con las necesidades inmediatas y financieras del dueño para recomendar la mejor clínica disponible.

Estos antecedentes demuestran que, aunque existen propuestas aisladas para el agendamiento digital, la gestión de clínicas y el uso temprano de IoT en mascotas, aún no se ha implementado una solución unificada. Esta brecha justifica plenamente el desarrollo de PetCare, una plataforma integral que no solo centralice la información y facilite el emparejamiento inteligente entre usuarios y veterinarias mediante IA, sino que también cambie el paradigma hacia la medicina preventiva a través del monitoreo IoT en tiempo real.

### Problematica
A pesar del crecimiento del sector de cuidado de mascotas y la digitalización de servicios en el Perú, la gestión de la salud veterinaria sigue siendo fragmentada y dependiente de procesos manuales o aislados. Los historiales clínicos suelen mantenerse en formatos físicos o en los sistemas cerrados de cada clínica, lo que genera pérdida de información y estrés para los dueños, especialmente ante emergencias o al cambiar de especialista. No existe una plataforma unificada y centralizada que permita a los usuarios buscar, comparar presupuestos y agendar citas de manera informada. Esta situación contrasta con el estilo de vida de los usuarios actuales, quienes se ven obligados a depender del "boca a boca" para encontrar la atención adecuada.

Esta falta de integración tecnológica afecta tanto el bienestar de las mascotas como la economía y experiencia de los dueños. Además, la carencia de herramientas de monitoreo continuo provoca que las enfermedades graves sean detectadas únicamente en etapas avanzadas, cuando los síntomas ya son visibles y los tratamientos resultan más invasivos y costosos. Aunque en el mercado existen directorios veterinarios básicos y dispositivos portátiles limitados al rastreo GPS, el entorno local aún no cuenta con un ecosistema integral que combine el emparejamiento inteligente de servicios (IA) y la recolección de datos biométricos en tiempo real (IoT) para habilitar una verdadera medicina preventiva.

## "5W" & "2H"

| Elemento | Pregunta | Definición para PetCare |
| :--- | :--- | :--- |
| ("Who") Quién | ¿A quiénes afecta? | Afecta directamente a los dueños de mascotas, quienes experimentan estrés, pérdida de tiempo y altos costos por tratamientos tardíos. Indirectamente, también afecta a las clínicas veterinarias y especialistas, quienes pierden eficiencia operativa al no contar con historiales clínicos previos ni un canal inteligente para captar pacientes que requieran sus servicios específicos. |
| ("What") Qué | ¿Cuál es el problema? | El problema radica en la ineficiencia y desarticulación del ecosistema de atención veterinaria. Los dueños de mascotas enfrentan graves dificultades para encontrar especialistas adecuados de forma rápida y carecen de herramientas para anticipar problemas de salud, lo que deteriora la calidad de vida de los animales e incrementa los gastos médicos por emergencias. |
| ("Where") Dónde | ¿Dónde ocurre? | El problema se presenta a nivel urbano en Lima Metropolitana, afectando simultáneamente dos frentes: los hogares de los dueños (donde ocurren las emergencias y falta prevención) y las clínicas veterinarias (que operan con sistemas de información aislados o físicos, impidiendo la interoperabilidad). |
| ("When") Cuándo | ¿Cuándo ocurre? | Esta situación es una constante diaria, pero alcanza su punto crítico en tres momentos específicos: durante una emergencia médica donde el tiempo es vital, al momento de requerir una derivación a un especialista (como cardiólogos u oncólogos), y cuando una enfermedad silenciosa se agrava por no haber sido detectada a tiempo en su fase temprana. |
| ("Why") Por qué | ¿Por qué ocurre el problema? | Este problema se debe a la fragmentación de la información clínica y a un enfoque médico que solo actúa cuando los síntomas en la mascota ya son evidentes. La falta de una base de datos unificada y la nula adopción de tecnologías de monitoreo continuo obligan a los dueños a depender de síntomas visibles o graves para buscar ayuda médica, dejando rezagada la prevención de enfermedades frente a las capacidades tecnológicas actuales. |
| ("How") Cómo | ¿Cómo se originó el problema? | El problema se originó debido al rápido aumento en la tenencia responsable y la "humanización" de las mascotas, lo cual generó una alta demanda de servicios especializados. Sin embargo, el sector veterinario no acompañó este crecimiento con una modernización tecnológica, manteniendo historiales en papel o sistemas cerrados, y retrasando la implementación de la Inteligencia Artificial y el IoT en el seguimiento clínico. |
| ("How much") Cuánto | ¿Cuánto costaría solucionarlo? | Se estima que el desarrollo del MVP (Producto Mínimo Viable) que incluye la plataforma web/móvil con IA y la creación de los primeros prototipos de biosensores IoT requerirá una inversión inicial de S/.36,500. |

## Objetivos
Objetivo General:


Objetivos Específicos


## Restricciones


### 1.2.2 Lean UX Process
#### 1.2.2.1 Lean UX Problem Statements
-Los dueños de mascotas tienen dificultades para poder organizar y dar seguimiento al historial medico de sus mascotas, especialmente en procedimientos frecuentes como  baños, vacunas y controles, debido a la gran cantidad de informacion que deben gestionar. Ademas, al presentarse un emergencia con sus mascotas no saben a que veterinaria acudir por que no tiene informacion previa de que procedimientos ofrecen ni de los precios y el horario de atencion, perdiendo tiempo valioso. Por otro lado, los dueños de mascotas no conocen que metodo de pago manejan cada veterinaria, ni los tiempos de respuesta para agendar una cita, los cuales en su mayoria de casos son de varios dias, provocando demora en la atencion.

-La mayoria de veterinarias cuentan con una gestion de datos de sus usuarios muy poco eficiente, basados en registros fisicos como tarjetas o historial medico en papel, difucultando identificar a sus clientes mas frecuentes, saber que procedimientos que se realizan con mayor frecuencia y mas datos valioso para el negocio. Asimismo, cuentan con dificultad para captar nuevos clientes, debido a la falta de visibilidad de su informacion sobre los servicios que ofrecen, años de experiencia, reseñas de sus usuarios, horarios de atencion y ubicaciones. Ademas, tienen limitaciones para hacer un seguimiento personalizado de cada mascota, lo que puede afectar en la calidad de atención, especialmente en situaciones de emergencia o en la deteccion de patrones para determinar la causa de algunas enermedades. Por otro lado, no tienen control suficiente de la gestion de vacunas, medicamentos o productos que utilizen, perjudicando a la veterinaria y a los usuarios. Finalmente, no cuentan con un registro organizado de los pagos realizados por consultas o procedimientos, teniendo problemas en su gestion administrativa.<br><br>El dominio de este proyecto se centra en el sector salud y cuidado de mascotas, especificamente en la gestion de los servicios veterinarios y el buen manejo de informacion clinica de las mascotas.<br>Los segmentos identificados son los dueños de mascotas que buscan un seguimiento y buen cuidado de las salud de sus mascotas y las veterinarias que nesecitan optimizar la gestion de sus recursos, servicios y tener mayor rango de visibilidad del publico.<br>Actualemnte no existe una plataforma que este centrada en la gestion del historial medico de las mascotas con informacion detallada de las veterinarias, incluyendo servicios, horarios, precios, metodos de pago y la opcion de agendar citas.<br>La vision del proyecto es desarrollar una plataforma digital que conecte a dueños de mascotas con veterinarias, logrando optimizar la gestion de informacion, mejorando la toma de decisiones y garantizando el facil el acceso a un buen servicio de salud de forma rapida, eficiente y confiable.

#### 1.2.2.1 Lean UX Assumptions
Para los dueños de mascotas:<br>
-Se interesan por la salud y el buen cuidado de sus mascotas.<br>
-Prefieren obtener informacion de las veterinarias de forma digital sin acudir presencialmente.<br>
-Nesecitan una forma digitalizada de organizar y dar seguimiento del historial medico de sus mascotas.<br>
-Quieren una atencion rapida y que cumpla con las fechas y horas establecidas.<br><br>Para las veterinarias:<br>-Buscan mejorar la gestion de la informacion de sus clientes y de las mascotas.<br>-Prefieren digtilizar sus procesos para optimizar tiempo y reducir errores.<br>-Nesecitan una manera rapida y organizada de registrar y dar seguimiento al historial clinico de las mascotas.<br>-Buscan ampliar su rango de visibilidad para atraer nuevos clientes.<br>-Quieren mostrar informacion de sus servicios, precios, horarios y ubicacion sin tener que enviar la informacion manualmente a cada cliente.<br>-Nesecitan herramientas que les permitan gestionar citas, pagos y la atencion al cliente.<br>-Buscan mejorar la calidad de atencion mediante un seguimiento mucho mas personalizado de cada mascota.

#### 1.2.2.1 Lean UX Hypothesis Statements
-Creemos que con nuestra aplicación los dueños de mascotas podrán organizar y dar seguimiento al historial médico de sus mascotas de manera más eficiente. Sabremos que hemos tenido éxito cuando veamos que al menos el 70% de los usuarios registrados utilizan la función de historial médico de forma recurrente. Mediremos esto mediante las estadísticas de uso dentro de la plataforma.<br><br>
-Creemos que con nuestra aplicación los usuarios podrán encontrar veterinarias de forma más rápida y eficiente. Sabremos que hemos tenido éxito cuando al menos el 60% de los usuarios seleccionen una veterinaria desde la plataforma. Mediremos esto mediante las estadísticas de búsqueda y selección registradas en la base de datos.<br><br>-Creemos que con nuestra aplicación se reducirá el tiempo para agendar citas veterinarias. Sabremos que hemos tenido éxito cuando el tiempo promedio de agendamiento disminuya en al menos un 40% en comparación con métodos tradicionales. Mediremos esto mediante los tiempos registrados en el sistema de agendamiento<br><br>-Creemos que con nuestra aplicación las veterinarias podrán mejorar la gestión de sus clientes y servicios. Sabremos que hemos tenido éxito cuando al menos el 70% de las veterinarias registradas utilicen activamente la plataforma. Mediremos esto mediante las estadísticas de uso dentro del sistema.<br><br>-Creemos que con nuestra aplicación las veterinarias aumentarán su visibilidad y captación de clientes. Sabremos que hemos tenido éxito cuando las citas agendadas a través de la plataforma aumenten en un 50%. Mediremos esto mediante los registros de citas en la base de datos.

#### 1.2.2.1 Lean UX Canvas


<table>  
<tr>  
<td>  
<h2>Business Problem</h2>  
-Las Veterinarias y los dueños de mascotas tienen dificultades para gestionar la informacion de los procesos y actividades relacionadas con el cuidado de las mascotas. Actualmente no existe una plataforma intermediaria que facilite la conexion entre los dueños de mascotas y las veterinarias, lo que genera desorganizacion, perdida de tiempo y limita el acceso a los servicios veterinarios.
</td>  
<td>  
<h2>Solutions</h2>  
-Plataforma centrada en conectar a dueños de mascotas con las veterinarias <br><br>-Sistema de registro y gestion del historial medico de las mascotas.<br><br>-Busqueda de veterinarias y que contengan informacion detallada de servicios, precios, horarios y ubicacion.<br><br>-Sistema de agendamiento de citas en linea.<br><br>-Apartado de gestion para veterinaria de clientes, mascotas, productos y servicos que brindan.<br><br>-Sistema de recordatorio para las citas, vacunas, controles y tratamientos. 
</td>  
<td>  
<h2>Business Outcomes</h2>  
-la cantidad de usuarios registrados en la plataforma aumentara en un 30% durante los primero 5 meses despues del lanzamiento.<br>KPI: Porcentaje de crecimiento mensual de usuarios registrados.<br>Metodo de medicion: Analisis de la base de datos de usuarios registrados en la plataforma.<br><br>-El numero de citas en la veterinaria agendadas por medio de la plataforma aumentara en un 40% en los proximos 7 meses.<br>KPI: Numero de citas agendadas por mes.<br>Metodos de medicion: Comparacion del resgistro de citas actuales con las anteriores, dentro del sistema.<br><br>-La cantidad de veterinarias registradas aumentara en un 25% durante el primer año.<br>KPI: Numero de veterinarias activas a la actualidad.<br>Metodo de medicion: Comparacion en la base de datos de la cantidad de veterinarias actuales con las antiguas.<br><br>- El uso de la plataforma por parte de los usuarios aumentara un 35% en los primeros 6 meses.<br>KPI: Cantidad de usuarios navegando en la plataforma.<br>Metodo de medicion: Registro de los usuarios activos mediante herramientas de analitica, que monitorean la actividad dentro de la plataforma.
</td>  
</tr>  
<tr>  
<td>  
<h2>Users</h2>  
-Dueños de mascotas<br>Personas que tienen una o varias mascotas y buscan mejorar su cuidado mediante un seguimiento mas preciso de su salud.<br><br>-veterinarias: Centros de atencion que buscan captar mas clientes, optimizar la gestion de su negocio y brindar una mejor experiencia a sus clientes.
</td>  
<td></td>  
<td>  
<h2>User Outcomes & Benefits</h2>  
-Dueños de las mascotas: Podran organizar y dar seguimiento al historial medico de sus mascotas de manera mas eficiente.<br>Podran acceder rapidamente a informacion de veterinarias, ayudando a tomar una mejor desicion.<br>Recibira una atencion mas rapida, organizada y personalizada.<br><br>-Veterinarias: Mejoraran la gestion de sus clientes, los servicios que brindan, productos que ofrecen y los pagos realizados.<br>Aumentaran su visibilidad y captacion de nuevos clientes.
</td>  
</tr>  
<tr>  
<td>  
<h2>Hypotheses</h2>  
-Los dueños de mascotas nesecitan llevar un registro del historial medico de sus mascotas.<br>Los usuarios consideran util revisar el historial medico de forma frecuente.<br>-Los usuarios utilizaran la funcion de historial medico frecuentemente si es facil de acceder.<br>-La gestion digital del historial medico es mas eficiente que metodos manuales como papel o memorizar.<br>-Los usuarios tienen dificultades para encontrar veterinarias que cumplan con sus nesecidades.<br>-Los usuarios prefieren buscar las veterinarias dentro de la plataforma por que esta enfocada en ello.<br>-Los usuarios confiaran en la informacion de las veterinarias mostradas en la paltaforma.<br>-El proceso actual que se usa para agendar citas es lento o poco eficiente.<br>-Los usuarios prefieren agendar citas desde una plataforma digital en lugar de realizar llamadas o ir presencialmente.<br>-Un sistema digital reduce el tiempo que se tardan en agendar una cita.<br>-Los usuarios completaran el proceso de agendamiento sin abandonar la plataforma por que sera intuitiva, facil de realizar y sin muchos clicks.<br>-Las veterinarias estan dispuestas a adoptar plataformas digitales para la mejora de su negocio.<br>-El uso de una plataforma mejora la organizacion interna de las veterinarias.<br>-Las veterinarias usaran de forma continua la plataforma si ven beneficios notables.<br>-Las veterinarias buscan aumentar su visibilidad frente a nuevos clientes.<br>-Los usuarios confiaran en las veterianrias que esten en la plataforma.
</td>  
<td>  
<h2>What’s the most important thing we need to learn first?</h2>  
-Lo mas importante que nesecitamos aprender primero es si los dueños de mascotas estaran dispuestos a utilizar una plataforma digital para gestionar el historial medico de sus mascotas. Tambien si las veterinarias estan dispuestas a colocar informacion en la plataforma, como ubicacion y reseña de usarios. Por ultimo, en que meses del año es donde las veterinarias concentran una mayor demanda de servicios.
</td>  
<td>  
<h2>What’s the least amount of work we need to do to learn the next most important thing?</h2>  
-Realizar encuestas para obtener los datos más importantes que debemos saber de nuestros usuarios y así mejorar la forma en la que interactúan con la plataforma.<br>
</td>  
</tr>  
</table>

## 1.3 Segmentos objetivo

### Segmento Objetivo 1: Dueños de mascotas

Personas entre 18 y 30 años que poseen mascotas y buscan mejorar la gestión de su salud mediante herramientas digitales.

**Características:**
- Interesados en vacunas, controles periódicos y prevención de enfermedades.
- Buscan facilidad para agendar citas veterinarias.
- Valoran el ahorro de tiempo y el acceso rápido a clínicas confiables.
- Algunos requieren seguimiento constante (mascotas enfermas o de edad avanzada).

**Necesidad:**
Gestionar la salud de su mascota de forma rápida, organizada y accesible.

**Valor que reciben:**
Comodidad en la gestión, control del historial clínico y acceso a recomendaciones inteligentes personalizadas.



### Segmento Objetivo 2: Clínicas veterinarias y veterinarios

Centros veterinarios y profesionales independientes que ofrecen servicios de atención médica para mascotas.

**Características:**
- Necesitan mayor visibilidad en el mercado y captar nuevos clientes.
- Buscan digitalizar y organizar historiales clínicos.
- Quieren optimizar la gestión de citas y la atención al cliente.

**Necesidad:**
Digitalizar procesos operativos y aumentar su clientela.

**Valor que reciben:**
Mayor alcance, mejor organización interna y fidelización de clientes.
# Capitulo II: Requirements Elicitation & Analysis
## 2.1 Competidores

### 2.1.1 Análisis Competitivo

<table border="1" cellpadding="5" cellspacing="0">
  <tr>
    <th colspan="6"><b>Competitive Analysis Landscape</b></th>
  </tr>
  <tr>
    <td>¿Por qué llevar a cabo este análisis?</td>
    <td colspan="5"> xx</td>
  </tr>
  <tr>
    <td colspan="2">Nombre y logo de competidor</td>
    <td><b>xxx<img src="assets/xxx.jpeg"  width="120" height="120" /> </b></td>
    <td><b>xxx</b> <img src="assets/xxx.png" width="120" height="120" /> </td>
    <td><b>xxx</b> <img src="assets/xxx.png" width="120" height="120" /> </td>
    <td><b>xx</b> <img src="assets/xxx.png" width="120" height="120" /> </td>
  </tr>
  <tr>
    <td rowspan="2"><b>Perfil</b></td>
    <td><b>Overview</b></td>
    <td> xxx </td>
    <td> xxx</td>
    <td>xxx</td>
    <td>xxx</td>
  </tr>
  <tr>
    <td><b>Ventaja competitiva ¿Qué valor ofrece a los clientes?</b></td>
    <td> xxx </td>
    <td> xxx</td>
    <td> xxx</td>
    <td>xxx</td>
  </tr>
  <tr>
    <td rowspan="2"><b>Perfil de Marketing</b></td>
    <td><b>Mercado objetivo</b></td>
    <td>xxx</td>
    <td>xxx</td>
    <td>xxx</td>
    <td>xxx</td>
  </tr>
  <tr>
    <td><b>Estrategias de marketing</b></td>
    <td>xxxx</td>
    <td>xxx.</td>
    <td>xxx</td>
    <td>
xxx</td>
  </tr>
  <tr>
    <td rowspan="3"><b>Perfil de Producto</b></td>
    <td><b>Productos y Servicios</b></td>
    <td>xxx </td>
    <td>xxx</td>
    <td>xxx</td>
    <td>xxx</td>
  </tr>
  <tr>
    <td><b>Precios y Costos</b></td>
    <td> xxx</td>
    <td> xxx</td>
    <td>xxx</td>
    <td>xxx</td>
  </tr>
  <tr>
    <td><b>Canales de distribución (Web y/o móvil)</b></td>
    <td>xxx</td>
    <td>xxx</td>
    <td>
xxx</td>
    <td>
xxx</td>
  </tr>
  <tr>
    <td rowspan="5"><b>Análisis SWOT</b></td>
    <td colspan="5">Realice esto para su startup y sus competidores. Sus fortalezas deberían apoyar sus oportunidades y contribuir a lo que ustedes definen como su posible ventaja competitiva.</td>
  </tr>
  <tr>
    <td><b>Fortalezas</b></td>
    <td>xxx</td>
    <td>xxxx</td>
    <td>
xxx</td>
    <td>
xxx</td>
  </tr>
  <tr>
    <td><b>Debilidades</b></td>
    <td>xxx</td>
    <td>xxx</td>
    <td>
xxx</td>
    <td>
xxx</td>
  </tr>
  <tr>
    <td><b>Oportunidades</b></td>
    <td>xxx</td>
    <td>
xxx</td>
    <td>
xxx</td>
  <td>
xxx</td>
  </tr>
  <tr>
    <td><b>Amenazas</b></td>
    <td>xxx</td>
    <td>
xxx</td>
    <td>
-xxx</td>
    <td>
xxx</td>
  </tr>
</table>

### **2.1.2 Estrategias y tácticas frente a competidores**

## 2.2 Entrevistas
### 2.2.1. Diseño de entrevistas

##### Preguntas Generales



##### Preguntas Específicas

###### Segmento 1:
###### Segmento 2: 


### 2.2.2. Registro de entrevistas 
URL del video:

Segmento 1:

| N | Datos |Descripción |Imagen referencial
|--|--|--|--|
|1  | Nombre:  <br>Edad: <br>Distrito: |<br>|<img src="assets/seg1 - img1.jpg">
|2  | Nombre: <br>Apellido: <br>Edad: <br>Distrito: ||<img src="assets/seg1 - img2.jpg">
|3  | Nombre:  <br>Apellido:   <br>Edad:  <br>Distrito:   | |<img src="assets/Entrevista-xx.png">

Segmento 2:


| N | Datos |Descripción |Imagen referencial
|--|--|--|--|
|1  | Nombre:  <br>Apellido:  <br>Edad:  <br>Distrito:  | |<img src="assets/xxx.png">
|2  | Nombre: <br>Apellido: <br>Edad: <br>Distrito: ||<img src="assets/xxx.png">
|3  | Nombre:  <br>Apellido:   <br>Edad:  <br>Distrito:   | | <img src="assets/xxx3.png">


### 2.2.3. Análisis de entrevistas 
## 2.3. Needfinding
### 2.3.1. User Personas 
### 2.3.2. User Task Matrix 
### 2.3.3. User Journey Mapping 
### 2.3.4. Empathy Mapping
## 2.4. Big Picture Event Storming
## 2.5. Ubiquitous Language
# Capitulo III: Requirements Specification
## 3.1. User Stories
En esta sección, profundizaremos en la definición y elaboración de las User Stories relacionadas con nuestro proyecto. Las User Stories son una herramienta fundamental en el desarrollo de software y proyectos de diseño centrados en el usuario.

**EPICS**

| **Epic ID** | **Título** | **Descripción** | **Criterio de aceptación** |
|---|---|---|---|
| EPIC-01 | Gestión de Mascotas | Como dueño de mascota, quiero administrar el perfil, salud y dieta de mis mascotas, para centralizar su cuidado preventivo. | **Dado** que el usuario accede al módulo de mascotas. <br> **Cuando** registra datos, fotos, vacunas, peso o dietas. <br> **Entonces** el sistema actualiza la ficha individual y resalta alertas de alergias o condiciones médicas. |
| EPIC-02 | Gestión de Citas Veterinarias | Como dueño y veterinario, queremos gestionar el agendamiento de citas, para organizar la atención y evitar cruces de horarios. | **Dado** que existe disponibilidad en el calendario. <br> **Cuando** se reserva, reprograma o cancela una cita. <br> **Entonces** el sistema actualiza el estado en tiempo real, notifica a ambas partes y sincroniza el calendario. |
| EPIC-03 | Búsqueda y Descubrimiento | Como dueño de mascota, quiero localizar veterinarias por filtros y ubicación, para encontrar la atención más cercana y confiable. | **Dado** que el usuario utiliza filtros de distrito, especialidad o mapa. <br> **Cuando** realiza la búsqueda. <br> **Entonces** el sistema muestra los locales disponibles, sus perfiles profesionales, calificaciones y tiempos de espera. |
| EPIC-04 | Comunicación y Soporte | Como usuario, quiero disponer de canales de comunicación directa y soporte, para resolver dudas técnicas o médicas rápidamente. | **Dado** que el usuario requiere asistencia o seguimiento. <br> **Cuando** envía mensajes por chat, adjunta archivos o genera un ticket de soporte. <br> **Entonces** el sistema canaliza la solicitud y notifica la respuesta. |
| EPIC-05 | Gestión Administrativa | Como administrador de veterinaria, quiero gestionar mi negocio, staff y recursos, para optimizar la operación y visibilidad comercial. | **Dado** que el administrador accede al panel de control. <br> **Cuando** gestiona el staff, stock, precios, servicios o planes premium. <br> **Entonces** el sistema actualiza el perfil comercial y genera reportes de rendimiento e ingresos. |
| EPIC-06 | Operación Clínica | Como veterinario, quiero gestionar la información médica avanzada de los pacientes, para garantizar un diagnóstico y tratamiento preciso. | **Dado** que el médico atiende a una mascota. <br> **Cuando** registra el historial, emite recetas digitales o carga laboratorios. <br> **Entonces** el sistema genera archivos PDF descargables y actualiza el expediente clínico. |
| EPIC-07 | Pagos y Fidelización | Como dueño de mascota, quiero realizar pagos seguros y acumular beneficios, para agilizar mis transacciones y obtener recompensas. | **Dado** que se ha seleccionado un servicio o cita. <br> **Cuando** el usuario procesa el pago y confirma la transacción. <br> **Entonces** el sistema valida el cobro, guarda el historial de gastos y suma puntos de lealtad. |
| EPIC-08 | Comunidad y Experiencia | Como usuario, quiero interactuar con la plataforma y otros miembros, para mejorar la experiencia de cuidado y seguridad de las mascotas. | **Dado** que el usuario participa en la plataforma. <br> **Cuando** califica servicios, guarda favoritos, reporta mascotas perdidas o documenta evoluciones visuales. <br> **Entonces** el sistema publica la información para la red de usuarios. |
| EPIC-09 | Seguridad y Usuarios | Como usuario de la plataforma, quiero gestionar mis credenciales y acceso, para proteger mi información personal y médica. | **Dado** que el usuario desea acceder o modificar su cuenta. <br> **Cuando** edita sus datos, recupera su clave, activa el 2FA o vincula familiares. <br> **Entonces** el sistema valida la identidad y asegura el acceso. |
| EPIC-10 | Comunicación y Feedback | Como usuario del sistema, quiero recibir alertas automáticas y calificar la plataforma, para estar al día con la salud de mi mascota y mejorar el servicio. | **Dado** que ocurren eventos programados o cierres de atención. <br> **Cuando** el sistema envía recordatorios de salud o solicita evaluaciones de soporte. <br> **Entonces** se registra el feedback y se garantiza el cumplimiento del plan médico. |


**USER STORIES**
| Epic/User Story ID | Título | Descripción | Criterio de aceptación | Relación (EPIC ID) |
|---|---|---|---|---|
| US01 | Buscar veterinarias con filtros | Como dueño de mascota, quiero buscar veterinarias mediante filtros por distrito, horario y especialidad, para encontrar una opción adecuada rápidamente. | **Escenario 1: Búsqueda con filtros exitosos**<br>**Dado** que el usuario se encuentra en la sección de búsqueda,<br>**Cuando** selecciona distrito, horario o especialidad,<br>**Entonces** el sistema muestra veterinarias relacionadas con los filtros elegidos.<br><br>**Escenario 2: Sin resultados disponibles**<br>**Dado** que no existen coincidencias registradas,<br>**Cuando** el usuario realiza la búsqueda,<br>**Entonces** el sistema informa que no se encontraron resultados. | EP03  |
| US02 | Visualizar reseñas de veterinarias | Como dueño de mascota, quiero visualizar reseñas y calificaciones de otros usuarios, para elegir una veterinaria confiable. | **Escenario 1: Visualización de reseñas**<br>**Dado** que la veterinaria posee valoraciones registradas,<br>**Cuando** el usuario accede al perfil de la veterinaria,<br>**Entonces** el sistema muestra reseñas y calificaciones disponibles.<br><br>**Escenario 2: Sin reseñas registradas**<br>**Dado** que la veterinaria no posee reseñas,<br>**Cuando** el usuario visualiza su perfil,<br>**Entonces** el sistema informa que aún no existen valoraciones. | EP03 |
| US03 | Consultar historial clínico digital | Como dueño de mascota, quiero acceder al historial clínico digital de mis mascotas, para consultar tratamientos y antecedentes médicos. | **Escenario 1: Consulta de historial disponible**<br>**Dado** que la mascota posee registros médicos,<br>**Cuando** el usuario accede al historial clínico,<br>**Entonces** el sistema muestra la información almacenada.<br><br>**Escenario 2: Sin historial registrado**<br>**Dado** que la mascota no posee registros previos,<br>**Cuando** el usuario accede al historial clínico,<br>**Entonces** el sistema informa que no existen datos registrados. | EP01 |
| US04 | Registrar vacunas y controles médicos | Como dueño de mascota, quiero registrar vacunas y controles médicos, para mantener actualizado el seguimiento preventivo de mis mascotas. | **Escenario 1: Registro exitoso**<br>**Dado** que el usuario ingresa la información requerida,<br>**Cuando** registra una vacuna o control,<br>**Entonces** el sistema guarda los datos correctamente.<br><br>**Escenario 2: Datos incompletos**<br>**Dado** que faltan campos obligatorios,<br>**Cuando** el usuario intenta registrar la información,<br>**Entonces** el sistema solicita completar los datos faltantes. | EP01 |
| US05 | Reservar citas veterinarias online | Como dueño de mascota, quiero reservar citas veterinarias en línea, para ahorrar tiempo y evitar llamadas. | **Escenario 1: Reserva confirmada**<br>**Dado** que existen horarios disponibles,<br>**Cuando** el usuario selecciona fecha y hora,<br>**Entonces** el sistema registra la cita correctamente.<br><br>**Escenario 2: Horario ocupado**<br>**Dado** que el horario ya no se encuentra disponible,<br>**Cuando** el usuario intenta reservarlo,<br>**Entonces** el sistema informa que debe elegir otro horario. | EP02 |
| US06 | Reprogramar o cancelar citas | Como dueño de mascota, quiero modificar o cancelar citas programadas, para adaptarme a cambios de horario. | **Escenario 1: Reprogramación exitosa**<br>**Dado** que la cita se encuentra vigente,<br>**Cuando** el usuario selecciona una nueva fecha disponible,<br>**Entonces** el sistema actualiza la cita correctamente.<br><br>**Escenario 2: Cancelación exitosa**<br>**Dado** que existe una cita programada,<br>**Cuando** el usuario solicita cancelarla,<br>**Entonces** el sistema elimina la reserva y confirma la acción. | EP02 |
| US07 | Recibir recordatorios automáticos | Como dueño de mascota, quiero recibir notificaciones automáticas, para recordar vacunas y controles médicos pendientes. | **Escenario 1: Envío de recordatorio**<br>**Dado** que existe una vacuna próxima a vencer,<br>**Cuando** llega la fecha programada,<br>**Entonces** el sistema envía una notificación al usuario.<br><br>**Escenario 2: Recordatorio de control médico**<br>**Dado** que existe una cita próxima,<br>**Cuando** se acerca la fecha establecida,<br>**Entonces** el sistema envía una alerta preventiva. | EP10 |
| US08 | Visualizar calendario de citas y controles | Como dueño de mascota, quiero visualizar un calendario con citas y controles, para organizar mejor el cuidado de mis mascotas. | **Escenario 1: Calendario con eventos registrados**<br>**Dado** que existen citas o controles agendados,<br>**Cuando** el usuario accede al calendario,<br>**Entonces** el sistema muestra los eventos programados.<br><br>**Escenario 2: Calendario vacío**<br>**Dado** que no existen eventos registrados,<br>**Cuando** el usuario visualiza el calendario,<br>**Entonces** el sistema informa que no hay actividades pendientes. | EP02 |
| US-09 | Registro de veterinaria en la plataforma | Como administrador de veterinaria, quiero registrar mi negocio en la plataforma para aumentar mi visibilidad y captar nuevos clientes. | **Escenario 1: Registro exitoso**<br>**Dado** que el administrador se encuentra en el formulario de registro,<br>**Cuando** completa correctamente los datos obligatorios de la veterinaria,<br>**Entonces** el sistema registra la cuenta exitosamente.<br><br>**Escenario 2: Campos incompletos**<br>**Dado** que el administrador desea registrarse,<br>**Cuando** deja campos obligatorios vacíos,<br>**Entonces** el sistema muestra un mensaje solicitando completar la información faltante. | EP05  |
| US-10 | Gestión de perfil comercial | Como administrador de veterinaria, quiero actualizar horarios, promociones y datos comerciales para mantener informados a los clientes. | **Escenario 1: Actualización de información**<br>**Dado** que el administrador ingresó a su panel de control,<br>**Cuando** modifica horarios, dirección o datos comerciales y guarda cambios,<br>**Entonces** el sistema actualiza la información correctamente.<br><br>**Escenario 2: Publicación de promociones**<br>**Dado** que el administrador desea promocionar un servicio,<br>**Cuando** registra una nueva promoción,<br>**Entonces** esta se muestra en el perfil de la veterinaria. | EP05 |
| US-11 | Sistema de citas online | Como veterinario, quiero gestionar citas digitales para organizar mejor la atención de mis pacientes. | **Escenario 1: Visualización de citas**<br>**Dado** que el veterinario accede al módulo de citas,<br>**Cuando** ingresa al calendario,<br>**Entonces** el sistema muestra las citas programadas por fecha y hora.<br><br>**Escenario 2: Reprogramación de cita**<br>**Dado** que existe una cita registrada,<br>**Cuando** el veterinario cambia fecha u hora,<br>**Entonces** el sistema actualiza la cita y notifica al cliente. | EP02 |
| US-12 | Historial clínico digital | Como veterinario, quiero registrar el historial clínico de cada mascota para acceder rápidamente a su información médica. | **Escenario 1: Registro médico exitoso**<br>**Dado** que el veterinario se encuentra en la ficha de una mascota,<br>**Cuando** agrega vacunas, diagnósticos o tratamientos,<br>**Entonces** el sistema guarda la información en el historial clínico.<br><br>**Escenario 2: Consulta de historial**<br>**Dado** que la mascota cuenta con registros previos,<br>**Cuando** el veterinario accede a su perfil,<br>**Entonces** el sistema muestra el historial médico completo. | EP06 |
| US-13 | Plan premium de posicionamiento | Como administrador de veterinaria, quiero contratar un plan premium para destacar mi negocio dentro de la plataforma. | **Escenario 1: Contratación del plan premium**<br>**Dado** que el administrador visualiza los planes disponibles,<br>**Cuando** selecciona el plan premium y confirma el pago,<br>**Entonces** el sistema activa los beneficios correspondientes.<br><br>**Escenario 2: Mayor visibilidad**<br>**Dado** que la veterinaria tiene plan premium activo,<br>**Cuando** los usuarios realizan búsquedas relacionadas,<br>**Entonces** el perfil aparece en posiciones destacadas. | EP05 |
| US-14 | Recordatorios automáticos de citas | Como veterinario, quiero enviar recordatorios automáticos a mis clientes para reducir ausencias y cancelaciones. | **Escenario 1: Envío de recordatorio**<br>**Dado** que existe una cita próxima programada,<br>**Cuando** faltan 24 horas para la atención,<br>**Entonces** el sistema envía un recordatorio automático al cliente.<br><br>**Escenario 2: Confirmación de asistencia**<br>**Dado** que el cliente recibe el recordatorio,<br>**Cuando** confirma o solicita reprogramación,<br>**Entonces** el sistema actualiza el estado de la cita. | EP02 |
| US15 | Registro de perfil de mascota | Como dueño de mascota, quiero crear un perfil individual para mis mascotas, para centralizar su información y fotos. | **Escenario 1: Registro exitoso**<br>**Dado** que el usuario completa nombre, especie y raza,<br>**Cuando** guarda la información,<br>**Entonces** el sistema crea la ficha de la mascota.<br><br>**Escenario 2: Foto de perfil**<br>**Dado** que el usuario desea personalizar la ficha,<br>**Cuando** sube una imagen,<br>**Entonces** el sistema la muestra como foto principal. | EP01 |
| US16 | Edición de datos del dueño | Como dueño de mascota, quiero actualizar mi contacto y dirección, para que las veterinarias tengan mis datos vigentes. | **Escenario 1: Actualización exitosa**<br>**Dado** que el usuario modifica su teléfono,<br>**Cuando** guarda los cambios,<br>**Entonces** el sistema actualiza la información de contacto.<br><br>**Escenario 2: Validación de formato**<br>**Dado** que el usuario ingresa un teléfono inválido,<br>**Cuando** intenta guardar,<br>**Entonces** el sistema muestra un error de formato. | EP09 |
| US17 | Registro de alergias y cuidados | Como dueño de mascota, quiero anotar alergias o condiciones especiales, para prevenir negligencias en las consultas. | **Escenario 1: Alerta visible**<br>**Dado** que la mascota tiene alergias registradas,<br>**Cuando** el veterinario abre su ficha,<br>**Entonces** el sistema resalta las alergias en una sección prioritaria. | EP01 |
| US18 | Pago de reserva en línea | Como dueño de mascota, quiero pagar la cita mediante la app, para asegurar mi cupo y agilizar el proceso presencial. | **Escenario 1: Pago aprobado**<br>**Dado** que el usuario ingresa datos de su tarjeta,<br>**Cuando** confirma la transacción,<br>**Entonces** el sistema procesa el pago y confirma la cita.<br><br>**Escenario 2: Pago rechazado**<br>**Dado** que la tarjeta no tiene fondos,<br>**Cuando** se intenta procesar,<br>**Entonces** el sistema informa el fallo. | EP07 |
| US19 | Chat de consultas post-cita | Como dueño de mascota, quiero chatear con el veterinario que atendió a mi mascota, para resolver dudas sobre el tratamiento. | **Escenario 1: Inicio de conversación**<br>**Dado** que existe una consulta finalizada,<br>**Cuando** el usuario envía un mensaje,<br>**Entonces** el veterinario recibe la notificación en su panel. | EP04 |
| US20 | Adjuntar archivos en el chat | Como usuario, quiero enviar fotos de los síntomas de mi mascota, para que el veterinario tenga una referencia visual rápida. | **Escenario 1: Envío de imagen**<br>**Dado** que el chat está activo,<br>**Cuando** el usuario adjunta una foto,<br>**Entonces** el sistema la muestra correctamente en la conversación. | EP04 |
| US21 | Reportar reseña inapropiada | Como administrador de veterinaria, quiero reportar reseñas falsas, para proteger la reputación de mi negocio. | **Escenario 1: Reporte enviado**<br>**Dado** que una reseña infringe las normas,<br>**Cuando** el administrador la marca como inapropiada,<br>**Entonces** el sistema envía el caso a revisión global. | EP08 |
| US22 | Guardar veterinarias favoritas | Como dueño de mascota, quiero marcar veterinarias como favoritas, para acceder a sus perfiles de forma recurrente. | **Escenario 1: Añadir a favoritos**<br>**Dado** que el usuario pulsa el ícono de "favorito",<br>**Cuando** accede a su perfil,<br>**Entonces** el sistema muestra su lista personalizada. | EP08 |
| US23 | Filtro de veterinarias 24 horas | Como dueño de mascota, quiero filtrar solo veterinarias con atención de emergencia, para actuar rápido ante accidentes nocturnos. | **Escenario 1: Búsqueda de emergencia**<br>**Dado** que el usuario activa el filtro "24 horas",<br>**Cuando** realiza la búsqueda,<br>**Entonces** el sistema muestra solo locales abiertos. | EP03 |
| US24 | Descarga de recetas digitales | Como dueño de mascota, quiero descargar las recetas médicas en PDF, para comprarlas en cualquier establecimiento. | **Escenario 1: Generación de PDF**<br>**Dado** que el veterinario emitió una receta,<br>**Cuando** el usuario hace clic en "Descargar",<br>**Entonces** el sistema genera el archivo con firma digital. | EP06 |
| US25 | Gestión de servicios y precios | Como administrador de veterinaria, quiero configurar mi catálogo de servicios, para que los clientes conozcan los costos. | **Escenario 1: Actualización de precios**<br>**Dado** que el administrador edita el costo de un servicio,<br>**Cuando** guarda los cambios,<br>**Entonces** el nuevo precio se refleja en el perfil público. | EP05 |
| US26 | Bloqueo de fechas por feriados | Como administrador de veterinaria, quiero bloquear días específicos del calendario, para evitar citas en fechas no laborables. | **Escenario 1: Día no disponible**<br>**Dado** que el administrador marca una fecha como feriado,<br>**Cuando** un usuario intenta reservar,<br>**Entonces** el sistema muestra el horario como bloqueado. | EP05 |
| US27 | Dashboard de citas mensuales | Como administrador de veterinaria, quiero ver estadísticas de citas realizadas, para medir el rendimiento del negocio. | **Escenario 1: Visualización de reporte**<br>**Dado** que el administrador accede a estadísticas,<br>**Cuando** selecciona un mes,<br>**Entonces** el sistema muestra un gráfico con el total de atenciones. | EP05 |
| US28 | Registro de personal (Staff) | Como administrador de veterinaria, quiero crear cuentas para mis veterinarios, para que gestionen sus propios pacientes. | **Escenario 1: Creación de usuario**<br>**Dado** que el administrador ingresa el email del médico,<br>**Cuando** asigna el rol,<br>**Entonces** el sistema envía las credenciales al nuevo usuario. | EP05 |
| US29 | Historial de pagos realizados | Como dueño de mascota, quiero ver el detalle de mis gastos, para llevar un control financiero de los cuidados de mi mascota. | **Escenario 1: Listado de transacciones**<br>**Dado** que el usuario accede a "Mis Pagos",<br>**Cuando** consulta su historial,<br>**Entonces** el sistema muestra fecha, monto y local. | EP07 |
| US30 | Notificación de "Mascota lista" | Como dueño de mascota, quiero recibir una alerta cuando termine el servicio de grooming, para pasar a recoger a mi mascota. | **Escenario 1: Envío de alerta**<br>**Dado** que el servicio ha finalizado,<br>**Cuando** el personal marca "Finalizado",<br>**Entonces** el sistema envía una notificación push al dueño. | EP08 |
| US31 | Recuperación de contraseña | Como usuario, quiero restablecer mi contraseña mediante mi correo, para recuperar el acceso si la olvido. | **Escenario 1: Restablecimiento exitoso**<br>**Dado** que el usuario solicita un cambio,<br>**Cuando** ingresa el código enviado,<br>**Entonces** el sistema permite definir una nueva clave. | EP09 |
| US32 | Autenticación de dos factores | Como administrador, quiero activar la verificación en dos pasos, para proteger los datos médicos de mi negocio. | **Escenario 1: Login seguro**<br>**Dado** que la opción está activa,<br>**Cuando** el usuario inicia sesión,<br>**Entonces** el sistema solicita un código enviado al celular. | EP09 |
| US33 | Carga de resultados de laboratorio | Como veterinario, quiero subir informes de exámenes externos, para que el historial clínico esté completo. | **Escenario 1: Carga de archivo**<br>**Dado** que el veterinario selecciona un PDF,<br>**Cuando** lo asigna a una consulta,<br>**Entonces** el archivo queda guardado en la ficha. | EP06 |
| US34 | Recordatorio de desparasitación | Como dueño de mascota, quiero alertas de cuándo toca la próxima desparasitación, para mantener la salud preventiva. | **Escenario 1: Notificación programada**<br>**Dado** que pasaron 3 meses de la última dosis,<br>**Cuando** llega la fecha,<br>**Entonces** el sistema envía un recordatorio automático. | EP10 |
| US35 | Exportar historial médico | Como dueño de mascota, quiero exportar el historial a PDF, para presentarlo en otras clínicas si fuera necesario. | **Escenario 1: Exportación exitosa**<br>**Dado** que la mascota tiene registros,<br>**Cuando** el usuario selecciona "Exportar",<br>**Entonces** el sistema genera un documento consolidado. | EP06 |
| US36 | Registro de peso y medidas | Como dueño de mascota, quiero registrar el peso periódicamente, para monitorear el crecimiento de mi mascota. | **Escenario 1: Registro de peso**<br>**Dado** que el usuario ingresa a salud,<br>**Cuando** guarda el peso,<br>**Entonces** el sistema muestra una gráfica de evolución. | EP01 |
| US37 | Visualizar mapa de veterinarias | Como dueño de mascota, quiero ver las veterinarias en un mapa interactivo, para identificar la más cercana a mi ubicación. | **Escenario 1: Ubicación en mapa**<br>**Dado** que el GPS está activo,<br>**Cuando** el usuario abre el buscador,<br>**Entonces** el sistema posiciona marcadores en el mapa. | EP03 |
| US38 | Perfiles de médicos veterinarios | Como dueño de mascota, quiero ver el perfil del médico que atenderá a mi mascota, para conocer su especialidad. | **Escenario 1: Visualización profesional**<br>**Dado** que el usuario ve una clínica,<br>**Cuando** selecciona a un médico,<br>**Entonces** el sistema muestra su experiencia y colegiatura. | EP03 |
| US39 | Gestión de stock de vacunas | Como administrador de veterinaria, quiero registrar el stock de vacunas, para evitar agendar citas sin suministros. | **Escenario 1: Alerta de stock bajo**<br>**Dado** que el inventario llega al mínimo,<br>**Cuando** se realiza una aplicación,<br>**Entonces** el sistema notifica la necesidad de reposición. | EP05 |
| US40 | Sistema de puntos y recompensas | Como dueño de mascota, quiero acumular puntos por citas pagadas, para canjearlos por descuentos futuros. | **Escenario 1: Acumulación de puntos**<br>**Dado** que se confirma el pago,<br>**Cuando** el sistema cierra la atención,<br>**Entonces** suma los puntos al perfil del usuario. | EP07 |
| US41 | Notificación de cita en curso | Como dueño de mascota, quiero saber cuándo mi mascota ingresó a consulta, para estar informado mientras espero fuera. | **Escenario 1: Cambio de estado**<br>**Dado** que el médico inicia la atención,<br>**Cuando** marca inicio en el sistema,<br>**Entonces** el dueño recibe una notificación push. | EP02 |
| US42 | Soporte técnico por tickets | Como usuario, quiero enviar reportes de errores en la app, para que el equipo técnico los solucione. | **Escenario 1: Envío de ticket**<br>**Dado** que el usuario encuentra un fallo,<br>**Cuando** completa el formulario,<br>**Entonces** el sistema genera un número de seguimiento. | EP04 |
| US43 | Vinculación de múltiples dueños | Como dueño de mascota, quiero compartir el perfil con otro familiar, para que ambos gestionemos sus citas. | **Escenario 1: Invitación aceptada**<br>**Dado** que el dueño primario envía invitación,<br>**Cuando** el familiar acepta,<br>**Entonces** ambos visualizan la misma mascota. | EP09 |
| US44 | Filtro por urgencia inmediata | Como dueño de mascota, quiero ver qué veterinarias tienen menor tiempo de espera, para una emergencia médica. | **Escenario 1: Búsqueda por espera**<br>**Dado** que el usuario activa "Urgencia",<br>**Cuando** el sistema procesa,<br>**Entonces** ordena los resultados por disponibilidad inmediata. | EP03 |
| US45 | Configuración de notificaciones | Como usuario, quiero elegir qué alertas recibir, para no saturar mi teléfono con mensajes innecesarios. | **Escenario 1: Personalización**<br>**Dado** que el usuario entra a ajustes,<br>**Cuando** desactiva correos y deja push,<br>**Entonces** el sistema respeta su preferencia. | EP04 |
| US46 | Registro de dieta y alimentación | Como dueño de mascota, quiero anotar el tipo de alimento, para que el veterinario lo considere en su diagnóstico. | **Escenario 1: Registro de dieta**<br>**Dado** que el usuario edita nutrición,<br>**Cuando** guarda marca y porción,<br>**Entonces** la información queda adjunta a la ficha médica. | EP01 |
| US47 | Reporte de ingresos financieros | Como administrador de veterinaria, quiero generar reportes de ganancias, para llevar la contabilidad del negocio. | **Escenario 1: Reporte de ventas**<br>**Dado** que el administrador accede al panel,<br>**Cuando** selecciona un rango de fechas,<br>**Entonces** el sistema calcula el total de ingresos. | EP05 |
| US48 | Galería de fotos del tratamiento | Como veterinario, quiero subir fotos de la evolución de una lesión, para documentar el progreso visualmente. | **Escenario 1: Registro fotográfico**<br>**Dado** que se realiza seguimiento,<br>**Cuando** el médico sube una foto,<br>**Entonces** se guarda cronológicamente en la galería. | EP08 |
| US49 | Alerta de mascotas perdidas | Como dueño de mascota, quiero emitir una alerta de extravío, para que la comunidad ayude en la búsqueda. | **Escenario 1: Modo "Perdido"**<br>**Dado** que la mascota se extravió,<br>**Cuando** el dueño activa la alerta,<br>**Entonces** el sistema notifica a usuarios en un radio cercano. | EP08 |
| US50 | Evaluación del servicio técnico | Como usuario, quiero calificar la atención del soporte, para ayudar a mejorar la calidad de la plataforma. | **Escenario 1: Calificación de ticket**<br>**Dado** que se cerró un ticket,<br>**Cuando** el usuario valora con estrellas,<br>**Entonces** el sistema registra el feedback. | EP10 |

### Technical Epic
| Epic ID  | Título                                   | Descripción                                                                 |
|----------|------------------------------------------|-----------------------------------------------------------------------------|
| EPIC-T01 | Autenticación y control de acceso        | Gestiona registro, inicio de sesión y autorización de usuarios mediante mecanismos seguros. |
| EPIC-T02 | Gestión de entidades del sistema         | Administra usuarios, mascotas y veterinarias mediante operaciones CRUD.     |
| EPIC-T03 | Gestión de citas y disponibilidad        | Controla la lógica de reservas, horarios y estado de citas.                 |
| EPIC-T04 | Gestión de datos clínicos y notificaciones | Maneja almacenamiento de información médica y envío de alertas automáticas. |

### Technical Story

| Technical Story ID | Título                              | Descripción                                               | Criterios de aceptación                                                                 | EPIC      |
|-------------------|-------------------------------------|-----------------------------------------------------------|------------------------------------------------------------------------------------------|-----------|
| TS01              | Validación de disponibilidad        | Evitar conflictos de horarios en citas.                   | Dado horario ocupado, cuando se intenta reservar, entonces el sistema rechaza la operación. | EPIC-T03 |
| TS02             | Sistema de notificaciones           | Implementar envío de alertas automáticas.                 | Dado evento programado, cuando se cumple la condición, entonces el sistema envía notificación. | EPIC-T04 |
| TS03              | Autenticación de usuarios           | Implementar registro e inicio de sesión seguro.           | Dado credenciales válidas, cuando el usuario inicia sesión, entonces el sistema autentica correctamente. | EPIC-T01 |
| TS04             | Control de acceso por roles         | Implementar autorización según tipo de usuario.           | Dado un usuario autenticado, cuando accede a un recurso, entonces el sistema valida permisos según rol. | EPIC-T01 |
| TS05              | Gestión de historial clínico        | Implementar almacenamiento de datos médicos.              | Dado registros clínicos, cuando se consultan, entonces el sistema los muestra correctamente. | EPIC-T04 |
| TS06              | Gestión de usuarios                 | Implementar operaciones CRUD de usuarios.                 | Dado datos válidos, cuando se registra o edita, entonces el sistema guarda correctamente. | EPIC-T02 |
| TS07              | Gestión de mascotas                 | Implementar operaciones CRUD de mascotas.                 | Dado datos de mascota, cuando se registra, entonces el sistema almacena información. | EPIC-T02 |
| TS08              | Gestión de citas                    | Implementar lógica de reservas y estados de citas.        | Dado disponibilidad, cuando se agenda una cita, entonces el sistema la registra correctamente. | EPIC-T03 |
| TS09              | Motor de búsqueda y filtrado        | Implementar búsqueda de veterinarias por filtros.         | Dado filtros aplicados, cuando se consulta, entonces el sistema retorna resultados correctos. | EPIC-T03 |
| TS10             | Gestión de veterinarias             | Implementar registro y administración de veterinarias.    | Dado datos válidos, cuando se procesa, entonces el sistema persiste la información. | EPIC-T02 |
| TS11              | Generación de documentos PDF        | Implementar exportación de recetas e historial.           | Dado solicitud, cuando se genera, entonces el sistema produce archivo válido. | EPIC-T04 |
| TS12             | Recuperación de contraseña          | Implementar recuperación segura mediante correo.          | Dado solicitud válida, cuando el usuario confirma, entonces puede cambiar su contraseña. | EPIC-T01 |

## 3.2. Impact Mapping

#### Segmento 1: Dueños de Mascotas
<img src="assets/impact-mapping-pet-owners.png" />

#### Segmento 2: Veterinarios / Profesionales independientes
<img src="assets/impact-mapping-veterinarians.png" />

## 3.3. Product Backlog
| # Orden | User Story ID | Título | Descripción | Story Points |
|---|---|---|---|---|
| 1 | US15 | Registro de perfil de mascota | Como dueño de mascota, quiero crear un perfil individual para mis mascotas, para centralizar su información y fotos. | 3 |
| 2 | US01 | Buscar veterinarias con filtros | Como dueño de mascota, quiero buscar veterinarias mediante filtros por distrito, horario y especialidad, para encontrar una opción adecuada rápidamente. | 5 |
| 3 | US05 | Reservar citas veterinarias online | Como dueño de mascota, quiero reservar citas veterinarias en línea, para ahorrar tiempo y evitar llamadas. | 5 |
| 4 | US03 | Consultar historial clínico digital | Como dueño de mascota, quiero acceder al historial clínico digital de mis mascotas, para consultar tratamientos y antecedentes médicos. | 5 |
| 5 | US04 | Registrar vacunas y controles médicos | Como dueño de mascota, quiero registrar vacunas y controles médicos, para mantener actualizado el seguimiento preventivo de mis mascotas. | 3 |
| 6 | US08 | Visualizar calendario de citas y controles | Como dueño de mascota, quiero visualizar un calendario con citas y controles, para organizar mejor el cuidado de mis mascotas. | 3 |
| 7 | US22 | Guardar veterinarias favoritas | Como dueño de mascota, quiero marcar veterinarias como favoritas, para acceder a sus perfiles de forma recurrente. | 2 |
| 8 | US02 | Visualizar reseñas de veterinarias | Como dueño de mascota, quiero visualizar reseñas y calificaciones de otros usuarios, para elegir una veterinaria confiable. | 2 |
| 9 | US23 | Filtro de veterinarias 24 horas | Como dueño de mascota, quiero filtrar solo veterinarias con atención de emergencia, para actuar rápido ante accidentes nocturnos. | 2 |
| 10 | US37 | Visualizar mapa de veterinarias | Como dueño de mascota, quiero ver las veterinarias en un mapa interactivo, para identificar la más cercana a mi ubicación. | 5 |
| 11 | US07 | Recibir recordatorios automáticos | Como dueño de mascota, quiero recibir notificaciones automáticas, para recordar vacunas y controles médicos pendientes. | 3 |
| 12 | US06 | Reprogramar o cancelar citas | Como dueño de mascota, quiero modificar o cancelar citas programadas, para adaptarme a cambios de horario. | 3 |
| 13 | US41 | Notificación de cita en curso | Como dueño de mascota, quiero saber cuándo mi mascota ingresó a consulta, para estar informado mientras espero fuera. | 2 |
| 14 | US19 | Chat de consultas post-cita | Como dueño de mascota, quiero chatear con el veterinario que atendió a mi mascota, para resolver dudas sobre el tratamiento. | 5 |
| 15 | US20 | Adjuntar archivos en el chat | Como usuario, quiero enviar fotos de los síntomas de mi mascota, para que el veterinario tenga una referencia visual rápida. | 2 |
| 16 | US18 | Pago de reserva en línea | Como dueño de mascota, quiero pagar la cita mediante la app, para asegurar mi cupo y agilizar el proceso presencial. | 5 |
| 17 | US24 | Descarga de recetas digitales | Como dueño de mascota, quiero descargar las recetas médicas en PDF, para comprarlas en cualquier establecimiento. | 2 |
| 18 | US35 | Exportar historial médico | Como dueño de mascota, quiero exportar el historial a PDF, para presentarlo en otras clínicas si fuera necesario. | 3 |
| 19 | US29 | Historial de pagos realizados | Como dueño de mascota, quiero ver el detalle de mis gastos, para llevar un control financiero de los cuidados de mi mascota. | 2 |
| 20 | US40 | Sistema de puntos y recompensas | Como dueño de mascota, quiero acumular puntos por citas pagadas, para canjearlos por descuentos futuros. | 5 |
| 21 | US38 | Perfiles de médicos veterinarios | Como dueño de mascota, quiero ver el perfil del médico que atenderá a mi mascota, para conocer su especialidad. | 2 |
| 22 | US17 | Registro de alergias y cuidados | Como dueño de mascota, quiero anotar alergias o condiciones especiales, para prevenir negligencias en las consultas. | 2 |
| 23 | US36 | Registro de peso y medidas | Como dueño de mascota, quiero registrar el peso periódicamente, para monitorear el crecimiento de mi mascota. | 3 |
| 24 | US46 | Registro de dieta y alimentación | Como dueño de mascota, quiero anotar el tipo de alimento, para que el veterinario lo considere en su diagnóstico. | 3 |
| 25 | US34 | Recordatorio de desparasitación | Como dueño de mascota, quiero alertas de cuándo toca la próxima desparasitación, para mantener la salud preventiva. | 2 |
| 26 | US30 | Notificación de “Mascota lista” | Como dueño de mascota, quiero recibir una alerta cuando termine el servicio de grooming, para pasar a recoger a mi mascota. | 2 |
| 27 | US49 | Alerta de mascotas perdidas | Como dueño de mascota, quiero emitir una alerta de extravío, para que la comunidad ayude en la búsqueda. | 5 |
| 28 | US44 | Filtro por urgencia inmediata | Como dueño de mascota, quiero ver qué veterinarias tienen menor tiempo de espera, para una emergencia médica. | 2 |
| 29 | US45 | Configuración de notificaciones | Como usuario, quiero elegir qué alertas recibir, para no saturar mi teléfono con mensajes innecesarios. | 2 |
| 30 | US42 | Soporte técnico por tickets | Como usuario, quiero enviar reportes de errores en la app, para que el equipo técnico los solucione. | 3 |
| 31 | US50 | Evaluación del servicio técnico | Como usuario, quiero calificar la atención del soporte, para ayudar a mejorar la calidad de la plataforma. | 2 |
| 32 | US43 | Vinculación de múltiples dueños | Como dueño de mascota, quiero compartir el perfil con otro familiar, para que ambos gestionemos sus citas. | 3 |
| 33 | US16 | Edición de datos del dueño | Como dueño de mascota, quiero actualizar mi contacto y dirección, para que las veterinarias tengan mis datos vigentes. | 1 |
| 34 | US31 | Recuperación de contraseña | Como usuario, quiero restablecer mi contraseña mediante mi correo, para recuperar el acceso si la olvido. | 2 |
| 35 | US32 | Autenticación de dos factores | Como administrador, quiero activar la verificación en dos pasos, para proteger los datos médicos de mi negocio. | 3 |
| 36 | US09 | Registro de veterinaria | Como administrador de veterinaria, quiero registrar mi negocio en la plataforma para aumentar mi visibilidad y captar nuevos clientes. | 5 |
| 37 | US10 | Gestión de perfil comercial | Como administrador de veterinaria, quiero actualizar horarios, promociones y datos comerciales para mantener informados a los clientes. | 3 |
| 38 | US25 | Gestión de servicios y precios | Como administrador de veterinaria, quiero configurar mi catálogo de servicios, para que los clientes conozcan los costos. | 3 |
| 39 | US26 | Bloqueo de fechas por feriados | Como administrador de veterinaria, quiero bloquear días específicos del calendario, para evitar citas en fechas no laborables. | 2 |
| 40 | US27 | Dashboard de citas mensuales | Como administrador de veterinaria, quiero ver estadísticas de citas realizadas, para medir el rendimiento del negocio. | 5 |
| 41 | US47 | Reporte de ingresos financieros | Como administrador de veterinaria, quiero generar reportes de ganancias, para llevar la contabilidad del negocio. | 5 |
| 42 | US28 | Registro de personal (Staff) | Como administrador de veterinaria, quiero crear cuentas para mis veterinarios, para que gestionen sus propios pacientes. | 5 |
| 43 | US13 | Plan premium de posicionamiento | Como administrador de veterinaria, quiero contratar un plan premium para destacar mi negocio dentro de la plataforma. | 5 |
| 44 | US39 | Gestión de stock de vacunas | Como administrador de veterinaria, quiero registrar el stock de vacunas, para evitar agendar citas sin suministros. | 3 |
| 45 | US48 | Galería de fotos del tratamiento | Como veterinario, quiero subir fotos de la evolución de una lesión, para documentar el progreso visualmente. | 3 |
| 46 | US33 | Carga de resultados de laboratorio | Como veterinario, quiero subir informes de exámenes externos, para que el historial clínico esté completo. | 3 |
| 47 | US21 | Reportar reseña inapropiada | Como administrador de veterinaria, quiero reportar reseñas falsas, para proteger la reputación de mi negocio. | 2 |
| 48 | US11 | Sistema de citas online | Como veterinario, quiero gestionar citas digitales para organizar mejor la atención de mis pacientes. | 5 |
| 49 | US12 | Historial clínico veterinario | Como veterinario, quiero registrar el historial clínico de cada mascota para acceder rápidamente a su información médica. | 5 |
| 50 | US14 | Recordatorios automáticos de citas | Como veterinario, quiero enviar recordatorios automáticos a mis clientes para reducir ausencias y cancelaciones. | 3 |

# Capitulo IV: Product Design
## 4.1. Style Guidelines
### 4.1.1. General Style Guidelines
### 4.1.2. Web Style Guidelines
## 4.2. Information Architecture
### 4.2.1. Organization Systems
### 4.2.2. Labeling Systems
### 4.2.3. SEO Tags and Meta Tags 
### 4.2.4. Searching Systems
### 4.2.5. Navigation Systems
## 4.3. Landing Page UI Design
### 4.3.1. Landing Page Wireframe
### 4.3.2. Landing Page Mock-up
## 4.4. Web Applications UX/UI Design
### 4.4.1. Web Applications Wireframes
### 4.4.2. Web Applications Wireflow Diagrams
### 4.4.2. Web Applications Mock-ups
### 4.4.3. Web Applications User Flow Diagrams
## 4.5. Web Applications Prototyping
## 4.6. Domain-Driven Software Architecture
### 4.6.1. Design-Level Event Storming
### 4.6.2. Software Architecture Context Diagram
### 4.6.3. Software Architecture Container Diagrams
### 4.6.4. Software Architecture Components Diagrams
## 4.7. Software Object-Oriented Design
### 4.7.1. Class Diagrams
## 4.8. Database Design
### 4.8.1. Database Diagrams.
# Capitulo V: Product Implementation, Validation & Deployment
## 5.1. Software Configuration Management
### 5.1.1. Software Development Environment Configuration
### 5.1.2. Source Code Management
### 5.1.3. Source Code Style Guide & Conventions
### 5.1.4. Software Deployment Configuration
## 5.2. Landing Page, Services & Applications Implementation
### 5.2.X. Sprint n 
#### 5.2.X.1. Sprint Planning n
#### 5.2.X.2. Aspect Leaders and Collaborators
#### 5.2.X.3. Sprint Backlog n. 
#### 5.2.X.4. Development Evidence for Sprint Review
#### 5.2.X.5. Execution Evidence for Sprint Review
#### 5.2.X.6. Services Documentation Evidence for Sprint Review
#### 5.2.X.7. Software Deployment Evidence for Sprint Review
#### 5.2.X.8. Team Collaboration Insights during Sprint.
## 5.3. Validation Interviews
### 5.3.1. Diseño de Entrevistas
### 5.3.2. Registro de Entrevistas
### 5.3.3. Evaluaciones según heurísticas
## 5.4. Video About-the-Product.
# Conclusiones
## Conclusiones y recomendaciones
## Video About-the-Team.
# Bibliografía 
# Anexos
