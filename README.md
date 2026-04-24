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
- Las Veterinarias y los dueños de mascotas tienen dificultades para gestionar la informacion de los procesos y actividades relacionadas con el cuidado de las mascotas. Actualmente no existe una plataforma intermediaria que facilite la conexion entre los dueños de mascotas y las veterinarias, lo que genera desorganizacion, perdida de tiempo y limita el acceso a los servicios veterinarios.
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
- Dueños de mascotas<br>Personas que tienen una o varias mascotas y buscan mejorar su cuidado mediante un seguimiento mas preciso de su salud.<br><br>-veterinarias: Centros de atencion que buscan captar mas clientes, optimizar la gestion de su negocio y brindar una mejor experiencia a sus clientes.
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

## 1.3 Segmentos Objetivo
# Capitulo II: Requirements Elicitation & Analysis
## 2.1 Competidores
En esta sección se identificarán los principales referentes del mercado para posteriormente realizar un análisis competitivo que permitirá conocer el posicionamiento de PetCare y el valor agregado que ofrecerá dentro del sector de servicios veterinarios digitales.

Según la investigación realizada, se encontraron diversas plataformas web y aplicaciones móviles orientadas al cuidado de mascotas, servicios veterinarios y gestión sanitaria animal. Sin embargo, se han seleccionado tres competidores directos e indirectos que presentan mayor similitud con la propuesta de valor de nuestra startup.

* **DIMU**<br>
DIMU es una plataforma peruana orientada al ecosistema pet care que conecta a dueños de mascotas con distintos servicios como veterinarias, cuidado animal y atención especializada. Su modelo de negocio se basa en la intermediación digital entre usuarios y proveedores de servicios. Es un competidor directo debido a que participa en el mismo mercado objetivo. Sin embargo, PetCare se diferencia al integrar monitoreo de salud mediante dispositivos IoT e historial clínico digital en una sola plataforma.

* **RVM**<br>
RVM es una plataforma enfocada en el registro virtual de mascotas, control de vacunas e historial clínico veterinario. Su propuesta está centrada en la organización sanitaria y seguimiento médico de las mascotas. Representa un competidor directo en la gestión de información clínica. No obstante, PetCare amplía esta propuesta al incluir búsqueda de veterinarias, promociones, marketplace y monitoreo en tiempo real.

* **Rover**<br>
Rover es una plataforma internacional reconocida por conectar dueños de mascotas con cuidadores, paseadores y hospedajes temporales. Su modelo de negocio funciona mediante comisiones por servicios contratados dentro de la plataforma. Es considerado un competidor indirecto, ya que participa dentro del mercado digital pet care, aunque su enfoque principal no está en la salud veterinaria. A diferencia de Rover, PetCare prioriza la atención médica animal, historial clínico y monitoreo inteligente mediante IoT.

### 2.1.1 Análisis Competitivo

<table border="1" cellpadding="5" cellspacing="0">
  <tr>
    <th colspan="6"><b>Competitive Analysis Landscape</b></th>
  </tr>
  <tr>
    <td>¿Por qué llevar a cabo este análisis?</td>
    <td colspan="5">
      El análisis competitivo se realiza para identificar a los principales competidores en el mercado de servicios veterinarios digitales, comprender sus fortalezas, debilidades y estrategias, y definir una propuesta de valor diferenciada para PetCare. Además, permite reconocer oportunidades de innovación como la integración de tecnología IoT en el cuidado de mascotas.
    </td>
  </tr>
  <tr>
    <td colspan="2">Nombre y logo de competidor</td>
    <td align="center">
  <b>PetCare</b><br>
  <img src="assets/petcare.png" width="120" height="120" />
</td>

<td align="center">
  <b>DIMU</b><br>
  <img src="assets/DIMU.jpg" width="120" height="120" />
</td>

<td align="center">
  <b>RVM</b><br>
  <img src="assets/RVM.png" width="120" height="120" />
</td>

<td align="center">
  <b>Rover</b><br>
  <img src="assets/ROVER.png" width="120" height="120" />
</td>
  </tr>
  <tr>
    <td rowspan="2"><b>Perfil</b></td>
    <td><b>Overview</b></td>
    <td>Plataforma web que conecta dueños de mascotas con veterinarios, integrando historial clínico, gestión de citas y monitoreo de salud mediante IoT.</td>
    <td>Aplicación peruana que conecta usuarios con servicios para mascotas, permitiendo agendar citas y encontrar veterinarias.</td>
    <td>Plataforma digital que permite el registro de mascotas, historial clínico y seguimiento de vacunas.</td>
    <td>Plataforma internacional que conecta dueños con cuidadores de mascotas y servicios.</td>
  </tr>
  <tr>
    <td><b>Ventaja competitiva ¿Qué valor ofrece a los clientes?</b></td>
    <td>Integración de IoT, historial clínico y marketplace en una sola plataforma.</td>
    <td>Facilidad de uso y posicionamiento en el mercado local.</td>
    <td>Gestión organizada del historial y control de vacunas.</td>
    <td>Amplia red de servicios y reconocimiento global.</td>
  </tr>
  <tr>
    <td rowspan="2"><b>Perfil de Marketing</b></td>
    <td><b>Mercado objetivo</b></td>
    <td>Dueños de mascotas y veterinarias en Perú.</td>
    <td>Dueños de mascotas en Perú.</td>
    <td>Dueños de mascotas que buscan control de salud de sus animales.</td>
    <td>Dueños de mascotas a nivel internacional.</td>
  </tr>
  <tr>
    <td><b>Estrategias de marketing</b></td>
    <td>Marketing digital, suscripciones y posicionamiento de veterinarias.</td>
    <td>Marketing digital y alianzas con veterinarias.</td>
    <td>Promoción de control sanitario y registro digital.</td>
    <td>Publicidad online, SEO y expansión global.</td>
  </tr>
  <tr>
    <td rowspan="3"><b>Perfil de Producto</b></td>
    <td><b>Productos y Servicios</b></td>
    <td>Marketplace veterinario, historial clínico, monitoreo IoT, promociones.</td>
    <td>Agenda de citas, listado de veterinarias.</td>
    <td>Registro de mascotas, historial clínico, control de vacunas.</td>
    <td>Servicios de cuidado, paseo y alojamiento de mascotas.</td>
  </tr>
  <tr>
    <td><b>Precios y Costos</b></td>
    <td>Modelo con plan gratuito y plan de suscripción para funciones avanzadas.</td>
    <td>Gratuito con posibles comisiones.</td>
    <td>Gratuito o con servicios adicionales.</td>
    <td>Pago por servicio con comisión.</td>
  </tr>
  <tr>
    <td><b>Canales de distribución (Web y/o móvil)</b></td>
    <td>Web y app móvil.</td>
    <td>App móvil.</td>
    <td>Web.</td>
    <td>Web y app móvil.</td>
  </tr>
  <tr>
    <td rowspan="5"><b>Análisis SWOT</b></td>
    <td colspan="5">
      Este análisis permite identificar fortalezas, debilidades, oportunidades y amenazas de PetCare frente a sus competidores para definir estrategias competitivas.
    </td>
  </tr>
  <tr>
    <td><b>Fortalezas</b></td>
    <td>Uso de IoT y plataforma integral.</td>
    <td>Posicionamiento local.</td>
    <td>Especialización en historial clínico.</td>
    <td>Reconocimiento internacional.</td>
  </tr>
  <tr>
    <td><b>Debilidades</b></td>
    <td>Nueva en el mercado.</td>
    <td>No incluye IoT.</td>
    <td>No tiene marketplace de servicios.</td>
    <td>No enfocado en salud veterinaria.</td>
  </tr>
  <tr>
    <td><b>Oportunidades</b></td>
    <td>Crecimiento del mercado pet y tecnología.</td>
    <td>Expansión digital en Perú.</td>
    <td>Digitalización de registros veterinarios.</td>
    <td>Expansión global.</td>
  </tr>
  <tr>
    <td><b>Amenazas</b></td>
    <td>Competencia creciente.</td>
    <td>Nuevas startups.</td>
    <td>Limitaciones tecnológicas.</td>
    <td>Competidores especializados.</td>
  </tr>
</table>

### 2.1.2 Estrategias y tácticas frente a competidores <br> 
En esta sección, se llevará a cabo el análisis de las estrategias y tácticas que serán usadas con el objetivo de buscar provecho a las debilidades de la competencia y afrontar sus fortalezas. Además, gracias al análisis FODA, se lograron identificar las oportunidades y amenazas de mercado presentes, debido a la evaluación de las fortalezas que ofrece nuestro software y las debilidades frente a empresas con mayor posicionamiento y trayectoria dentro del sector veterinario digital. De esa manera, este enfoque nos permite concebir estrategias adecuadas para nuestros segmentos objetivos dentro del mercado pet care.

**Estrategia de Diferenciación:**

* Con el propósito de satisfacer las necesidades de los dueños de mascotas, PetCare propone una plataforma integral orientada al bienestar animal y al acceso rápido a servicios veterinarios confiables. A diferencia de otras alternativas que únicamente funcionan como directorios o plataformas de registro, PetCare se diferencia gracias a la integración de historial clínico digital, recordatorios de vacunas, agendamiento de citas y monitoreo inteligente mediante dispositivos IoT. Ello permitirá que los usuarios administren la salud de sus mascotas desde un solo entorno digital.

* En vista de enriquecer la experiencia de las veterinarias afiliadas, PetCare busca posicionarse como una herramienta comercial y tecnológica. Mientras otras plataformas solo muestran información básica, nuestra solución permitirá promociones, recomendaciones destacadas y posicionamiento dentro de las búsquedas internas. De esa manera, la plataforma ayudará a generar mayor visibilidad y captación de nuevos clientes para los negocios veterinarios asociados.

**Estrategia de Liderazgo en Costos:**

* Como resultado de la búsqueda de accesibilidad para los usuarios, se ofrecerá un modelo freemium. Ello permitirá que los dueños de mascotas accedan inicialmente a funciones esenciales como búsqueda de veterinarias, información básica y consultas generales, sin necesidad de asumir costos inmediatos. Posteriormente, podrán acceder a planes premium con beneficios avanzados como monitoreo IoT e historial clínico ampliado.

* A manera de buscar la satisfacción de las veterinarias afiliadas, la estrategia empleada se basará en planes escalables de bajo costo. En lugar de competir únicamente por precio, nuestra monetización se enfocará en el valor generado mediante publicidad digital, posicionamiento destacado y acceso a una mayor cartera de clientes potenciales dentro de la plataforma.

**Estrategia de Marketing:**

Para ambos segmentos, la estrategia estará centrada en el concepto de "Mascotas saludables con tecnología inteligente". Teniendo esa visión como eje central, se desarrollarán campañas de marketing digital en Lima Metropolitana y otras ciudades principales, demostrando cómo PetCare facilita el cuidado preventivo, mejora el acceso a veterinarias confiables y optimiza el seguimiento de la salud animal. El mensaje central será que una mascota saludable refleja un hogar responsable y conectado.

**Tácticas:**

Establecer alianzas estratégicas con veterinarias locales en Perú para ampliar la cobertura de servicios, lanzar promociones exclusivas dentro de la plataforma, implementar campañas SEO y publicidad digital para posicionar la marca, así como ofrecer periodos de prueba gratuitos para captar usuarios y negocios afiliados.

## 2.2 Entrevistas
### 2.2.1 Diseño de entrevistas

### Segmento Objetivo 1: Dueños de Mascotas (18-40 años)

**Objetivo de la entrevista:**  
Comprender las necesidades, hábitos, dificultades y expectativas de los dueños de mascotas respecto al cuidado, seguimiento médico y búsqueda de servicios veterinarios.

#### 1. Datos Generales

- ¿Qué edad tienes?
- ¿En qué distrito vives?
- ¿A qué te dedicas actualmente? (Estudias, trabajas o ambos)
- ¿Qué dispositivo utilizas con mayor frecuencia? (Celular, laptop, tablet)
- ¿Sueles utilizar aplicaciones o páginas web para organizar servicios en tu día a día? ¿Cuáles?

#### 2. Relación con la Mascota

- ¿Tienes mascotas actualmente?
- ¿Qué tipo de mascota tienes y cuántas?
- ¿Desde hace cuánto tiempo tienes mascotas?
- ¿Cómo es la rutina de cuidado de tu mascota?

#### 3. Servicios Veterinarios

- ¿Con qué frecuencia llevas a tu mascota al veterinario?
- ¿Qué es lo más importante que buscas en una veterinaria?
- ¿Tienes actualmente una veterinaria de confianza? ¿Por qué?
- ¿Qué servicios sueles buscar en una veterinaria?
- ¿Has tenido dificultades para encontrar una veterinaria que cumpla con tus necesidades? ¿Cómo fue esa experiencia?
- ¿Cuánto tiempo te tomó encontrar una veterinaria de confianza?

#### 4. Gestión y Seguimiento

- ¿Cómo sueles agendar citas para tu mascota?
- ¿Cuánto tiempo suele tardar conseguir una cita?
- ¿Cómo organizas los documentos o historial médico de tu mascota?
- ¿Cómo haces el seguimiento de citas, vacunas o tratamientos?
- ¿Qué problemas has tenido al gestionar el cuidado de tu mascota?

#### 5. Necesidades y Solución Digital

- ¿Qué te gustaría mejorar en los servicios veterinarios actuales?
- ¿Te ayudaría una plataforma que te permita encontrar veterinarias según tus necesidades y las de tu mascota? ¿Por qué?
- ¿Qué funcionalidades te gustaría que tenga una aplicación web para el cuidado de mascotas?
- ¿Qué opinas de usar una aplicación para gestionar citas, recordatorios y servicios veterinarios?

---

### Segmento Objetivo 2: Centros Veterinarios y Profesionales Independientes

**Objetivo de la entrevista:**  
Comprender las necesidades, procesos y dificultades de clínicas veterinarias y profesionales independientes en la gestión de citas, pacientes y comunicación con clientes.

#### 1. Información General

- ¿En qué distrito está ubicada su clínica o centro veterinario?
- ¿Cuántos trabajadores tiene actualmente?
- ¿Cuántos años lleva trabajando en este rubro?
- ¿Qué tipo de clientes atienden con mayor frecuencia?

#### 2. Digitalización Actual

- ¿Utilizan actualmente algún sistema digital o software para la gestión de su clínica? ¿Cuál?
- ¿Qué tan útil considera la herramienta que utilizan actualmente?

#### 3. Operaciones y Servicios

- ¿Qué servicios ofrece actualmente su clínica veterinaria?
- ¿Cómo gestionan actualmente las citas para sus pacientes?
- ¿Cómo realizan el seguimiento y recordatorio de citas?
- ¿Cómo manejan la información y el historial de sus pacientes?

#### 4. Comunicación con Clientes

- ¿Qué canales utilizan sus clientes para comunicarse con la clínica? (WhatsApp, llamadas, redes sociales, etc.)
- ¿Cómo gestionan la comunicación con los clientes sobre indicaciones o tratamientos?

#### 5. Problemas y Oportunidades

- ¿Qué dificultades enfrentan en la gestión de citas y servicios?
- ¿Qué tipo de problemas han tenido con la organización o atención de pacientes?
- ¿Cómo evalúa el nivel de satisfacción de sus clientes?
- ¿Qué estrategias de marketing utilizan actualmente para promocionar su clínica?
- ¿Qué aspectos considera más importantes al usar una herramienta digital para su negocio?

#### 6. Solución Propuesta

- ¿Estaría dispuesto a utilizar una plataforma digital que le ayude a gestionar citas y pacientes? ¿Por qué?
- ¿Qué funcionalidades le gustaría que tenga una aplicación para clínicas veterinarias?
- ¿Qué beneficios esperaría obtener de una herramienta digital como esta?

### 2.2.2. Registro de entrevistas 
URL del video:

Segmento 1:

| N | Datos |Descripción |Imagen referencial
|--|--|--|--|
|1  | Nombre: Keidy Maquera  <br>Edad: 21 <br>Distrito: Callao |Ella menciona que usa excel para organizarse, siendo el celular y la laptop los dispositivos que mas utiliza.<br>Las mascotas que tiene son 4 gatos y un perro, uno de sus gatos tiene 7 años y los demas gatos y el perro estan entre 3-4 años.<br>El cuidado de sus mascotas lo hace por medio de una alimentacion saludable y vacunas anuales.<br>La ultima vez que llevo a sus mascotas al veterinario fue hace  3 meses y ella desearia que las veterinarias cuenten con todos los implementos necesarios para atender la mayoria de casos que suelen presentarse.<br>Su veterinaria de confianza la escogio por que es la mas cercana a su casa, y busca que las veterinarias cuenten con todo lo necesario para atender a sus mascotas ante una emergencia.<br>Hubo una ocacion donde llevo a su gato de emergencia por la noche y su veterinaria de confianza no tenia los implementos para atenderlo y tubo que irse a buscar otra que atienda las 24 horas, sintio mucha desesperacion.<br>Ella suele frecuentar las veterinarias por vacunas para sus gatos, pero es mas por el corte y baño de su perro, agendando sus citas por whatsapp y aveces no le responden o tardan mucho en responder.<br>Para controlar el historial de sus mascotas lo hace por medio de tarjetas que le entregan al terminar una cita con fecha y el procedimiento que se realizo.<br>Lo que ella mejoraria de las veterinaria es que cuenten con todo los implementos para atender a sus mascotas y que sea 24  horas la atencion.<br>Le parece increible una plataforma para encontrar veterinarias segun sus nesecidades, asi se ahorraria el tiempo de ir preguntando una por una.<br> Ademas, le fascinaria que brinde informacion adicional, como los procedimientos que tienen disponibles. y menciona que la gestion de citas, recordatorios y servicios le ayudaria para una rapida comunicacion y una efectiva organizacion.|<img src="assets/Segm1-Keidy-PetCare.jpg">|
|2  | Nombre: <br>Johan Yonel: <br>Edad: 20 <br>Distrito: Santiago de Surco|El con mayor frecuencia el celular y la laptop, además de aplicaciones web como Trello, Notion y Google Calendar para organizar sus actividades diarias. Actualmente tiene dos mascotas: un perro desde hace dos años y un gato desde hace tres meses. Su rutina de cuidado incluye baños mensuales, cepillado constante, limpieza y supervisión cuando salen a la calle. Suele llevar a sus mascotas al veterinario aproximadamente una vez al mes, principalmente para baños, chequeos médicos y revisiones rápidas cuando presentan algún malestar. Considera importante que el veterinario brinde atención rápida, confianza y buen trato hacia los animales. Cuenta con una veterinaria de confianza y normalmente agenda citas por WhatsApp o llamadas. Sin embargo, a veces demora entre dos y tres días en conseguir una cita debido a la disponibilidad del profesional y sus propios horarios como estudiante. El historial médico de sus mascotas lo organiza en formato físico, mediante hojas o folletos donde registra vacunas, tratamientos y chequeos realizados. Entre las mejoras que propone para los servicios veterinarios actuales destaca una mayor adaptación a la virtualidad, permitiendo citas rápidas en línea, seguimiento digital de la mascota y acceso al historial médico. Finalmente, considera útil una plataforma web que permita encontrar veterinarios según necesidad, ubicación, calidad y opiniones de otros usuarios. También le gustaría que la aplicación incluya registro de vacunas, historial clínico compartido y acceso a distintas veterinarias en caso de cambio o emergencia.|<img src="assets/SEG1-Entrevista.jpg">
|3  | Nombre: Carolina Guzman  <br>Edad:40 Años  <br>Distrito: Jesus Maria  | Carolina menciona que usa más su celular y no suele usar servicios web para organizarse, además cuenta con 4 gatas desde hace 4 años cuya rutina es la limpieza de su espacio y brindarle comida y agua fres al igual que su revisión al veterinario una vez al año buscando experiencia como su veterinaria de confianza en donde ya atendió previamente a sus gatas como en el proceso de esterilización. En una veterinaria suele buscar explicaciones sobre los tratamientos que le darán a su mascota y nunca a tenido dificultades para buscar una veterinaria que cumpla con sus requisitos, genera citas por previa llamada y organiza el historial médico de su mascota por una carpeta física,  por otro lado ella piensa que en caso de tener que buscar a otro veterinario ella cree que el aspecto más importante que debería tener una aplicación que la ayude a resolver ese problema es una sección de reseñas para ver qué piensa la gente. |<img src="assets/Seg1-Carolina-Guzman.png">

Segmento 2:


| N | Datos |Descripción |Imagen referencial|
|--|--|--|--|
|1  | Nombre: Mariana <br>Apellido: Espinoza <br>Edad: 39 <br>Distrito: Surco <br>Profesión: Médica Veterinaria <br>Experiencia: 12 años <br>Negocio: Veterinaria Santa Rosa | Mariana Espinoza es un veterinaria con amplia trayectoria que lidera una clínica consolidada en el distrito de Surco. Su negocio cuenta con un equipo mediano y un flujo constante de paciente, compuesto principalmente por vecinos leales de la zona que buscan una atención personalizada. La clínica ofrece servicios esenciales como consultas, vacunación y cirugías menores. Actualmente, la gestión se apoya en métodos mixtos, utiliza excel y una agenda física para las citas, lo que refleja un digitalización parcial pero insuficiente. Estos procesos manuales genera cuellos de botella operativos, como la duplicidad de turnos y la falta de un seguimiento automatizado para las vacunas o desparasitaciones. La comunicación se centraliza casi exclusivamente en WhatsApp, lo que satura al personal y dificulta la separación entre la vida laboral y personal. Aunque el nivel de satisfacción de sus clientes es alto gracias a la confianza, Mariana identifica que la falta de organización en las historias clínicas limita el trabajo y la eficiencia del mismo. Ella esta dispuesta a adoptar una herramienta digital, priorizando la facilidad de uso y la automatización de recordatorios para mejorar su gestión. |<img src="assets/xxx.png">|
|2  | Nombre: Ricardo <br>Apellido: Chavez <br>Edad: 35 <br>Distrito: Miraflores | Ricardo Chavez es un administrador y médico veterinario encargado de un centro de alta rotación en Miraflores que opera las 24 horas. Su clínica cuenta con una infraestructura robusta, un equipo numeroso y tecnología avanzada para servicios especializados como laboratorio y hospitalización. A diferencia de otros negocios, ya utiliza un software de gestión, pero este resulta complejo de operar para el personal nuevo y carece de integraciones móviles, lo que limita el acceso a la información fuerea de los terminales de recepción. El principal problema que enfrente es el ausentismo de los clientes y la ineficiencia en el flujo de comunicación, ya que el sistema es el ausentismo de los clientes y la ineficiencia en el flujo de comunicación, ya que el sistema actual no logra que los recordatorios sean efectivos. A pesar de tener procesos más digitalizacos, la carga operativa en recepción sigue siendo alta debido a la gestión manual de consultas por redes sociales y llamadas. Ricardo busca una solución que permita la integración total entre las citas, las historias clínicas digitales y el inventario. Su interés en una nueva plataforma radica en la posibilidad de ofrecer un portal de autoservicio para el cliente, buscando optimizar la rentabilidad del negocio y reducir los tiempos de espera en sala a través de una tecnología más moderna y conectada. |<img src="assets/xxx.png">|
| 3 | Nombre: Diego <br>Apellido: Fernández Baca <br>Edad: 27 años <br>Distrito: Los Olivos <br>Profesión: Médico Veterinario <br>Experiencia: 4 años <br>Negocio: Veterinaria Patitas Sanas | Diego Fernández es un veterinario joven que ha iniciado su propio negocio, el cual se encuentra en una etapa temprana de crecimiento y presenta un flujo de atención bajo a moderado. Su veterinaria ofrece servicios básicos como consultas, vacunación y tratamientos generales, además de la venta de productos para mascotas. La gestión del negocio se realiza principalmente de forma manual. Utiliza WhatsApp para la comunicación con clientes y Excel para registrar información básica; sin embargo, no cuenta con un sistema digital integrado. Esto genera desorganización y dificulta el acceso rápido a la información, especialmente en el manejo del historial clínico, que aún se realiza en fichas físicas.<br><br>Asimismo, la gestión de citas es manual, lo que ocasiona inconvenientes como desorden en los horarios y falta de confirmación por parte de los clientes. La captación de nuevos clientes depende en gran medida de recomendaciones, lo que limita el crecimiento del negocio. A pesar de estas limitaciones, el nivel de satisfacción de los clientes es positivo. No obstante, el entrevistado reconoce que la implementación de herramientas digitales permitiría mejorar la organización, optimizar tiempos y brindar un mejor servicio.<br><br>Finalmente, muestra disposición a adoptar una plataforma digital que integre la gestión de citas, historiales clínicos y recordatorios automáticos, además de mejorar la visibilidad de su veterinaria para atraer nuevos clientes. | <img src="assets/S2-VeterinariaPatitasSanas.png"> |


## 2.2.3. Análisis de entrevistas 

En esta sección se presenta el análisis  de los hallazgos obtenidos mediante las entrevistas a profundidad realizadas a los dos segmentos objetivos. El análisis se sustenta con datos estadísticos.

## Segmento 1: Dueños de Mascotas

Este segmento está compuesto por usuarios entre 20 y 40 años, residentes en distritos de Lima y Callao. Se caracterizan por un alto uso de dispositivos móviles y una preocupación genuina por la salud preventiva de sus mascotas.

### Cuadro 1: Comportamiento y Gestión del Dueño
| Característica | Detalle Estadístico | Sustento en Entrevistas |
| :--- | :---: | :--- |
| **Uso de Herramientas Digitales** | **67%** | Keidy y Johan utilizan laptops y apps (Notion, Trello, Excel) para su organización personal. |
| **Gestión de Historial Médico** | **100% Físico** | El 100% de los entrevistados depende de tarjetas, folders o folletos físicos entregados por la clínica. |
| **Canal de Reserva de Citas** | **100% Tradicional** | La totalidad de la muestra utiliza WhatsApp o llamadas telefónicas directas para agendar. |
| **Frecuencia de Visita** | **67% Mensual/Trimestral** | La mayoría acude con frecuencia para baños y chequeos; solo un 33% acude anualmente. |

* **Frustración por Comunicación:** El 67% reporta malestar por la lentitud de respuesta en WhatsApp o la dificultad para encontrar citas inmediatas.
* **Inseguridad en Emergencias:** Existe una necesidad latente de conocer qué servicios y equipos tiene una veterinaria antes de asistir, para evitar desplazamientos en vano durante emergencias.
* **Valor de la Reputación:** El acceso a reseñas y opiniones es considerado un factor determinante para elegir un nuevo especialista.

## Segmento 2: Especialistas y Centros Veterinarios

Este segmento incluye médicos veterinarios y administradores de clínicas con distintos niveles de experiencia, desde emprendimientos jóvenes hasta centros de atención 24 horas.

### Madurez Digital y Operaciones
| Característica | Detalle Estadístico | Sustento en Entrevistas |
| :--- | :---: | :--- |
| **Método de Gestión Actual** | **67% Manual/Mixto** | Mariana y Diego dependen de Excel y agendas de papel. Ricardo usa software pero con limitaciones de acceso móvil. |
| **Saturación de Canales** | **100%** | Todos los especialistas coinciden en que la gestión por WhatsApp/Redes Sociales es caótica y consume tiempo excesivo. |
| **Disposición a la Adopción Digital** | **100% Alta** | El 100% de los entrevistados está dispuesto a implementar una plataforma que centralice sus procesos. |
| **Problemas de Ausentismo** | **67%** | El ausentismo y la falta de confirmación de citas afectan la rentabilidad de las clínicas con mayor flujo. |

### Necesidades según el Perfil del Negocio
| Arquetipo de Negocio | Necesidad Primordial | Factor Crítico |
| :--- | :--- | :--- |
| **Clínica Consolidada (Mariana)** | Automatización de recordatorios | Ordenar el flujo de clientes antiguos. |
| **Centro 24 Horas (Ricardo)** | Integración y Movilidad | Acceder a datos desde cualquier dispositivo. |
| **Emprendimiento Joven (Diego)** | Visibilidad y Crecimiento | Atraer nuevos clientes y crear historiales digitales. |

1.  **Brecha de Comunicación:** Existe un desfase entre la inmediatez que busca el dueño de la mascota y la capacidad de respuesta manual de la veterinaria. WhatsApp, aunque es el canal preferido, actúa como un cuello de botella operativo.
2.  **El Problema del "Papel":** El historial clínico físico es el punto de dolor compartido. El dueño teme perderlo y el veterinario admite que buscar fichas físicas o folders ralentiza la atención.
3.  **Oportunidad de Mercado:** El 100% de los especialistas reconoce que una herramienta digital mejoraría la satisfacción del cliente y la eficiencia del negocio, lo que valida la viabilidad de la solución propuesta.
   
## 2.3. Needfinding

Para identificar las necesidades específicas de los segmentos objetivos, realizamos entrevistas con representantes de nuestros dos perfiles clave. Los dueños de mascotas expresaron frustración por la desorganización de los historiales médicos físicos y la desesperación al no encontrar clínicas adecuadamente equipadas durante emergencias, mostrando un gran interés en una plataforma de búsqueda inteligente que incluya reseñas y recordatorios. Por su parte, los médicos veterinarios manifestaron que la gestión manual de citas mediante WhatsApp y el uso de fichas de papel generan desorden y limitan el crecimiento de sus negocios, respondiendo muy positivamente a la adopción de una herramienta digital que centralice agendas y expedientes. Estos hallazgos confirman la necesidad de modernizar e integrar el ecosistema de salud animal para mejorar la eficiencia operativa y la experiencia de todos los usuarios.

## 2.3.1. User Personas 
### User Persona - Dueño de mascota
<img src="assets/User-Persona-Dueño-De-Mascotas.png">

### User Persona - Veterinario
<img src="assets/User-Persona-Veterinario.png">

## 2.3.2. User Task Matrix 

| Tareas Principales (Task Matrix) | Dueños de Mascotas (Lucia Mendoza) | | Médicos Veterinarios (Diego Fernandez) | |
| :--- | :--- | :--- | :--- | :--- |
| | **Frecuencia** | **Importancia** | **Frecuencia** | **Importancia** |
| Registrar y configurar cuenta en la plataforma. | Baja | Alta | Baja | Alta |
| Registrar / Actualizar el historial clínico de la mascota. | A veces | Alta | Seguido | Alta |
| Buscar clínicas y especialistas usando Inteligencia Artificial. | A veces | Alta | Baja | Baja |
| Agendar, confirmar o reprogramar citas médicas. | A veces | Alta | Seguido | Alta |
| Monitorear métricas de salud en tiempo real (Dispositivo IoT). | A veces | Alta | A veces | Alta |
| Gestionar notificaciones y recordatorios (vacunas, controles). | A veces | Alta | Seguido | Alta |
| Procesar pagos o cobros por consultas y servicios. | A veces | Alta | Seguido | Alta |
| Leer, escribir o responder reseñas de atención veterinaria. | A veces | Media | Seguido | Alta |

## 2.3.3. User Journey Mapping 

### User Journey Map - Dueño de Mascota
<img src="assets/User-Journey-Map-Dueño-De-Mascotas.png">

### User Journey Map - Veterinario
<img src="assets/User-Journey-Map-Veterinario.png">

## 2.3.4. Empathy Mapping

### Empathy Map -  Dueño de mascota
<img src="assets/Empathy-Map-Dueño-De-Mascotas.png">

### Empathy Map - Veterinario
<img src="assets/Empathy-Map-Veterinario.png">

## 2.4. Big Picture Event Storming
-Para comenzar con el desarrollo de este seccion nos guiamos de la revista Revista Event Storming, tomando como referencia el arituculo "Guia de pasos para levar acabo su evento Big Picture event Storming" de Felipe Bourgau(2022).<br><br>-  Preparar la Habitacion: Para la preparacion dle espacio de trabajo, usaremos la aplicacion web Miro, ya que por limitaciones de tiempo y disponibilidad, no es posible realizar una reunion presencial. Esta herramienta simulara un entorno colaborativo virtual, donde podremos modelar el proceso de manera virtual y en tiempo real.<br><br>- Energizar a la audiencia: Se inicio la sesion conversando sobre las actividades realizadas durante el dia, con el objetivo de generar un ambiente de confianza en el grupo, para asi lanzar nuestras ideas sin temor.<br><br>- Informar y presentar el plan: Se conversó acerca del proyecto Petcare, definimos claramente los objetivos del sistema. Asimismo, se explicaron los pasos de la reunion realizada en Miro, desde el analisis del sistema hasta la identificacion de nesecidades y funcionalidades importantes, comprendiendo como cada etapa ayuda a llegar a un diseño de solucion final.<br><br>- Generacion de Eventos de Dominio: En esta fase se comenzo a plasmar las ideas en el Miro, identificando y colocando los eventos de dominio, los cuales representas hechos que ocurren dentro del negocio, Adjuntamos la evidencia: <br> <br><img src="assets/EventosDeDominio.png"><br><br>- Clasificacion de Eventos de Dominio: Se ordenaron los eventos colocados anterioromente en una linea de tiempo, desde lo que ocurre primero hasta lo que ocurre al final, discutiendlo ademas los eventos paralelos que suceden.<br><br> <img src="assets/AgrupaciondeEventonDominio.png"><br><br>- Incorporacion de actores y sistemas externos: En esta fase se identificaron los actores principales del sistema, como el dueño de mascotas, veterinarias y administradores, asi como los sistemas externos involucrados, como servicios de pago, notificaciones, mapas, inteligencia artificial y dispositivos IoT.<br><br> <img src="assets/EventosDeDominioConActoresSistemas.png">
## 2.5. Ubiquitous Language
El Ubiquitous Language es un elemento fundamental dentro del enfoque Domain-Driven Design (DDD), el cual se basa en la creación de un lenguaje común que sea compartido por todos los involucrados en el proyecto. Su finalidad es reducir confusiones y garantizar que tanto el equipo de desarrollo como los stakeholders tengan una interpretación clara y uniforme de los conceptos relacionados al dominio del negocio.

En el contexto del proyecto PetCare, orientado a la gestión integral de la salud de mascotas, este lenguaje permite mejorar la comunicación entre los dueños de mascotas y las clínicas veterinarias mediante la definición precisa de términos como Pet (Mascota), Medical Record (Historial clínico), Appointment (Cita) y Health Monitoring (Monitoreo de salud). Además, los términos se establecen en inglés junto con su equivalente en español y se emplean de manera consistente en todos los artefactos del sistema, contribuyendo a una mejor comprensión y desarrollo de la solución.

| Término | Definición en el contexto |
| :------ | :------------------------ |
| Pet (Mascota) | Animal doméstico registrado en la plataforma, cuya información general, comportamiento y estado de salud son gestionados digitalmente. |
| Pet Owner (Dueño de mascota) | Persona responsable del cuidado de la mascota, encargada de registrar, consultar y actualizar su información dentro del sistema. |
| Veterinary Clinic (Clínica veterinaria) | Entidad que ofrece servicios de atención médica para mascotas y que se encuentra registrada en la plataforma con información relevante como ubicación, servicios y costos. |
| Veterinarian (Veterinario) | Profesional especializado en salud animal que realiza evaluaciones, diagnósticos y tratamientos a las mascotas. |
| Medical Record (Historial clínico) | Registro digital estructurado que almacena toda la información médica de la mascota, incluyendo vacunas, enfermedades, diagnósticos, tratamientos y cirugías. |
| Appointment (Cita) | Programación anticipada de un servicio veterinario entre el dueño de la mascota y una clínica o profesional. |
| Consultation (Consulta) | Atención médica realizada durante una cita, en la cual el veterinario evalúa el estado de salud de la mascota. |
| Treatment (Tratamiento) | Plan de acciones médicas definido por el veterinario para tratar una condición de salud específica. |
| Vaccination (Vacunación) | Procedimiento preventivo mediante el cual se administran vacunas para proteger a la mascota contra enfermedades. |
| Symptom (Síntoma) | Indicador físico o conductual que evidencia una posible alteración en el estado de salud de la mascota. |
| Diagnosis (Diagnóstico) | Conclusión médica emitida por el veterinario basada en la evaluación clínica de la mascota. |
| Health Monitoring (Monitoreo de salud) | Proceso continuo de recopilación de datos biométricos y de actividad de la mascota mediante dispositivos conectados. |
| Alert (Alerta) | Notificación generada automáticamente por el sistema ante eventos relevantes, como anomalías detectadas o recordatorios importantes. |
| Recommendation (Recomendación) | Sugerencia personalizada generada por el sistema en base a datos históricos, condiciones actuales y preferencias del usuario. |
| Veterinary Service (Servicio veterinario) | Tipo de atención ofrecida por una clínica, como consulta general, emergencia, cirugía o especialidad médica. |
| Specialty (Especialidad) | Área específica de atención veterinaria enfocada en un tipo de tratamiento o sistema del animal. |
| Location (Ubicación) | Referencia geográfica de la clínica veterinaria, utilizada para facilitar su búsqueda y acceso. |
| Budget (Presupuesto) | Rango económico definido por el usuario para acceder a servicios veterinarios. |
| Emergency (Emergencia) | Situación crítica que requiere atención veterinaria inmediata para preservar la vida o bienestar de la mascota. |
| Follow-up (Seguimiento) | Proceso de control posterior a una atención médica para evaluar la evolución del estado de salud de la mascota. |

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
Definiremos los lineamientos de diseño del sistema para  mantener una presentación consistente y enfocada.
### 4.1.1. General Style Guidelines

#### Branding: 
Es una plataforma de gestión de salud para mascotas donde se integra historial clínico, búsqueda de veterinarias y agendamiento de citas. El objetivo principal del sistema es la prevención de la salud de las mascotas, centralizando la información médica y facilitando la toma de decisiones del usuario.
#### Usuarios:
- Dueños de mascotas que requieren un seguimiento de la salud de sus mascota o que buscan facilidades para cuidar la salud de sus mascotas
- Clínicas veterinarias que ofrecen servicios de atención médica y buscan una plataforma que les facilite agendar citas, llevar un historial clínico y la comunicación con sus pacientes.

#### Personalidad del sistema
El sistema se define con una personalidad confiable, profesional y amable
Ya que, el sistema maneja información delicada relacionada con la salud de las mascotas, por lo que es importante que transmita seguridad y confianza.

#### Principios de diseño
- Claridad: la información médica debe ser fácil de entender.
- Confianza: el sistema debe transmitir seguridad en las recomendaciones.
- Eficiencia: el tiempo para encontrar veterinarias o agendar citas debe ser el menor posible.
- Accesibilidad: asegurar la comprensión para todo tipo de usuarios, creando así un sistema inclusivo.

#### Typography:

| Uso | Fuente | Ejemplo |
|-----|--------|--------|
| Encabezados (H1, H2) | Anton | TÍTULO PRINCIPAL |
| Subtítulos / botones | Antonio | Subtítulo / Acción |
| Texto general | Sans-serif del sistema | Párrafo estándar 

Se utilizan tipografías sans-serif debido a su alta legibilidad en interfaces digitales. La diferencia entre fuentes permite establecer una jerarquía visual, facilitando la lectura de la información. 

#### Colors

| Color | Hex | Uso |
|------|-----|-----|
| Azul principal | #1A3458 | Botones principales, navegación, headers |
| Azul claro | #F2F6FF | Fondos, secciones y cards |
| Negro | #000000 | Texto principal sobre fondos claros |
| Blanco | #FFFFFF | Texto sobre fondos oscuros, íconos |
| Escala de grises | #333333 – #DDDDDD | Bordes, placeholders, elementos secundarios |

La paleta se basa en tonos azules debido a su relación con la confianza y seguridad, aspectos fundamentales en un sistema relacionado con salud. Los grises se utilizan para mantener la jerarquía visual.

#### Spacing

- Sistema basado en una cuadrícula de 8px.
- Márgenes y paddings consistentes en toda la interfaz.
- Bordes redondeados de 8px en botones y tarjetas.
- Sombras suaves para elementos elevados como cards y modales.

El uso de un sistema de espaciado consistente reduce la carga cognitiva del usuario y mejora la coherencia visual en toda la interfaz.

### 4.1.2. Web Style Guidelines

### Layout

La interfaz web sigue una estructura tipo dashboard, orientada a la gestión de información de salud de mascotas. Se prioriza el acceso rápido a funcionalidades clave como búsqueda de veterinarias, historial clínico y agendamiento de citas.

Se utiliza una navegación persistente (navbar superior o sidebar) que permite al usuario acceder a las principales secciones sin perder el contexto de la vista actual.

El contenido principal se organiza mediante cards y secciones claramente delimitadas, facilitando la lectura y comprensión de la información.

### Components

Los componentes principales del sistema incluyen:

- **Cards:** utilizadas para mostrar veterinarias, mascotas, citas y resúmenes de información relevante.  
- **Formularios:** empleados para registro de usuarios, mascotas, agendamiento de citas y actualización de datos clínicos.  
- **Listas estructuradas:** para la visualización del historial clínico (vacunas, enfermedades, tratamientos).  
Estos componentes permiten organizar la información de manera jerárquica y mantener consistencia en toda la interfaz.

### Navigation

La navegación está diseñada para ser clara y accesible en todo momento. Se prioriza el acceso directo a las siguientes secciones:

- Perfil de usuario y mascota  
- Historial clínico  
- Búsqueda de veterinarias  
- Agenda de citas  

Se reduce la cantidad de pasos necesarios para completar acciones clave, mejorando la eficiencia del usuario dentro del sistema.

### Interactions

El sistema proporciona retroalimentación visual constante para mejorar la experiencia del usuario:

- Estados de carga durante procesos como búsqueda con IA o envío de formularios  
- Indicadores visuales en botones (hover, activo, deshabilitado)  
- Confirmaciones después de acciones importantes (registro, agendamiento, actualización de datos)  
- Mensajes informativos en caso de errores o ausencia de resultados  

Esto permite al usuario comprender el estado del sistema en todo momento.

### Responsive Design

El sistema está diseñado bajo un enfoque responsive para adaptarse a distintos dispositivos:

- **Mobile:** estructura de una sola columna, priorizando acciones principales y navegación simplificada.  
- **Tablet:** distribución en dos columnas para mejorar el uso del espacio sin saturar la interfaz.  
- **Desktop:** layout completo tipo dashboard, permitiendo visualizar mayor cantidad de información de forma organizada.  

Se mantiene la consistencia visual y funcional en todos los tamaños de pantalla.

## 4.2. Information Architecture
### 4.2.1. Organization Systems

### 1. Organización Visual del Contenido

* **Organización Secuencial (Step-by-Step to Accomplish):** Se usará en el proceso de agendamiento de citas veterinarias y en la vinculación del collar IoT. Esto guiará a los usuarios paso a paso (selección de clínica -> selección de mascota -> selección de horario -> confirmación/pago) para completar la reserva o configuración de manera eficiente, asegurando que se realice mediante una serie de pasos consecuentes y ordenados sin abrumar al usuario.
* **Organización Jerárquica (Visual Hierarchy):** Se aplicará en los paneles principales (Dashboards) de ambos usuarios. Para el dueño de la mascota, la información más crítica (alertas de salud del IoT y citas próximas) se mostrará en la parte superior con mayor peso visual, desglosándose hacia abajo hacia información secundaria (consejos de salud o configuración de cuenta). Para el veterinario, la jerarquía priorizará las emergencias y la agenda del día sobre el inventario.
* **Organización Matricial (Matrix):** Se utilizará en el sistema inteligente de búsqueda de clínicas. Dado que los usuarios tienen múltiples necesidades, este sistema les permitirá cruzar y organizar los resultados bajo dos o más dimensiones simultáneamente (por ejemplo, ordenar por "Precio" y filtrar por "Distancia" o "Especialidad"), dándole al usuario el control de cómo visualizar las opciones.

### 2. Esquemas de Categorización de Contenido

* **Según Audiencia (Grupos de Usuarios):** Será el esquema principal de división estructural de la plataforma. El contenido y las interfaces estarán estrictamente separados en dos grandes grupos: el Portal para Dueños de Mascotas (enfocado en búsqueda, prevención y agendamiento) y el Portal para Veterinarios/Clínicas (enfocado en gestión de pacientes, historias clínicas y agenda de trabajo).
* **Cronológico:** Se aplicará fundamentalmente en el Historial Clínico de la mascota y en el Registro de Datos IoT. Los veterinarios y dueños verán las vacunas, cirugías, enfermedades y ritmo cardíaco/temperatura ordenadas desde el evento más reciente hasta el más antiguo, facilitando el seguimiento temporal de la salud del animal.
* **Por Tópicos (Topical):** Se utilizará para organizar el catálogo de Servicios Veterinarios. La información de las clínicas estará agrupada por especialidades temáticas claras (Ej. Odontología, Oncología, Baño y Corte, Emergencias 24h), lo que facilitará al motor de Inteligencia Artificial recomendar la clínica adecuada según el síntoma de la mascota.
* **Alfabético:** Se empleará en listas de referencia estáticas dentro de la aplicación, como el menú de selección de Razas de animales, el listado de especies al registrar una nueva mascota, o un glosario de términos médicos básicos en los resultados de sus exámenes.

### 4.2.2. Labeling Systems
Mis Mascotas: En esta sección se mostrarán los perfiles individuales de cada animal registrado por el usuario, consolidando su información básica, raza, edad y características principales.

Veterinarias: En esta sección se mostrará el directorio inteligente de clínicas y especialistas disponibles, detallando sus servicios, equipos (ej. rayos X, emergencias 24h) y ubicación.

Historial Clínico: En esta sección se mostrará el registro médico completo y centralizado de la mascota (vacunas, cirugías, tratamientos previos) para una consulta rápida tanto por el dueño como por el especialista.

Citas: En esta sección se mostrarán los turnos médicos agendados, el historial de visitas pasadas y el calendario de disponibilidad para organizar la atención de forma ordenada.

Monitoreo IoT: En esta sección se mostrarán en tiempo real los signos vitales recolectados por el collar inteligente (temperatura, frecuencia cardíaca) y las alertas tempranas de prevención de enfermedades.

Reseñas: En esta sección se mostrarán las calificaciones y comentarios de otros usuarios sobre las clínicas veterinarias, ayudando al dueño a tomar decisiones basadas en experiencias previas.

Perfil: En esta sección el usuario (ya sea el dueño de la mascota o el médico veterinario) podrá gestionar su información personal, los datos de su clínica, métodos de pago y configuraciones de la cuenta.

### 4.2.3. SEO Tags and Meta Tags 
### SEO Tags and Meta Tags

A continuación se mostrarán las etiquetas que representarán el contenido de la Landing Page y de la aplicación web para que los buscadores las indexen correctamente y los usuarios las encuentren con mayor facilidad.

#### **Landing Page:**
* **Meta Tags de Título:** PetCare - Prevención y Salud para tu Mascota.
* **Meta Tags de Descripción:** Landing Page oficial de PetCare. Descubre la plataforma que conecta dueños de mascotas con los mejores especialistas mediante Inteligencia Artificial e IoT.
* **Meta Tags de Palabras Clave:** Cuidado de mascotas, collares IoT, prevención veterinaria, veterinarias especializadas, bienestar animal.
* **Meta Tag de Autor:** Equipo PetCare.

#### **Aplicación Web:**
* **Meta Tags de Título:** PetCare App - Gestión Veterinaria Inteligente.
* **Meta Tags de Descripción:** Aplicación web oficial de PetCare. Centraliza el historial clínico de tu mascota, recibe alertas tempranas de salud y agenda citas veterinarias en segundos.
* **Meta Tags de Palabras Clave:** Plataforma veterinaria, historial clínico digital, inteligencia artificial veterinaria, agendar cita veterinaria, veterinarias 24 horas Lima, monitoreo IoT para mascotas, gestión de clínicas.
* **Meta Tag de Autor:** Equipo PetCare.

### 4.2.4. Searching Systems
### Searching Systems

Para evitar que los usuarios de PetCare se sientan abrumados por el volumen de información de las clínicas, historiales, citas y datos biométricos, la plataforma ofrecerá herramientas de búsqueda adaptadas a las necesidades específicas de cada segmento de usuario, tanto para dueños de mascotas como para veterinarios.

#### **Filtros de Búsqueda:**

**Para el Dueño de Mascota en búsqueda de clínicas:**
* **Ubicación y Distancia:** Rango de las veterinarias disponibles en kilómetros o "Usar mi ubicación actual".
* **Especialidad y Servicios:** Oncología, Traumatología, Baño/Corte, Rayos X, Ecografía.
* **Disponibilidad:** Atención 24/7, Emergencias, Abierto ahora.
* **Presupuesto:** Rango de precios para consultas generales ($ - $$$).
* **Calificación:** Filtrar por clínicas con 4 o más estrellas basadas en reseñas.

**Para el Médico Veterinario durante búsqueda interna:**
* **Estado de la Cita:** Pendiente, Confirmada, Completada, Cancelada.
* **Rango de Fechas:** Selector de calendario para buscar atenciones pasadas o futuras.

### 4.2.5. Navigation Systems

**Landing Page:**
* **Barra de navegación global:** Ubicada en la parte superior, contendrá enlaces directos (Inicio, Beneficios, Cómo Funciona, Planes) que desplazarán al usuario hacia la sección correspondiente dentro de la misma página.
* **Botones de Llamado a la Acción (CTA):** Botones llamativos y estratégicamente ubicados con textos como "Regístrate ahora" o "Iniciar Sesión", que servirán como puente para llevar al visitante hacia la aplicación principal.

**En la Aplicación Web/Móvil:**
* **Menú de navegación principal:** Para los **dueños de mascotas**, se implementará una barra de navegación inferior con iconos rápidos hacia las funciones más usadas: Inicio, Buscar Clínicas, Mis Mascotas y Citas.
* Para los **veterinarios**, se utilizará un menú lateral fijo que facilite la gestión administrativa: Dashboard, Agenda, Pacientes y Configuraciones.
* **Navegación contextual:** Se usarán enlaces internos dentro de los elementos visuales. Por ejemplo, si un usuario está viendo su próxima cita, podrá hacer clic en el nombre de la clínica para navegar directamente al perfil de la veterinaria o ver su ubicación en el mapa.

## 4.3. Landing Page UI Design
### 4.3.1. Landing Page Wireframe
-Desktop Web Browser:<br>
<br>
En este primer Frame se presenta la seccion de bienvenida al usuario, donde se incluye el nombre de la aplicacion, para que el usuario reconozca de inmediato que ingreso al sitio web correcto. Asimismo, se comunica de forma clara que la plataforma esta orientada al cuidado del bienestar de su mascota. Por otro lado, la barra de navegacion se ubica en la parte superior ya que la mayoria de paginas estan hechas con esta estructura, y el usuario ya esta mas familiarizado. Tambien, colocamos los botones de iniciar sesion y registrarse en la barra de navegacion para un facil acceso a la plataforma.<br><br><img src="assets/FrameBienvenido.png">

Al realizar un desplazamiento (Scroll), el usuario encuentra la seccion "Quienes Somos", la cual presenta informacion importante sobre la plataforma. Utilizamos un titulo de letras grandes para captar la atencion del usuario e incentivar la lectura dle contenido.<br><br><img src ="assets/FrameQuienesSomos.png">
<br></br>La seccion de beneficios se organiza en tres bloques horizontales, permitiendo una presentacion clara y ordenada. El uso de un titulo de tamaño grande, facilita su identificacion y ayuda al usuario a comprender rapido las ventajas de la plataforma.<br><br>
<img src="assets/FrameBeneficios.png"></img><br><br>La seccion de suscripciones se organiza en los bloques horizontales, permitiendo una comparacion clara. Cada uno incluye un boton de "saber mas" para acceder a informacion detallada<br><br><img src="assets/FrameSuscripcion.png"></img><br><br> Finalmente, se incluye un bloque donde se le invita al usuario a registrarse, con un titulo grande. Es un formulario de ingreso de datos, facilitando el registro de manera directa. <br><br><img src="assets/FrameRegistrarFooter.jpeg"><br><br><br>-Mobile Web Browser:<br><br>En la version mobile, en este apartado el contenido se organiza de forma vertical, priorizando el nombre de la aplicacion y su proposito. Los botones principales son intuitivos, facilitando la navegacion y siendo esta fluida. Ademas, se simplifico la navegacion mediante una navegacion de tipo hamburguesa, optimizando el espacio en pantalla y permitiendo acceder a las opciones de forma ordenada.<br><br><img src="assets/ImagenesWireframeMobile/Bienvenido.png" height = 700px><img src="assets/ImagenesWireframeMobile/BienvenidoHamburguesa.png" height = 700px><br><br>En esta seccion se presenta en formato vertical, maneteniendo una jerarquia clara para facilitar la lectura y comprension del contenido.<br><br><img src="assets/ImagenesWireframeMobile/QuienesSomos.png" height = 700px> <br><br> En este bloque, que describe cuales son los beneficios, se organizo de igual forma, en vertical, permitiendo una visualizacion clara y secuencial en pantallas reducidas.<br><br><img src="assets/ImagenesWireframeMobile/BeneficiosUno.png" height = 700px><img src="assets/ImagenesWireframeMobile/BeneficiosDos.png" height = 700px><img src="assets/ImagenesWireframeMobile/BeneficiosTres.png" height = 700px><br><br>En la seccion de suscripciones tambien se organizo de forma vertical, facilitando la comparacion y acceso a informacion adicional mediante botones.<br><br><img src="assets/ImagenesWireframeMobile/SuscripcionUno.png" height = 700px><img src="assets/ImagenesWireframeMobile/SuscripcionDos.png" height = 700px><br><br>En la seccion de registro se agrego un bloque donde esta el formulario, pensado para que el usuario pueda registrarse de forma rapida y sencilla desde el celular.<br><br><img src="assets/ImagenesWireframeMobile/RegistrarFooter.png" height = 700px>

### 4.3.2. Landing Page Mock-up
-Desktop Web Browser:<br><br>
<img src="assets/mockup1.png"></img><br><br>
<img src="assets/mockup2.png"></img><br><br>
<img src="assets/mockup3.png"></img><br><br>
<img src="assets/mockup4.png"></img><br><br>
<img src="assets/mockup5.png"></img><br><br>
-Mobile Web Browser:<br><br><img src = "assets/ImagenesMock-UpDesktop/Bienvenido.png" height = 700px><img src = "assets/ImagenesMock-UpDesktop/BienvenidoHamburguesa.png" height = 700px><br><br><img src = "assets/ImagenesMock-UpDesktop/QuienesSomos.png" height = 700px><br><br><img src = "assets/ImagenesMock-UpDesktop/BeneficioUno.png" height = 700px><img src = "assets/ImagenesMock-UpDesktop/BeneficioDos.png" height = 700px><img src = "assets/ImagenesMock-UpDesktop/BeneficioTres.png" height = 700px><br><br><img src = "assets/ImagenesMock-UpDesktop/SuscripcionUno.png" height = 700px><img src = "assets/ImagenesMock-UpDesktop/SuscripcionDos.png" height = 700px><br><br><img src = "assets/ImagenesMock-UpDesktop/RegistrarseFooter.png" height = 700px><br><br>

## 4.4. Web Applications UX/UI Design
### 4.4.1. Web Applications Wireframes
<img src="assets/webapplicationswireframes1.png"></img><br>
<img src="assets/webapplicationswireframes2.png"></img><br>
<img src="assets/webapplicationswireframes3.png"></img><br>
<img src="assets/webapplicationswireframes4.png"></img><br>
<img src="assets/webapplicationswireframes5.png"></img><br>
<img src="assets/webapplicationswireframes6.png"></img><br>
<img src="assets/webapplicationswireframes7.png"></img><br>
<img src="assets/webapplicationswireframes8.png"></img><br>
<img src="assets/webapplicationswireframes9.png"></img><br>
<img src="assets/webapplicationswireframes10.png"></img><br>
### 4.4.2. Web Applications Wireflow Diagrams
<img src="assets/wireflow diagrams.png"></img><br>
### 4.4.2. Web Applications Mock-ups
<img src="assets/mockupapp1.png"></img><br>
<img src="assets/mockupapp2.png"></img><br>
<img src="assets/mockupapp3.png"></img><br>
<img src="assets/mockupapp4.png"></img><br>
<img src="assets/mockupapp5.png"></img><br>
<img src="assets/mockupapp6.png"></img><br>
<img src="assets/mockupapp7.png"></img><br>
<img src="assets/mockupapp8.png"></img><br>
<img src="assets/mockupapp9.png"></img><br>
<img src="assets/mockupapp10.png"></img><br>

### 4.4.3. Web Applications User Flow Diagrams
-User Goal : El usuario desea registrarse en la plataforma para gestionar la informacion de su mascota<br><br>-Happy path:<br><img src= "assets/ImagenesUserFlowDiagrams/UserGoalRegistroHappyPath.png" height= 1000px><br><br>-UnHappy Path: <br><img src="assets/ImagenesUserFlowDiagrams/UserGoalRegistroUnHappyPath.png" height= 1100px><br><br>
-User Goal : El usuario desea encontrar veterinarias confiables para atender a su mascota rapidamente.<br><br>-Happy Path<img src="assets/ImagenesUserFlowDiagrams/UserGoalBuscarVeterinariasHappyPath.png" ><br><br>-UnHappy Path:<img src="assets/ImagenesUserFlowDiagrams/UserGoalBuscarVeterinariasUnHappyPath.png" height= 1000px><br><br>-User Goal : El usuario desea registrar y consultar el historial medico de su mascota.<br><br>-Happy Path:<br><img src="assets/ImagenesUserFlowDiagrams/UseGoalHistorialMedicoHappyPath.png"><br><br>-UnHappy Path 1:<br><img src="assets/ImagenesUserFlowDiagrams/UseGoalHistorialMedicoUnHappyPathUno.png"><br><br>-UnHappy Path 2:<br><img src="assets/ImagenesUserFlowDiagrams/UseGoalHistorialMedicoUnHappyPathDos.png"><br><br>-UnHappy Path 3:<br><img src="assets/ImagenesUserFlowDiagrams/UseGoalHistorialMedicoUnHappyPathTres.png"><br><br>-User Goal: El usuario desea recibir recordatorios de vacunas para cuidar la salud preventiva de su mascota.<br><br>-Happy Path: <br><img src="assets/ImagenesUserFlowDiagrams/UserGoalRecordatorioshappy.png"><br><br>-User Goal: El usuario desea registrar diagnosticos y citas medicas de forma digital para reducir el uso de papeleo.<br><br>-Happy Path:<br><img src="assets/ImagenesUserFlowDiagrams/UserGoalCitasServiciosHappyPath.png"><br><br>-UnHappy Path:<br><img src="assets/ImagenesUserFlowDiagrams/UserGoalCitasServiciosUnHappyPath.png"><br>
## 4.5. Web Applications Prototyping
En esta sección se presenta el flujo de cada frame. Se utilizaron los User Goals como base para construir los diagramas y posteriormente se conectaron en el User Flow. A continuación, se adjuntan imágenes como evidencia:<br><br><img src="assets/ImagenesUserFlowDiagrams/UserFlowDiagramDesktopPrototype.png"><br><br>[Link del video donde se explican los User Flow Diagrams](https://1drv.ms/v/c/6f853fb278bb6268/IQBpn0BRBk22RJm7W5r_gqs5AVBObmjJoZsgVpKlszwqLBA?e=qGSUQC)
## 4.6. Domain-Driven Software Architecture

### 4.6.1. Design-Level Event Storming
En esta sección se presenta el proceso de Design-Level Event Storming, el cual permitió identificar, analizar y organizar los eventos clave del dominio del sistema PetCare.

A través de esta técnica, se logró construir una visión más clara del comportamiento del sistema, facilitando la comprensión de los flujos principales, las interacciones entre los actores y la definición de los límites del dominio. Esto sirvió como base para una aproximación más estructurada y refinada del diseño a nivel general de la arquitectura del sistema.

<img src="assets/PetCare - Event Storming.jpg" alt="Design-Level Event Storming"><br>

<a href="https://miro.com/app/board/uXjVGgIlPes=/?share_link_id=504466486725" target="_blank">
  <img src="https://img.shields.io/badge/Miro-Design%20Level%20Event%20Storming-blue?style=for-the-badge&logo=miro&logoColor=white" alt="Miro Event Storming">
</a>

### 4.6.2. Software Architecture Context Diagram
<img src="assets/4.6.2. Software Architecture Context Diagram.png" alt="Software Architecture Context Diagram"><br>

### 4.6.3. Software Architecture Container Diagrams
<img src="assets/4.6.3. Software Architecture Container Diagrams.png" alt="Software Architecture Container Diagrams"><br>

### 4.6.4. Software Architecture Components Diagrams
<img src="assets/4.6.4. Software Architecture Components Diagrams.png" alt="Software Architecture Components Diagrams"><br>

## 4.7. Software Object-Oriented Design
### 4.7.1. Class Diagrams
<img src="assets/Diagrama-Petcard.drawio.png" alt="Diagrama de Clases - PetCard"><br>

## 4.8. Database Design
Para el diseño del sistema de la base de datos se uso un diagrama entidad-relacion (ERD). En él se modela cómo un Usuario puede tener múltiples Mascotas, y cómo cada mascota puede estar asociada a citas veterinarias, historial clínico, vacunas, dispositivos IoT y alertas. También se incluye un Perfil con información adicional del usuario y una entidad de Veterinarias para gestionar las clínicas. Además, el sistema incorpora el monitoreo en tiempo real mediante dispositivos IoT, que generan datos almacenados en Datos IoT, permitiendo registrar información y alertas sobre el estado de las mascotas.<br><br><img src="assets/DiagramaDBPetCareERD.png">
### 4.8.1. Database Diagrams.
# Capitulo V: Product Implementation, Validation & Deployment
## 5.1. Software Configuration Management
### 5.1.1. Software Development Environment Configuration
**Project Management y Requirements Management:**
  * **Miro:** Plataforma en línea que permite la colaboración en tiempo real a través de pizarras digitales. Ofrece herramientas para la creación de diagramas, mapas mentales y flujos.

**Product UX/UI Design:**
  * **Figma:** Herramienta de diseño de interfaces de usuario (UI) y prototipado colaborativo basada en la nube. En este caso, utilizamos Figma para la elaboración del prototipo interactivo de la aplicación móvil para los dueños de mascotas y el panel administrativo web para las clínicas veterinarias.

**Software Development:**
  * **IntelliJ IDEA:** Entorno de desarrollo integrado (IDE) profesional diseñado para maximizar la productividad del desarrollador. En este caso, lo utilizamos para el desarrollo robusto de toda la lógica de negocio y el backend del proyecto empleando Java y el framework Spring Boot.
  * **GitHub:** Plataforma de desarrollo colaborativo basada en la nube que utiliza el sistema de control de versiones Git. Permite a los desarrolladores alojar, revisar y colaborar en proyectos de software. En este caso, utilizamos GitHub como un repositorio remoto para almacenar, unificar y gestionar el código fuente de todo nuestro proyecto.

**Software Deployment y Bases de Datos:**
  * **SQL Server:** Sistema de gestión de bases de datos relacionales (RDBMS) desarrollado por Microsoft que utiliza el lenguaje SQL para la manipulación y consulta de datos. En este caso, utilizamos SQL Server como el motor principal para garantizar la integridad referencial de la plataforma, permitiendo estructurar los perfiles de usuarios, historiales médicos fijos y la gestión de citas mediante relaciones complejas y transacciones seguras

### 5.1.2. Source Code Management
Durante todo el desarrollo del proyecto, nuestro equipo hará uso de versiones de Git en la cual toda la evidencia podrá ser visualizada para posteriormente ser subida a la plataforma de github de la organización, en donde se podrán observar todas las modificaciones que se le harán realizando al proyecto a lo largo del desarrollo por cada uno de los miembros del equipo.

GitHub URL: https://github.com/Co-Designers/PetCare

### 5.1.3. Source Code Style Guide & Conventions

Para asegurar la escalabilidad, legibilidad y el mantenimiento del código de PetCare, el equipo adoptará como regla general que toda la nomenclatura (variables, clases, métodos, archivos y bases de datos) se escribirá estrictamente en idioma inglés. Además, nos apegaremos a las siguientes convenciones estándar según cada tecnología:

#### **HTML:**
Para el lenguaje HTML utilizaremos las siguientes convenciones:
* Usar nombres de elementos y etiquetas siempre en minúsculas.
* Cerrar obligatoriamente todos los elementos HTML.
* Usar nombres de atributos en minúsculas y encerrar sus valores entre comillas dobles.
* Evitar líneas de código demasiado largas para facilitar la lectura en el editor.

#### **CSS:**
Para el lenguaje CSS, utilizaremos las siguientes prácticas para alcanzar un código coherente y ordenado:
* Utilizar `camelCase` (capitalizar la primera letra de cada palabra excepto la primera) para los nombres de clases e IDs.
* Utilizar nombres de clases que sean descriptivos en inglés y que reflejen la función estructural del elemento, no su apariencia visual.

#### **JavaScript / TypeScript (Angular):**
Para la lógica del frontend, seguiremos las siguientes convenciones:
* Utilizar `camelCase` para nombrar variables, propiedades y métodos (ejemplo: `getPetHistory`).
* Utilizar `PascalCase` para nombrar Clases e Interfaces (ejemplo: `PetProfileComponent`).
* Utilizar `UPPER_SNAKE_CASE` para constantes inmutables (ejemplo: `MAX_UPLOAD_SIZE`).
* En Angular, nombrar los archivos separando las palabras con guiones y especificando su tipo (ejemplo: `vet-list.component.ts`, `auth.service.ts`).

#### **Java (Spring Boot):**
Para el desarrollo del backend, nos guiaremos de las siguientes convenciones:
* Utilizar `PascalCase` para el nombre de las Clases y `camelCase` para los métodos y atributos.
* Mantener la regla de escribir una sola clase por archivo.
* Usar `UPPER_SNAKE_CASE` para las constantes (`static final`).
* Utilizar las anotaciones semánticas de Spring Boot para definir claramente la capa lógica de cada clase (`@RestController` para controladores, `@Service` para lógica de negocio, `@Repository` para acceso a datos).
* Agrupar las clases en paquetes lógicos según su dominio (ejemplo: `com.petcare.users`, `com.petcare.appointments`).

### 5.1.4. Software Deployment Configuration
Para realizar el despliegue de nuestro landing page haremos uso de la herramienta GitHub. En donde el equipo deberá contar con una organización y repositorio donde ubicamos los documentos. En este mismo observaremos los siguientes elementos:

  * Una carpeta “html” con el “index.html” en donde almacenaremos el código de nuestra landing page. 
  * Una carpeta “js” la cual contiene los scripts con la lógica para el landing page en un archivo “index.js”
  * Una carpeta “css” la cual contiene los estilos que usaremos en un archivo “style.css” 
  * Una carpeta “images” la cual contiene las imágenes empleadas en el landing page

## 5.2. Landing Page, Services & Applications Implementation
### 5.2.1. Sprint 1 
#### 5.2.1.1. Sprint Planning 1
| Categoría | Detalle |
| :--- | :--- |
| **Sprint#** | Sprint 1 |
| **Sprint Planning Background** | |
| Date | 2026-04-22 |
| Time | 8:00PM-12PM |
| Location | Discord |
| Prepared By | Mejia Aliaga, Katherine Maryory |
| Attendees (to planning meeting) | Katherine Maryory Mejia Aliaga<br>Mauricio Silva, Ghiou Justinn<br>Ghorghet Saul Tuncar Vila<br>Diego Roberto Campoblanco Guzman<br>Jean Pool Huaman de la Cruz |
| Sprint 0 Review Summary | Diseño de landing page |
| Sprint 0 Retrospective Summary | Se logró planear el diseño y estructura que tendrá el landing page en coordinación con el equipo tomando las historias de usuario 1, 23, 13, 7, 19 y 10 previamente definidas. |
| **Sprint Goal & User Stories** | |
| Sprint 1 Goal | Our focus is on offering a friendly landing page to the users that adjust to their needs while starting to use PetCare.<br>We believe it helps the user for their first time using the app in a way that can be easy to understand.<br>This will be confirmed when the landing page is fully deployed in production, is fully responsive on mobile devices, and all Call-to-Action (CTA) buttons successfully redirect visitors to the PetCare Web App registration portal without errors. |
| Sprint 1 Velocity | 15 |
| Sum of Story Points | 15 |
#### 5.2.1.2. Aspect Leaders and Collaborators
En el presente Sprint se prioriza el desarrollo del Landing Page de la plataforma PetCare, el cual constituye el principal punto de entrada para los usuarios del sistema. Este componente cumple un rol estratégico, ya que permite comunicar de manera clara, estructurada y visualmente atractiva la propuesta de valor del producto, orientada a optimizar la gestión de la salud veterinaria mediante el uso de tecnologías digitales.

El Sprint se enfoca en el diseño e implementación de la interfaz del Landing Page, abarcando la estructura visual, la organización de contenidos y la navegación del usuario, garantizando una experiencia intuitiva, accesible y responsive. Para optimizar la distribución del trabajo, se define una Leadership and Collaboration Matrix (LACX) que establece los roles de Leader y Collaborator por cada aspecto técnico, facilitando la coordinación del equipo y la ejecución eficiente de las tareas del Sprint. A continuación, se presenta un cuadro a detalle.

**Leadership and Collaboration Matrix (LACX)**

| Team Member (Last Name, First Name) | GitHub Username | Landing Page HTML (L/C) | Landing Page CSS (L/C) | Landing Page JS (L/C) | UI/UX Design (L/C) |
|------------------------------------|-----------------|--------------------------|--------------------------|------------------------|---------------------|
| Mejia Aliaga, Katherine Maryory | KathMJ     | L                        | L                        | L                      | C                   |
| Tuncar Vila, Ghorghet Saul   | Ghorghet     | C                        | C                        | C                      | C       |

 **Aspecto: Desarrollo del Landing Page de PetCare**

| Aspecto | Descripción |
|--------|------------|
| **Feature** | Diseño, desarrollo e implementación del Landing Page de la plataforma PetCare. |
| **Objetivo Principal** | Desarrollar una landing page informativa, moderna y altamente usable que comunique de manera efectiva la propuesta de valor de PetCare, destacando sus funcionalidades principales como la gestión de historial clínico digital, recordatorios automatizados y búsqueda de servicios veterinarios, con el objetivo de incentivar la interacción y el registro de nuevos usuarios. |
| **Elementos incluidos** | • Diseño de layout principal adaptable (responsive design)<br>• Barra de navegación con acceso a secciones clave (Inicio, Quiénes somos, Beneficios, Suscripción, Contacto)<br>• Sección Hero con mensaje principal y llamada a la acción (CTA)<br>• Sección “Quiénes somos” con descripción institucional<br>• Sección de Beneficios estructurada en tarjetas informativas<br>• Sección de Planes de suscripción (Plan Premium y Plan Salud)<br>• Formulario de contacto para captación de usuarios<br>• Footer con información general del sistema<br>• Botones de acción: “Saber más”, “Registrarse”, “Elegir plan”<br>• Implementación de internacionalización básica (idiomas ES/EN) |
| **Criterios de aceptación** | • Navegación fluida entre secciones mediante enlaces internos (anclas)<br>• Correcta visualización en distintos dispositivos (mobile, tablet y desktop)<br>• Coherencia visual con la identidad de marca (paleta de colores, tipografía y estilos)<br>• Contenido claro, legible y estructurado<br>• Correcta carga de recursos (imágenes, estilos, scripts)<br>• Funcionamiento adecuado de botones y enlaces interactivos<br>• Formulario de contacto operativo<br>• Implementación funcional del cambio de idioma<br>• Uso adecuado del framework Materialize CSS para componentes UI |
| **Resultado esperado** | Un Landing Page completamente funcional, accesible y visualmente consistente que represente de manera adecuada la propuesta de valor de PetCare, facilitando la comprensión del sistema por parte de los usuarios, generando confianza y promoviendo la conversión de visitantes en usuarios registrados. |




#### 5.2.1.3. Sprint Backlog 1. 
| US ID | User Story Title | Task ID | Task Title | Description | Estimation | Assigned To | Status |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| US01 | Buscar veterinarias con filtros | W-1 | Buscar Resultados | Como dueño de mascotas, quiero buscar veterinarias mediante filtros por distrito, horario y especialidad, para encontrar una opción adecuada rápidamente. | 1 hora | Mejia Aliaga, Katherine Maryory | In-Process |
| US23 | Filtro de veterinarias 24 horas | W-2 | Filtro de Búsqueda | Como dueño de mascota, quiero filtrar solo veterinarias con atención de emergencia, para actuar rápido ante accidentes nocturnos. | 30 minutos | Mejia Aliaga, Katherine Maryory | In-Process |
| US13 | Plan premium de posicionamiento | W-3 | Plan de Pago | Como administrador de veterinaria, quiero contratar un plan premium para destacar mi negocio dentro de la plataforma. | 30 minutos | Mejia Aliaga, Katherine Maryory | Done |
| US07 | Recibir recordatorios automáticos | W-4 | Automatización de Recordatorios | Como dueño de mascota, quiero recibir notificaciones automáticas, para recordar vacunas y controles médicos pendientes. | 1 hora | Mejia Aliaga, Katherine Maryory | In-Process |
| US19 | Chat de consultas post-cita | W-5 | Chat de consultas post-cita | Como dueño de mascota, quiero chatear con el veterinario que atendió a mi mascota, para resolver dudas sobre el tratamiento. | 30 minutos | Mejia Aliaga, Katherine Maryory | In-Process |
| US10 | Gestión de perfil comercial | W-6 | Gestión de perfiles | Como administrador de veterinaria, quiero actualizar horarios, promociones y datos comerciales para mantener informados a los clientes. | 30 minutos | Mejia Aliaga, Katherine Maryory | In-Process |

#### 5.2.1.4. Development Evidence for Sprint Review
En esta sección se presenta la evidencia del progreso alcanzado durante el desarrollo del Sprint 1, específicamente en la implementación del Landing Page de la plataforma PetCare. Se destacan los avances realizados en la estructura, diseño y despliegue inicial de la interfaz, alineados con los objetivos definidos en el Sprint Planning.

A continuación, se muestra la tabla que documenta los commits más relevantes asociados al repositorio del proyecto, permitiendo evidenciar el avance técnico y la contribución del equipo durante el Sprint.

| Repository                   | Branch | Commit Id | Commit Message | Commit Message Body | Committed on (Date) |
|----------------------------|--------|----------|----------------|---------------------|----------------------|
|petcare-landingpage /KathMJ| main   | cc6ebf3  | chore: initial landing page setup | Initial commit of the landing page structure and base files | 22/04/2026 |


#### 5.2.1.5. Execution Evidence for Sprint Review

**Sprint 1:**

Durante el desarrollo del Sprint 1 se realizaron las siguientes implementaciones:

**1.- Barra de navegación:** En esta se puede observar cómo el usuario puede acceder con un simple click a información esencial como Quienes somos, beneficios de la app, Suscripción y contacto.

<img src="assets/Barra-De-Navegacion.png">

**2.- Seccion del héroe:** Se implemento la seccion hero la cual incluye un mensaje atractivo y puntual para los clientes

<img src="assets/Seccion-Del-Heroe.png">

**3.- Sección quienes somos:** Añadimos la sección con información esencial sobre el grupo y la Petcare para brindar una rapida introduccion a los usuarios

<img src="assets/Seccion-Del-Quienes-Somos.png">

**4.- Sección Beneficios:** Añadimos las sección de beneficios  en la cual se explica de manera concisa al usuario los beneficios por usar la aplicación para el cuidado clínico de su mascota

<img src="assets/Seccion-Beneficios.png">

**5.- Sección de suscripciones:** En este apartado mostramos los planes disponibles a los usuarios para que pueda ver la opción que mejor se acomode a sus necesidades 

<img src="assets/Seccion-Suscripciones.png">

**6.- Sección de Registro:** Se añadió el apartado de registro donde si el posible usuario esta interesado puede registrarse en la aplicación añadiendo sus nombres, apellidos, correo y teléfono.

<img src="assets/Seccion-de-Registro.png">

**Link del video de demostración:** https://drive.google.com/file/d/1ThG-uKVHmkH3e956boju7AyqltXSUESM/view?usp=sharing 

#### 5.2.1.6. Services Documentation Evidence for Sprint Review

En esta sección se presenta la documentación relacionada con los servicios web que formarán parte de la plataforma PetCare. Estos servicios estarán orientados a gestionar de manera eficiente la información de usuarios, mascotas y clínicas veterinarias, así como a facilitar el acceso a funcionalidades clave como recordatorios, historial clínico digital y comunicación entre usuarios y profesionales veterinarios.

Los servicios web de PetCare están diseñados para centralizar la información de salud de las mascotas y optimizar la interacción entre los distintos actores del sistema (dueños de mascotas y clínicas veterinarias). A través de estos servicios, se busca garantizar una experiencia integrada, segura y eficiente, permitiendo el acceso a información relevante en tiempo real y mejorando la toma de decisiones en el cuidado de las mascotas.

A continuación, se describen los principales servicios que serán implementados en la plataforma:

- **Servicios de Autenticación y Autorización:** Registro de usuarios, inicio de sesión, gestión de sesiones mediante tokens (JWT) y control de acceso según el tipo de usuario (dueño de mascota o clínica veterinaria).

- **Servicios de Gestión de Usuarios:** Creación, edición y consulta de perfiles de usuarios, almacenamiento de información personal y configuración de preferencias dentro de la plataforma.

- **Servicios de Gestión de Mascotas:** Registro de mascotas, actualización de datos (edad, raza, historial), asociación con su propietario y acceso a información clínica centralizada.

- **Servicios de Historial Clínico:** Registro, almacenamiento y consulta del historial médico de cada mascota, incluyendo vacunas, tratamientos, cirugías y diagnósticos.

- **Servicios de Recordatorios y Seguimiento:** Generación automática de recordatorios para vacunas, controles médicos y desparasitaciones, así como notificaciones programadas para el usuario.

- **Servicios de Búsqueda de Veterinarias:** Consulta de clínicas veterinarias cercanas, filtrado por tipo de atención, disponibilidad y ubicación.

- **Servicios de Suscripciones:** Gestión de planes (Premium y Salud), control de beneficios asociados y administración del estado de suscripción de cada usuario.

- **Servicios de Contacto y Comunicación:** Recepción de datos desde formularios de contacto, gestión de solicitudes de usuarios y futura integración de canales de comunicación con veterinarias.


#### 5.2.1.7. Software Deployment Evidence for Sprint Review
En esta sección se describe el proceso de despliegue del Landing Page de la plataforma PetCare en un entorno accesible para los usuarios. Este proceso permite validar la correcta implementación de la interfaz desarrollada durante el Sprint 1, asegurando su disponibilidad, visualización y funcionamiento en línea.

El despliegue del Landing Page representa un hito importante dentro del desarrollo del proyecto, ya que permite contar con una versión funcional del sistema accesible mediante un enlace público, facilitando la validación del producto por parte del equipo y de los usuarios objetivo.

**URL de despliegue del Landing Page:**

[![Landing Page](https://img.shields.io/badge/Visit-Landing%20Page-blue?style=for-the-badge&logo=githubpages&logoColor=white)](https://co-designers.github.io/petcare-landingpage/)

**Landing Page Desplegado**

1. Para el despliegue del Landing Page, el equipo utilizó el repositorio del proyecto *petcare-landingpage*, en el cual se gestionaron todos los archivos correspondientes a la estructura HTML, estilos CSS y funcionalidades JavaScript desarrolladas durante el Sprint.

<img src="assets/deployment-evidence/img1-petcare-landingpage.png" alt="Repositorio Landing Page PetCare" width="100%">

2. Se trabajó sobre la rama principal *main*, donde se integraron los cambios finales del Landing Page, asegurando una versión estable y lista para su publicación.

<img src="assets/deployment-evidence/img2-petcare-landingpage.png" alt="Rama main del repositorio PetCare" width="100%">

3. Posteriormente, se configuró el servicio GitHub Pages, el cual permite el alojamiento de sitios web estáticos directamente desde el repositorio. A través de esta herramienta, se seleccionó la rama *main* como fuente de despliegue.

<img src="assets/deployment-evidence/img3-petcare-landingpage.png" alt="Configuración GitHub Pages PetCare" width="100%">

4. Finalmente, se generó el enlace público del sitio, permitiendo acceder al Landing Page de PetCare desde cualquier navegador web, validando su correcto funcionamiento, diseño responsive y experiencia de usuario.

<img src="assets/deployment-evidence/img4-petcare-landingpage.png" alt="Landing Page desplegado PetCare" width="100%">

El resultado de este proceso es un Landing Page desplegado y accesible en línea, que representa de manera efectiva la propuesta de valor de PetCare y sirve como punto de entrada para los usuarios del sistema.


#### 5.2.1.8. Team Collaboration Insights during Sprint.

En esta sección se presenta una visión general de la colaboración del equipo durante el Sprint 1 del proyecto PetCare. Se abordan la organización de las actividades, la distribución de tareas y la interacción entre los integrantes, lo que contribuyó a una gestión eficiente de responsabilidades y al correcto desarrollo del Sprint.

Asimismo, se incluye evidencia del avance del equipo en GitHub, donde se reflejan los commits realizados por cada integrante, tal como se muestra en la imagen a continuación, evidenciando su participación activa en el desarrollo del proyecto.

# Conclusiones
# Bibliografía 
# Anexos
