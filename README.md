#### Universidad Peruana de Ciencias Aplicadas
#### Ingeniería de Software
#### Aplicaciones Web - SW53
<hr>

# <center>COURSE PROJECT</center>

<p align="center">
    <strong>Universidad Peruana de Ciencias Aplicadas</strong><br>
    <img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png"></img><br>
    <strong>Ingeniería de Software - 5to Ciclo</strong><br>
    <strong>Desarrollo de Aplicaciones Aplicaciones Web - SW53</strong><br>
    <strong>Profesor: Naldo Reupo</strong><br>
    <br>INFORME DE TRABAJO FINAL - TB2
</p>


## StartUp Name
### Team Members:
| Member | Code |
|:----|:----:|
|Castillo Robles, Steve| U202121679 |
|Castro Soto, Diego Mauricio | U202216636|
|Espinoza Quispe, Jennifer Mary | U202120911 |
|Esquivel Aguayo, Diego Martín | U202116749 |

### <center>Ciclo 2023-02</center>
<br><br>

# Registro de Versiones del Informe


| Versión | Fecha | Autor | Descripción de modificación | 
|:-------:|:-----:|:-----:|:----------------------------| 
|TB1|05/09/2023|  Todos los integrantes del equipo|Se estableció la solución propuesta, se realizó un análisis Lean UX, se definió el segmento objetivo y se recopilaron los requisitos necesarios para desarrollar las herramientas necesarias (Personas de Usuario, Historias de Usuario, Product Backlog, Impact Mapping, entre otros). Posteriormente, se diseñaron los mockups y prototipos de la página de inicio en base a la información obtenida. Por último, se creó la página de inicio con la ayuda del sprint backlog para tener un control de los avances.|
|TP|26/09/2023|  Todos los integrantes del equipo|En resúmen, en el proceso de desarrollo de nuestra Aplicación Web Frontend, comenzamos por cuidadosamente seleccionar los user stories que formarían parte de nuestro primer avance. Luego, procedimos a implementar estos user stories en Angular, basándonos en los mockups que habíamos previamente diseñado. Finalmente, culminamos esta fase al desplegar con éxito el frontend de nuestra aplicación web, logrando así un hito significativo en el proceso de desarrollo.| 
|TB2|01/11/2023|  Todos los integrantes del equipo |  En resumen, el proceso de desarrollo de nuestra aplicación web backend comenzó con una revisión exhaustiva de la base de datos para asegurarnos de tener una base sólida. Luego, creamos el proyecto en .NET y organizamos las carpetas y la distribución del trabajo. Al mismo tiempo, creamos unit tests bien pensados para ayudar a detectar errores en el backend. Finalmente, desplegamos la aplicación en Azure Web Apps. | 

<br><br>

# Project Report Collaboration Insights
<br><br>

# Contenido
## Tabla de Contenidos
### [Registro de versiones del informe](#registro-de-versiones-del-informe)
### [Project Report Collaboration Insights](#project-report-collaboration-insights)
### [Contenido](#contenido)
### [Student Outcome](#student-outcome-1)
### [Capítulo I: Introducción](#capc3adtulo-i-introduccic3b3n-1)
- [1.1. Startup Profile](#11-startup-profile)
    - [1.1.1. Descripción de la Startup](#111-description-de-la-startup)
    - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
- [1.2. Solution Profile](#12-solution-profile)
    - [1.2.1 Antecedentes y problemática](#121-antecedentes-y-problemática)
    - [1.2.2 Lean UX Process](#122-lean-ux-process)
        - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
        - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
        - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
        - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
- [1.3. Segmentos objetivo](#13-segmentos-objetivo)

### [Capítulo II: Requirements Elicitation & Analysis](#capc3adtulo-ii-requirements-elicitation--analysis-1)
- [2.1. Competidores](#21-competidores)
    - [2.1.1. Análisis competitivo](#211-análisis-competitivo)
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

### [Capítulo III: Requirements Specification](#capc3adtulo-iii-requirements-specification-1)
- [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
- [3.2. User Stories](#32-user-stories)
- [3.3. Impact Mapping](#33-impact-mapping)
- [3.4. Product Backlog](#34-product-backlog)

### [Capítulo IV: Product Design](#capc3adtulo-iv-product-design-1)
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
    - [4.6.1. Software Architecture Context Diagram](#461-software-architecture-context-diagram)
    - [4.6.2. Software Architecture Container Diagrams](#462-software-architecture-container-diagrams)
    - [4.6.3. Software Architecture Components Diagrams](#463-software-architecture-components-diagrams)
- [4.7. Software Object-Oriented Design](#47-software-object-oriented-design)
    - [4.7.1. Class Diagrams](#471-class-diagrams)
    - [4.7.2. Class Dictionary](#472-class-dictionary)
- [4.8. Database Design](#48-database-design)
    - [4.8.1. Database Diagram](#481-database-diagram)

### [Capítulo V: Product Implementation, Validation & Deployment](#capc3adtulo-v-product-implementation-validation--deployment-1)
- [COURSE PROJECT](#course-project)
  - [StartUp Name](#startup-name)
    - [Team Members:](#team-members)
    - [Ciclo 2023-02](#ciclo-2023-02)
- [Registro de Versiones del Informe](#registro-de-versiones-del-informe)
- [Project Report Collaboration Insights](#project-report-collaboration-insights)
- [Contenido](#contenido)
  - [Tabla de Contenidos](#tabla-de-contenidos)
    - [Registro de versiones del informe](#registro-de-versiones-del-informe-1)
    - [Project Report Collaboration Insights](#project-report-collaboration-insights-1)
    - [Contenido](#contenido-1)
    - [Student Outcome](#student-outcome)
    - [Capítulo I: Introducción](#capítulo-i-introducción)
    - [Capítulo II: Requirements Elicitation \& Analysis](#capítulo-ii-requirements-elicitation--analysis)
    - [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
    - [Capítulo IV: Product Design](#capítulo-iv-product-design)
    - [Capítulo V: Product Implementation, Validation \& Deployment](#capítulo-v-product-implementation-validation--deployment)
    - [Conclusiones](#conclusiones)
    - [Bibliografía](#bibliografía)
    - [Anexos](#anexos)
- [Student Outcome](#student-outcome-1)
  - [Capítulo I: Introducción](#capítulo-i-introducción-1)
  - [1.1. StartUp Profile](#11-startup-profile)
    - [1.1.1. Description de la StartUp](#111-description-de-la-startup)
    - [1.1.2. Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  - [1.2. Solution Profile](#12-solution-profile)
    - [1.2.1. Antecedentes y problemática](#121-antecedentes-y-problemática)
    - [1.2.2. Lean UX Process](#122-lean-ux-process)
      - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
      - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
      - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
      - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
- [1.3. Segmentos Objetivo](#13-segmentos-objetivo)
- [Capítulo II: Requirements Elicitation \& Analysis](#capítulo-ii-requirements-elicitation--analysis-1)
  - [2.1. Competidores](#21-competidores)
    - [2.1.1. Análisis competitivo](#211-análisis-competitivo)
    - [2.1.2. Estrategias y tácticas frente a competidores](#212-estrategias-y-tácticas-frente-a-competidores)
  - [2.2. Entrevistas](#22-entrevistas)
    - [2.2.1. Diseño de entrevistas](#221-diseño-de-entrevistas)
    - [2.2.2. Registro de entrevistas](#222-registro-de-entrevistas)
    - [Segmento 02](#segmento-02)
    - [2.2.3. Análisis de entrevistas](#223-análisis-de-entrevistas)
  - [2.3. Needfinding](#23-needfinding)
    - [2.3.1. User Personas](#231-user-personas)
    - [2.3.2. User Task Matrix](#232-user-task-matrix)
    - [2.3.3. User Journey Mapping](#233-user-journey-mapping)
    - [2.3.4. Empathy Mapping](#234-empathy-mapping)
    - [2.3.5. As-is Scenario Mapping](#235-as-is-scenario-mapping)
- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification-1)
  - [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
  - [3.2. User Stories](#32-user-stories)
  - [3.3. Impact Mapping](#33-impact-mapping)
  - [3.4. Product Backlog](#34-product-backlog)
- [Capítulo IV: Product Design](#capítulo-iv-product-design-1)
  - [4.1. Style Guidelines.](#41-style-guidelines)
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
    - [4.6.1. Software Architecture Context Diagram](#461-software-architecture-context-diagram)
    - [4.6.2. Software Architecture Container Diagrams](#462-software-architecture-container-diagrams)
    - [4.6.3. Software Architecture Components Diagrams](#463-software-architecture-components-diagrams)
  - [4.7. Software Object-Oriented Design](#47-software-object-oriented-design)
    - [4.7.1. Class Diagrams](#471-class-diagrams)
    - [4.7.2. Class Dictionary](#472-class-dictionary)
  - [4.8. Database Design](#48-database-design)
    - [4.8.1. Database Diagram](#481-database-diagram)
- [Capítulo V: Product Implementation, Validation \& Deployment](#capítulo-v-product-implementation-validation--deployment-1)
    - [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
    - [5.1.2. Source Code Management](#512-source-code-management)
    - [5.1.3. Source Code Style Guide \& Conventions](#513-source-code-style-guide--conventions)
    - [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
  - [5.2. Landing Page, Services \& Applications Implementation](#52-landing-page-services--applications-implementation)
    - [5.2.1. Sprint 1](#521-sprint-1)
      - [5.2.1.1. Sprint Planning 1](#5211-sprint-planning-1)
      - [5.2.1.2. Sprint Backlog 1](#5212-sprint-backlog-1)
      - [5.2.1.3. Development Evidence for Sprint Review](#5213-development-evidence-for-sprint-review)
      - [5.2.1.4. Testing Suite Evidence for Sprint Review](#5214-testing-suite-evidence-for-sprint-review)
      - [5.2.1.5. Execution Evidence for Sprint Review](#5215-execution-evidence-for-sprint-review)
      - [5.2.1.6. Services Documentation Evidence for Sprint Review](#5216-services-documentation-evidence-for-sprint-review)
      - [5.2.1.7. Software Deployment Evidence for Sprint Review](#5217-software-deployment-evidence-for-sprint-review)
      - [5.2.1.8. Team Collaboration Insights during Sprint](#5218-team-collaboration-insights-during-sprint)
    - [5.2.2. Sprint 2](#522-sprint-2)
      - [5.2.2.1. Sprint Planning 2](#5221-sprint-planning-2)
      - [5.2.2.2. Sprint Backlog 2](#5222-sprint-backlog-2)
      - [5.2.2.3. Development Evidence for Sprint Review](#5223-development-evidence-for-sprint-review)
      - [5.2.2.4. Testing Suite Evidence for Sprint Review](#5224-testing-suite-evidence-for-sprint-review)
      - [5.2.2.5. Execution Evidence for Sprint Review](#5225-execution-evidence-for-sprint-review)
      - [5.2.2.6. Services Documentation Evidence for Sprint Review](#5226-services-documentation-evidence-for-sprint-review)
      - [5.2.2.7. Software Deployment Evidence for Sprint Review](#5227-software-deployment-evidence-for-sprint-review)
      - [5.2.2.8. Team Collaboration Insights during Sprint.](#5228-team-collaboration-insights-during-sprint)
    - [5.2.3. Sprint 3](#523-sprint-3)
      - [5.2.3.1. Sprint Planning 3](#5231-sprint-planning-3)
      - [5.2.3.2. Sprint Backlog 3](#5232-sprint-backlog-3)
      - [5.2.3.3. Development Evidence for Sprint Review.](#5233-development-evidence-for-sprint-review)
      - [5.2.3.4. Testing Suite Evidence for Sprint Review.](#5234-testing-suite-evidence-for-sprint-review)
      - [5.2.3.5. Execution Evidence for Sprint Review.](#5235-execution-evidence-for-sprint-review)
      - [5.2.3.6. Services Documentation Evidence for Sprint Review.](#5236-services-documentation-evidence-for-sprint-review)
      - [5.2.3.7. Software Deployment Evidence for Sprint Review.](#5237-software-deployment-evidence-for-sprint-review)
      - [5.2.3.8. Team Collaboration Insights during Sprint.](#5238-team-collaboration-insights-during-sprint)
    - [5.2.4. Sprint 4](#524-sprint-4)
      - [5.2.4.1. Sprint Planning 4](#5241-sprint-planning-4)
      - [5.2.4.2. Sprint Backlog 4](#5242-sprint-backlog-4)
      - [5.2.4.6. Services Documentation Evidence for Sprint Review.](#5246-services-documentation-evidence-for-sprint-review)
      - [5.2.4.7. Software Deployment Evidence for Sprint Review.](#5247-software-deployment-evidence-for-sprint-review)
  - [5.3 Validation Interview](#53-validation-interview)
    - [5.3.1 Diseño de Entrevistas](#531-diseño-de-entrevistas)
    - [5.3.2 Registro de Entrevistas](#532-registro-de-entrevistas)
    - [Segmento 01: (Chambeadores)](#segmento-01-chambeadores)
    - [SEGMENTO 02: (Empleadores)](#segmento-02-empleadores)
    - [5.3.3 Evaluación según heurísticas](#533-evaluación-según-heurísticas)
      - [UX Heuristics \& Principles Evaluation](#ux-heuristics--principles-evaluation)
        - [Usability – Inclusive Design – Information Architecture](#usability--inclusive-design--information-architecture)
  - [5.4 Video About the Product](#54-video-about-the-product)
- [Conclusiones](#conclusiones-1)
- [Bibliografía](#bibliografía-1)
- [Anexos](#anexos-1)


### [Conclusiones](#conclusiones-1)
- [Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)

### [Bibliografía](#bibliografc3ada-1)
### [Anexos](#anexos-1)

<br><br>

# Student Outcome

Criterio: Trabaja efectivamente en un equipo cuyos miembros juntos proporcionan liderazgo; crea un entorno colaborativo e inclusivo y establece metas, planifica tareas y cumple objetivos.

En el siguiente cuadro se describe las acciones realizadas y enunciados de 
conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro 
del ABET – EAC - Student Outcome 5.

<table>
  <tr>
    <td><b>Criterio específico</b></td>
    <td><b>Acciones realizadas</b></td>
    <td><b>Conclusiones</b></td>
  </tr>
  <tr>
    <td rowspan="3"><b>Participa en equipos multidisciplinarios con eficacia, eficiencia y objetividad, en el marco de un proyecto en soluciones de ingeniería de software.</b></td>
    <td> TB1<br><br>
         <b>Steve Roger Castillo Robles </b><br>
        - Realizamos la planificación adecuada para formar de manera efectiva el plan de desarrollo de nuestra solución.
        <br><br> 
         <b>Diego Mauricio Castro Soto</b><br>
        - Trabajamos de manera colaborativa para distribuir todas las tareas de la entrega, realizar una tormenta de ideas y colaborar de forma efectiva en cada etapa del proyecto.
        <br><br>
        <b>Jennifer Mary Espinoza Quispe</b><br>
        - Hemos establecido una estructura para identificar todos los elementos del proceso Lean UX, con el objetivo de comprender la problemática y encontrar soluciones en la medida de lo posible.
        <br><br> 
        <b>Diego Martín Esquivel Aguayo</b>
        - Colaboramos con los miembros del equipo para acordar cómo serán los prototipos, íconos y otros diseños.
        <br><br>
   </td>
    <td>TB1<br><br>
    Seleccionamos crear una aplicación destinada a empleadores y trabajadores eventuales, en la cual desarrollamos enunciados del problema y declaraciones de hipótesis para evaluar el alcance del desarrollo y proporcionar una solución efectiva a las necesidades de ambos grupos.</td>
  </tr>
  <tr>
    <td> TP<br><br>
         <b>Steve Roger Castillo Robles </b><br>
        - Nuestra sólida organización y planificación nos permitieron establecer de manera efectiva todos los puntos clave para el desarrollo exitoso de nuestro primer avance en la Aplicación Web Frontend.
        <br><br> 
         <b>Diego Mauricio Castro Soto</b><br>
        - La colaboración activa y las reuniones efectivas entre el equipo de trabajo mejoraron significativamente nuestra capacidad para distribuir tareas, realizar tormentas de ideas y avanzar en cada etapa del proyecto de manera eficiente.
        <br><br>
        <b>Jennifer Mary Espinoza Quispe</b><br>
        - Gracias a nuestra meticulosa organización, logramos identificar y mejorar varios aspectos clave en la ejecución de nuestro plan de desarrollo, lo que contribuyó a un progreso más fluido y efectivo.
        <br><br> 
        <b>Diego Martín Esquivel Aguayo</b>
        - La coordinación y comunicación efectiva del equipo nos permitieron establecer con éxito todos los elementos necesarios para llevar a cabo el primer avance de la Aplicación Web Frontend, demostrando nuestro compromiso con la entrega exitosa del proyecto.
        <br><br>
   </td>
    <td>TP<br><br>
    Se seleccionaron cuidadosamente las user stories que abordaríamos en nuestro nuevo sprint para el desarrollo del Frontend Application Web, asegurando así un enfoque claro y efectivo en la implementación de las funcionalidades esenciales.</td>
  </tr>
  <tr>
    <td> TB2<br><br>
         <b>Steve Roger Castillo Robles </b><br>
        - Las entrevistas desempeñaron un papel fundamental en la mejora de nuestra plataforma web. El feedback recibido resultó invaluable para perfeccionar nuestro proyecto. A través de esta retroalimentación, hemos fortalecido nuestra capacidad para satisfacer las necesidades de nuestros usuarios y ofrecer una plataforma más efectiva y funcional.
        <br><br> 
         <b>Diego Mauricio Castro Soto</b><br>
        - Realizamos una nueva versión del servicio, implementando las mejoras continúas recibidas de la entrega anterior.
        <br><br>
        <b>Jennifer Mary Espinoza Quispe</b><br>
        - Se implementaron mejoras en la funcionalidad principal de la aplicación, optimizando su rendimiento y aumentando la eficiencia del sistema. También se corrigieron varios errores reportados por los usuarios para ofrecer una experiencia más fluida y sin interrupciones.
        <br><br> 
        <b>Diego Martín Esquivel Aguayo</b>
        - Se realizaron mejoras en la aplicación web para mejorar la experiencia de usuario al realizar una reserva. Además, de pulir el diseño de algunos componentes y colaborar en el desarrollo con los otros miembros del equipo.
        <br><br>
   </td>
    <td>TB2<br><br>
    Se desarrollaron nuevas vistas en la parte del Front-end, así como también se implementó el Back-end de nuestra aplicación.</td>
  </tr>
  
  <tr>
    <td rowspan="3"><b>Conoce al menos un sector empresarial o dominio de aplicación de soluciones de software.</b></td>
    <td> TB1<br><br>
         <b>Steve Roger Castillo Robles</b><br>
        - Se realizó un análisis para poder ofrecer una solución innovadora a un sector que tenga falta de apoyo.
        <br><br> 
         <b>Diego Mauricio Castro Soto</b><br>
        - Realizamos un estudio detallado de cada uno de nuestros grupos objetivo en el proyecto, con el fin de garantizar que nuestra aplicación cumpla con todas las necesidades de nuestros usuarios objetivo.
        <br><br>
        <b>Jennifer Mary Espinoza Quispe</b><br>
        - Realicé una entrevista a un miembro de uno de los grupos objetivo con el objetivo de obtener información relevante para llevar a cabo algunos de los aspectos del trabajo.
        <br><br> 
        <b>Diego Martín Esquivel Aguayo</b>
        - Se realizó la elaboración de los prototipos según las propuestas realizadas por los usuarios en las entrevistas y lo acordado con el grupo.
        <br><br>
   </td>
    <td>TB1<br><br>
    Se recopiló la información necesaria para poder enfrentar a los competidores y ofrecer un producto innovador basado en la tecnología.</td>
  </tr>
  <tr>
    <td> TP<br><br>
         <b>Steve Roger Castillo Robles </b><br>
        - Nuestro análisis cuidadoso nos permitió seleccionar con precisión las user stories que utilizaríamos en el desarrollo, lo que resultó en una solución altamente adaptada a las necesidades del sector con falta de apoyo.
        <br><br> 
         <b>Diego Mauricio Castro Soto</b><br>
        - La implementación exitosa de los mockups en nuestra aplicación reflejó nuestro compromiso en ofrecer una solución innovadora y visualmente efectiva para abordar las carencias del sector en cuestión.
        <br><br>
        <b>Jennifer Mary Espinoza Quispe</b><br>
        - A través de un riguroso sprint planning, pudimos analizar minuciosamente los puntos de mejora, lo que contribuyó significativamente a la optimización de nuestro proceso de desarrollo y al fortalecimiento de nuestra solución.
        <br><br> 
        <b>Diego Martín Esquivel Aguayo</b>
        - La exitosa implementación de los user stories seleccionados durante el sprint en nuestra Aplicación Web Frontend demuestra nuestro enfoque en la ejecución efectiva de nuestro plan y en la entrega de una solución que realmente aborda las necesidades del sector con falta de apoyo.
        <br><br>
   </td>
    <td>TP<br><br>
    Hemos alcanzado un hito significativo en nuestro proyecto al lograr con éxito el primer avance de la Aplicación Web Frontend, implementando con destreza y eficacia la solución en Angular. Este logro demuestra nuestro compromiso con la excelencia en el desarrollo y nos impulsa hacia el cumplimiento de nuestros objetivos.</td>
  </tr>
  <tr>
    <td> TB2<br><br>
         <b>Steve Roger Castillo Robles </b><br>
        - Se realizaron entrevistas a ambos sectores para recaudar información sobre qué mejoras y nuevas funcionalidades se pueden añadir a nuestra aplicación web.
        <br><br> 
         <b>Diego Mauricio Castro Soto</b><br>
        - Se llevó a cabo un análisis exhaustivo de la retroalimentación de los usuarios, identificando áreas clave de mejora en nuestra aplicación web. Posteriormente, se diseñaron y desarrollaron nuevas características y funcionalidades para abordar las necesidades y desafíos identificados, mejorando así la experiencia del usuario.
        <br><br>
        <b>Jennifer Mary Espinoza Quispe</b><br>
        - Se implementaron los servicios para las respectivas entidades, cumpliendo con los requerimientos funcionales y no funcionales, y también la lógica de negocio. Además de consumirlo desde las aplicaciones web.
        <br><br> 
        <b>Diego Martín Esquivel Aguayo</b>
        - Nuestra habilidad para comunicar de manera objetiva en el ámbito de la ingeniería, específicamente en el desarrollo de nuestra plataforma web, se ha enriquecido a través del proceso de entrevistas. Esta retroalimentación ha contribuido significativamente a mejorar nuestra comunicación escrita, permitiéndonos conectar eficazmente con audiencias de diversas especialidades y niveles jerárquicos.
        <br><br>
   </td>
    <td>TB2<br><br>
    Realizamos una nueva versión del servicio, el cual seguirá recibiendo mejoras continuas por parte de nuestro equipo de trabajo.</td>
  </tr>
</table>

## Capítulo I: Introducción
## 1.1. StartUp Profile
### 1.1.1. Description de la StartUp
DigitalDart emerge como un arquitecto digital, diseñando soluciones web para resolver la búsqueda de trabajos ocasionales. Este startup de software reimagina cómo se generan ingresos y se busca la libertad laboral. A través de su plataforma ingeniosa, DigitalDart brindará ayuda a jóvenes con diversas habilidades entre 18 y 30 años conectándolos con los demandantes de servicios, considerando ubicación y habilidades. Al redefinir las convenciones laborales, esta flexibilidad no solo cambia la narrativa laboral, sino que también da un nuevo matiz a la economía contemporánea.
### 1.1.2. Perfiles de integrantes del equipo

<table align="center"  border="1" width="70%" style="text-align:center;">
    <tr align="center">
        <td rowspan="3">
            <img src="https://media.discordapp.net/attachments/1145421916413366426/1156371563462012988/SteveTerno.png?ex=6514ba71&is=651368f1&hm=d05c74182c340b15dac29465470e8796d438f002b90109fb6e85479f0562f471&=&width=932&height=1242" alt="Steve Castillo" style="margin-bottom: 5px;" width="600"/>
        </td>
        <td align="left">
            <b>Nombre y Apellido:</b>
            <br>            
            Steve Roger Castillo Robles
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Carrera:</b>
        <br>
        Ing. de Software
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Acerca de:</b>
        <br>
        Soy Steve Roger Castillo Robles y soy estudiante de la carrera de Ing. de Software y tengo conocimientos de JS, HTML y CSS. Ya en la universidad adquirí conocimientos de C++ que me dio la base para entender de manera más profunda todo este mundo de la programación e informática; además, cuento con conocimientos en Git y GitHub que me ayudan a gestionar mis proyectos además de poder revisarlos en cualquier momento. 
        </td>
    </tr>
    <tr align="center">
        <td rowspan="3">
            <img src="https://media.discordapp.net/attachments/1145421916413366426/1145446948267118775/Diego-Uchiha.png" alt="Diego Esquivel" style="margin-bottom: 5px;" width="600"/>
        </td>
        <td align="left">
            <b>Nombre y Apellido:</b>
            <br>            
            Diego Martín Esquivel Aguayo
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Carrera:</b>
        <br>
        Ing. de Software
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Acerca de:</b>
        <br>
        Tengo 19 años, me encuentro en el quinto ciclo de Ingeniería de Software. Soy una persona amigable, tranquila, responsable y ordenada. Cumplo con entregar los trabajos en los plazos establecidos y me adapto fácilmente a las condiciones del trabajo en equipo.
        </td>
    </tr>
    <tr align="center">
        <td rowspan="3">
            <img src="https://media.discordapp.net/attachments/1145421916413366426/1145446947935764600/Def-foto.png" alt="Diego Defilippi" style="margin-bottom: 5px;" width="600"/>
        </td>
        <td align="left">
            <b>Nombre y Apellido:</b>
            <br>            
            Diego Defilippi Santillán
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Carrera:</b>
        <br>
        Ing. de Software
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Acerca de:</b>
        <br>
        Soy Diego Defilippi y tengo una gran pasión por la programación y el diseño de software. Desde hace dos años, estoy aprendiendo las diversas ramas de esta fascinante ingeniería, como el backend, frontend y data science. De igual modo, estoy estudiando diferentes idiomas como el inglés y el portugués, así como distintas habilidades blandas. Finalmente, me considero una persona autodidacta, organizada y con muchos ánimos de aprender. 
        </td>
    </tr>
    <tr align="center">
        <td rowspan="3">
            <img src="https://media.discordapp.net/attachments/1145421916413366426/1145446948808163449/Jenn-Foto.jpg" alt="Jennifer Espinoza" style="margin-bottom: 5px;" width="600"/>
        </td>
        <td align="left">
            <b>Nombre y Apellido:</b>
            <br>            
            Jennifer Mary Espinoza Quispe
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Carrera:</b>
        <br>
        Ing. de Software
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Acerca de:</b>
        <br>
        Soy Jennifer Espinoza, me encuentro en el 5to ciclo de la carrera de Ing. de Software. En lo personal, me agrada aprender cosas nuevas, como nuevos lenguajes de programación e idiomas. Actualmente manejo el lenguaje de C++, un poco de Python y JavaScript. Me considero una persona creativa, responsable y paciente, habilidades que ayudarán en el presente proyecto.
        </td>
    </tr>
    <tr align="center">
        <td rowspan="3">
                        <img src="https://i.imgur.com/SQ3MPq7.png" alt="Diego Castro"  style="margin-bottom: 5px;" width="600"/>
        </td>
        <td align="left">
            <b>Nombre y Apellido:</b>
            <br>            
            Diego Mauricio Castro Soto
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Carrera:</b>
        <br>
        Ing. de Software
        </td>
    </tr>
    <tr>
        <td align="left">
        <b>Acerca de:</b>
        <br>
        Soy Diego Castro, tengo 22 años y me considero alguien autodidacta a quién le gusta siempre aprender nuevas cosas leyendo diversos recursos en la web, ya sea investigando en foros, leyendo libros o a través de videos. Desde ya hace un tiempo me encuentro adquiriendo nuevos conocimientos de diversos lenguajes de programación como C, C++ y C#. Adicional a esto me encuentro sumamente interesado en ahondar en las ramas del desarrollo de videojuegos, la seguridad informática y el desarrollo de aplicaciones web.
        </td>
    </tr>
</table>

## 1.2. Solution Profile
### 1.2.1. Antecedentes y problemática
La búsqueda de trabajos confiables y adecuados, especialmente para
aquellos sin experiencia previa o para quienes buscan trabajos
temporales, es un desafío persistente en la sociedad actual. Los
trabajadores a menudo enfrentan dificultades para encontrar
oportunidades que se adapten a sus habilidades y horarios disponibles,
mientras que los empleadores pueden tener dificultades para identificar
candidatos confiables y calificados para trabajos específicos. Esta
problemática se acentúa en jóvenes y estudiantes universitarios, que
pueden carezcan de experiencia laboral relevante y deseen trabajos
cortos.

Según una encuesta de RPP (2022), se reveló que el 80% de los jóvenes
peruanos enfrenta dificultades al buscar trabajo. La falta de
experiencia fue identificada como el principal obstáculo para conseguir
empleo. Además, otro informe de Perú21 (2023) destacó que el 50% de los
peruanos se encuentran en la situación de estudiar y trabajar
simultáneamente, llevando a buscar trabajos no necesariamente
relacionados con su carrera para financiar sus estudios.

**ChambeaPe** es una aplicación diseñada para abordar los desafíos
mencionados, creando un puente entre personas desempleadas dispuestas a
trabajar de manera eventual y empleadores que buscan cubrir trabajos
temporales, proyectos o tareas específicas. Se busca crear una comunidad
en línea donde los trabajadores y empleadores puedan conectarse de
manera eficiente y satisfacer sus necesidades laborales.

-   **What?**

    El principal problema identificado es la dificultad que tienen los
    jóvenes al encontrar trabajo. Esto conlleva a estancamiento económico,
    aumento del desempleo juvenil, frustración y desmotivación. También,
    debemos resaltar la dependencia económica que se tiene a algún trabajo
    para continuar sus estudios.

-   **When?**

    El problema surge cuando no se tiene experiencia previa y se desee
    realizar trabajos cortos que impliquen un horario flexible. La falta de
    oportunidades adecuadas para este grupo de edad puede tener un impacto
    negativo en su desarrollo económico y personal.

-   **Where?**

    El problema se identifica en cualquier lugar donde los jóvenes busquen
    empleo eventual sin experiencia. Desde áreas urbanas hasta zonas
    rurales, el desafío de encontrar empleo adecuado para los jóvenes es una
    preocupación que trasciende fronteras. Principalmente en lugares en
    donde se requiera personal, pero no de manera estable, sino que se le
    ofrezca un pago por el trabajo realizado.

-   **Who?**

    Este problema afecta directamente a los jóvenes en edad laboral, entre
    los [18]{.underline} y 30 años, que buscan oportunidades de empleo.
    También puede impactar a los estudiantes universitarios que desean
    trabajar de manera ocasional para financiar sus estudios. Además, las
    empresas y empleadores también están involucrados en este problema, ya
    que necesitan identificar y contratar trabajadores jóvenes para trabajos
    temporales o proyectos específicos.

- **Why?**

    Una de las principales causas es la falta de experiencia, no tener un
    respaldo de comentarios o proyectos realizados para otros que puedan
    respaldar el conocimiento pequeño o avanzado del trabajo. La falta de
    referencias sólidas puede ser un obstáculo al competir con candidatos
    más experimentados en el mercado laboral. Esto crea un ciclo en el que
    los jóvenes luchan por conseguir trabajo debido a la falta de
    experiencia, pero no pueden ganar experiencia sin tener la oportunidad
    de trabajar.

-   **How?**

    La solución que proponemos es **ChambeaPe**, una aplicación diseñada
    para cubrir las necesidades tanto de los jóvenes en busca de empleo como
    de los empleadores en busca de trabajadores eventuales. Su objetivo es
    conectarlos de manera segura y dar seguimiento a las actividades
    realizadas.

    **ChambeaPe** está pensada para ser una aplicación intuitiva y fácil de
    usar, brindando una oportunidad de comunicación entre un individuo con
    ganas de trabajar y un empleador.

-   **How much?**

    Esta problemática que estamos abordando afecta de gran manera a los
    jóvenes, pues se desea que ganen experiencia y que a su vez logren la
    independencia económica. El desempleo juvenil va en aumento, tal cual lo
    demuestra RPP (2022) que menciona que 8 de cada 10 jóvenes peruanos
    presentan al intentar trabajar. Mencionando también que cerca del 44% de
    jóvenes llevan buscando un trabajo en los últimos 6 meses.

### 1.2.2. Lean UX Process
#### 1.2.2.1. Lean UX Problem Statements
- En la sociedad actual, los jóvenes enfrentan constantes problemas para encontrar un trabajo seguro, especialmente si carecen de experiencia o necesitan un trabajo ocasional para financiar sus estudios. Esta situación conduce al estancamiento económico, aumenta el desempleo juvenil y crea dependencia económica. La falta de oportunidades y experiencia laboral previa son los principales obstáculos. <br>
Según una encuesta realizada en Perú, el 80% de los jóvenes tiene dificultades para encontrar trabajo por falta de experiencia. Para pagar sus estudios, muchos jóvenes eligen trabajos no relacionados. Para solucionar este problema se creó ChambeaPe, una aplicación que conecta a jóvenes que quieren trabajar temporalmente con empleadores. El objetivo es crear una comunidad en línea que facilite estas conexiones y aborde las preocupaciones laborales de ambos grupos. <br>
El problema afecta a adultos jóvenes y estudiantes universitarios de entre 18 y 30 años. La falta de oportunidades y experiencia crea un círculo vicioso de desempleo juvenil. ChambeaPe tiene como objetivo romper este ciclo proporcionando una plataforma para que los jóvenes encuentren trabajo temporal y adquieran experiencia que contribuya a su independencia financiera y crecimiento personal.
#### 1.2.2.2. Lean UX Assumptions
**Business outcomes:**
 - **Incremento de la plataforma:** Al conectar de manera eficiente a jóvenes con habilidades diversas con demandantes de servicios, DigitalDart puede aumentar la adopción de su plataforma, lo que resultará en un aumento en la cantidad de transacciones y usuarios activos.

- **Generación de ingresos:** Al facilitar un mercado para trabajos ocasionales, DigitalDart tiene el potencial de generar ingresos a través de comisiones por transacciones, suscripciones premium u otras fuentes de monetización, contribuyendo a la sostenibilidad financiera del negocio.

- **Expansión geográfica:** Al considerar la ubicación en su algoritmo de coincidencia, DigitalDart puede expandir su alcance geográfico y atraer a usuarios de diferentes regiones, lo que a su vez puede conducir a la expansión de la plataforma a nivel internacional.

- **Fomento de la economía flexible:** Al proporcionar una plataforma que fomente trabajos ocasionales y flexibles, DigitalDart puede desempeñar un papel en la evolución de la economía laboral, impulsando la demanda de servicios laborales no tradicionales.

- **Colaboración con empresas y emprendedores:** Al establecer conexiones entre jóvenes talentosos y empresas que buscan habilidades específicas, DigitalDart puede crear oportunidades de colaboración y proyectos únicos, lo que podría llevar a asociaciones a largo plazo.

**Users:**
- **Trabajador (18-30 años):** Jóvenes con diversas habilidades en busca de trabajos ocasionales para generar ingresos y libertad laboral. Utilizan la plataforma para conectarse con quienes necesitan sus habilidades.

- **Empleador (18-50 años):** Personas o empresas que buscan contratar personas para proyectos específicos. Utilizan la plataforma para encontrar trabajadores flexibles con las habilidades requeridas.

**Users outcomes:**
- **Oportunidades laborales flexibles:** Los jóvenes entre 18 y 30 años pueden acceder a una variedad de trabajos ocasionales que se ajusten a sus habilidades y horarios, lo que les brinda flexibilidad y control sobre su trabajo.
-  **Generación de ingresos adicionales:** Los usuarios de DigitalDart pueden ganar dinero extra al participar en trabajos ocasionales, lo que les permite aumentar sus ingresos y alcanzar sus metas financieras de manera más efectiva.
- **Experiencia laboral diversa:** Los usuarios tienen la oportunidad de explorar diferentes tipos de trabajos y adquirir una amplia gama de experiencias laborales, lo que puede enriquecer sus habilidades y aumentar su empleabilidad a largo plazo.
- **Empoderamiento y autonomía:** DigitalDart empodera a los jóvenes al permitirles ofrecer sus servicios directamente a través de la plataforma, lo que les brinda un sentido de autonomía y control sobre su carrera laboral.
- **Conexiones y redes profesionales:** Los usuarios pueden establecer conexiones valiosas con demandantes de servicios y otros profesionales en su campo, lo que puede llevar a oportunidades futuras y crecimiento en su red profesional.
#### 1.2.2.3. Lean UX Hypothesis Statements

- Creemos que al desarrollar una plataforma donde los empleadores puedan publicar ofertas de empleo temporal y los empleados puedan explorar y contactar directamente a los empleadores, aumentaremos la eficiencia en la búsqueda y contratación de empleos temporales. Sabremos que hemos tenido éxito cuando veamos un aumento en el número de empleos publicados, la tasa de respuesta de los empleados a las ofertas y la tasa de éxito en la contratación.

- Creemos que al enfocarnos en jóvenes de 18 a 30 años como público objetivo para empleados y personas de 18 a 50 años como empleadores, podremos atender las necesidades y preferencias de ambos grupos de manera efectiva. Sabremos que hemos tenido éxito mediante el seguimiento de la distribución de edades de los usuarios registrados y la retroalimentación recopilada por cada segmento objetivo para verificar que se cumplen las necesidades de cada grupo.

- Creemos que al implementar un sistema de calificaciones y comentarios en donde se evalúen tanto a los empleadores como empleados, incrementaremos la confianza entre las partes y fomentaremos una mayor satisfacción en la plataforma. Sabremos que hemos tenido éxito mediante el seguimiento de la cantidad y calidad de las calificaciones y comentarios proporcionados, así como la frecuencia de las contrataciones recurrentes.

- Creemos que al ofrecer una función de reclamos que permita a los usuarios reportar problemas o situaciones insatisfactorias, aumentaremos la sensación de seguridad y protección en la plataforma, lo que fomentará un ambiente más positivo y colaborativo. Sabremos que hemos tenido éxito cuando incremente la satisfacción general de nuestros usuarios respecto a la resolución de problemas mediante reclamos.

- Creemos que al proporcionar oportunidades de empleo temporal para los jóvenes y promover el uso de la plataforma como fuente de ingresos, contribuiremos a la independencia financiera y al crecimiento económico personal, lo que se traducirá en una mayor participación y retención de usuarios. Sabremos que hemos tenido éxito mediante la recopilación de testimonios de casos de éxito de jóvenes usuarios que hayan logrado generar ingresos a través de la plataforma.

#### 1.2.2.4. Lean UX Canvas

<div align=center>
    <img src="https://cdn.discordapp.com/attachments/1145583761182965852/1145991046635982898/Lean_UX_Canvas.png" alt="Canvas"  width="90%"/>
</div>

# 1.3. Segmentos Objetivo

Para el desarrollo de nuestro proyecto, reconocimos la importancia de delimitar de manera vital nuestros segmentos objetivos, con el fin de obtener un enfoque nítido sobre nuestros usuarios potenciales.

**Primer Segmento Objetivo:**

En nuestro primer segmento objetivo, nos dirigimos a una audiencia de entre 18 y 30 años, que busca la oportunidad de asegurar su subsistencia mediante empleos eventuales. Además, desean tener la capacidad de exhibir sus habilidades y experiencia para trabajos específicos.

**Segundo Segmento Objetivo:**

Como segundo segmento objetivo, nos enfocamos en usuarios de 18 a 50 años. Esta audiencia está interesada en encontrar profesionales especializados para trabajos ocasionales y busca la opción de explorar y contratar personal con competencias específicas para tareas particulares.

De acuerdo con la investigación de Vásquez et al. (2006), realizada en el año 2000, la tasa de desempleo en Perú se mantuvo baja, alcanzando un 5,4%. Sin embargo, los resultados de una encuesta revelaron que el 40% de los encuestados consideraba el desempleo como uno de los problemas más apremiantes del país. Esta aparente contradicción entre las estadísticas y la percepción de la población se explica por la dinámica intrínseca del mercado laboral: los puestos de trabajo se crean y desaparecen rápidamente, lo que lleva a las personas a buscar empleos temporales o "cachuelos" para mantenerse activas. En otras palabras, la tasa de desempleo es fluctuante y las personas buscan autogenerarse empleo o subemplearse para evitar la inactividad laboral.

<br><br>

# Capítulo II: Requirements Elicitation & Analysis
## 2.1. Competidores

Luego de realizar una investigación en el mercado peruano, hemos hallado tres portales de trabajo que ofrecen características similares a la de ChambeaPe. Es por eso que son considerados como potenciales competidores. Estos son:

1. **Computrabajo:**

Es un portal de empleos y reclutamiento que ofrece una amplia gama de ofertas laborales en diferentes industrias. 
<div style="text-align: center;">
                <img src="https://media.discordapp.net/attachments/1145421916413366426/1146125730942554232/favicon_ct.png?width=600&height=600" alt="Computrabajo" style="max-width: 400px; width: 25%;">
</div>

1. **Laborum:**

Es un portal del empleo, ofrece una amplia variedad de oportunidades laborales, trabajaos a plazo fijo y por proyecto. En donde se pueden aplicar filtros de acuerdo con tus necesidades de búsqueda. 
<div style="text-align: center;">
                <img src="https://media.discordapp.net/attachments/1145421916413366426/1146125731219374101/545921-imageonline-co-transparentimage-6.png?width=547&height=118" alt="Computrabajo" style="max-width: 600px; width: 25%;">
</div>

1. **Bumeran:**

Un portal de empleos popular en el Perú, ofrece opciones de búsqueda de empleos temporales o por proyectos específicos. 
<div style="text-align: center; ">
    <img src="https://media.discordapp.net/attachments/1145421916413366426/1146125730586034227/maxresdefault.jpg?width=1447&height=814" style="max-width: 600px; width: 40%;">
</div>

### 2.1.1. Análisis competitivo

<table>
  <tr>
    <th colspan="7" valign="top"><b>Competitive Analysis Landscape</b></th>
  </tr>
  <tr>
    <td colspan="2" rowspan="2">¿Por qué llevar a cabo este análisis?</td>
    <td colspan="5">Escriba en el recuadro la pregunta que busca responder o el objetivo de este análisis.</td>
  </tr>
  <tr>
    <td colspan="5">Este análisis se realizó con la finalidad de poder identificar a nuestros potenciales competidores e idear estrategias y tácticas para diferenciarnos de estos.</td>
  </tr>
  <tr>
    <td colspan="3">(En la cabecera colocar por cada competidor nombre y logo)</td>
    <td colspan="1" valign="top" style="font-weight: bold;">
        ChambeaPe
        <br>
        <div style="text-align: center; margin-top: 10px;">
                <img src="https://media.discordapp.net/attachments/1145421916413366426/1146125730242113576/WhatsApp_Image_2023-08-27_at_11.01.45_PM.jpeg?width=2002&height=1342" alt="ChambeaPe" width="60px">
        </div>
    <td colspan="1" valign="top" style="font-weight: bold;">
    CompuTrabajo
    <div style="text-align: center;">
                <img src="https://media.discordapp.net/attachments/1145421916413366426/1146125730942554232/favicon_ct.png?width=600&height=600" alt="Computrabajo" width="60px">
        </div>
    </td>
    <td colspan="1" valign="top" style="font-weight: bold;">
      Laborum
      <div style="text-align: center; margin-top: 20px;">
                <img src="https://media.discordapp.net/attachments/1145421916413366426/1146125731219374101/545921-imageonline-co-transparentimage-6.png?width=547&height=118" alt="ChambeaPe" width="60px">
            </div>
      </td>
    <td colspan="1" valign="top" style="font-weight: bold;" >
      Bumeran
      <div style="text-align: center; margin-top: 10px;">
                <img src="https://media.discordapp.net/attachments/1145421916413366426/1146125730586034227/maxresdefault.jpg?width=1447&height=814" alt="ChambeaPe" width="60px">
            </div>
    </td>
  </tr>
  <tr>
    <td colspan="1" rowspan="2"><p>Perfil</p></td>
    <td colspan="2">Overview</td>
    <td colspan="1" valign="top">Portal de empleo que ofrece una variedad de oportunidades de empleos temporales, conocidos como "cachuelos". Implementa un sistema de seguimiento de los trabajos realizados y brindar retroalimentación.</td>
    <td colspan="1" valign="top">Ofrece una amplia gama de oportunidades laborales en diversos sectores y niveles.</td>
    <td colspan="1" valign="top">Portal de empleo que brinda oportunidades laborales en Perú. Tiene una amplia gama de ofertas laborales.</td>
    <td colspan="1" valign="top">Portal de empleo que conecta a empleadores y candidatos. Proporciona opciones para una variedad de industrias y niveles de experiencia.</td>
  </tr>
  <tr>
    <td colspan="2">Ventaja competitiva</td>
    <td colspan="1" valign="top">Se enfoca en ayudar a personas jóvenes sin experiencia a encontrar trabajos eventuales y proyectos freelance. Brinda un estatus del proyecto y seguridad al momento del pago entre el empleador y chambeador.</td>
    <td colspan="1" valign="top">Posee una cobertura local e internacional en múltiples sectores. Facilita a los usuarios una amplia gama de ofertas laborales.</td>
    <td colspan="1" valign="top">Cuenta con buen posicionamiento en América Latina. Ofrece oportunidades laborales en diversos sectores y regiones. Es una herramienta efectiva para publicar y promocionar vacantes.</td>
    <td colspan="1" valign="top">Presencia en múltiples países de América Latina. Ofrece una amplia variedad de ofertas laborales y brinda opción para publicar empleos temporales.</td>
  </tr>
  <tr>
    <td colspan="1" rowspan="2"><p>Perfil de Marketing</p></td>
    <td colspan="2">Mercado objetivo</td>
    <td colspan="1" valign="top">Jóvenes de entre 18 a 30 años y empleadores entre 18 y 50 años.</td>
    <td colspan="1" valign="top">Público en general mayor de 18 años que busque empleo.</td>
    <td colspan="1" valign="top">Abierto a diversas edades, ya que ofrece oportunidades de empleo.</td>
    <td colspan="1" valign="top">Dirigido a personas de diferentes edades en búsqueda de empleos.</td>
  </tr>
  <tr>
    <td colspan="2">Estrategias de marketing</td>
    <td colspan="1" valign="top">ChambeaPe ofrece simplicidad y facilidad de uso, con campañas en redes sociales y colaboraciones locales y promociones.</td>
    <td colspan="1" valign="top">Destaca por su red de empresas y variedad de ofertas, empleando campañas de correo electrónico y participación en eventos.</td>
    <td colspan="1" valign="top">Posee amplia cobertura y opciones premium, con anuncios en línea como estrategia de marketing.</td>
    <td colspan="1" valign="top">Enfoque regional, con campañas y recursos locales, buscando colaboraciones para fortalecer su presencia.</td>
  </tr>
  <tr>
    <td colspan="1" rowspan="3"><p>Perfil de Producto</p></td>
    <td colspan="2">Productos & Servicios</td>
    <td colspan="1" valign="top">Plataforma inclusiva que conecta empleadores y trabajadores temporales, proporcionando una experiencia sencilla y segura para encontrar proyectos eventuales en Perú.</td>
    <td colspan="1" valign="top">Proporciona una amplia gama de trabajos temporales y oportunidades de corta duración, respaldada por sus opciones avanzadas de búsqueda.</td>
    <td colspan="1" valign="top">La aplicación brinda una plataforma donde se muestra gráficas sencillas sobre tus gastos con la finalidad de planificar un presupuesto.</td>
    <td colspan="1" valign="top">Ofrece empleos tanto temporales como permanentes, dando un espacio consolidado para diversos perfiles laborales y oportunidades.</td>
  </tr>
  <tr>
    <td colspan="2">Precios & Costos</td>
    <td colspan="1" valign="top">La aplicación cuenta con una versión gratuita y una versión de pago la cual costará S/.14.90.</td>
    <td colspan="1" valign="top">La aplicación cuenta con una versión gratuita y una versión de pago la cual tiene tarifas de acuerdo al consumo.</td>
    <td colspan="1" valign="top">La aplicación es totalmente gratuita.</td>
    <td colspan="1" valign="top">La aplicación cuenta con una versión gratuita y una versión de pago la cual varía de acuerdo a lo que busque el empleador.</td>
  </tr>
  <tr>
    <td colspan="2">Canales de distribución (Web y/o Móvil)</td>
    <td colspan="1" valign="top">Los canales de distribución son digitales, como La App Store y Google Play.</td>
    <td colspan="1" valign="top">Los canales de distribución son digitales, como La App Store y Google Play.</td>
    <td colspan="1" valign="top">Los canales de distribución son digitales, como La App Store y Google Play.</td>
    <td colspan="1" valign="top">Los canales de distribución son digitales, como La App Store y Google Play.</td>
  </tr>
  <tr>
    <td colspan="1" rowspan="5"><p>Análisis SWOT</p></td>
    <td colspan="6">Realice esto para su startup y sus competidores. Sus fortalezas deberían apoyar sus oportunidades y contribuir a lo que ustedes definen como su posible ventaja competitiva.</td>
  </tr>
  <tr>
    <td colspan="2">Fortalezas</td>
    <td colspan="1" valign="top">Variedad de trabajos temporales, seguimiento del estatus del trabajo, retroalimentación entre ambas partes y pago seguro para garantizar la satisfacción del empleador y trabajador.</td>
    <td colspan="1" valign="top">Amplia variedad de ofertas laborales en diferentes sectores y permite a los candidatos cargar su currículum para facilitar el reclutamiento.</td>
    <td colspan="1" valign="top">Cuenta con una comunidad activa de usuarios y empresas, fomentando la interacción y el networking.</td>
    <td colspan="1" valign="top">Ofrece opciones premium para empresas que buscan destacar sus ofertas laborales, generando ingresos adicionales. Herramientas avanzadas de reclutamiento.</td>
  </tr>
  <tr>
    <td colspan="2">Debilidades</td>
    <td colspan="1" valign="top">Inicialmente, no se podrá contar con comentarios de ninguna de las dos partes. Debido a que estamos iniciando desde cero.</td>
    <td colspan="1" valign="top">La falta de funciones avanzadas de filtrado y búsqueda podría dificultar la navegación para los usuarios que buscan ofertas específicas.</td>
    <td colspan="1" valign="top">La competencia con otras plataformas consolidadas podría dificultar la retención y adquisición de usuarios en un mercado saturado.</td>
    <td colspan="1" valign="top">La opción premium para empresas podría limitar la visibilidad de algunas ofertas laborales para las empresas que no pueden pagar por esta opción.</td>
  </tr>
  <tr>
    <td colspan="2">Oportunidades</td>
    <td colspan="1" valign="top">La creciente tendencia hacia trabajos temporales y flexibles podría impulsar la demanda de plataformas que se centran en este tipo de empleos.</td>
    <td colspan="1" valign="top">El desarrollo de alianzas estratégicas con empresas y universidades podría aumentar la diversidad de oportunidades laborales y atraer a más usuarios.</td>
    <td colspan="1" valign="top">El enfoque en mercados específicos de América Latina podría permitir una mayor profundización en áreas locales y satisfacer necesidades específicas.</td>
    <td colspan="1" valign="top">La opción de diversificar su gama de servicios para incluir capacitación y desarrollo profesional podría generar ingresos adicionales.</td>
  </tr>
  <tr>
    <td colspan="2">Amenazas</td>
    <td colspan="1" valign="top">Dificultades para establecer relaciones sólidas y de confianza entre los usuarios y los empleadores.</td>
    <td colspan="1" valign="top">La entrada de nuevos competidores y el aumento de la competencia en el mercado de búsqueda de empleo podría reducir su participación de mercado.</td>
    <td colspan="1" valign="top">La competencia de otras plataformas de búsqueda de empleo y la evolución de las tendencias de búsqueda de empleo podrían disminuir la relevancia de Laborum en el mercado.</td>
    <td colspan="1" valign="top">El escaso número de funciones hace que muchas personas opten por buscar otra aplicación más completa.</td>
  </tr>
</table>

### 2.1.2. Estrategias y tácticas frente a competidores

Usaremos estrategias y tácticas que aprovechen nuestras fortalezas y oportunidades y poder sacar ventaja de las debilidades y amenazas de nuestros competidores. Por lo mismo nuestras estrategias son las siguientes:

- Nos aseguraremos de fortaleces nuestra interfaz incluyendo búsqueda intuitiva, perfiles detallados y retroalimentación transparente. Lo que nos permitirá sobresalir ante nuestra competencia con satisfacción al usuario y usabilidad.
- Usaremos datos del usuario para ofrecer recomendaciones de trabajos relevantes para los futuros trabajadores. Además, facilitaremos la búsqueda de personal al empleador preseleccionando a personas que más se acerquen al perfil que buscan.
- Garantizaremos transparencia al momento de realizar los pago, los cuales se retendrán hasta dar concluido el trabajo y se haya verificado el estatus del mismo por ambas partes.
- Fomentaremos la retroalimentación mutua y usaremos esos datos con el fin de mejorar nuestra plataforma para así cumplir con las necesidades del usuario.
- Invertiremos en campañas de marketing en línea dirigida a públicos específicos, aprovechando las redes sociales.

## 2.2. Entrevistas
### 2.2.1. Diseño de entrevistas

En esta sección se han definido una cierta cantidad de preguntas para nuestro segmento objetivo, con la finalidad de obtener información cualitativa como opiniones o descripciones. Esta información nos será de gran ayuda en el desarrollo de nuestra solución.

**Preguntas demográficas:**

1. ¿Cómo te llamas?
2. ¿Cuántos años tienes?
3. ¿Lugar de residencia?
4. ¿A qué te dedicas actualmente?

**Preguntas sobre personalidad**

1. ¿Te consideras una persona extrovertida o introvertida? ¿Por qué?

**Preguntas Segmento 1: Chambeador** 

1. ¿Has tenido la necesidad de buscar algún trabajo?
    1. ¿Presentaste dificultades al encontrar trabajo? ¿Cuáles?
2. ¿Tuviste algún problema con el empleador?
3. ¿Qué actividades podrías desempeñar para un empleador?
4. ¿Cómo estableces la tarifa por dichas actividades?
5. ¿Cuál es tu opinión sobre la importancia de adquirir experiencia laboral a una edad temprana?
6. ¿Alguna vez has considerado trabajar en empleos temporales o por proyecto? ¿Por qué sí o por qué no?
7. ¿Qué obstáculos crees que podrías enfrentar al buscar trabajo a tu edad y cómo piensas superarlos?
8. ¿Cómo equilibras tus estudios y otras actividades con la posibilidad de trabajar de manera temporal?
9. ¿Qué aspectos valoras más al considerar un trabajo temporal? ¿La flexibilidad, el tipo de trabajo, el salario?
10. ¿Qué te motivaría a aceptar un trabajo eventual y qué te haría rechazarlo?

**Segmento 2: Empleador** 

1. ¿ Qué consideras importante al momento de contratar a alguien?
2. ¿ Consideras que la experiencia previa es importante?
3. ¿Prefieren contratar a trabajadores especializados o están abiertos a considerar a aquellos sin experiencia previa?
4. ¿Cuáles son las cualidades o habilidades clave que buscas al contratar a un trabajador para un empleo eventual o proyecto?
5. ¿Qué factores influyen en tu decisión de contratar a alguien que carece de experiencia laboral pero muestra entusiasmo y potencial?
6. ¿Has tenido experiencias previas con trabajadores jóvenes o sin experiencia? ¿Cuáles fueron los aspectos positivos y los desafíos?
7. ¿Qué tan importante es la flexibilidad de horarios en los candidatos que consideras para empleos temporales?

**Sobre una posible app: Segmento 01**

1. ¿Te gustaría que una aplicación de búsqueda de empleo le ayudará a encontrar trabajos que se ajusten a sus habilidades y horarios?
2. ¿Cuáles serían las características más importantes para usted en una aplicación de búsqueda de empleo eventual (por ejemplo, facilidad de uso, variedad de oportunidades, retroalimentación de otros empleadores)?

**Sobre una posible app: Segmento 02** 

1. ¿Cómo le gustaría que una aplicación de búsqueda de trabajadores temporales le ayudará a encontrar candidatos que se ajusten a las necesidades de su proyecto?
2. ¿Cuáles serían las características más importantes para usted en una aplicación de búsqueda y contratación de trabajadores eventuales (por ejemplo, facilidad de uso, calidad de candidatos, retroalimentación de otros empleadores)?

**Explicación de ChambeaPe**

**ChambeaPe** es una aplicación que tiene como principal objetivo innovar en el ámbito laboral para abordar las limitaciones de los trabajos ocasionales o "cachuelos", como son comúnmente conocidos. Su enfoque central es proporcionar oportunidades de empleo temporal a una amplia variedad de usuarios, permitiéndoles asegurar su sustento económico y avanzar en términos financieros. Esta plataforma estará dotada de funcionalidades que posibilitarán a los solicitantes examinar su historial laboral previo y simplificarán la divulgación de requerimientos de personal especializado en tareas específicas. A través de esta iniciativa, nuestra aspiración es brindar respaldo a las numerosas personas que enfrentan cotidianamente los retos derivados del desempleo en nuestra nación.

**Para mejorar la idea del negocio**

1. ¿Qué te parece la idea de nuestro proyecto? ¿Te sería útil?
2. ¿Tienes sugerencias sobre posibles mejoras o características adicionales que podríamos integrar en nuestra aplicación?

### 2.2.2. Registro de entrevistas

**Entrevista 01**

Nombres: Leonardo Alfredo

Apellidos: Chunga Navarro

Edad: 23 años

Distrito: Bellavista

Evidencia de la reunión:
<div align=center>
    <img src="https://media.discordapp.net/attachments/1145421916413366426/1146326468977238097/1.jpg?width=1595&height=897" alt="Canvas"  width="90%"/>
</div>

Enlace de entrevista: [https://upcedupe-my.sharepoint.com/:v:/g/personal/u202120911_upc_edu_pe/Ef0y2ARRFH9OqL0vuz6ed9wB8Na7-7Vy2X6EMJzA87-fyw?e=jf0n4n&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZyIsInJlZmVycmFsQXBwUGxhdGZvcm0iOiJXZWIiLCJyZWZlcnJhbE1vZGUiOiJ2aWV3In0sInBsYXliYWNrT3B0aW9ucyI6eyJzdGFydFRpbWVJblNlY29uZHMiOjAuMTJ9fQ%3D%3D](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202120911_upc_edu_pe/Eb5VKDTmZiZMqj3rZeGiOOgBrBnyhTPc7Kg2Xu71NGpLMw?e=RbHF0n&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZyIsInJlZmVycmFsQXBwUGxhdGZvcm0iOiJXZWIiLCJyZWZlcnJhbE1vZGUiOiJ2aWV3In0sInBsYXliYWNrT3B0aW9ucyI6e319)

Inicio: 00:04

Fin: 05:03

Resumen de la entrevista:

Se entrevistó a Leonardo Chunga, un joven de 23 años, estudiante de ingeniería civil en la Universidad Privada del Norte. Respecto a su personalidad, se considera una persona extrovertida.
Al preguntarle sobre su experiencia buscando trabajo, él menciona que tuvo la necesidad de hacerlo en ciertas ocasiones pues necesitaba el dinero para la universidad. Además, tuvo malas experiencias con sus superiores en una empresa en la que trabajó, lo que lo motivó a renunciar.

Respecto a posibles empleos que él podría realizar menciona pasear perros, cuidar personas y dar clases particulares sobre las materias que domina. Comenta que las tarifas que establecería a las actividades mencionadas anteriormente dependerían del tipo de trabajo, cantidad de horas y horario.

Acerca de trabajar en un empleo temporal, considera que es una excelente opción para él y para todos los jóvenes que estudian y trabajan, ya que brinda flexibilidad con los horarios, a diferencia de cuando existe un contrato de por medio que establece horarios fijos.

Al mencionar sobre una posible aplicación, él desearía que los usuarios tuviesen la opción de publicar todos los trabajos que requieren para que de esta manera sea más sencilla la comunicación entre empleados y empleadores. Entre las características más importantes que considera debería tener esta app se encuentran la calificación de empleados y empleadores, la facilidad para encontrar empleos y un sistema de comunicación eficiente entre usuarios.

Por último, menciona que la aplicación le parece una idea muy interesante que recomendaría, a la cual le daría uso y que ayudaría a los jóvenes a ganar experiencia laboral a temprana edad, pues indica que esto es clave para vencer miedos y temores y aprender a lidiar con la presión que sienten muchos jóvenes en su primer contacto con este mundo.

**Entrevista 02**

Nombres: Viviana

Apellidos: Huamán Pinedo

Edad: 23 años

Distrito: San Miguel

Evidencia de la reunión:
<div align=center>
    <img src="https://media.discordapp.net/attachments/1145421916413366426/1146326469300211752/2.png?width=1595&height=897" alt="Canvas"  width="90%"/>
</div>


Enlace de entrevista: [https://upcedupe-my.sharepoint.com/:v:/g/personal/u202120911_upc_edu_pe/Ef0y2ARRFH9OqL0vuz6ed9wB8Na7-7Vy2X6EMJzA87-fyw?e=FIJndf&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZyIsInJlZmVycmFsQXBwUGxhdGZvcm0iOiJXZWIiLCJyZWZlcnJhbE1vZGUiOiJ2aWV3In0sInBsYXliYWNrT3B0aW9ucyI6eyJzdGFydFRpbWVJblNlY29uZHMiOjMwNC43NX19](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202120911_upc_edu_pe/Eb5VKDTmZiZMqj3rZeGiOOgBrBnyhTPc7Kg2Xu71NGpLMw?e=SnPQ93&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZyIsInJlZmVycmFsQXBwUGxhdGZvcm0iOiJXZWIiLCJyZWZlcnJhbE1vZGUiOiJ2aWV3In0sInBsYXliYWNrT3B0aW9ucyI6eyJzdGFydFRpbWVJblNlY29uZHMiOjMwNC4zOX19)

Inicio: 05:04

Fin: 09:25

Resumen de la entrevista:

Se entrevistó a Viviana Huamán, una joven de 23 años, estudiante de administración de negocios globales en la Universidad Ricardo Palma. Ella se considera introvertida al interactuar con nuevas personas y extrovertida con su familia y amigos cercanos.

Respecto a su experiencia buscando trabajo, ella menciona que tuvo dificultades para encontrar uno, pues la competencia era alta y los requisitos solicitados por los empleadores eran muy exigentes. Además, indica que una vez fue contratada tuvo problemas con la empleadora, pues esta era muy estricta con los protocolos del negocio y no tenía paciencia con los nuevos empleados.

En relación a los obstáculos con los que se podría enfrentar al trabajar a su edad, ella considera que el horario es uno de los principales problemas a los que se enfrentan los jóvenes pues muchas veces las clases en la universidad se realizan en las mañanas y en las noches, por lo que el tiempo libre para laborar es limitado.

Acerca de la posibilidad de trabajar en un empleo temporal, Viviana asegura que ha considerado dicha opción y está sumamente interesada. Además, indica que una de las características principales que valora de este tipo de trabajos es la flexibilidad ya que con su trabajo part-time actual no tiene mucha libertad en tema de horarios.

Por un lado, al mencionar sobre una posible aplicación, indica que desea que los empleadores no soliciten muchos requisitos a los jóvenes estudiantes y que brinden horarios flexibles. Por otro lado, entre las características más importantes con las que debería contar la app serían múltiples opciones de trabajos y un filtro de personas para evitar personas malintencionadas que puedan poner en peligro la integridad de los usuarios.

Por último, comenta que la aplicación le parece una buena idea que le ayudaría a ella y a otros jóvenes que necesitan dinero y que una característica que recomendaría añadir sería la posibilidad de adjuntar imágenes y videos a las calificaciones de los usuarios.

**Entrevista 03**

Nombres: Jessica

Apellidos: Alvarado

Edad: 27 años

Distrito: La Victoria

Evidencia de la reunión:
<div align=center>
    <img src="https://media.discordapp.net/attachments/1145421916413366426/1146300745029799976/jessica-alvarado.png?width=1105&height=552" alt="Canvas"  width="90%"/>
</div> 


Enlace de entrevista: [https://upcedupe-my.sharepoint.com/:v:/g/personal/u202120911_upc_edu_pe/Eb5VKDTmZiZMqj3rZeGiOOgBrBnyhTPc7Kg2Xu71NGpLMw?e=n2Jw6M&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZyIsInJlZmVycmFsQXBwUGxhdGZvcm0iOiJXZWIiLCJyZWZlcnJhbE1vZGUiOiJ2aWV3In0sInBsYXliYWNrT3B0aW9ucyI6eyJzdGFydFRpbWVJblNlY29uZHMiOjU2Ni4wN319](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202120911_upc_edu_pe/Eb5VKDTmZiZMqj3rZeGiOOgBrBnyhTPc7Kg2Xu71NGpLMw?e=n2Jw6M&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZyIsInJlZmVycmFsQXBwUGxhdGZvcm0iOiJXZWIiLCJyZWZlcnJhbE1vZGUiOiJ2aWV3In0sInBsYXliYWNrT3B0aW9ucyI6eyJzdGFydFRpbWVJblNlY29uZHMiOjU2Ni4wN319)

Inicio: 09:26

Fin: 14:24

Resumen de la entrevista:

Jessica es una pastelera que trabaja en una pastelería. Se describe a sí misma como extrovertida en ciertos círculos y reservada con personas a las que no conoce bien. Ha enfrentado dificultades al encontrar trabajo debido a su falta de experiencia y estudios, a menudo siendo rechazada por su edad y falta de experiencia.

Ha tenido desafíos en trabajos anteriores, como la inflexibilidad de horarios y la falta de reconocimiento por ser madre. También ha sido explotada en algunos trabajos, lo que la llevó a tomar acciones legales para defender sus derechos laborales.

Jessica valora la remuneración justa, la flexibilidad de horarios y la oportunidad de trabajar en proyectos pequeños. Ella tiene su propio emprendimiento en el área de la pastelería y valora la posibilidad de realizar proyectos adicionales para empresas conocidas.

Respecto a la adquisición de experiencia laboral en una edad temprana, opina que es importante en algunos casos, pero no es un requisito indispensable. Cree que la disposición para aprender y la dedicación son más cruciales.

Ha superado obstáculos adaptándose a diferentes trabajos y circunstancias. Jessica ve una aplicación como "ChambeaPe" como algo útil, ya que busca trabajos temporales y proyectos en diversas áreas, brindando una fuente de ingresos adicional y formalizando la relación entre empleadores y empleados temporales.

La idea de " ChambeaPe " le parece interesante y beneficiosa, especialmente por la seguridad de los pagos y la variedad de oportunidades laborales que ofrece. Sugiere reforzar la seguridad, ampliar las opciones de áreas y rubros, y permitir la contratación por días para eventos y trabajos más cortos.

**Entrevista 04**

Nombres: Leonardo Paul

Apellidos: López Huarcaya

Edad: 19 años

Distrito: San Miguel

Evidencia de la reunión:
<div align=center>
    <img src="https://media.discordapp.net/attachments/1145583761182965852/1146321049072451674/image.png?width=1547&height=690" alt="Canvas"  width="90%"/>
</div>  

Enlace de entrevista: [https://upcedupe-my.sharepoint.com/:v:/g/personal/u202120911_upc_edu_pe/Eb5VKDTmZiZMqj3rZeGiOOgBrBnyhTPc7Kg2Xu71NGpLMw?e=B5XpB0&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZyIsInJlZmVycmFsQXBwUGxhdGZvcm0iOiJXZWIiLCJyZWZlcnJhbE1vZGUiOiJ2aWV3In0sInBsYXliYWNrT3B0aW9ucyI6eyJzdGFydFRpbWVJblNlY29uZHMiOjg2NS43fX0%3D](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202120911_upc_edu_pe/Eb5VKDTmZiZMqj3rZeGiOOgBrBnyhTPc7Kg2Xu71NGpLMw?e=B5XpB0&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZyIsInJlZmVycmFsQXBwUGxhdGZvcm0iOiJXZWIiLCJyZWZlcnJhbE1vZGUiOiJ2aWV3In0sInBsYXliYWNrT3B0aW9ucyI6eyJzdGFydFRpbWVJblNlY29uZHMiOjg2NS43fX0%3D)

Inicio: 14:24

Fin: 19:11

Resumen de la entrevista:

Leonardo es una persona carismática pero seria a la vez, él nos comenta que al estar estudiando una carrera relacionada con la programación quisiera buscar empleos que le puedan dar pequeños ingresos y así él pueda ayudarse económicamente y a su vez que consigue experiencia con lo que le gusta hacer. También le preguntamos en qué servicios prestaría nos dijo que él quiere ofrecer servicios como pen tester junior o el otro servicio que brindaría es de dar clases particulares a personas que quieren empezar con todo esto de la programación.

En la entrevista también hizo un enfoque a que sus clases como estudiante universitario muchas de las veces no le permitían buscar empleos puesto que estos no son muy flexibles con lo que respecta a horarios.

Al momento de hacerle la propuesta de la creación de ChambeaPe dijo que la idea en concreta le gustaba, y nos explica que si puede buscar a personas que le brinden trabajos con flexibilidad de horarios y a su vez acepten a personas con poca experiencia, es una ayuda para las personas que están buscando empleo por primera vez y no tienen experiencia. Para finalizar las entrevistas le preguntamos cuales eran las sugerencias que nos planteaba y pues él se enfocó mucho en la parte de los contratos chambeador-empleador y en los filtros de búsqueda de los chambeadores.

### Segmento 02

**Entrevista 01**

Nombres: Claudia

Apellidos: Ríos Piña

Edad: 22 años

Distrito:

Evidencia de la reunión:
<div align=center>
    <img src="https://media.discordapp.net/attachments/1145421916413366426/1146300745335971850/claudia-rios.png?width=1105&height=521" alt="Canvas"  width="90%"/>
</div> 

Enlace de entrevista: [https://upcedupe-my.sharepoint.com/:v:/g/personal/u202120911_upc_edu_pe/Ef0y2ARRFH9OqL0vuz6ed9wB8Na7-7Vy2X6EMJzA87-fyw?e=om1glJ&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZyIsInJlZmVycmFsQXBwUGxhdGZvcm0iOiJXZWIiLCJyZWZlcnJhbE1vZGUiOiJ2aWV3In0sInBsYXliYWNrT3B0aW9ucyI6eyJzdGFydFRpbWVJblNlY29uZHMiOjE0NDIuMjF9fQ%3D%3D](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202120911_upc_edu_pe/Eb5VKDTmZiZMqj3rZeGiOOgBrBnyhTPc7Kg2Xu71NGpLMw?e=GRf4ra&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZyIsInJlZmVycmFsQXBwUGxhdGZvcm0iOiJXZWIiLCJyZWZlcnJhbE1vZGUiOiJ2aWV3In0sInBsYXliYWNrT3B0aW9ucyI6eyJzdGFydFRpbWVJblNlY29uZHMiOjExNTIuMjR9fQ%3D%3D) 

Inicio: 19:11

Fin: 24:04

Resumen de la entrevista:

Claudia Ríos, de 22 años, es estudiante de laboratorio clínico y tiene experiencia en repostería y panadería. Ella se considera una persona extrovertida en su círculo social, pero puede ser introvertida en situaciones nuevas. Valora las decisiones emocionales y busca personas comprometidas al contratar.

Claudia tiene su propio emprendimiento llamado "Merenguito", que comenzó en 2021. Comenzó vendiendo postres como alfajores y mini brownies y se ha expandido a tortas y pasteles más personalizados.

Ella considera que la experiencia es importante pero no indispensable porque también entiende que la única oportunidad de aprender es haciendo. No tendría ningún problema a personas sin experiencia como apoyo en su emprendimiento, básicamente para fechas festivas. Cree que el compromiso de una persona sin experiencia y sus ganas de salir adelante son fundamental para que los pueda tomar en cuenta para un empleo por proyecto.

En cuanto a la aplicación ChambeaPe, ve su utilidad en encontrar personal confiable y brindar oportunidades a personas inexpertas. Valora la flexibilidad en los horarios y la adaptabilidad de los candidatos. Busca características como la facilidad de uso, retroalimentación y categorización de candidatos.

Claudia tiene experiencia con otras aplicaciones de búsqueda de trabajadores temporales, habiendo utilizado "CompuTrabajo". Sin embargo, ha encontrado que algunos candidatos no son realmente especializados, lo que ha sido un desafío.

En resumen, ve en ChambeaPe una oportunidad de mejorar la búsqueda de trabajadores temporales confiables y brindar oportunidades a personas sin experiencia. Valora la facilidad de uso, la retroalimentación y la verificación de certificados como características clave en la aplicación. Estaría dispuesta a invertir en una aplicación de calidad que le ayude en su emprendimiento y recomendaría la aplicación a otros colegas.

Resumen de la entrevista:

**Entrevista 02**

Nombres: José Carlos Isaac

Apellidos: Ampudia Flores 

Edad: 19 

Distrito: Monterrico

Evidencia de la reunión:
<div align=center>
    <img src="https://media.discordapp.net/attachments/1145583761182965852/1146321191523586149/image.png?width=1562&height=550" alt="Canvas"  width="90%"/>
</div>


Enlace de entrevista: [https://upcedupe-my.sharepoint.com/:v:/g/personal/u202120911_upc_edu_pe/Eb5VKDTmZiZMqj3rZeGiOOgBrBnyhTPc7Kg2Xu71NGpLMw?e=e9IaF6&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZyIsInJlZmVycmFsQXBwUGxhdGZvcm0iOiJXZWIiLCJyZWZlcnJhbE1vZGUiOiJ2aWV3In0sInBsYXliYWNrT3B0aW9ucyI6eyJzdGFydFRpbWVJblNlY29uZHMiOjE0NDQuNDN9fQ%3D%3D](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202120911_upc_edu_pe/Eb5VKDTmZiZMqj3rZeGiOOgBrBnyhTPc7Kg2Xu71NGpLMw?e=e9IaF6&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZyIsInJlZmVycmFsQXBwUGxhdGZvcm0iOiJXZWIiLCJyZWZlcnJhbE1vZGUiOiJ2aWV3In0sInBsYXliYWNrT3B0aW9ucyI6eyJzdGFydFRpbWVJblNlY29uZHMiOjE0NDQuNDN9fQ%3D%3D)

Inicio: 24:04

Fin:  28:54

Resumen de la entrevista:

La entrevista con Isaac comienza porque momentos previos a la entrevista me comunicó que tenía problemas al momento de contratar a personas para que realicen trabajos que él requería, mientras la entrevista se realizaba nos pudo hablar sobre el problema que es encontrar a personas de confianza, pusimos el ejemplo de que siempre busca a alguien para que pasee a sus perros.

También nos menciona que las personas que busca para contratar tienen que estar cualificados para el trabajo y si se pudiera, deberían de tener referencias positivas. 

Al momento de plantearle la propuesta de la app “ChambeaPe” nos dio a conocer su aprobación ya que a él le gusta la idea de que existan personas que postulen al trabajo que publica y así él poder examinar a dichos postulantes para que al final se pueda elegir a uno.

El feedback que nos da para poder ejercer como startup conjuntamente con ChambeaPe es que la app no se parezca mucho a plataformas existentes como lo puede ser LinkedIn y nos centremos en ayudar a encontrar trabajo al que más lo necesite.

**Entrevista 03**

Nombres: Cristian Andrés

Apellidos: Quito Igreda

Edad: 19

Distrito: Los olivos

Evidencia de la reunión:
<div align=center>
    <img src="https://media.discordapp.net/attachments/1145421916413366426/1146300081658658836/image.png?width=1187&height=421" alt="Canvas"  width="90%"/>
</div> 

Enlace de entrevista: [https://upcedupe-my.sharepoint.com/:v:/g/personal/u202120911_upc_edu_pe/Eb5VKDTmZiZMqj3rZeGiOOgBrBnyhTPc7Kg2Xu71NGpLMw?e=qs94Bh&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZyIsInJlZmVycmFsQXBwUGxhdGZvcm0iOiJXZWIiLCJyZWZlcnJhbE1vZGUiOiJ2aWV3In0sInBsYXliYWNrT3B0aW9ucyI6eyJzdGFydFRpbWVJblNlY29uZHMiOjE3MzQuNzV9fQ%3D%3D](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202120911_upc_edu_pe/Eb5VKDTmZiZMqj3rZeGiOOgBrBnyhTPc7Kg2Xu71NGpLMw?e=qs94Bh&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZyIsInJlZmVycmFsQXBwUGxhdGZvcm0iOiJXZWIiLCJyZWZlcnJhbE1vZGUiOiJ2aWV3In0sInBsYXliYWNrT3B0aW9ucyI6eyJzdGFydFRpbWVJblNlY29uZHMiOjE3MzQuNzV9fQ%3D%3D)

Inicio: 28:54

Fin: 32:23

Resumen de la entrevista: 

En la entrevista, Cristian compartió su enfoque al seleccionar candidatos para contratar, destacando su atención a factores como reseñas, calificaciones, comentarios y, especialmente, el precio. Además, considera que la experiencia previa es un factor fundamental en su proceso de elección. Mencionó experiencias desfavorables con aplicaciones en las que los profesionales más solicitados a menudo se encontraban ocupados. Sin embargo, Cristian expresó su disposición a considerar candidatos sin experiencia previa, siempre y cuando cuenten con un sólido currículum.

Cristian también mencionó que valora la idea de una aplicación que ofrezca filtrado de alta calidad y personalización. En particular, le gustaría tener acceso a información sobre la disponibilidad de los trabajadores, así como a un sistema de calificación y una función de chat integrada.

**Entrevista 04**

Nombres: Gabriel

Apellidos: Careño

Edad: 20

Distrito: San Borja

Evidencia de la reunión:
<div align=center>
    <img src="https://media.discordapp.net/attachments/1145421916413366426/1146300156321472593/image.png?width=1170&height=381" alt="Canvas"  width="90%"/>
</div>  


Enlace de entrevista: [https://upcedupe-my.sharepoint.com/:v:/g/personal/u202120911_upc_edu_pe/Eb5VKDTmZiZMqj3rZeGiOOgBrBnyhTPc7Kg2Xu71NGpLMw?e=H3kTGJ&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZyIsInJlZmVycmFsQXBwUGxhdGZvcm0iOiJXZWIiLCJyZWZlcnJhbE1vZGUiOiJ2aWV3In0sInBsYXliYWNrT3B0aW9ucyI6eyJzdGFydFRpbWVJblNlY29uZHMiOjE5NDMuMjl9fQ%3D%3D](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202120911_upc_edu_pe/Eb5VKDTmZiZMqj3rZeGiOOgBrBnyhTPc7Kg2Xu71NGpLMw?e=H3kTGJ&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZyIsInJlZmVycmFsQXBwUGxhdGZvcm0iOiJXZWIiLCJyZWZlcnJhbE1vZGUiOiJ2aWV3In0sInBsYXliYWNrT3B0aW9ucyI6eyJzdGFydFRpbWVJblNlY29uZHMiOjE5NDMuMjl9fQ%3D%3D)

Inicio: 32:23

Fin: 36:50

Resumen de la entrevista:

En la entrevista, Gabriel compartió su enfoque de contratación, centrado principalmente en la evaluación de la carta de presentación del candidato. Destacó la importancia de la experiencia previa, ya que considera que brinda un conocimiento fundamental en el ámbito laboral correspondiente. Gabriel subrayó que busca habilidades de organización y atención en los trabajadores.

En cuanto a sus preferencias para una aplicación, Gabriel manifestó su deseo de poder visualizar y ordenar los detalles de los trabajadores, incluyendo su experiencia en el campo y certificaciones. Además, expresó interés en contar con una función de filtrado que le permita encontrar al candidato adecuado para cada posición.

### 2.2.3. Análisis de entrevistas
**Segmento 1: Chambeador de 18 a 30 años**

Las entrevistas con los participantes reflejan diversas perspectivas sobre el empleo, la contratación y el potencial de la aplicación "ChambeaPe". Los entrevistados reconocen su capacidad para proporcionar oportunidades flexibles a jóvenes sin experiencia laboral. Se resaltan características como la evaluación de empleados y empleadores, la usabilidad y una comunicación eficiente entre las partes. Además, consideran la aplicación como una vía para adquirir experiencia temprana y diversificar ingresos. También se sugiere fortalecer la seguridad, ampliar las opciones de trabajo y establecer contratos claros entre empleados temporales y empleadores.

En conjunto, estas entrevistas subrayan la importancia de la flexibilidad, la experiencia temprana y la comunicación efectiva en la búsqueda y realización de empleos temporales, mientras destacan tanto las ventajas como las áreas de mejora potencial de la aplicación "ChambeaPe".

**Segmento 2: Empleador de 18 a 50 años**

En las entrevistas, se revelan diversas perspectivas sobre la contratación y la utilidad de la aplicación "ChambeaPe". 

En general, los participantes valoran la experiencia laboral, pero también reconocen la relevancia del compromiso y la disposición para aprender. Varios consideran la aplicación como una manera de mejorar la búsqueda de trabajadores temporales fiables y brindar oportunidades a individuos sin experiencia. Destacan la facilidad de uso, la retroalimentación y la adaptabilidad como características clave. Además, se subraya la importancia de encontrar personas confiables y cualificadas para los puestos. Algunos entrevistados también expresan la necesidad de características de filtrado y personalización en la aplicación para optimizar el proceso de selección de candidatos adecuados. En resumen, estas entrevistas reflejan la variedad de enfoques en la contratación y la disposición a utilizar herramientas como "ChambeaPe" para mejorar este proceso.
## 2.3. Needfinding
### 2.3.1. User Personas

**Segmento 1**

<div align=center>
    <img src="https://cdn.discordapp.com/attachments/1145583761182965852/1145926601859674152/Luis_Perez_1.png" alt="Segmento 1 user persona"  width="90%"/>
</div>

</br>

**Segmento 2**

<div align=center>
    <img src="https://cdn.discordapp.com/attachments/1145583761182965852/1145926636429131796/Jose_Dias.png" alt="Segmento 2 user persona"  width="90%"/>
</div>

### 2.3.2. User Task Matrix

<table align="center" border="1" width="90%" style="text-align:center;">
    <tr>
        <td></td>
        <td colspan=2>
            <b>User Persona</b>
        </td>
    </tr>
    <tr>
        <td></td>
        <td colspan=2>
            <b>Luis Perez</b> </br>Segmento Objetivo 01 (Chambeador entre 18 a 30 años)
        </td>
    </tr>
    <tr>
        <td>
            <b>Task</b>
        </td>
        <td>
            <b>Frequency</b>
        </td>
        <td>
            <b>Importance</b>
        </td>
    </tr>
    <tr>
        <td>
            Postular a trabajos
        </td>
        <td>
            High
        </td>
        <td>
            High
        </td>
    </tr>
    <tr>
        <td>
            Editar su perfil de chambeador
        </td>
        <td>
            Low
        </td>
        <td>
            Medium
        </td>
    </tr>
    <tr>
        <td>
            Agregar certifaciones o  </br> capacitaciones a su perfil
        </td>
        <td>
            Medium
        </td>
        <td>
            High
        </td>
    </tr>
    <tr>
        <td>
            Coordinar con el empleador
        </td>
        <td>
            High
        </td>
        <td>
            High
        </td>
    </tr>
    <tr>
        <td>
            Cumplir con el trabajo aceptado
        </td>
        <td>
            High
        </td>
        <td>
            High
        </td>
    </tr>
    <tr>
        <td>
            Informar sobre algun percance </br> que le impida cumplir con el trabajo
        </td>
        <td>
            Low
        </td>
        <td>
            High
        </td>
    </tr>
</table>

</br></br>

<table align="center" border="1" width="90%" style="text-align:center;">
    <tr>
        <td></td>
        <td colspan=2>
            <b>User Persona</b>
        </td>
    </tr>
    <tr>
        <td></td>
        <td colspan=2>
            <b>José Días</b> </br>Segmento Objetivo 02 (Empleador entre 18 a 50 años)
        </td>
    </tr>
    <tr>
        <td>
            <b>Task</b>
        </td>
        <td>
            <b>Frequency</b>
        </td>
        <td>
            <b>Importance</b>
        </td>
    </tr>
    <tr>
        <td>
            Crear una oferta de trabajo
        </td>
        <td>
            Medium
        </td>
        <td>
            High
        </td>
    </tr>
    <tr>
        <td>
            Seleccionar un chambeador
        </td>
        <td>
            Medium
        </td>
        <td>
            High
        </td>
    </tr>
    <tr>
        <td>
            Coordinar con el chambeador
        </td>
        <td>
            Medium
        </td>
        <td>
            High
        </td>
    </tr>
    <tr>
        <td>
            Cumplir la remuneración </br> acordada con el chambeador
        </td>
        <td>
            High
        </td>
        <td>
            High
        </td>
    </tr>
        <tr>
        <td>
            Avisar al chambeador si el </br> trabajo se suspende
        </td>
        <td>
            Low
        </td>
        <td>
            High
        </td>
    </tr>
</table>

### 2.3.3. User Journey Mapping

**Segmento 1**

<div align=center>
    <img src="https://cdn.discordapp.com/attachments/1145421916413366426/1147730437419061278/User_Journey_Map.png" alt="Segmento 1 journey map"  width="90%"/>
</div>

</br>

**Segmento 2**

<div align=center>
    <img src="https://cdn.discordapp.com/attachments/1145421916413366426/1147730458977775776/User_Journey_Map_2.png" alt="Segmento 2 journey map"  width="90%"/>
</div>

### 2.3.4. Empathy Mapping

**Segmento 1**

<div align=center>
    <img src="https://cdn.discordapp.com/attachments/1145421916413366426/1147730477780836474/Luis_Perez.png" alt="Segmento 1 empathy map"  width="90%"/>
</div>

</br>

**Segmento 2**

<div align=center>
    <img src="https://cdn.discordapp.com/attachments/1145421916413366426/1147730495849889925/Jose_Dias.png" alt="Segmento 2 empathy map"  width="90%"/>
</div>

### 2.3.5. As-is Scenario Mapping

<div align=center>
    <img src="https://media.discordapp.net/attachments/1145583761182965852/1146694430343036948/AS-IS_Empleador.png?width=1920&height=810" alt="As-Is(Empleador)"  width="90%"/>
</div>
</br>
<div align=center>
    <img src="https://media.discordapp.net/attachments/1145583761182965852/1146694430108176494/AS-IS_Chambeador.png?width=1840&height=896" alt="As-Is(Chambeador)"  width="90%"/>
</div>

</br></br>

# Capítulo III: Requirements Specification
## 3.1. To-Be Scenario Mapping

<div align=center>
    <img src="https://media.discordapp.net/attachments/1145583761182965852/1146694429860708392/TO-BE_Empleador.png?width=1920&height=812" alt="To-Be(Empleador)"  width="90%"/>
</div>
<br>
<div align=center>
    <img src="https://media.discordapp.net/attachments/1145583761182965852/1146694429625810964/TO-BE_Chambeador.png?width=1842&height=897" alt="To-Be(Chambeador)"  width="90%"/>
</div>

## 3.2. User Stories

<table align="center"     border="1" width="90%" style="text-align:center;">
    <tr align="left">
        <td colspan=2>
            <b>Épica</b>
        </td>
        <td colspan=2>
            Acceso a la cuenta
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>ID-HU</b>
        </td>
        <td>
            01
        </td>
        <td>
            <b>Owner</b>
        </td>
        <td>
            Diego Esquivel
        </td>
    </tr>
        <tr align="left">
        <td colspan=2>
            <b>Título HU</b>
        </td>
        <td colspan=2>
            Iniciar sesión
        </td>
    </tr>
    <tr align="left">
        <td colspan=4>
            <b>Descripción:</b></br>
            <b>Como</b>  usuario, <b>quiero</b> iniciar sesión con mi correo y contraseña <b>para</b> un acceso seguro.
        </td>
    </tr>
    <tr align="left">
        <td colspan=4>
            <b>Criterio de Aceptación:</b></br>
            <b>Scenario 01:</b> Inicio de sesión exitoso</br>
            <b>Dado</b> que el usuario ya se encuentra registrado en la plataforma </br>
            <b>Cuando</b> ingresa su respectivo correo y contraseña </br>
            <b>Entonces</b> el sistema permitirá al usuario iniciar sesión correctamente en la plataforma.</br> </br>
            <b>Scenario 02:</b> Inicio de sesión fallido </br>
            <b>Dado</b> que el usuario ya se encuentra registrado en la plataforma</br>
            <b>Cuando</b> ingresa un correo o contraseña incorrecta</br>
            <b>Entonces</b> el sistema no permitirá al usuario iniciar sesión </br>
            <b>Y</b> se mostrará un mensaje de error indicando que las creedenciales son incorrectas.   
        </td>
    </tr>
    </tr>
</table>
</br>
<table align="center"     border="1" width="90%" style="text-align:center;">
    <tr align="left">
        <td colspan=2>
            <b>Épica</b>
        </td>
        <td colspan=2>
            Acceso a la cuenta
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>ID-HU</b>
        </td>
        <td>
            02
        </td>
        <td>
            <b>Owner</b>
        </td>
        <td>
            Diego Esquivel
        </td>
    </tr>
        <tr align="left">
        <td colspan=2>
            <b>Título HU</b>
        </td>
        <td colspan=2>
            Registrar con correo
        </td>
    </tr>
    <tr align="left">
        <td colspan=4>
            <b>Descripción:</b></br>
            <b>Como</b> usuario <b>quiero</b> poder registrarme con mi correo a la plataforma <b>para</b> agilizar el proceso de registro.
        </td>
    </tr>
    <tr align="left">
        <td colspan=4>
            <b>Criterio de Aceptación:</b></br>
            <b>Scenario 01:</b> Registro exitoso</br>
            <b>Dado</b> que el cliente quiere registrarse en la plataforma </br>
            <b>Cuando</b> el cliente ingresa un correo electrónico válido y una contraseña segura </br>
            <b>Entonces </b>el sistema procesara el registro </br>
            <b>Y</b> creará una cuenta asociada con ese correo electrónico. </br> </br>
            <b>Scenario 02:</b> Registro fallido </br>
            <b>Dado</b> que el cliente quiere registrarse en la plataforma </br>
            <b>Cuando</b> el cliente ingresa un correo electrónico que ya esta en uso </br>
            <b>Entonces</b> el sistema no permitirá que el usuario complete el registro</br>
            <b>Y</b> mostrará un mensaje de error indicando que ese correo ya ha sido registrado.  
        </td>
    </tr>
    </tr>
</table>
<table align="center"     border="1" width="90%" style="text-align:center;">
    <tr align="left">
        <td colspan=2>
            <b>Épica</b>
        </td>
        <td colspan=2>
            Acceso a la cuenta
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>ID-HU</b>
        </td>
        <td>
            03
        </td>
        <td>
            <b>Owner</b>
        </td>
        <td>
            Diego Esquivel
        </td>
    </tr>
        <tr align="left">
        <td colspan=2>
            <b>Título HU</b>
        </td>
        <td colspan=2>
            Manejar información del perfil
        </td>
    </tr>
    <tr align="left">
        <td colspan=4>
            <b>Descripción:</b></br>
            <b>Como</b> usuario, <b>quiero</b> manejar la información de mi perfil <b>para</b> mantener mis datos personales actualizados.
        </td>
    </tr>
    <tr align="left">
        <td colspan=4>
            <b>Criterio de Aceptación:</b></br>
            <b>Scenario 01:</b> Actualización de datos exitosa</br>
            <b>Dado</b> que el usuario ya se encuentra dentro de la plataforma </br>
            <b>Y</b> desea actualizar la información de su perfil </br>
            <b>Cuando</b> el usuario modifica sus datos personales y guarda los cambios </br>
            <b>Entonces</b> el sistema actualizará los detalles del perfil del usuario </br> </br>
            <b>Scenario 02:</b> Visualización de información </br> 
            <b>Dado</b> que el usuario ya se encuentra dentro de la plataforma </br>
            <b>Y</b> desea visualizar la información de su perfil </br>
            <b>Cuando</b> el usuario ingrese a la sección de perfil de la plataforma </br> 
            <b>Entonces</b> el sistema mostrará todos los datos de la información personal del usuario.             
        </td>
    </tr>
    </tr>
</table>
<table align="center"     border="1" width="90%" style="text-align:center;">
    <tr align="left">
        <td colspan=2>
            <b>Épica</b>
        </td>
        <td colspan=2>
            Pasarela de Pago
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>ID-HU</b>
        </td>
        <td>
            04
        </td>
        <td>
            <b>Owner</b>
        </td>
        <td>
            Diego Esquivel
        </td>
    </tr>
        <tr align="left">
        <td colspan=2>
            <b>Título HU</b>
        </td>
        <td colspan=2>
            Mejorar a cuenta premium
        </td>
    </tr>
    <tr align="left">
        <td colspan=4>
            <b>Descripción:</b></br>
            <b>Como</b> usuario, <b>quiero</b> mejorar mi cuenta a premium con diferentes métodos de pagos <b>para</b> obtener mejoras en mi cuenta.
        </td>
    </tr>
    <tr align="left">
        <td colspan=4>
           <b>Criterio de Aceptación:</b></br>
            <b>Scenario 01:</b> Actualización a cuenta premium exitosa</br>
            <b>Dado</b> que el usuario se encuentra con una cuenta free </br>
            <b>Y</b> desea ascender su estado a premium </br>
            <b>Cuando</b> el usuario seleccione la opción de mejorar su cuenta a premium </br>
            <b>Y</b> seleccione su método de pago </br>
            <b>Y</b> realize la respectiva transacción </br>
            <b>Entonces</b> el sistema concederá al usuario el estado premium</br>
            <b>Y</b> podrá acceder a las funciones adicionales que ofrece. </br> </br>
            <b>Scenario 02:</b> Método de pago inválido </br>
            <b>Dado</b> que el usuario se encuentra con una cuenta free </br>
            <b>Y</b> desea ascender su estado a premium </br>
            <b>Cuando</b> el usuario seleccione la opción de mejorar su cuenta a premium </br>
            <b>Y</b> seleccione método de pago que no sea válido </br>
            <b>Entonces</b> el sistema no permitirá al usuario que complete la transacción </br>
            <b>Y</b> mostrará un mensaje de error indicando que el método de pago no es válido.          
        </td>
    </tr>
    </tr>
</table>
<table align="center"     border="1" width="90%" style="text-align:center;">
    <tr align="left">
        <td colspan=2>
            <b>Épica</b>
        </td>
        <td colspan=2>
            Pasarela de Pago
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>ID-HU</b>
        </td>
        <td>
            05
        </td>
        <td>
            <b>Owner</b>
        </td>
        <td>
            Diego Esquivel
        </td>
    </tr>
        <tr align="left">
        <td colspan=2>
            <b>Título HU</b>
        </td>
        <td colspan=2>
            Administrar tarjeta
        </td>
    </tr>
    <tr align="left">
        <td colspan=4>
            <b>Descripción:</b></br>
            <b>Como</b> usuario <b>quiero</b> administrar los datos de mi tarjeta <b>para</b> permitirá realizar transacciones dentro de la aplicación.
        </td>
    </tr>
    <tr align="left">
        <td colspan=4>
            <b>Criterio de Aceptación:</b></br>
            <b>Scenario 01:</b> Agregar tarjeta</br>
            <b>Dado</b> que el usuario desea guardar su tarjeta en la plataforma para futuras transacciones </br>
            <b>Cuando</b> el usuario ingresa los detalles de su tarjeta</b> </br>
            <b>Y</b> le da a la opción guardar </br>
            <b>Entonces</b> el sistema agregará la tarjeta al perfil del usuario</br> 
            <b>Y</b> mostrará un mensaje de confirmación indicando que se agregó la tarjeta correctamente. </br> </br>
            <b>Scenario 02:</b> Eliminar tarjeta </br>
            <b>Dado</b> que el usuario desea eliminar su tarjeta de la plataforma </br>
            <b>Cuando</b> el usuario seleccione la opción de eliminar tarjeta </br>
            <b>Entonces</b> el sistema eliminará la tarjeta seleccionada </br>
            <b>Y</b> mostrará un mensaje de confirmacion indicando que la tarjeta ha sido eliminada correctamente.          
        </td>
    </tr>
    </tr>
</table>
<br>
<table align="center"     border="1" width="90%" style="text-align:center;">
    <tr align="left">
        <td colspan=2>
            <b>Épica</b>
        </td>
        <td colspan=2>
            Funcionalidades Premium
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>ID-HU</b>
        </td>
        <td>
            06
        </td>
        <td>
            <b>Owner</b>
        </td>
        <td>
            Diego Castro
        </td>
    </tr>
        <tr align="left">
        <td colspan=2>
            <b>Título HU</b>
        </td>
        <td colspan=2>
            Destacar perfil de chambeador
        </td>
    </tr>
    <tr align="left">
        <td colspan=4>
            <b>Descripción:</b></br>
            <b>Como</b> chambeador <b>quiero</b> contar con la opción de destacar mi perfil en
            los resultados de búsqueda <b>para</b> aumentar mis posibilidades de ser seleccionado.
        </td>
    </tr>
    <tr align="left">
        <td colspan=4>
            <b>Criterio de Aceptación:</b></br>
            <b>Scenario 01:</b> Perfil destacado correctamente</br>
            <b>Dado</b> que el usuario chambeador se encuentre en la sección de "Opciones" </br>
            <b> Y</b> tenga una suscripción premium activa  <br>
            <b>Cuando</b> active la opción "Destacar mi perfil"  </br>
            <b>Entonces</b> el perfil tendrá prioridad elevada en los resultados de búsqueda.<br>
            <br>
            <b>Scenario 02:</b> La opción de destacar perfil se encuentra desactivada</br>
            <b>Dado</b> que el usuario chambeador se encuentre en la sección de "Opciones" </br>
            <b> Y</b> tenga una suscripción premium activa  <br>
            <b>Cuando</b> la opción "Destacar mi perfil" se encuentre desactivada  </br>
            <b>Entonces</b> el perfil tendrá prioridad normal en los resultados de búsqueda.  
            <br>     
        </td>
    </tr>
    </tr>
</table>
<br>
<table align="center"     border="1" width="90%" style="text-align:center;">
    <tr align="left">
        <td colspan=2>
            <b>Épica</b>
        </td>
        <td colspan=2>
            Funcionalidades Premium
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>ID-HU</b>
        </td>
        <td>
            07
        </td>
        <td>
            <b>Owner</b>
        </td>
        <td>
            Diego Castro
        </td>
    </tr>
        <tr align="left">
        <td colspan=2>
            <b>Título HU</b>
        </td>
        <td colspan=2>
            Filtrar perfiles de chambeadores
        </td>
    </tr>
    <tr align="left">
        <td colspan=4>
            <b>Descripción:</b></br>
            <b>Como</b> empleador <b>quiero</b> tener la opción de filtrar perfiles
            <b>para</b> reducir el tiempo de selección.
        </td>
    </tr>
    <tr align="left">
        <td colspan=4>
            <b>Criterio de Aceptación:</b></br>
            <b>Scenario 01:</b> Filtro por calificación</br>
            <b>Dado</b> que el usuario empleador se encuentre en la sección de "Chambeadores" </br>
            <b> Y</b> tenga una suscripción premium activa  <br>
             <b> Y</b> seleccione la opción de "Ajustar filtros" <br>
            <b>Cuando</b> elija la calificación mínima  </br>
            <b>Entonces</b> se mostrarán solo los perfiles con la calificación mínima seleccionada.<br>
            <br>
            <b>Scenario 02:</b> Filtro por antigüedad</br>
            <b>Dado</b> que el usuario empleador se encuentre en la sección de "Chambeadores" </br>
            <b> Y</b> tenga una suscripción premium activa  <br>
             <b> Y</b> seleccione la opción de "Ajustar filtros" <br>
            <b>Cuando</b> elija la antigüedad mínima  </br>
            <b>Entonces</b> se mostrarán solo los perfiles con la antigüedad mínima seleccionada.<br>       
        </td>
    </tr>
    </tr>
</table>
<br>
<table align="center"     border="1" width="90%" style="text-align:center;">
    <tr align="left">
        <td colspan=2>
            <b>Épica</b>
        </td>
        <td colspan=2>
            Funcionalidades Premium
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>ID-HU</b>
        </td>
        <td>
            08
        </td>
        <td>
            <b>Owner</b>
        </td>
        <td>
            Diego Castro
        </td>
    </tr>
        <tr align="left">
        <td colspan=2>
            <b>Título HU</b>
        </td>
        <td colspan=2>
            Notificar trabajos recomendados
        </td>
    </tr>
    <tr align="left">
        <td colspan=4>
            <b>Descripción:</b></br>
            <b>Como</b> chambeador <b>quiero</b> recibir notificaciones sobre
            trabajos relevantes a mi perfil mediante la suscripción premium
            <b>para</b> postular más rápido.
        </td>
    </tr>
    <tr align="left">
        <td colspan=4>
            <b>Criterio de Aceptación:</b></br>
            <b>Scenario 01:</b> Preferencias de trabajo suministradas </br>
            <b>Dado</b> que el usuario chambeador tenga las notificaciones activadas </br>
            <b>Cuando</b> complete sus preferencias de trabajo </br>
            <b> Y</b> cuente con una suscripción premium activa  <br>
            <b>Entonces</b> se enviarán notificaciones periódicamente informándole sobre trabajos que le puedan interesar.<br>
            <br>
            <b>Scenario 02:</b> Preferencias de trabajo incompletas o no suministradas </br>
            <b>Dado</b> que el usuario chambeador tenga las notificaciones activadas </br>
            <b>Cuando</b> sus preferencias de trabajo estén incompletas</br>
            <b> Y</b> cuente con una suscripción premium activa  <br>
            <b>Entonces</b> el sistema le notificará que las preferencias deben ser completadas para recibir notificaciones de trabajos sugeridos<br>        
        </td>
    </tr>
    </tr>
</table>
<br>
<table align="center"     border="1" width="90%" style="text-align:center;">
    <tr align="left">
        <td colspan=2>
            <b>Épica</b>
        </td>
        <td colspan=2>
            Funcionalidades Premium
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>ID-HU</b>
        </td>
        <td>
            09
        </td>
        <td>
            <b>Owner</b>
        </td>
        <td>
            Diego Castro
        </td>
    </tr>
        <tr align="left">
        <td colspan=2>
            <b>Título HU</b>
        </td>
        <td colspan=2>
            Publicar anuncios como chambeador
        </td>
    </tr>
    <tr align="left">
        <td colspan=4>
            <b>Descripción:</b></br>
            <b>Como</b> chambeador <b>quiero</b> publicar un anuncio de trabajo
            <b>para</b> que me contacten más rápido.
        </td>
    </tr>
    <tr align="left">
        <td colspan=4>
            <b>Criterio de Aceptación:</b></br>
            <b>Scenario 01:</b> Publicación de anuncio de trabajo correcta</br>
            <b>Dado</b> que el usuario chambeador se encuentre en la sección de "Publicar" </br>
            <b> Y</b> tenga una suscripción premium activa  <br>
            <b>Cuando</b> llene los datos solicitados  </br>
            <b>Entonces</b> se publicará un anuncio de trabajo para que los empleadores puedan contactarse.<br>
            <br>
            <b>Scenario 02:</b> Datos incompletos en la publicación</br>
            <b>Dado</b> que el usuario chambeador se encuentre en la sección de "Publicar" </br>
            <b> Y</b> tenga una suscripción premium activa  <br>
            <b>Cuando</b> los datos estén incompletos  </br>
            <b>Entonces</b> se mostrará un mensaje de error indicando que faltan llenar datos en la publicación.<br>       
        </td>
    </tr>
    </tr>
</table>
<br>
<table align="center"     border="1" width="90%" style="text-align:center;">
    <tr align="left">
        <td colspan=2>
            <b>Épica</b>
        </td>
        <td colspan=2>
            Funcionalidades Premium
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>ID-HU</b>
        </td>
        <td>
            10
        </td>
        <td>
            <b>Owner</b>
        </td>
        <td>
            Diego Castro
        </td>
    </tr>
        <tr align="left">
        <td colspan=2>
            <b>Título HU</b>
        </td>
        <td colspan=2>
            Resaltar anuncios del empleador
        </td>
    </tr>
    <tr align="left">
        <td colspan=4>
            <b>Descripción:</b></br>
            <b>Como</b> empleador con membresía premium <b>quiero</b> que mis publicaciones tengan prioridad al ser publicadas
            <b>para</b> atraer la atención de trabajadores cualificados y entusiastas. 
        </td>
    </tr>
    <tr align="left">
        <td colspan=4>
            <b>Criterio de Aceptación:</b></br>
            <b>Scenario 01:</b> Anuncio resaltado correctamente</br>
            <b>Dado</b> que el usuario es un empleador con membresía premium </br>
            <b> Cuando</b> publique un anuncio en la plataforma <br>
            <b>Entonces</b> el anuncio obtendrá automáticamente prioridad<br>
            <b>Y</b> se mostrará en una sección destacada   
        </td>
    </tr>
    </tr>
</table>
</br>
<table align="center"     border="1" width="90%" style="text-align:center;">
    <tr align="left">
        <td colspan=2>
            <b>Épica</b>
        </td>
        <td colspan=2>
            Funcionalidades del Empleador
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>ID-HU</b>
        </td>
        <td>
            11
        </td>
        <td>
            <b>Owner</b>
        </td>
        <td>
            Steve Roger Castillo Robles
        </td>
    </tr>
    <tr align="left">
        <td colspan=2>
            <b>Título HU</b>
        </td>
        <td colspan=2>
            Registrar pago del Chambeador.
        </td>
    </tr>
    <tr align="left">
        <td colspan=4>
            <b>Descripción:</b></br>
            <b>Como</b> empleador <b>quiero</b> definir el pago con el chambeador <b>para</b> tener un registro en la aplicación.
        </td>
    </tr>
    <tr align="left">
        <td colspan=4>
            <b>Criterio de Aceptación:</b></br>
            <b>Scenario 01:</b> Definiendo el pago del chambeador seleccionado</br>
            <b>Dado</b> que el empleador necesita definir el costo su trabajo</br>
            <b>Cuando</b> haga contacto con el chambeador</br>
            <b>Entonces</b> podrán acordar un precio final del trabajo. </br></br>
            <b>Scenario 02:</b> Definiendo el pago del chambeador postulante</br>
            <b>Dado</b> que el empleador necesita definir el costo su trabajo</br>
            <b>Y</b> este revisó los perfiles de los postulantes </br>
            <b>Cuando</b> haga contacto con el chambeador elegido</br>
            <b>Y</b> se contacte con él</br>
            <b>Entonces</b> podrán acordar un precio final del trabajo.            
        </td>
    </tr>
</table>

</br>

<table align="center"     border="1" width="90%" style="text-align:center;">
    <tr align="left">
        <td colspan=2>
            <b>Épica</b>
        </td>
        <td colspan=2>
            Funcionalidades Empleador
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>ID-HU</b>
        </td>
        <td>
            12
        </td>
        <td>
            <b>Owner</b>
        </td>
        <td>
            Steve Roger Castillo Robles
        </td>
    </tr>
    <tr align="left">
        <td colspan=2>
            <b>Título HU</b>
        </td>
        <td colspan=2>
            Comunicar entre empleado y chambeador.
        </td>
    </tr>
    <tr align="left">
        <td colspan=4>
            <b>Descripción:</b></br>
            <b>Como</b> empleador <b>quiero</b> tener la opción definir las características del trabajo directamente con los chambeadores <b>para</b> mantener un medio de comunicación seguro.
        </td>
    </tr>
    <tr align="left">
        <td colspan=4>
            <b>Criterio de Aceptación:</b></br>
            <b>Scenario 01:</b> Definiendo las características del trabajo</br>
            <b>Dado</b> que el empleador se contactó con el chambeador</br>
            <b>Cuando</b> se inicie el chat de la app</br>
            <b>Entonces</b> podrán acordar las pautas y características del trabajo.            
        </td>
    </tr>
</table>

</br>

<table align="center"     border="1" width="90%" style="text-align:center;">
    <tr align="left">
        <td colspan=2>
            <b>Épica</b>
        </td>
        <td colspan=2>
            Funcionalidades Empleador
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>ID-HU</b>
        </td>
        <td>
            13
        </td>
        <td>
            <b>Owner</b>
        </td>
        <td>
            Steve Roger Castillo Robles
        </td>
    </tr>
    <tr align="left">
        <td colspan=2>
            <b>Título HU</b>
        </td>
        <td colspan=2>
            Reseñar empleador al chambeador.
        </td>
    </tr>
    <tr align="left">
        <td colspan=4>
            <b>Descripción:</b></br>
            <b>Como</b> empleador <b>quiero</b> quiero dejar una reseña sobre la experiencia con el chambeador después de que el trabajo se haya completado <b>para</b> calificar su servicio.
        </td>
    </tr>
    <tr align="left">
        <td colspan=4>
            <b>Criterio de Aceptación:</b></br>
            <b>Scenario 01:</b> Dejando una reseña al chambeador</br>
            <b>Dado</b> que el empleador quiere dejar una reseña</br>
            <b>Cuando</b> el chambeador terminó de hacer su trabajo</br>
            <b>Entonces</b> puntuaría en función de 0 – 5 el trabajo realizado </br>
            <b>Y</b> agregaría un comentario a la calificación.
        </td>
    </tr>
</table>

</br>

<table align="center"     border="1" width="90%" style="text-align:center;">
    <tr align="left">
        <td colspan=2>
            <b>Épica</b>
        </td>
        <td colspan=2>
            Funcionalidades Empleador
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>ID-HU</b>
        </td>
        <td>
            14
        </td>
        <td>
            <b>Owner</b>
        </td>
        <td>
            Steve Roger Castillo Robles
        </td>
    </tr>
    <tr align="left">
        <td colspan=2>
            <b>Título HU</b>
        </td>
        <td colspan=2>
            Visualizar perfiles de chambeadores
        </td>
    </tr>
    <tr align="left">
        <td colspan=4>
            <b>Descripción:</b></br>
            <b>Como</b> empleador <b>quiero</b> poder visualizar los perfiles de los chambeadores, <b>para</b> evaluar su experiencia y estilo de trabajo antes de contratarlos.
        </td>
    </tr>
    <tr align="left">
        <td colspan=4>
            <b>Criterio de Aceptación:</b></br>
            <b>Scenario 01:</b> Visualizando los perfiles de los chambeadores</br>
            <b>Dado</b> que el empleador está buscando a un chambeador</br>
            <b>Cuando</b>se necesita para contratar por un servicio</br>
            <b>Entonces</b> revisará los perfiles de los chambeadores para ver si están calificados para el trabajo.
        </td>
    </tr>
</table>

</br>

<table align="center"     border="1" width="90%" style="text-align:center;">
    <tr align="left">
        <td colspan=2>
            <b>Épica</b>
        </td>
        <td colspan=2>
            Funcionalidades Empleador
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>ID-HU</b>
        </td>
        <td>
            15
        </td>
        <td>
            <b>Owner</b>
        </td>
        <td>
            Steve Roger Castillo Robles
        </td>
    </tr>
    <tr align="left">
        <td colspan=2>
            <b>Título HU</b>
        </td>
        <td colspan=2>
            Manejar anuncios de trabajo.
        </td>
    </tr>
    <tr align="left">
        <td colspan=4>
            <b>Descripción:</b></br>
            <b>Como</b> empleador <b>quiero</b> manejar (crear- editar) mis anuncios de trabajo <b>para</b> buscar candidatos.
        </td>
    </tr>
    <tr align="left">
        <td colspan=4>
            <b>Criterio de Aceptación:</b></br>
            <b>Scenario 01:</b> Crear anuncios de trabajo</br>
            <b>Dado</b> que el empleador quiere crear sus anuncios</br>
            <b>Cuando</b> requiera un chambeador</br>
            <b>Entonces</b> podrá subir un anuncio a la app web
            </br></br>
            <b>Scenario 02:</b> Editar anuncios de trabajo</br>
            <b>Dado</b> que el empleador quiere editar sus anuncios</br>
            <b>Cuando</b> requiera cambiar algún parámetro o característica</br>
            <b>Entonces</b> podrá modificar su anuncio </br>
            <b>Y</b> se actualizará en la app web.
        </td>
    </tr>
</table>

<br>

<table align="center"     border="1" width="90%" style="text-align:center;">
    <tr align="left">
        <td colspan=2>
            <b>Épica</b>
        </td>
        <td colspan=2>
            Funcionalidades empleador
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>ID-HU</b>
        </td>
        <td>
            16
        </td>
        <td>
            <b>Owner</b>
        </td>
        <td>
            Jennifer Espinoza
        </td>
    </tr>
        <tr align="left">
        <td colspan=2>
            <b>Título HU</b>
        </td>
        <td colspan=2>
            Evaluar historial laboral de chambeadores
        </td>
    </tr>
    <tr align="left">
        <td colspan=4>
            <b>Descripción:</b></br>
            <p>
            <b>Como</b> empleador <b>quiero</b> tener acceso al historial laboral de los candidatos que se postulan en mis puestos de trabajo <b>para</b> evaluar y seleccionar a un futuro trabajador.
            </p>
        </td>
    </tr>
    <tr align="left">
        <td colspan=4>
            <b>Criterio de Aceptación:</b>
            </br>
            <b>Scenario 01: Acceso al perfil de los candidatos</b></br>
            <b>Dado </b>que el empleador selecciona uno de sus trabajos publicados
            </br>
            <b>Cuando</b> seleccione el botón de “Postulantes”
            </br>
            <b>Y</b> visualice la lista de candidatos que se han postulado para ese puesto 
            </br>
            <b>Y</b> le dé clic alguno de los postulantes
            </br>
            <b>Entonces</b> visualizará el perfil del postulante.   
            </br>
            <br>
            <b>Scenario 02: Visualización del historial laboral </b>
            </br>
            <b>Dado </b>que el empleador se encuentre en el perfil del postulante
            </br>
            <b>Y</b> seleccione el botón “Historial Laboral” 
            </br>
            <b>Cuando</b> se le redirija al apartado del historial laboral
            </br>
            <b>Entonces</b> podrá visualizar los proyectos realizados para los demás empleadores
            <br>
            <br>
            <b>Scenario 03: Visualización de comentarios de otros empleadores</b>
            </br>
            <b>Dado </b>que el empleador se encuentra en el perfil del postulante
            </br>
            <b>Cuando</b> seleccione el botón “Comentarios” 
            </br>
            <b>Y</b> visualice los comentarios de otros empleadores  
            </br>  
            <b>Entonces</b> podrá verificar las referencias de su trabajo     
        </td> 
    </tr>
    </tr>
</table>

<br>

<table align="center"     border="1" width="90%" style="text-align:center;">
    <tr align="left">
        <td colspan=2>
            <b>Épica</b>
        </td>
        <td colspan=2>
            Funcionalidades empleador
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>ID-HU</b>
        </td>
        <td>
            17
        </td>
        <td>
            <b>Owner</b>
        </td>
        <td>
            Jennifer Espinoza
        </td>
    </tr>
        <tr align="left">
        <td colspan=2>
            <b>Título HU</b>
        </td>
        <td colspan=2>
            Gestionar seguimiento de Estado de Trabajos
        </td>
    </tr>
    <tr align="left">
        <td colspan=4>
            <b>Descripción:</b></br>
            <p>
            <b>Como</b> empleador <b>quiero</b> actualizar y gestionar el estado de los trabajos <b>para</b> poder mantener un registro claro del progreso de cada trabajo.
            </p>
        </td>
    </tr>
    <tr align="left">
        <td colspan=4>
            <b>Criterio de Aceptación:</b>
            </br>
            <b>Scenario 01: Acceso a la Lista de Trabajos</b></br>
            <b>Dado </b> que el empleador inicia sesión en su cuenta
            </br>
            <b>Cuando</b> acceda a su perfil
            </br>
            <b>Y</b> de clic en la sección “Trabajos”
            </br>
            <b>Entonces</b> debe poder ver una lista completa de los trabajos publicados   
            </br>
            <br>
            <b>Scenario 02: Actualización del Estado del Trabajo</b>
            </br>
            <b>Dado </b>que el empleador está en la lista de "Mis Trabajos"
            </br>
            <b>Y</b> selecciona un trabajo específico, 
            </br>
            <b>Cuando</b> hace clic en un botón de "Gestionar",
            </br>
            <b>Entonces</b> debe ser redirigido a una página de edición del trabajo.
            <br>
            <br>
            <b>Scenario 03: Registro de Cambios y Confirmación</b>
            </br>
            <b>Dado </b>que el empleador está en la edición del trabajo
            </br>
            <b>Y</b> seleccione “Actualizar Estado” 
            </br> 
            <b>Entonces</b> podrá escoger entre "En Progreso" y "Completado"
            </br> 
            <b>Cuando</b> presione el botón “Guardar” 
            </br>
            <b>Entonces</b> se guardará el estado con la fecha y hora de la actualización    
        </td> 
    </tr>
    </tr>
</table

<br>

<table align="center"     border="1" width="90%" style="text-align:center;">
    <tr align="left">
        <td colspan=2>
            <b>Épica</b>
        </td>
        <td colspan=2>
            Funciones de edición de la interfaz
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>ID-HU</b>
        </td>
        <td>
            18
        </td>
        <td>
            <b>Owner</b>
        </td>
        <td>
            Jennifer Espinoza
        </td>
    </tr>
        <tr align="left">
        <td colspan=2>
            <b>Título HU</b>
        </td>
        <td colspan=2>
            Personalizar interfaz de usuario
        </td>
    </tr>
    <tr align="left">
        <td colspan=4>
            <b>Descripción:</b></br>
            <p>
            <b>Como</b> usuario <b>quiero</b> poder personalizar la apariencia y configuración de la aplicación, <b>para</b> que se adapte a mis preferencias.
            </p>
        </td>
    </tr>
    <tr align="left">
        <td colspan=4>
            <b>Criterio de Aceptación:</b>
            </br>
            <b>Scenario 01: Personalización de Apariencia</b></br>
            <b>Dado </b>que el usuario está en la sección de "Perfil"
            </br>
            <b>Cuando</b> seleccione el simbolo de configuración
            </br>
            <b>Y</b> elija en aparecencias las opciones de "Claro" u "Oscuro" 
            </br>
            <b>Entonces</b> la apariencia de la aplicación cambiará de acuerdo con la elección del usuario.   
            </br>
            <br>
            <b>Scenario 02: Cambio de Idioma </b>
            </br>
            <b>Dado </b>que el usuario está en la sección de "Perfil"
            </br>
            <b>Cuando</b> seleccione la opción de "Cambiar Idioma"
            </br>
            <b>Y</b> elija entre los idiomas disponibles (por ejemplo, español e inglés) 
            </br>
            <b>Entonces</b> la aplicación se adaptará al idioma seleccionado por el usuario.
            <br>   
        </td> 
    </tr>
    </tr>
</table>

<br>

<table align="center"     border="1" width="90%" style="text-align:center;">
    <tr align="left">
        <td colspan=2>
            <b>Épica</b>
        </td>
        <td colspan=2>
            Funcionalidades usuario
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>ID-HU</b>
        </td>
        <td>
            19
        </td>
        <td>
            <b>Owner</b>
        </td>
        <td>
            Jennifer Espinoza
        </td>
    </tr>
        <tr align="left">
        <td colspan=2>
            <b>Título HU</b>
        </td>
        <td colspan=2>
            Reportar Inconvenientes a través de la Función de Reclamos
        </td>
    </tr>
    <tr align="left">
        <td colspan=4>
            <b>Descripción:</b></br>
            <p>
            <b>Como</b> usuario <b>quiero</b> tener acceso a una función de reclamos donde pueda reportar inconvenientes <b>para</b> obtener una resolución justa hazte de esta
            </p>
        </td>
    </tr>
    <tr align="left">
        <td colspan=4>
            <b>Criterio de Aceptación:</b>
            </br>
            <b>Scenario 01: Presentación de un Reclamo</b></br>
            <b>Dado </b>que estoy en la conversación con el chambeador en el chat de la plataforma,
            </br>
            <b>Cuando</b> surge un conflicto durante el trabajo,
            </br>
            <b>Entonces</b> hago clic en el ícono de "Reclamo" dentro de la conversación,
            </br>
            <b>Y</b> se abre un formulario donde puedo describir el conflicto en detalle
            </br>
            <br>
            <b>Scenario 02: Adjuntar imágenes como evidencia en el reclamo </b>
            </br>
            <b>Dado </b>que un usuario está presentando un reclamo en la conversación de chat,
            </br>
            <b>Cuando</b> describen el conflicto en el formulario de reclamo,
            </br>
            <b>Y</b> decide presentar evidencias para evidencia como capturas de pantalla, fotos u otros archivos.
            </br>
            <b>Entonces</b> tendrá que presionar “Subir archivos” en el hilo del reclamo 
            <br>   
        </td> 
    </tr>
    </tr>
</table>

</br>

<table align="center"     border="1" width="90%" style="text-align:center;">
    <tr align="left">
        <td colspan=2>
            <b>Épica</b>
        </td>
        <td colspan=2 style="text-align: center;">
        Funcionalidad del usuario chambeador
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>ID-HU</b>
        </td>
        <td style="text-align: center;">
            20
        </td>
        <td>
            <b>Owner</b>
        </td>
        <td style="text-align: center;">
            Jennifer Espinoza
        </td>
    </tr>
        <tr align="left">
        <td colspan=2>
            <b>Título HU</b>
        </td>
        <td colspan=2  style="text-align: center;">
            Recepcionar calificaciones y comentarios de Empleadores
        </td>
    </tr>
    <tr align="left">
        <td colspan=4>
            <b>Descripción:</b><br/>
            <b>Como</b> chambeador <b>quiero</b> recibir calificaciones y comentarios de los empleadores después de completar un trabajo <b>para</b> demostrar mi experiencia y calidad de trabajo.
        </td>
    </tr>
    <tr align="left">
        <td colspan=4>
            <b>Criterio de Aceptación:</b><br/>
            <b>Scenario 01:</b> Recepción de Calificaciones y Comentarios<br/>
            <b>Dado</b> que he completado un trabajo en ChambeaPe<br/>
            <b>Cuando</b> el empleador me califique y deje comentarios sobre mi desempeño, y reciba una notificación informándome de la revisión de mi trabajo <br/>
            <b>Y </b>haga clic en el botón “Ver Reseña” para ver la reseña<br/>
            <b>Entonces</b>  podré visualizar el comentario y la calificación que me hayan otorgado        
            <br/> <br/>
            <b>Scenario 02:</b> Recepción de Calificaciones y Comentarios<br/>
            <b>Dado</b> que he realizado múltiples trabajos en ChambeaPe y he recibido calificaciones y comentarios de empleadores <br/>
            <b>Cuando</b> acceda a mi perfil de usuario <br/>
            <b>Y </b>seleccione la opción para ver mi historial laboral<br/>
            <b>Entonces</b> podré ver de manera consolidada todas las calificaciones y comentarios que he recibido en trabajos anteriores
        </td>      
    </tr>
    </tr>
</table>

<br>

<table align="center"     border="1" width="90%" style="text-align:center;">
    <tr align="left">
        <td colspan=2>
            <b>Épica</b>
        </td>
        <td colspan=2 style="text-align: center;">
        Funcionalidad del usuario chambeador
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>ID-HU</b>
        </td>
        <td style="text-align: center;">
            21
        </td>
        <td>
            <b>Owner</b>
        </td>
        <td style="text-align: center;">
            Steve Castillo
        </td>
    </tr>
        <tr align="left">
        <td colspan=2>
            <b>Título HU</b>
        </td>
        <td colspan=2  style="text-align: center;">
            Postular a vacantes de trabajo
        </td>
    </tr>
    <tr align="left">
        <td colspan=4>
            <b>Descripción:</b><br/>
            <b>Como</b> chambeador <b>quiero</b> poder postular a una vacante <b>para</b> demostrar mis habilidades y crecer profesionalmente.
        </td>
    </tr>
    <tr align="left">
        <td colspan=4>
            <b>Criterio de Aceptación:</b><br/>
            <b>Scenario 01:</b> Postulación a una Vacante de Trabajo<br/>
            <b>Dado</b> que he identificado una vacante laboral compatible con mis habilidades en ChambeaPe <br/>
            <b>Cuando</b> elija la opción para postularme a la vacante <br/>
            <b>Y </b>haga clic en "Confirmar"<br/>
            <b>Entonces</b> se mostrara un mensaje “Solicitud Enviada” y seré considerado en el proceso de selección.
            <br/> <br/>
            <b>Scenario 02:</b> Seguimiento de Postulaciones<br/>
            <b>Dado</b> que he postulado a varias vacantes de trabajo en ChambeaPe <br/>
            <b>Cuando</b> acceda a mi perfil de usuario <br/>
            <b>Y </b> elija la sección de "Mis Postulaciones"<br/>
            <b>Entonces</b> podré ver una lista de las vacantes a las que he postulado y su estado actual
        </td>      
    </tr>
</table>

</br>

<table align="center"     border="1" width="90%" style="text-align:center;">
    <tr align="left">
        <td colspan=2>
            <b>Épica</b>
        </td>
        <td colspan=2 style="text-align: center;">
        Funcionalidad del usuario chambeador
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>ID-HU</b>
        </td>
        <td style="text-align: center;">
            22
        </td>
        <td>
            <b>Owner</b>
        </td>
        <td style="text-align: center;">
            Diego Castro
        </td>
    </tr>
        <tr align="left">
        <td colspan=2>
            <b>Título HU</b>
        </td>
        <td colspan=2  style="text-align: center;">
            Actualizar estado según disponibilidad
        </td>
    </tr>
    <tr align="left">
        <td colspan=4>
            <b>Descripción:</b><br/>
            <b>Como</b> chambeador <b>quiero</b> que mi estado en la plataforma se actualice automáticamente según mi disponibilidad laboral <b>para</b> para definir mi perfil.
        </td>
    </tr>
    <tr align="left">
        <td colspan=4>
            <b>Criterio de Aceptación:</b><br/>
            <b>Scenario 01:</b> Actualización Automática de Estado durante un Trabajo<br/>
            <b>Dado</b> que soy un chambeador en ChambeaPe y deseo que mi disponibilidad laboral sea transparente <br/>
            <b>Cuando</b> me encuentre realizando un trabajo con un empleador dentro de la aplicación <br/>
            <b>Entonces</b> mi estado en la plataforma se actualizará automáticamente a "Trabajando"    
            <br/> <br/>
            <b>Scenario 02:</b> Cambio de Estado al Finalizar un Trabajo<br/>
            <b>Dado</b> que soy un chambeador y he concluido un trabajo en ChambeaPe <br/>
            <b>Cuando</b> acceda a mi perfil de usuario <br/>
            <b>Y </b>seleccione la opción para ver mi historial laboral<br/>
            <b>Entonces</b> mi estado en la plataforma cambiará automáticamente a "Disponible”
        </td>      
    </tr>
</table>

</br>

<table align="center"     border="1" width="90%" style="text-align:center;">
    <tr align="left">
        <td colspan=2>
            <b>Épica</b>
        </td>
        <td colspan=2 style="text-align: center;">
        Funcionalidad del usuario chambeador
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>ID-HU</b>
        </td>
        <td style="text-align: center;">
            23
        </td>
        <td>
            <b>Owner</b>
        </td>
        <td style="text-align: center;">
            Diego Esquivel
        </td>
    </tr>
        <tr align="left">
        <td colspan=2>
            <b>Título HU</b>
        </td>
        <td colspan=2  style="text-align: center;">
            Manejar certificados 
        </td>
    </tr>
    <tr align="left">
        <td colspan=4>
            <b>Descripción:</b><br/>
            <b>Como</b> chambeador <b>quiero</b> manejar mis certificados <b>para</b> tener una mejor oportunidad laboral.
        </td>
    </tr>
    <tr align="left">
        <td colspan=4>
            <b>Criterio de Aceptación:</b><br/>
            <b>Scenario 01:</b> Agregación de Certificados a mi Perfil<br/>
            <b>Dado</b> que soy un usuario chambeador en ChambeaPe y deseo fortalecer mi perfil laboral<br/>
            <b>Cuando</b> acceda a mi cuenta y navegue a la sección de "Certificados" <br/>
            <b>Y </b>seleccione la opción para agregar un nuevo certificado<br/>
            <b>Entonces</b> podré cargar una imagen o documento que respalde mis habilidades y logros   
            <br/> <br/>
            <b>Scenario 02:</b> Visualización de Certificados en mi Perfil <br/>
            <b>Dado</b> que he añadido certificados a mi perfil en ChambeaPe <br/>
            <b>Cuando</b> acceda a la sección de "Certificados" en mi perfil <br/>
            <b>Entonces</b> podré visualizar todos los certificados que he subido
        </td>      
    </tr>
    </tr>
</table>

## 3.3. Impact Mapping

<br>

<div align=center>
    <img src="https://cdn.discordapp.com/attachments/1145583761182965852/1149502374931599390/Impact_Mapping_1.png" alt="Impact-Mapping"  width="90%"/>
</div>

## 3.4. Product Backlog

Les presentamos nuestro [Product Backlog](https://trello.com/b/KONj0nS6/product-backlog) para el desarrollo de nuestra landing page.

<div align=center>
    <img src="https://cdn.discordapp.com/attachments/1145421916413366426/1149773251933896768/image.png" alt="Product-Backlog"  width="80%"/>
</div>
</br>

<table align="center" border="1" width="90%" style="text-align:center;">
    <tr>
        <th>
            # Orden
        </th>
        <th>
            User Story ID
        </th>
        <th>
            Título
        </th>
        <th>
            Descripción
        </th>
        <th>
            Story Points </br> (1 / 2 / 3 / 5 / 8)
        </th>
    </tr>
    <tr>
        <td>
            01
        </td>
        <td>
            04
        </td>
        <td>
            Mejorar a cuenta premium
        </td>
        <td>
            Como usuario, quiero mejorar mi cuenta a premium con diferentes métodos de pagos para obtener mejoras en mi cuenta.
        </td>
        <td>
            8
        </td>
    </tr>
    <tr>
        <td>
            02
        </td>
        <td>
            19
        </td>
        <td>
            Reportar Inconvenientes a través de la Función de Reclamos
        </td>
        <td>
            Como usuario quiero tener acceso a una función de reclamos donde pueda reportar inconvenientes para obtener una resolución justa hazte de esta.
        </td>
        <td>
            8
        </td>
    </tr>
    <tr>
        <td>
            03
        </td>
        <td>
            01
        </td>
        <td>
            Iniciar Sesión
        </td>
        <td>
            Como usuario, quiero iniciar sesión con mi correo y contraseña para un acceso seguro.
        </td>
        <td>
            5
        </td>
    </tr>
    <tr>
        <td>
            04
        </td>
        <td>
            05
        </td>
        <td>
            Administrar tarjeta
        </td>
        <td>
            Como usuario quiero administrar los datos de mi tarjeta para permitirá realizar transacciones dentro de la aplicación.
        </td>
        <td>
            5
        </td>
    </tr>
    <tr>
        <td>
            05
        </td>
        <td>
            17
        </td>
        <td>
            Gestionar seguimiento de Estado de Trabajos 
        </td>
        <td>
            Como empleador quiero actualizar y gestionar el estado de los trabajos para poder mantener un registro claro del progreso de cada trabajo.
        </td>
        <td>
            5
        </td>
    </tr>
    <tr>
        <td>
            06
        </td>
        <td>
            12
        </td>
        <td>
            Comunicar entre empleado y chambeador.
        </td>
        <td>
            Como empleador quiero tener la opción definir las características del trabajo directamente con los chambeadores para mantener un medio de comunicación seguro.
        </td>
        <td>
            5
        </td>
    </tr>
    <tr>
        <td>
            07
        </td>
        <td>
            23
        </td>
        <td>
            Manejar certificados
        </td>
        <td>
            Como chambeador quiero manejar mis certificados para tener una mejor oportunidad laboral.
        </td>
        <td>
            8
        </td>
    </tr>
    <tr>
        <td>
            08
        </td>
        <td>
            02
        </td>
        <td>
            Registrar con correo
        </td>
        <td>
            Como usuario quiero poder registrarme con mi correo a la plataforma para agilizar el proceso de registro.
        </td>
        <td>
            3
        </td>
    </tr>
    <tr>
        <td>
            09
        </td>
        <td>
            08
        </td>
        <td>
            Notificar trabajos recomendados
        </td>
        <td>
            Como chambeador quiero recibir notificaciones sobre trabajos relevantes a mi perfil mediante la suscripción premium para postular más rápido.
        </td>
        <td>
            3
        </td>
    </tr>
    <tr>
        <td>
            10
        </td>
        <td>
            09
        </td>
        <td>
            Publicar anuncios como chambeador
        </td>
        <td>
            Como chambeador quiero publicar un anuncio de trabajo para que me contacten más rápido.
        </td>
        <td>
            3
        </td>
    </tr>
    <tr>
        <td>
            11
        </td>
        <td>
            16
        </td>
        <td>
            Evaluar historial laboral de chambeadores
        </td>
        <td>
            Como empleador quiero tener acceso al historial laboral de los candidatos que se postulan en mis puestos de trabajo para evaluar y seleccionar a un futuro trabajador.
        </td>
        <td>
            3
        </td>
    </tr>
    <tr>
        <td>
            12
        </td>
        <td>
            11
        </td>
        <td>
            Registrar pago del Chambeador.
        </td>
        <td>
            Como empleador quiero definir el pago con el chambeador para tener un registro en la aplicación.
        </td>
        <td>
            3
        </td>
    </tr>
    <tr>
        <td>
            13
        </td>
        <td>
            15
        </td>
        <td>
            Manejar anuncios de trabajo.
        </td>
        <td>
            Como empleador quiero manejar (crear- editar) mis anuncios de trabajo para buscar candidatos.
        </td>
        <td>
            3
        </td>
    </tr>
    <tr>
        <td>
            14
        </td>
        <td>
            20
        </td>
        <td>
            Recepcionar calificaciones y comentarios de Empleadores.
        </td>
        <td>
            Como chambeador quiero recibir calificaciones y comentarios de los empleadores después de completar un trabajo para demostrar mi experiencia y calidad de trabajo.
        </td>
        <td>
            3
        </td>
    </tr>
    <tr>
        <td>
            15
        </td>
        <td>
            03
        </td>
        <td>
            Manejar información del perfil
        </td>
        <td>
            Como usuario, quiero manejar la información de mi perfil para mantener mis datos personales actualizados.
        </td>
        <td>
            3
        </td>
    </tr>
    <tr>
        <td>
            16
        </td>
        <td>
            07
        </td>
        <td>
            Filtrar perfiles de chambeadores
        </td>
        <td>
            Como empleador quiero tener la opción de filtrar perfiles para reducir el tiempo de selección.
        </td>
        <td>
            2
        </td>
    </tr>
    <tr>
        <td>
            17
        </td>
        <td>
            10
        </td>
        <td>
            Resaltar anuncios del empleador
        </td>
        <td>
            Como empleador con membresía premium quiero que mis publicaciones tengan prioridad al ser publicadas para atraer la atención de trabajadores cualificados y entusiastas.
        </td>
        <td>
            2
        </td>
    </tr>
    <tr>
        <td>
            18
        </td>
        <td>
            13
        </td>
        <td>
            Reseñar empleador al chambeador.
        </td>
        <td>
            Como empleador quiero quiero dejar una reseña sobre la experiencia con el chambeador después de que el trabajo se haya completado para calificar su servicio.
        </td>
        <td>
            5
        </td>
    </tr>
    <tr>
        <td>
            19
        </td>
        <td>
            18
        </td>
        <td>
            Personalizar interface de usuario
        </td>
        <td>
            Como usuario quiero poder personalizar la apariencia y configuración de la aplicación, para que se adapte a mis preferencias.
        </td>
        <td>
            2
        </td>
    </tr>
    <tr>
        <td>
            20
        </td>
        <td>
            21
        </td>
        <td>
            Postular a vacantes de trabajo
        </td>
        <td>
            Como chambeador quiero poder postular a una vacante para demostrar mis habilidades y crecer profesionalmente.
        </td>
        <td>
            2
        </td>
    </tr>
    <tr>
        <td>
            21
        </td>
        <td>
            22
        </td>
        <td>
            Actualizar estado según disponibilidad
        </td>
        <td>
            Como chambeador quiero que mi estado en la plataforma se actualice automáticamente según mi disponibilidad laboral para para definir mi perfil.
        </td>
        <td>
            2
        </td>
    </tr>
    <tr>
        <td>
            22
        </td>
        <td>
            06
        </td>
        <td>
            Destacar perfil de chambeador
        </td>
        <td>
            Como chambeador quiero contar con la opción de destacar mi perfil en los resultados de búsqueda para aumentar mis posibilidades de ser seleccionado.
        </td>
        <td>
            1
        </td>
    </tr>
    <tr>
        <td>
            23
        </td>
        <td>
            14
        </td>
        <td>
            Visualizar perfiles de chambeadores
        </td>
        <td>
            Como empleador quiero poder visualizar los perfiles de los chambeadores, para evaluar su experiencia y estilo de trabajo antes de contratarlos.
        </td>
        <td>
            1
        </td>
    </tr>
    <tr>
        <td>
            24
        </td>
        <td>
            24
        </td>
        <td>
            Página no encontrada
        </td>
        <td>
            Como usuario quiero visualizar un apartado especial cuando no sea la ruta correcta para saber que estoy ingresando un ruta erronea.
        </td>
        <td>
            1
        </td>
    </tr>
</table>

<br><br>
<br><br>

# Capítulo IV: Product Design
## 4.1. Style Guidelines.
### 4.1.1. General Style Guidelines

**Branding:**
- El ícono de nuestro proyecto captura el apretón de dos manos entrelazadas, un poderoso símbolo de la comunión entre individuos. Con esta representación, buscamos plasmar de manera elocuente la estrecha conexión que nuestros valiosos usuarios experimentarán al unirse a nuestra comunidad.

<div align=center>
    <img src="https://cdn.discordapp.com/attachments/1145583761182965852/1146508424524349480/ChambeaPeconFondo.png" alt="Branding"  width="50%"/>
</div>
</br>

**Typography:**
- La tipografía de nuestro logotipo adoptará el elegante estilo Roboto, reconocido por su modernidad y su atractivo visual para nuestros usuarios. Este estilo no solo refleja la innovación y la creatividad que caracterizarán a nuestra aplicación, sino que también resalta la vanguardia que buscamos transmitir.

<div align=center>
    <img src="https://cdn.discordapp.com/attachments/1145583761182965852/1146508424276873276/Typography.png" alt="Typography"  width="50%"/>
</div>
</br>

**Colors:**
- La paleta de colores que creamos para el proyecto contiene como color primario el #bf0a26, que es un anaranjado intenso, con una tonalidad cálida y vibrante. Los colores complementarios son el #e8e7e2, que es un gris claro con un toque de beige; el #e6ebee, que es un azul claro con un toque de verde; el #f7ebeb, que es un rosa pálido con un toque de blanco; y el #f4e8ec, que es un lila suave con un toque de rosa. El background es el #fff, que es el blanco puro. </br></br>
Esta paleta de colores es adecuada para un proyecto que quiera transmitir una sensación de profesionalismo, elegancia y serenidad. El color primario se usará para resaltar los títulos, los encabezados y los elementos importantes. Los colores complementarios se usarán para crear contraste, armonía y variedad en el texto, las imágenes y los gráficos. Y para finalizar, el background blanco se usará para dar claridad, limpieza y amplitud al diseño.

<div align=center>
    <img src="https://cdn.discordapp.com/attachments/1145421916413366426/1149317860120854559/PaletColor.png" alt="Colors"  width="60%"/>
</div>
</br>

**Spacing:**
- El “spacing” es un aspecto importante en el diseño de una página web, ya que ayuda a crear una apariencia coherente y atractiva. En una guía general de estilos, se pueden establecer reglas y directrices para el uso consistente de propiedades como ```margin``` y ```padding``` para controlar el espacio entre los elementos en la página. Por ejemplo, se puede establecer que todos los márgenes y rellenos deben ser múltiplos de una unidad base, como <b>1rem</b> (16px en dispositivos de escritorio), para asegurar una apariencia consistente en toda la página. </br>
Además, el uso de unidades relativas como rem en lugar de píxeles puede ayudar a abordar el problema del tamaño al hacer que una página web sea responsive. Esto se debe a que las unidades relativas se ajustan automáticamente en función del tamaño de la pantalla, mientras que los píxeles son unidades fijas que no cambian. Al utilizar unidades relativas para definir los espaciados, se puede lograr un diseño adaptable que se vea bien en diferentes tamaños de pantalla.

<div align=center>
    <img src="https://cdn.discordapp.com/attachments/1145583761182965852/1146508424822128700/Spacings.png" alt="Spacing"  width="40%"/>
</div>
</br>

### 4.1.2. Web Style Guidelines

**Icons:**
- Cuando se trata de diseñar una página web, los íconos desempeñan un papel fundamental en la creación de una interfaz de usuario intuitiva y fácil de usar. Estos pequeños elementos visuales tienen el poder de mejorar la comprensión de los usuarios sobre la funcionalidad de los diferentes elementos de tu página. Permíteme explicarte por qué los íconos son tan importantes. </br></br> Los íconos ayudan a los usuarios a comprender rápidamente la función de cada elemento en tu página web. Además, su simplicidad y claridad los hacen fáciles de entender. Al utilizar íconos consistentes en toda la página, evitamos confundir a los usuarios.
- Los que usaremos en el proyecto son los siguientes:

<div align=center>
    <img src="https://cdn.discordapp.com/attachments/1145421916413366426/1149317860691283968/Icons.png" alt="Icons"  width="50%"/>
</div>
</br>

**Breackpoints**
- Los breakpoints más conocidos son los siguientes:

<div align=center>
    <img src="https://cdn.discordapp.com/attachments/1145583761182965852/1146581389874036886/Brackpoints.png" alt="Breackpoints"  width="50%"/>
</div>
</br>

- Y los que usaremos en el proyecto principalmente son los de 768px y 1024px, ya que son los más comunes en los dispositivos móviles y de escritorio.

## 4.2. Information Architecture
### 4.2.1. Organization Systems

Al entrar a nuestra aplicación aplicación, el usuario podrá visualizar 4 secciones: el perfil, los perfiles de chambeadores, las publicaciones de trabajo y las notificaciones. En cada una de estas, el usuario contará con distintas acciones con las que podrá interactuar.

<div align=center>
    <img src="https://media.discordapp.net/attachments/1142626084358193254/1149516472524210237/opera_jrLunJP70X.png?width=1072&height=897" alt="Organization Systems"  width="90%"/>
</div>

### 4.2.2. Labeling Systems

Los sistemas de etiquetado en arquitectura de la información son un conjunto de reglas que permiten etiquetar los contenidos de un sitio web. Estos sistemas se basan en la clasificación de los contenidos y en la estructura de navegación del sitio.

En el proyecto manejaremos un sistema de **etiquetado por facetas**, el cual consiste en la clasificación de los contenidos por categorías, las cuales se pueden combinar entre sí para encontrar un contenido específico.

Dichas categorías son:

- HomePage (Página de inicio)
- Login (Inicio de sesión)
- Register (Registro)
- Profile (Perfil)
- Job (Empleo)
- JobOffer (Oferta de empleo)
- JobRequest (Solicitud de empleo)
- JobOfferList (Lista de ofertas de empleo)
- JobRequestList (Lista de solicitudes de empleo)
- JobOfferDetail (Detalle de oferta de empleo)
- JobRequestDetail (Detalle de solicitud de empleo)
- JobOfferCreate (Creación de oferta de empleo)
- JobRequestCreate (Creación de solicitud de empleo)
- Chat conector (Actualización de oferta de empleo)
- JobRequestUpdate (Actualización de solicitud de empleo)

### 4.2.3. SEO Tags and Meta Tags

**Landing Page:** La página de inicio de nuestra aplicación contará con los siguientes tags:
``` 
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ChambeaPe - Tu plataforma para encontrar empleo</title>
    <meta name="description" content="Encuentra empleo en Perú con ChambeaPe. Conectamos a empleadores y trabajadores de manera eficiente. ¡Regístrate y encuentra tu próximo trabajo!">
    <meta name="keywords" content="empleo, trabajo, Perú, búsqueda de empleo, ofertas de trabajo, empleos en Perú">
    <link rel="stylesheet" href="./assets/css/home.css">
    <link rel="shortcut icon" href="./assets/icons/Logo.svg" type="image/x-icon">

</head>
```

### 4.2.4. Searching Systems

Implementaremos sistemas de búsqueda por exploración, los cuales permitirán a nuestros usuarios encontrar la información que soliciten de manera rápida. Los empleadores que deseen buscar a chambeadores interesados con determinadas condiciones podrán hacerlo filtrándolos por calificación y antigüedad. Además, contaremos con un sistema de búsqueda por nombre de empleador o chambeador en la página principal de nuestra plataforma.

<div align=center>
    <img src="https://media.discordapp.net/attachments/1145583761182965852/1149470630777987232/opera_ddU1FiLJEX.png?width=413&height=896" alt="Searching System 1"  width="30%"/>
    <img src="https://media.discordapp.net/attachments/1145583761182965852/1149470630476009603/opera_c74u7VXwtN.png?width=415&height=897" alt="Searching System 2"  width="30%"/>
</div>

### 4.2.5. Navigation Systems

Para facilitar al usuario navegar por nuestro contenido, se utilizarán los siguientes sistemas de navegación:

- **Navegación principal o global:** Es el sistema de navegación más común, presente en todos los apartados de la página y usualmente representado por la barra de navegación y el footer.
- **Navegación local:** Se encuentra situado un nivel por debajo de la navegación global y su función es mostrar el contenido de la misma categoría, así como también lo que se encuentra jerárquicamente por debajo de esta.
- **Navegación contextual:** Conformada por enlaces que dirigen al usuario a una sección distinta o a otro sitio web. Existen dos tipos: la navegación embebida, en donde los enlaces son ciertas frases o palabras del texto; y los links relacionados, los cuales pueden aparecer al final o al lado del contenido.

<div align=center>
    <img src="https://media.discordapp.net/attachments/1145583761182965852/1149470630153035867/opera_9FgKvOpHuV.png?width=1437&height=803" alt="Navigation System 1"  width="50%"/>
    <img src="https://media.discordapp.net/attachments/1145583761182965852/1149470629897191466/ApplicationFrameHost_woK9WVAjPk.png?width=345&height=356" alt="Navigation System 2"  width="30%"/>
</div>

El patrón de lectura a utilizar para la visualización de nuestra web para las secciones que muestran contenido ligero será el patrón Z. Mientras que, para los apartados que cuenten con mayor volumen de texto, como en las ofertas de trabajo, se empleará el patrón F. De esta manera, lograremos captar la atención del lector durante más tiempo.  

<div align=center>
    <img src="https://media.discordapp.net/attachments/1145583761182965852/1149470631084175390/opera_FDtKlrQUG6.png?width=1263&height=897" alt="Patrón Z"  width="50%"/>
    </br>
    <p><b>Contenido ligero (patrón Z)</b></p>
    </br>
    <img src="https://media.discordapp.net/attachments/1145583761182965852/1149473093241274408/Imagen1.png?width=922&height=538" alt="Patrón F"  width="50%"/>
    <p><b>Contenido pesado (patrón F)</b></p>
</div>

## 4.3. Landing Page UI Design
### 4.3.1. Landing Page Wireframe

<div align=center>
    <img src="https://media.discordapp.net/attachments/1145583761182965852/1149433086304600187/image.png?width=1026&height=670" alt="version-web-wireframe"  width="90%"/>
</div>
</br>
<div align=center>
    <img src="https://media.discordapp.net/attachments/1145583761182965852/1149433086870814761/image.png?width=560&height=526" alt="version-web-wireframe"  width="90%"/>
</div>
</br>
<div align=center>
    <img src="https://media.discordapp.net/attachments/1145583761182965852/1149433086614982827/image.png?width=552&height=670" alt="version-web-wireframe"  width="90%"/>
</div>
</br>
<div align=center>
    <img src="https://media.discordapp.net/attachments/1145583761182965852/1149433087118295181/image.png?width=561&height=240" alt="version-web-wireframe"  width="90%"/>
</div>
</br>

### 4.3.2. Landing Page Mock-up

<div align=center>
    <img src="https://media.discordapp.net/attachments/1145583761182965852/1149434091909955746/image.png?width=562&height=401" alt="version-web-mockup"  width="90%"/>
</div>
</br>
<div align=center>
    <img src="https://media.discordapp.net/attachments/1145583761182965852/1149434092400680980/image.png?width=561&height=511" alt="version-web-mockup"  width="90%"/>
</div>
</br>
<div align=center>
    <img src="https://media.discordapp.net/attachments/1145583761182965852/1149434092639760384/image.png?width=560&height=485" alt="version-web-mockup"  width="90%"/>
</div>
</br>
<div align=center>
    <img src="https://media.discordapp.net/attachments/1145583761182965852/1149434092908200016/image.png?width=562&height=388" alt="version-web-mockup"  width="90%"/>
</div>
</br>

## 4.4. Web Applications UX/UI Design
### 4.4.1. Web Applications Wireframes

<div align=center>
    <img src="https://media.discordapp.net/attachments/1142626132357828689/1149627174094118983/21.png?width=1422&height=897" alt="wireframe 1"  width="100%"/>
</div>
<div align=center>
    <img src="https://media.discordapp.net/attachments/1142626132357828689/1149627174412894275/07.png?width=1262&height=897" alt="wireframe 2"  width="90%"/>
</div>
</br>

<div align=center>
    <img src="https://media.discordapp.net/attachments/1142626132357828689/1149627174639370270/08.png?width=1687&height=897" alt="wireframe 3"  width="90%"/>
</div>
<div align=center>
    <img src="https://media.discordapp.net/attachments/1142626132357828689/1149627174912008232/09.png?width=1920&height=796" alt="wireframe 4"  width="90%"/>
</div>
</br>
<div align=center>
    <img src="https://media.discordapp.net/attachments/1142626132357828689/1149627175251755028/10.png?width=1920&height=663" alt="wireframe 5"  width="90%"/>
</div>
<div align=center>
    <img src="https://media.discordapp.net/attachments/1142626132357828689/1149627175490814053/12.png?width=1356&height=897" alt="wireframe 6"  width="90%"/>
</div>
</br>
<div align=center>
    <img src="https://media.discordapp.net/attachments/1142626132357828689/1149627175742480454/15.png?width=1460&height=897" alt="wireframe 7"  width="90%"/>
</div>
</br>
<div align=center>
    <img src="https://media.discordapp.net/attachments/1142626132357828689/1149627176023506946/16.png?width=1610&height=897" alt="wireframe 8"  width="90%"/>
</div>
</br>
<div align=center>
    <img src="https://media.discordapp.net/attachments/1142626132357828689/1149627176308703292/19.png?width=1920&height=877" alt="wireframe 9"  width="90%"/>
</div>
</br>
<div align=center>
    <img src="https://media.discordapp.net/attachments/1142626132357828689/1149627176547786752/20.png?width=1431&height=897" alt="wireframe 10"  width="90%"/>
</div>
</br>
<div align=center>
    <img src="https://media.discordapp.net/attachments/1142626132357828689/1149627191726985226/23.png?width=1533&height=897" alt="wireframe 11"  width="90%"/>
</div>
</br>
</br>

### 4.4.2. Web Applications Wireflow Diagrams

**User goal: Usuario se registra, inicia sesión y ingresa su 2FA.**      

<div align=center>
    <img src="https://media.discordapp.net/attachments/1145583761182965852/1149488126671212625/Diagrama_en_blanco_-_Pagina_1_9.png?width=1296&height=897" alt="User Goal 01"  width="90%"/>
</div>


**Descripción:**

Cuando un usuario desee registrarse, deberá hacer click en ese dicho botón y completar sus datos personales, así como el rol que asumirá. Finalmente, presionará el botón de registrar.

Por otra parte, cuando el usuario desee iniciar sesión, deberá llenar su correo y contraseña y pulsar el botón iniciar sesión. Cuando se encuentre aquí deberá completar la verificación en 2 pasos, ingresando el código enviado por SMS a su teléfono móvil. Una vez se haya verificado su identidad se procederá al inicio de sesión. 

**User goal: Empleador ve las solicitudes de los chambeadores en los anuncios que publico**

<div align=center>
    <img src="https://media.discordapp.net/attachments/1145583761182965852/1149488159919460382/Diagrama_en_blanco_-_Pagina_1_6.png?width=1872&height=896 " alt="User Goal 02"  width="90%"/>
</div>


**Descripción:**

El empleador ingresa a la sección de empleos desde la página principal. En esta sección se listan todos los anuncios publicados por él y las opciones para ver el detalle y editar el anuncio. Luego de ajustar los filtros que desee, el empleador presiona en una publicación y observa el detalle del anuncio, así como las solicitudes de los chambeadores interesados en ese trabajo. Asimismo, puede observar el perfil de cada chambeador al pulsar el botón “Ver perfil”.

**User goal: Empleador filtra las solicitudes de los chambeadores para elegir el más apto**

<div align=center>
    <img src="https://media.discordapp.net/attachments/1145583761182965852/1149488158216552468/Diagrama_en_blanco_-_Pagina_1_4.png?width=1920&height=627" alt="User Goal 03"  width="90%"/>
</div>


**Descripción:**

El empleador ingresa a la sección de empleos desde la página principal. Desde aquí podrá observar la lista de ofertas de trabajo publicadas por él. Cuando presione uno de los anuncios se mostrarán todos los chambeadores interesados en el trabajo seleccionado. Finalmente, podrá ajustar los filtros que desee para mostrar al más apto según sus preferencias.

**User goal: Empleador  crea un anuncio de trabajo**

**User goal: Empleador elimina un anuncio** 

**User goal: El empleador revisa la lista de candidatos interesados en el trabajo, realiza un proceso de selección, evalúa sus perfiles y establece una  comunicación inicial antes de finalizar la contratación.**

<div align=center>
    <img src="https://media.discordapp.net/attachments/1145583761182965852/1149488127002558474/Diagrama_en_blanco_-_Pagina_1.png?width=1143&height=897" alt="User Goal 04"  width="90%"/>
</div>


**Descripción:**

El empleador se dirige a la sección de empleos desde la página principal. En este apartado podrá ver la lista de trabajos publicados por él junto a un botón para añadir una nueva publicación. Cuando haga click en ese botón el empleador será dirigido a un formulario donde debe rellenar los datos requeridos para la publicación como el título, categoría, descripción, imágenes, ubicación y algunas configuraciones adicionales. Luego, al completar todos los pasos se creará el anuncio de trabajo. 

Cuando el empleador desee ver la lista de chambeadores interesados en el anuncio que acaba de publicar, podrá hacerlo dirigiéndose a la sección de trabajos, pulsando en el ícono de la maleta. A continuación, deberá seleccionar el trabajo del que desea ver la lista, luego ajustar los filtros que desee y abrir el chat del chambeador más apto. Una vez aquí, el empleador podrá visualizar el perfil del interesado a detalle, como ver su historial de trabajos, y tomar la decisión de si desea contactar con él. Finalmente, si desea eliminar la publicación, se dirigirá a la sección de publicaciones y presionará el tacho de basura.

**User goal: Chambeador agrega un certificado a su perfil** 

**User goal: Chambeador postula a un trabajo**

**User goal: Chambeador publicita su perfil**

<div align=center>
    <img src="https://media.discordapp.net/attachments/1145583761182965852/1149488128936132719/Diagrama_en_blanco_-_Pagina_1_12.png?width=1157&height=897" alt="User Goal 05"  width="90%"/>
</div>

**Descripción:**

El chambeador ingresa a su perfil desde la página principal. Cuando presione el botón de agregar certificado podrá llenar los datos requeridos como los detalles y una fotografía de este. Una vez estén todos los datos podrá confirmarlo para que sea visible en su perfil y cuando pulse en “Ver certificado” se mostrará la información de este. Por otra parte, cuando el chambeador desee publicitar su perfil, deberá ser premium y dirigirse a la sección de chambeadores, representada por una tarjeta. Una vez aquí, deberá llenar los datos, seguir los pasos y presionar el botón de “Publicar”. Finalmente, si el chambeador desea unirse a un empleo deberá dirigirse a esa sección, seleccionar el empleo deseado y hacer click en unirse.

### 4.4.3. Web Applications Mock-ups

<div align=center>
    <img src="https://media.discordapp.net/attachments/1145421916413366426/1149642028007817277/7.png?width=1381&height=897" alt="Mockup 01"  width="90%"/>
</div>
</br>
<div align=center>
    <img src="https://media.discordapp.net/attachments/1145421916413366426/1149642028360155216/8.png?width=1912&height=897" alt="Mockup 02"  width="90%"/>
</div>
</br>
<div align=center>
    <img src="https://media.discordapp.net/attachments/1145421916413366426/1149642028704075796/9.png?width=1260&height=897" alt="Mockup 03"  width="90%"/>
</div>
</br>
<div align=center>
    <img src="https://media.discordapp.net/attachments/1145421916413366426/1149642029073186886/10.png?width=1920&height=601" alt="Mockup 04"  width="90%"/>
</div>
</br>
<div align=center>
    <img src="https://media.discordapp.net/attachments/1145421916413366426/1149642029526159380/12.png?width=1352&height=897" alt="Mockup 05"  width="90%"/>
</div>
</br>
<div align=center>
    <img src="https://media.discordapp.net/attachments/1145421916413366426/1149642029928824923/15.png?width=988&height=897" alt="Mockup 06"  width="90%"/>
</div>
</br>
<div align=center>
    <img src="https://media.discordapp.net/attachments/1145421916413366426/1149642030385987625/16.png?width=1655&height=897" alt="Mockup 07"  width="90%"/>
</div>
</br>
<div align=center>
    <img src="https://media.discordapp.net/attachments/1145421916413366426/1149642030792851478/21.png?width=1586&height=897" alt="Mockup 08"  width="90%"/>
</div>
</br>
<div align=center>
    <img src="https://media.discordapp.net/attachments/1145421916413366426/1149642027638722571/23.png?width=1606&height=897" alt="Mockup 09"  width="90%"/>
</div>
</br>

### 4.4.4. Web Applications User Flow Diagrams

**User goal 01:**  El empleador revisa la lista de candidatos interesados en el trabajo, realiza un proceso de selección, evalúa sus perfiles y establece una comunicación inicial antes de finalizar la contratación.

<img src="https://media.discordapp.net/attachments/1088250517282640072/1149465780979773511/Diagrama_en_blanco_-_Pagina_1_1.png?width=2880&height=822" width="90%" alt="User Goal 01">

</br>

**Descripción:** En este proceso de evaluación y selección de candidatos, el empleador acceder a sus listas de publicaciones, luego de acceder a todos sus trabajos publicados aplica filtros de acuerdo con sus preferencias, pero solo si lo desea. Después, ve el perfil del chambeador para asegurarse que sean y puede revisar sus trabajos realizados para tener una referencia.

**User goal 02:** Empleador maneja un anuncio de trabajo

<img src="https://media.discordapp.net/attachments/1145421916413366426/1149622649861967973/Diagrama_en_blanco_-_Pagina_1_2.png?width=1446&height=1242" width="90%" alt="User Goal 02">

</br>

**Descripción:** En el proceso de creación y eliminación de un anuncio de trabajo, el empleador comienza por definir los detalles de la posición vacante, como el título, la descripción, los requisitos y la ubicación. Luego, publica el anuncio en la plataforma. Si posteriormente decide retirarlo, puede eliminarlo de la lista de trabajos publicados. Este flujo permite al empleador gestionar las oportunidades laborales que ofrece en la plataforma de manera efectiva y sencilla.

**User goal 03:** Empleador ve las solicitudes de los chambeadores en los anuncios que publico.

<img src="https://media.discordapp.net/attachments/1145421916413366426/1149623757003030639/Diagrama_en_blanco_-_Pagina_1_3.png?width=2880&height=1158" width="90%" alt="User Goal 03">

**Descripción:** El objetivo del usuario es que el empleador pueda revisar las aplicaciones y solicitudes de los chambeadores que han mostrado interés en los anuncios de trabajo que él ha publicado en la plataforma. Esto le permite al empleador evaluar las opciones disponibles y tomar decisiones informadas sobre la selección de candidatos para sus puestos de trabajo. Por eso, presiona el ícono de la maleta, luego tiene la opción de editar, agregar y eliminar sus anuncios. El siguiente paso es que el empleador vea la lista de postulantes de su anuncio. Finalmente, el empleador puede ver el perfil de los chambeadores y decidir si los contacta o no.

**User goal 04:** El empleador conversa y realiza la negociación con el chambeador.

<img src="https://media.discordapp.net/attachments/1145421916413366426/1149625609476132924/Diagrama_en_blanco_-_Pagina_1_5.png?width=2880&height=998" width="90%" alt="User Goal 04">

**Descripción:** El objetivo del usuario es que el empleador pueda comunicarse y entablar una negociación efectiva con el chambeador interesado en su anuncio de trabajo. Esto facilita la discusión de detalles, acuerdos y condiciones del trabajo antes de finalizar la contratación, asegurando una comprensión mutua y una colaboración exitosa.

**User goal 05:** Empleador filtra las solicitudes de los chambeadores para elegir el más apto.

<img src="https://media.discordapp.net/attachments/1145421916413366426/1149629036717408277/Diagrama_en_blanco_-_Pagina_1_7.png?width=1322&height=690" width="90%" alt="User Goal 05">

**Descripción:** El objetivo del usuario es que el empleador pueda utilizar filtros y criterios de selección para revisar y elegir al chambeador más adecuado entre las solicitudes recibidas. Esto facilita la toma de decisiones informadas y asegura que el empleador elija al candidato que mejor se ajusta a sus necesidades y requisitos específicos para el trabajo. En el caso que no desee aplicarlos podrá ver a todos los postulantes.

**User goal 06:** Usuario se registra, inicia sesión y ingresa su 2FA.      

<img src="https://media.discordapp.net/attachments/1145421916413366426/1149629979789906000/Diagrama_en_blanco_-_Pagina_1_8.png?width=1322&height=1104" width="90%" alt="User Goal 06">

**Descripción:** El objetivo del usuario es completar el proceso de registro, iniciar sesión de manera segura y configurar la autenticación de dos factores (2FA) para proteger su cuenta. Esto garantiza que el usuario tenga un acceso seguro a la plataforma y una capa adicional de seguridad a través de la autenticación de dos factores. Para ello, tiene dos opciones al momento de entrar al apartado de sesión, si tiene una cuenta registrada los manda para la verificación de 2 pasos. También, hay otra toma de decisión, al momento de finalizar el registro, si es que el usuario tiene experiencia laboral previa o no podrá completar el registro de su trabajo.

**User goal 07:** Chambeador  publicita su perfil y  postula a un trabajo

<img src="https://media.discordapp.net/attachments/1145421916413366426/1149630584788877372/Diagrama_en_blanco_-_Pagina_1_9.png?width=1322&height=494" width="90%" alt="User Goal 07">

**Descripción:** El objetivo del chambeador es promocionar su perfil en la plataforma, destacando sus habilidades y experiencia laboral para atraer a posibles empleadores. Además, busca trabajos relevantes en la plataforma y envía solicitudes o postulaciones para ser considerado como candidato para dichos trabajos. Esto le permite al chambeador aumentar sus oportunidades de encontrar trabajos adecuados y conseguir oportunidades de empleo.

**User goal 08:** Chambeador realiza configuraciones de perfil  y añade métodos de pago

<img src="https://media.discordapp.net/attachments/1145421916413366426/1149631352103239763/Diagrama_en_blanco_-_Pagina_1_10.png?width=1216&height=1226" alt="User Goal 08">

**Descripción:** El objetivo del usuario chambeador es personalizar y configurar su perfil en la plataforma, lo que incluye proporcionar información relevante sobre sus habilidades y experiencia laboral, así como agregar métodos de pago para recibir pagos por los trabajos que realice a través de la plataforma. Esto le permite al chambeador tener un perfil completo y estar listo para buscar y aceptar trabajos de acuerdo a sus preferencias y necesidades de pago.

**User goal 09:** Chambeador agrega un certificado a su perfil

<img src="https://media.discordapp.net/attachments/1145421916413366426/1149632116074758194/Diagrama_en_blanco_-_Pagina_1_11.png?width=1866&height=1242" width="90%" alt="User Goal 09">

**Descripción:** El objetivo del chambeador es enriquecer su perfil al agregar un certificado que respalda sus habilidades y experiencia. Esto aumenta su credibilidad ante los empleadores y mejora sus posibilidades de ser seleccionado para trabajos relevantes en la plataforma. Para ello, el chambeador debe completar el proceso de registro y luego acceder a su perfil para agregar un certificado.

## 4.5. Web Applications Prototyping

Este es nuestro link de Figma, donde se encuentra el prototipo de alta fidelidad de nuestra aplicación web. 👇🏻👇🏻 </br>

<div align=center>
    <a href="https://www.figma.com/proto/w0g3AL36W7qu0bi2Kk6Kvj/Open-Web?page-id=308%3A6132&type=design&node-id=309-6135&viewport=2335%2C1740%2C0.45&t=XaViXdg2RtFlvDIl-1&scaling=min-zoom&starting-point-node-id=309%3A6135&mode=design" target="_blank">
        <img src="https://cdn.discordapp.com/attachments/1145421916413366426/1149517805620830300/Prototipo.png" alt="Prototype"  width="30%"/>
    </a>
</div>
</br>

## 4.6. Domain-Driven Software Architecture
### 4.6.1. Software Architecture Context Diagram

Se presenta el diagrama de contexto, donde el Sistema "ChambeaPe" es usado por tres clases de usuarios: Employer o Empleador, aquel que publica las ofertas de trabajo; Worker o Trabajador, aquel que ofrece sus servicios para el trabajo; y el Operator u Operador, empleados que manejas y dan soporte al sistema. Asimismo, el sistema principal se conecta con sistemas externos como el sistema de correo y de pago.
<div align=center>
    <img src="https://cdn.discordapp.com/attachments/1088250517282640072/1169736092250034246/opera_PpkkeMMkkd.png?ex=65567ca1&is=654407a1&hm=85560dc110076f22366ce9beba8a4e91096d42d2e20c5f57b6eae93b5fa5e064&" alt="context-diagram"  width="90%"/>
</div>
</br>

### 4.6.2. Software Architecture Container Diagrams

Se presenta el diagrama de contenedores. Existe una aplicación web para cada usuario, con el fin de separar por diferentes funcionalidades. Estas tres aplicaciones web se conectan a un API Gateway, el cual funciona como punto de entrada. Este último se conecta a los cuatro servicios que presenta el sistema: servicio de búsqueda, servicio de publicación, servicio de pago y servicio de autenticación y seguridad. Todos se conectan a una base de datos del sistema. 
<div align=center>
    <img src="https://media.discordapp.net/attachments/1088250517282640072/1169736154581569676/opera_dz1fxF3SZv.png?ex=65567caf&is=654407af&hm=f730e7717584f25e4c352332c03e654ca6633f3825ba6c067495efdda44a4853&=&width=1048&height=681" alt="container-diagram"  width="90%"/>
</div>
</br>

### 4.6.3. Software Architecture Components Diagrams

**Servicio de búsqueda**  
Maneja la información del empleado y del trabajo para permitir la búsqueda de estos. Para optimizar este trabajo, se tiene un controlador de la búsqueda, del filtro y de la pulicación de trabajadores. Esta última se conecta a un repositorio de las publicaciones, el cual se conecta a la base de datos.
<div align=center>
    <img src="https://media.discordapp.net/attachments/1145583761182965852/1149326690179371039/structurizr-85893-searchingComponents.png?width=600&height=670" alt="searching-service"  width="90%"/>
</div>
</br>

**Servicio de publicación**  
Maneja la información de las publicaciones. Primero, se verifican las publicaciones a partir de un controlador. Luego, cede a un pulication controller, para finalmente ser guardado en la base de datos a partir de un publication repository.
<div align=center>
    <img src="https://media.discordapp.net/attachments/1145583761182965852/1149326690489741382/structurizr-85893-publicationComponents.png?width=388&height=670" alt="publication-service"  width="90%"/>
</div>
</br>

**Payment service**  
Servicio cuyo fin es regular el intercambio monetario entre los usuario y la aplicación. Primero, ingresa a un Payment Controller. Luego, la fachada de pago conecta el servicio con el sistema externo de pago. Para finalmente, ser guardado en la base de datos a partir del repositorio de los pagos.
<div align=center>
    <img src="https://media.discordapp.net/attachments/1145583761182965852/1149326690766553108/structurizr-85893-PaymentComponents.png?width=1376&height=670" alt="payment-service"  width="90%"/>
</div>
</br>

**Authentication and security service**  
Servicio cuya finalidad es asegurarse que los datos ingresados son auténticos y se salvaguarda la seguridad de la aplicación. Al momento de iniciar sesión, se emplea un componente de seguridad; a la hora de crear una cuenta, se posee un controlador y un componente de Email que se conecta al servicio externo de correo para permitir la verificación; cuando el usuario agrega una certificación, esta debe ser validad por el componente de validación. Finalmente, todo se conecta a la repositorio de usuarios que permite el registro en la base de datos.
<div align=center>
    <img src="https://media.discordapp.net/attachments/1145583761182965852/1149326691026620467/structurizr-85893-Components.png?width=452&height=670" alt="authentication-and-security-service"  width="90%"/>
</div>
</br>

Link de los diagramas en Structurizr: https://structurizr.com/share/85893/9e321189-9da8-44bb-8557-4957e040b2a7 

## 4.7. Software Object-Oriented Design
### 4.7.1. Class Diagrams

<div align=center>
    <img src="https://cdn.discordapp.com/attachments/1145421916413366426/1149464293402746961/Diagrama_en_blanco_2.png" alt="Class diagram"  width="90%"/>
</div> 

### 4.7.2. Class Dictionary

A continuación explicaremos detalladamente cada clase con sus atributos y métodos correspondientes: 

<table align="center" border="1" width="90%" style="text-align:center">
  <tr>
    <th colspan="3"><b>User</b></th>
  </tr>
  <tr align="left">
    <td>int</td>
    <td>id</td>
    <td>Identificador único del usuario</td>
  </tr>
  <tr align="left">
    <td>string</td>
    <td>first_name</td>
    <td>Primer nombre del usuario</td>
  </tr>
  <tr>
   <tr align="left">
    <td>string</td>
    <td>last_name</td>
    <td>Apellido del usuario</td>
  </tr>
   <tr align="left">
    <td>string</td>
    <td>email</td>
    <td>Correo del usuario</td>
  </tr>
   <tr align="left">
    <td>string</td>
    <td>password</td>
    <td>Contraseña del usuario</td>
  </tr>
    <tr align="left">
    <td>int</td>
    <td>phone_number</td>
    <td>Número celular del usuario</td>
  </tr>
    <tr align="left">
    <td>date</td>
    <td>birthdate</td>
    <td>Fecha de nacimiento del usuario</td>
  </tr>
    <tr align="left">
    <td>char</td>
    <td>gender</td>
    <td>Género del usuario</td>
  </tr>
    <tr align="left">
    <td>bool</td>
    <td>has_premium</td>
    <td>Identificador de si tiene premium el usuario</td>
  </tr>
    <tr align="left">
    <td>List(Notification)</td>
    <td>notifications</td>
    <td>Lista de notificaciones del usuario</td>
  </tr>
  <tr align="left">
    <td>bool</td>
    <td>login()</td>
    <td>Iniciar sesión</td>
  </tr>
  <tr align="left">
    <td>void</td>
    <td>logout()</td>
    <td>Cerrar sesión</td>
  </tr>
  <tr align="left">
    <td>void</td>
    <td>updateProfile()</td>
    <td>Actualizar perfil</td>
  </tr>
</table>
</br>
<table align="center" border="1" width="90%" style="text-align:center">
  <tr>
    <th colspan="3"><b>Admin</b></th>
  </tr>
  <tr align="left">
    <td>void</td>
    <td>getInfo</td>
    <td>Obtener atributos del admin</td>
  </tr>
  <tr align="left">
    <td>void</td>
    <td>banUser(id)</td>
    <td>Banear usuario según su id</td>
  </tr>
</table>
</br>
<table align="center" border="1" width="90%" style="text-align:center">
  <tr>
    <th colspan="3"><b>Notification</b></th>
  </tr>
  <tr align="left">
    <td>int</td>
    <td>id</td>
    <td>Identificador único de la notificación</td>
  </tr>
  <tr align="left">
    <td>string</td>
    <td>content</td>
    <td>Contenido de la notificación</td>
  </tr>
  <tr>
   <tr align="left">
    <td>date</td>
    <td>date</td>
    <td>Fecha de la notificación</td>
  </tr>
  <tr align="left">
    <td>void</td>
    <td>sendNotification()</td>
    <td>Enviar notificación al destinatario</td>
  </tr>
</table>
</br>
<table align="center" border="1" width="90%" style="text-align:center">
  <tr>
    <th colspan="3"><b>ChatLine</b></th>
  </tr>
  <tr align="left">
    <td>User</td>
    <td>to</td>
    <td>Emisor del mensaje</td>
  </tr>
  <tr align="left">
    <td>User</td>
    <td>from</td>
    <td>Receptor del mensaje</td>
  </tr>
  <tr>
   <tr align="left">
    <td>string</td>
    <td>message</td>
    <td>Contenido del mensaje</td>
  </tr>
  <tr align="left">
    <td>void</td>
    <td>sendMessage()</td>
    <td>Enviar mensaje al destinatario</td>
  </tr>
</table>
</br>
<table align="center" border="1" width="90%" style="text-align:center">
  <tr>
    <th colspan="3"><b>Chat</b></th>
  </tr>
  <tr align="left">
    <td>int</td>
    <td>idWorker</td>
    <td>Identificador único del trabajador</td>
  </tr>
  <tr align="left">
    <td>int</td>
    <td>idEmployer</td>
    <td>Identificador único del empleador</td>
  </tr>
  <tr>
  <tr align="left">
    <td>List(ChatLine)</td>
    <td>chatlines</td>
    <td>Lista de líneas del chat</td>
  </tr>
   <tr align="left">
    <td>void</td>
    <td>sendMessage()</td>
    <td>Enviar mensaje al destinatario</td>
  </tr>
</table>
</br>
<table align="center" border="1" width="90%" style="text-align:center">
  <tr>
    <th colspan="3"><b>Advertising</b></th>
  </tr>
  <tr align="left">
    <td>int</td>
    <td>id</td>
    <td>Identificador único del anuncio</td>
  </tr>
  <tr align="left">
    <td>User</td>
    <td>user</td>
    <td>Identificador del usuario</td>
  </tr>
  <tr>
   <tr align="left">
    <td>string</td>
    <td>category</td>
    <td>Categoría del anuncio</td>
  </tr>
   <tr align="left">
    <td>string</td>
    <td>text</td>
    <td>Texto del anuncio</td>
  </tr>
   <tr align="left">
    <td>picture</td>
    <td>thumbnail</td>
    <td>Imágen del anuncio</td>
  </tr>
    <tr align="left">
    <td>date</td>
    <td>start_Day</td>
    <td>Fecha de inicio del anuncio</td>
  </tr>
    <tr align="left">
    <td>date</td>
    <td>end_day</td>
    <td>Fecha de fin del anuncio</td>
  </tr>
    <tr align="left">
    <td>void</td>
    <td>get_info()</td>
    <td>Obtener atributos del anuncio</td>
  </tr>
</table>
</br>
<table align="center" border="1" width="90%" style="text-align:center">
  <tr>
    <th colspan="3"><b>Subscription</b></th>
  </tr>
  <tr align="left">
    <td>int</td>
    <td>id</td>
    <td>Identificador único de la subscripción</td>
  </tr>
  <tr align="left">
    <td>Membership</td>
    <td>type</td>
    <td>Identificador único de la subscripción</td>
  </tr>
  <tr>
 <tr align="left">
    <td>date</td>
    <td>start_Day</td>
    <td>Fecha de inicio de la subscripción</td>
  </tr>
    <tr align="left">
    <td>date</td>
    <td>end_day</td>
    <td>Fecha de fin de la subscripción</td>
  </tr>
  <tr align="left">
    <td>void</td>
    <td>subscribe()</td>
    <td>Obtener subscripción</td>
  </tr>
</table>
</br>
<table align="center" border="1" width="90%" style="text-align:center">
  <tr>
    <th colspan="3"><b>Membership</b></th>
  </tr>
  <tr align="left">
    <td>string</td>
    <td>name</td>
    <td>Nombre de la membresía</td>
  </tr>
  <tr align="left">
    <td>Money</td>
    <td>price</td>
    <td>Costo de la membresía</td>
  </tr>
  <tr align="left">
    <td>void</td>
    <td>subscribe()</td>
    <td>Obtener subscripción</td>
  </tr>
</table>
</br>
<table align="center" border="1" width="90%" style="text-align:center">
  <tr>
    <th colspan="3"><b>Money</b></th>
  </tr>
  <tr align="left">
    <td>float</td>
    <td>amount</td>
    <td>Monto</td>
  </tr>
  <tr align="left">
    <td>string</td>
    <td>currecny</td>
    <td>Nombre de la divisa</td>
  </tr>
  <tr align="left">
    <td>void</td>
    <td>get_amount()</td>
    <td>Obtener monto de la factura</td>
  </tr>
  <tr align="left">
    <td>void</td>
    <td>get_currency()</td>
    <td>Obtener divisa de la factura</td>
  </tr>
</table>
</br>
<table align="center" border="1" width="90%" style="text-align:center">
  <tr>
    <th colspan="3"><b>PaymentManager</b></th>
  </tr>
  <tr align="left">
    <td>User</td>
    <td>user</td>
    <td>Identificador del usuario</td>
  </tr>
  <tr align="left">
    <td>Payment</td>
    <td>payment</td>
    <td>Identificador del pago</td>
  </tr>
   <tr align="left">
    <td>void</td>
    <td>doPayment()</td>
    <td>Realizar pago</td>
  </tr>
</table>
</br>
<table align="center" border="1" width="90%" style="text-align:center">
  <tr>
    <th colspan="3"><b>Payment</b></th>
  </tr>
   <tr align="left">
    <td>void</td>
    <td>pay()</td>
    <td>Firmar para el pago</td>
  </tr>
</table>
</br>
<table align="center" border="1" width="90%" style="text-align:center">
  <tr>
    <th colspan="3"><b>ProxyBankCard</b></th>
  </tr>
   <tr align="left">
    <td>Payment</td>
    <td>payment</td>
    <td>Identificador del pago</td>
  </tr>
  <tr align="left">
    <td>bool</td>
    <td>validePayment()</td>
    <td>Verifica el pago</td>
  </tr>
  <tr align="left">
    <td>void</td>
    <td>pay()</td>
    <td>Se realiza el pago si la función validePayment() retorna verdadero</td>
  </tr>
</table>
</br>
<table align="center" border="1" width="90%" style="text-align:center">
  <tr>
    <th colspan="3"><b>Mastercard</b></th>
  </tr>
   <tr align="left">
    <td>int</td>
    <td>num</td>
    <td>Número de la tarjeta</td>
  </tr>
  <tr align="left">
    <td>int</td>
    <td>cvv</td>
    <td>Código de seguridad de la tarjeta</td>
  </tr>
  <tr align="left">
    <td>string</td>
    <td>owner_name</td>
    <td>Dueño de la tarjeta</td>
  </tr>
  <tr align="left">
    <td>void</td>
    <td>pay()</td>
    <td>Realizar pago con la tarjeta</td>
  </tr>
</table>
</br>
<table align="center" border="1" width="90%" style="text-align:center">
  <tr>
    <th colspan="3"><b>Visa</b></th>
  </tr>
   <tr align="left">
    <td>int</td>
    <td>num</td>
    <td>Número de la tarjeta</td>
  </tr>
  <tr align="left">
    <td>int</td>
    <td>cvv</td>
    <td>Código de seguridad de la tarjeta</td>
  </tr>
  <tr align="left">
    <td>string</td>
    <td>owner_name</td>
    <td>Dueño de la tarjeta</td>
  </tr>
  <tr align="left">
    <td>void</td>
    <td>pay()</td>
    <td>Realizar pago con la tarjeta</td>
  </tr>
</table>
</br>
<table align="center" border="1" width="90%" style="text-align:center">
  <tr>
    <th colspan="3"><b>Employer</b></th>
  </tr>
   <tr align="left">
    <td>string</td>
    <td>description</td>
    <td>Descripción del perfil del empleador</td>
  </tr>
  <tr align="left">
    <td>void</td>
    <td>createJob()</td>
    <td>Publicar trabajo</td>
  </tr>
</table>
</br>
<table align="center" border="1" width="90%" style="text-align:center">
  <tr>
    <th colspan="3"><b>Worker</b></th>
  </tr>
   <tr align="left">
    <td>string</td>
    <td>description</td>
    <td>Descripción del perfil del trabajador</td>
  </tr>
  <tr align="left">
    <td>string</td>
    <td>occupation</td>
    <td>Ocupación del trabajador</td>
  </tr>
  <tr align="left">
    <td>List(Certificate)</td>
    <td>certificates</td>
    <td>Lista de certificados del trabajador</td>
  </tr>
  <tr align="left">
    <td>void</td>
    <td>searchJob()</td>
    <td>Buscar trabajo</td>
  </tr>
</table>
</br>
<table align="center" border="1" width="90%" style="text-align:center">
  <tr>
    <th colspan="3"><b>Certificate</b></th>
  </tr>
   <tr align="left">
    <td>int</td>
    <td>id</td>
    <td>Identificador único del certificado</td>
  </tr>
  <tr align="left">
    <td>string</td>
    <td>name</td>
    <td>Nombre del certificado</td>
  </tr>
  <tr align="left">
    <td>void</td>
    <td>seeCertificates()</td>
    <td>Visualizar certificados</td>
  </tr>
</table>
</br>
<table align="center" border="1" width="90%" style="text-align:center">
  <tr>
    <th colspan="3"><b>Contract</b></th>
  </tr>
   <tr align="left">
    <td>int</td>
    <td>id</td>
    <td>Identificador único del contrato</td>
  </tr>
   <tr align="left">
    <td>string</td>
    <td>content</td>
    <td>Contenido del contrato</td>
  </tr>
    <tr align="left">
    <td>date</td>
    <td>start_Day</td>
    <td>Fecha de inicio del contrato</td>
  </tr>
    <tr align="left">
    <td>date</td>
    <td>end_day</td>
    <td>Fecha de fin del contrato</td>
  </tr>
    <tr align="left">
    <td>Employer</td>
    <td>employer</td>
    <td>Identificador del empleador</td>
  </tr>
   <tr align="left">
    <td>Worker</td>
    <td>worker</td>
    <td>Identificador del trabajador</td>
  </tr>
  <tr align="left">
    <td>float</td>
    <td>salary</td>
    <td>Salario del contrato</td>
  </tr>
  <tr align="left">
    <td>Service</td>
    <td>service</td>
    <td>Identificador del servicio indicando en el contrato</td>
  </tr>
  <tr align="left">
    <td>void</td>
    <td>createJob()</td>
    <td>Crear empleo</td>
  </tr>
</table>
</br>
<table align="center" border="1" width="90%" style="text-align:center">
  <tr>
    <th colspan="3"><b>Service</b></th>
  </tr>
   <tr align="left">
    <td>int</td>
    <td>id</td>
    <td>Identificador único del servicio</td>
  </tr>
  <tr align="left">
    <td>string</td>
    <td>description</td>
    <td>Descripción del servicio</td>
  </tr>
  <tr align="left">
    <td>List(Review)</td>
    <td>reviews</td>
    <td>Comentarios del servicio</td>
  </tr>
  <tr align="left">
    <td>List(Claim)</td>
    <td>claims</td>
    <td>Reclamos del servicio</td>
  </tr>
  <tr align="left">
    <td>void</td>
    <td>createJob()</td>
    <td>Crear empleo</td>
  </tr>
</table>
</br>
<table align="center" border="1" width="90%" style="text-align:center">
  <tr>
    <th colspan="3"><b>Review</b></th>
  </tr>
   <tr align="left">
    <td>int</td>
    <td>id</td>
    <td>Identificador único del comentario</td>
  </tr>
  <tr align="left">
    <td>string</td>
    <td>message</td>
    <td>Enunciado del comentario</td>
  </tr>
  <tr align="left">
    <td>void</td>
    <td>sendReview()</td>
    <td>Enviar comentario</td>
  </tr>
</table>
</br>
<table align="center" border="1" width="90%" style="text-align:center">
  <tr>
    <th colspan="3"><b>Claim</b></th>
  </tr>
   <tr align="left">
    <td>int</td>
    <td>id</td>
    <td>Identificador único del reclamo</td>
  </tr>
  <tr align="left">
    <td>string</td>
    <td>message</td>
    <td>Enunciado del reclamo</td>
  </tr>
  <tr align="left">
    <td>List(Evidence)</td>
    <td>evidences</td>
    <td>Lista de las evidencias</td>
  </tr>
  <tr align="left">
    <td>void</td>
    <td>sendClaim()</td>
    <td>Enviar reclamo</td>
  </tr>
</table>
</br>
<table align="center" border="1" width="90%" style="text-align:center">
  <tr>
    <th colspan="3"><b>Evidence</b></th>
  </tr>
   <tr align="left">
    <td>int</td>
    <td>id</td>
    <td>Identificador único de la evidencia</td>
  </tr>
  <tr align="left">
    <td>string</td>
    <td>message</td>
    <td>Contenido de la evidencia</td>
  </tr>
  <tr align="left">
    <td>void</td>
    <td>upload()</td>
    <td>Adjuntar</td>
  </tr>
</table>
</br>
<table align="center" border="1" width="90%" style="text-align:center">
  <tr>
    <th colspan="3"><b>Image</b></th>
  </tr>
   <tr align="left">
    <td>void</td>
    <td>upload</td>
    <td>Subir imágen</td>
  </tr>
</table>
</br>
<table align="center" border="1" width="90%" style="text-align:center">
  <tr>
    <th colspan="3"><b>Archive</b></th>
  </tr>
   <tr align="left">
    <td>void</td>
    <td>upload</td>
    <td>Subir archivo</td>
  </tr>
</table>

## 4.8. Database Design
### 4.8.1. Database Diagram

A continuación presentaremos el Database Diagram:

<div align=center>
    <img src="https://cdn.discordapp.com/attachments/1038843215094227044/1149508720963887114/Database_ChambeaPe.png" alt="Database diagram"  width="90%"/>
</div> 

<br><br>

# Capítulo V: Product Implementation, Validation & Deployment
A continuación, presentaremos el proceso por el cual organizamos, gestionamos y controlamos los cambios en el desarrollo de este proyecto.  

### 5.1.1. Software Development Environment Configuration

El software necesita diferentes entornos para su desarrollo, prueba, despliegue y operación. La configuración del entorno de implementación de software es una actividad que se ocupa de crear y mantener estos entornos. Es por ello que en este apartado detallaremos las herramientas usadas.

<br>

**Project Management** 
1.	Notion:  https://www.notion.so/ 
Empleamos Notion para organizar las actividades que teníamos que realizar, principalmente respecto al desarrollo de este informe. Realizábamos seguimiento del estatus de las actividades, con la facilidad de organizarnos como equipo. Esta es una aplicación que te permite crear y gestionar tu propio espacio de trabajo conectado de manera intuitiva.

2.	Discord: https://discord.com/ 
Discord es una aplicación que te permite comunicarte por voz, video y texto con tus amigos y comunidades. Se empleó esta herramienta como el medio para realizar reuniones de trabajo con los integrantes del equipo.

**Requirements Managements**
1.	Trello: https://trello.com/ 
    
    Usamos esta herramienta para el manejo de nuestros requerimientos con el objetivo de organizar de manera más efectiva el backlog en equipo. Trello es una aplicación para gestionar proyectos. Te permite crear y organizar tareas, plazos y equipos. Trello se adapta a cualquier tipo de proyecto y se integra con otras aplicaciones.  
  
**Product UX/UI Design** 
1.	UXPressia: https://uxpressia.com/ 
    
    Esta herramienta nos ayudó en el desarrollo de nuestras User Personas, el Customer Journey Map, Empathy Map e Impac Map. Debido a que nos ofrece platillas para el desarrollo ágil de estos artefactos.
2.	Mural: https://www.mural.co/ 

    Realizamos nuestro scenarios mapping para nuestros dos segmentos objetivos debido a que mural es una herramienta fácil de usar y nos brinda plantillas de uso libre.
3.	Figma: https://www.figma.com/ 
    
    Usamos esta herramienta para la creación de nuestros Wireframes, mockups y mobile aplication prototyping ya que permite trabajar de manera colaborativa y tiene muchas utilidades.  
  
**Software Development** 
1.	Landing Page

    Para el desarrollo nuestro landing page usamos herramientas básicas para el diseño de páginas web como lo son: HTML5, CSS3 y JavaScript.  
  
**Software Documentation**
1.	LucidChart: https://lucid.app/ 
    
    Esta herramienta la usamos para el desarrllo de user flows diagrams, wireflows y el diagrama de clases. En LucidChart se pueden crear diversos diagramas de forma rápida y colaborativa.
2.	Structurizr: https://www.structurizr.com/ 
    
    Nos permitió realizar los diagramas C4 de manera rápida con el lenguaje de programación C#. 
3.	Vertabelo: https://vertabelo.com/ 

    Realizamos nuestra base de datos en esta herramienta debido que cuenta con una amplia variedad de motores y permite trabajar colaborativamente. 

### 5.1.2. Source Code Management

El manejo y registro de las modificaciones de nuestra landing page y este documento lo manejamos mediante una organización en Github.
- Organization: https://github.com/Web-Applications-SW53-Group-3
- Landing Page Repository: https://github.com/Web-Applications-SW53-Group-3/Landing-Page 
- Report Repository: https://github.com/Web-Applications-SW53-Group-3/Report-Group-03  

Además, para mejorar el control de nuestro proyecto usamos GitFlow para la creación de ramas y cambios en el código fuente.
Es por ello que se manejan dos ramas principales: main y develop.
-	Main: La rama main almacena el historial oficial de las publicaciones de nuestro repositorio listas para producción.
-	Develop: Esta rama sirve como una rama de integración para las características (“features”).
Ramas auxiliares:
-	Feature: Para desarrollar nuevas funcionalidades o mejoras a partir de la rama develop y fusionarlas con ella al terminar. Estas ramas permiten trabajar en el código sin afectar a la estabilidad de la rama develop, y facilitan la revisión y el control de calidad de las características antes de integrarlas.
-	Realese: Para preparar una nueva versión del proyecto a partir de la rama develop y fusionarla con la rama main y con la rama develop al terminar. Estas ramas permiten realizar correcciones de errores y tareas urgentes sin introducir nuevas características, y aseguran que la rama main solo reciba código probado y listo para publicar.
-	Hotflix: Para solucionar errores críticos o urgentes a partir de la rama main y fusionarla con la rama main y con la rama develop al terminar. Estas ramas permiten actuar rápidamente ante situaciones imprevistas que afecten al funcionamiento del proyecto, y garantizan que los cambios se reflejen tanto en la versión actual como en la versión en desarrollo.
Commit Conventions
Para el formato de nuestros commits nos hemos basado en la estructura de los “Conventional Commits” en su versión 1.0.0 (https://www.conventionalcommits.org/en/v1.0.0/). Seguimos el siguiente formato:
<type>[optional scope]:<description>
“feat: add chapter 1.1”
Donde:
-	Type: Es un identificador que indica el tipo de cambio que se ha realizado en el código. Puede ser uno de los siguientes valores: feat, fix, docs, style, refactor, perf, test, build, ci, chore, revert. 
-	Scope: Es un identificador opcional que indica el alcance o el contexto del cambio. Puede ser cualquier palabra que ayude a diferenciar el cambio de otros similares. Por ejemplo: [login], [navbar], [api], etc. 
-	Description: Es una descripción breve y concisa del cambio que se ha realizado. Debe explicar qué se ha hecho y por qué, pero no cómo.

### 5.1.3. Source Code Style Guide & Conventions

Para el desarrollo de la parte de HTML y CSS, seguiremos las convenciones del Google HTML/CSS Style Guide, que nos indica cómo trabajar con estas tecnologías. Algunas de las convenciones que aplicaremos son:
- Declarar siempre el tipo de documento con <DOCTYPE html>
- Usar siempre minúsculas para los nombres de los elementos HTML (como &lt;p&gt;, &lt;h1&gt;, &lt;section&gt;, etc.)
- Cerrar siempre los elementos HTML (por ejemplo, &lt;p&gt; &lt;/p&gt;)
- Poner siempre entre comillas los atributos de los elementos HTML (por ejemplo, &lt;p class="name"&gt;&lt;/p&gt;)
- Especificar alt, width y height para las imágenes
- Evitar líneas de código muy largas
- No olvidar el elemento &lt;title&gt; al principio
- Usar meta tags al inicio
Para el lenguaje JavaScript, seguiremos las convenciones del Google JavaScript Style Guide. Algunas de las convenciones que aplicaremos son:
- Nombrar las variables y funciones con camelcase, como "numberArray"
- Usar comillas simples para los strings, como 'This is a string'
- Usar punto y coma (; )  al final de cada sentencia
- Evitar declarar variables con var y usar *let* o *const* en su lugar

### 5.1.4. Software Deployment Configuration

**Landing Page:** En este caso, se utilizó el servicio "GitHub Pages" para desplegar la aplicación de manera automática desde una rama de GitHub. Este servicio generará un enlace con un dominio específico que permitirá acceder a la página. El proceso se lleva a cabo de la siguiente manera:

1. Después de lanzar la versión final al repositorio y asegurarse de que las ramas estén actualizadas, se accede a la plataforma GitHub.
   
   <img src="https://media.discordapp.net/attachments/1145421916413366426/1149635769321930825/image.png?width=2880&height=1082" width="90%" alt="Paso 01">
   
2. A continuación, se selecciona el repositorio del proyecto en cuestión.
   
   <img src="https://media.discordapp.net/attachments/1145421916413366426/1149635342014627881/image.png?width=2130&height=1242" width="90%" alt="Paso 02">
   
3. Luego, se hace clic en la pestaña llamada "Settings
   
   <img src="https://media.discordapp.net/attachments/1145421916413366426/1149636431581552720/image.png?width=2132&height=1242" width="90%" alt="Paso 03">

4. Luego, activas el GitHub Pages en la sección de GitHub Pages y seleccionas la rama que contiene el código de la aplicación.

   <img src="https://media.discordapp.net/attachments/1142626132357828689/1149510946637750383/image.png?width=1522&height=1242" width="90%" alt="Paso 04">

5. Finalmente, se genera un enlace con el dominio específico que permite acceder a la aplicación.

    <img src="https://media.discordapp.net/attachments/1145421916413366426/1149633659696054333/image.png?width=2304&height=1240" width="90%" alt="Prototipo">
    
    **Link de la landing page:** https://web-applications-sw53-group-3.github.io/Landing-Page/

## 5.2. Landing Page, Services & Applications Implementation
### 5.2.1. Sprint 1
#### 5.2.1.1. Sprint Planning 1

En esta sección se especifican los detalles del Sprint Planning Meeting, que es una reunión que se lleva a cabo al inicio de cada sprint con la finalidad de establecer las tareas que se realizarán durante el período determinado.

<table align="center"  border="1" width="70%" style="text-align:center;">
    <tr align="left">
        <td>
            <b>Sprint #</b>
        </td>
        <td>
            <b>Sprint 1</b>           
        </td>
    </tr>
    <tr align="left">
        <td colspan="2">
            <b>Sprint Planning Background</b>
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>Date</b>
        </td>
        <td>
            07/09/23         
        </td>
    </tr>
       <tr align="left">
        <td>
            <b>Time</b>
        </td>
        <td>
            16:00 pm         
        </td>
    </tr>
       <tr align="left">
        <td>
            <b>Location</b>
        </td>
        <td>
            Modalidad remota por Discord      
        </td>
    </tr>
     </tr>
       <tr align="left">
        <td>
            <b>Prepared By</b>
        </td>
        <td>
            Digital Dart     
        </td>
    </tr>
    </tr>
       <tr align="left">
        <td>
            <b>Attendess (to planning meeting)</b>
        </td>
        <td>
            Todos los miembros del grupo Digital Dart     
        </td>
    </tr>
      </tr>
       <tr align="left">
        <td>
            <b>Sprint n - 0</b>
            <b>Review Summary</b>
        </td>
        <td>
            Se establecieron las primeras historias de usuario centradas en el desarrollo del Landing Page y la implementación de la lógica de funcionamiento para la plataforma ChambeaPe.
            </br></br>
Se cumplió con éxito el despliegue del Landing Page dentro del plazo acordado.
</br></br>
La documentación se ha enriquecido con la expansión de la visión de negocio y la incorporación de los artefactos correspondientes.   
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>Sprint n - 1</b>
            <b>Retrospective Summary</b>
        </td>
        <td>
            En líneas generales, hemos logrado mantener una excelente organización y comunicación como equipo, gracias al uso de plataformas como Discord. Sin embargo, siempre hay margen para mejorar aún más nuestra coordinación y colaboración en pos de la excelencia en nuestros proyectos.
</br></br>
Para garantizar un progreso continuo en nuestros proyectos, es esencial que perfeccionemos la estimación del desarrollo de los wireframes y mockups. Esto evitará posibles desajustes en nuestro calendario y garantizará un flujo de trabajo más estable.
</br></br>
Debemos hacer un uso más frecuente y consistente del formato Markdown en nuestra documentación y comunicaciones, ya que esto facilitará la lectura y comprensión de la información por parte de todos los miembros del equipo.  
        </td>
    </tr>
     <tr align="left">
        <td colspan="2">
            <b>Sprint Goal & User Stories</b>
        </td>
    </tr>
      <tr align="left">
        <td>
            <b>Sprint 1 Velocity</b>
        </td>
        <td>
            8  
        </td>
    </tr>
       <tr align="left">
        <td>
            <b>Sum of Story Points</b>
        </td>
        <td>
            8  
        </td>
    </tr>
</table>
</br>

#### 5.2.1.2. Sprint Backlog 1

En esta sección se especifican los detalles del Sprint Backlog, que es una lista de tareas que se deben realizar para completar el Sprint.
- [Click aqui para ver el Trello](https://trello.com/b/mfAT1Gn2/sprint-backlog)

<div align=center>
    <img src="https://cdn.discordapp.com/attachments/1145583761182965852/1149792374013317150/image.png" alt="Trello-Sprint"  width="90%"/>
</div>
</br>

<table align="center" border="1" width="90%" style="text-align:center">
    <tr>
       <td colspan="1"><b>Sprint #</b></td>
       <td colspan="7"><b>Sprint 1</b></td>
     </tr>
     <tr>
       <td colspan="2"><b>User Story</b></td>
       <td colspan="6"><b>Work-Item / Task</b></td>
     </tr>
     <tr>
       <td><b>Id</b></td>
       <td><b>Title</b></td>
       <td><b>Id</b></td>
       <td><b>Title</b></td>
       <td><b>Description</b></td>
       <td><b>Estimation(Hours)</b></td>
       <td><b>Assigned To</b></td>
       <td><b>Status(To-do/ In-Process/ To-Review/ Done)</b></td>
     </tr>
     <tr>
       <td rowspan="3">US01</td>
       <td rowspan="3">Implementación de CSS</td>
       <td>T01</td>
       <td>Agregar RESET</td>
       <td>Restablecer los estilos predeterminados del navegador</td>
       <td>0.5</td>
       <td>Jennifer Espinoza</td>
       <td>Done</td>
    </tr>
    <tr>
       <td>T02</td>
       <td>Agregar CSS main</td>
       <td>Dar formato y estilo a la sección principal</td>
       <td>3</td>
       <td>Diego Esquivel</td>
       <td>Done</td>
    </tr>
     <tr>
       <td>T03</td>
       <td>Agregar CSS footer</td>
       <td>Dar formato y estilo al pie de página </td>
       <td>2</td>
       <td>Diego Castro</td>
       <td>Done</td>
    </tr>
    <tr>
       <td rowspan="2">US02</td>
       <td rowspan="2">Implementación de Diseño Responsivo</td>
       <td>T04</td>
       <td>Agregar CSS main (media queries)</td>
       <td>Hacer responsive a la sección principal</td>
       <td>1</td>
       <td>Diego Castro</td>
       <td>Done</td>
    </tr>
    <tr>
       <td>T05</td>
       <td>Agregar CSS footer (media queries)</td>
       <td>Hacer responsive al pie de página
</td>
       <td>0.5</td>
       <td>Jennifer Espinoza</td>
       <td>Done</td>
    </tr>
   <tr>
       <td>US03</td>
       <td>Implementación de JavaScript</td>
       <td>T06</td>
       <td>Agregar Botón en JS HTML y CSS</td>
       <td>Agregar comportamientos dinámicos al botón, estructurarlo y estilizarlo</td>
       <td>2</td>
       <td>Steve Castillo</td>
       <td>Done</td>
    </tr>
   <tr>
       <td>US04</td>
       <td>Implementación de Cover</td>
       <td>T07</td>
       <td>Agregar cover landing page</td>
       <td>Diseñar una portada atractiva</td>
       <td>3</td>
       <td>Steve Castillo</td>
       <td>Done</td>
    </tr>
   </table>

#### 5.2.1.3. Development Evidence for Sprint Review

- Se presentan los commits realizados en el repositorio de GitHub, en el cual se puede observar el trabajo realizado por cada integrante del equipo.
</br>

[Link al respositorio de la Landing Page](https://github.com/Web-Applications-SW53-Group-3/Landing-Page)

<table  align="left" border="1" width="100%">
    <tr>
        <th >Repository</th>
        <th >Branch</th>
        <th>Commit ID</th>
        <th>Author</th>
        <th>Message</th>
        <th>Time ago</th>
    </tr>
    <tr>
        <td rowspan=16 >Landing Page</td>
        <td>develop</td>
        <td>7e3d940</td>
        <td>Steve Castillo</td>
        <td>Merge pull request #5 from Web-Applications-SW53-Group-3/realese/v1.0</td>
        <td>08/09/2023</td>
    </tr>
    <tr>
        <td>develop</td>
        <td>49ef152</td>
        <td>Steve Castillo</td>
        <td>Merge pull request #4 from Web-Applications-SW53-Group-3/realese/v1.0</td>
        <td>08/09/2023</td>
    </tr>
    <tr>
        <td>realese/v1.0</td>
        <td>1eedffb</td>
        <td>Steve Castillo</td>
        <td>Update meta tag and prepare to realese</td>
        <td>08/09/2023</td>
    </tr>
    <tr>
        <td>develop</td>
        <td>1291432</td>
        <td>Steve Castillo</td>
        <td>Merge pull request #3 from Web-Applications-SW53-Group-3/feature/implemet-JS</td>
        <td>08/09/2023</td>
    </tr>
    <tr>
        <td>feature/implemet-JS</td>
        <td>34d3498</td>
        <td>Steve Castillo</td>
        <td>feat: add JS button</td>
        <td>08/09/2023</td>
    </tr>
    <tr>
        <td>develop</td>
        <td>49648aa</td>
        <td>Jennifer Espinoza</td>
        <td>Merge pull request #2 from Web-Applications-SW53-Group-3/feature/implement-css</td>
        <td>08/09/2023</td>
    </tr>
    <tr>
        <td>implement-css</td>
        <td>49ed2df</td>
        <td>Jenn Espinoza</td>
        <td>feat: add footer responsive</td>
        <td>08/09/2023</td>
    </tr>
    <tr>
        <td>implement-css</td>
        <td>8f1587e</td>
        <td>Diego Castro</td>
        <td>feat: add footer css</td>
        <td>08/09/2023</td>
    </tr>
    <tr>
        <td>implement-css</td>
        <td>9c39952</td>
        <td>Diego Castro</td>
        <td>feat: add responsive home</td>
        <td>08/09/2023</td>
    </tr>
    <tr>
        <td>implement-css</td>
        <td>89bb8b0</td>
        <td>Diego Esquivel</td>
        <td>feat: add home css</td>
        <td>08/09/2023</td>
    </tr>
    <tr>
        <td>implement-css</td>
        <td>0ff61c3</td>
        <td>Jenn Espinoza</td>
        <td>feat: add reset</td>
        <td>08/09/2023</td>
    </tr>
    <tr>
        <td>develop</td>
        <td>11d5e7c</td>
        <td>Steve Castillo</td>
        <td>Merge pull request #1 from Web-Applications-SW53-Group-3/feature/html-structure</td>
        <td>07/09/2023</td>
    </tr>
    <tr>
        <td>feature/html-structure</td>
        <td>56b258c</td>
        <td>Diego Esquivel</td>
        <td>feat: add footer</td>
        <td>07/09/2023</td>
    </tr>
    <tr>
        <td>feature/html-structure</td>
        <td>b278468</td>
        <td>Steve Castillo</td>
        <td>feat: add main and header in html</td>
        <td>07/09/2023</td>
    </tr>
    <tr>
        <td>develop</td>
        <td>5a4f2eb</td>
        <td>Steve Castillo</td>
        <td>loaded workspace</td>
        <td>07/09/2023</td>
    </tr>
    <tr>
        <td>main</td>
        <td>74122ed</td>
        <td>Steve Castillo</td>
        <td>First Commit</td>
        <td>07/09/2023</td>
    </tr>
</table>

<br><br>

#### 5.2.1.4. Testing Suite Evidence for Sprint Review

Presentamos las pruebas de aceptación realizadas para el presente sprint. Para el desarrollo de las pruebas de aceptación se ha utilizado las siguientes herramientas:

[Link al repositorio de las pruebas en Gherkin](https://github.com/Web-Applications-SW53-Group-3/Acceptance-Tests/tree/develop)

<table align="left" border="1" width="100%">
  <tr>
    <th>Repository</th>
    <th >Branch</th>
    <th>Commit</th>
    <th>Author</th>
    <th>Message</th>
    <th>Date</th>
  </tr>
  <tr>
    <td rowspan=20>Acceptance-Tests</td>
    <td>develop</td>
    <td>0c9b918</td>
    <td>Diego Esquivel</td>
    <td>Merge pull request #7 from Web-Applications-SW53-Group-3/feature/epic07</td>
    <td>2023-09-08</td>
  </tr>
  <tr>
    <td>Feature/epic07</td>
    <td>3c674fd</td>
    <td>Diego Esquivel</td>
    <td>feat: add acceptance test 23</td>
    <td>2023-09-08</td>
  </tr>
  <tr>
    <td>Feature/epic07</td>
    <td>9f526fc</td>
    <td>Diego Esquivel</td>
    <td>feat: add acceptance test 20</td>
    <td>2023-09-08</td>
  </tr>
  <tr>
    <td>develop</td>
    <td>2623764</td>
    <td>Diego Esquivel</td>
    <td>Merge pull request #6 from Web-Applications-SW53-Group-3/feature/epic06</td>
    <td>2023-09-08</td>
  </tr>
  <tr>
    <td>feature/epic06</td>
    <td>64cc49d</td>
    <td>Diego Esquivel</td>
    <td>feat: add acceptance test 19</td>
    <td>2023-09-08</td>
  </tr>
  <tr>
    <td>develop</td>
    <td>51c93b5</td>
    <td>Diego Esquivel</td>
    <td>Merge pull request #5 from Web-Applications-SW53-Group-3/feature/epic05</td>
    <td>2023-09-08</td>
  </tr>
  <tr>
    <td>feature/epic05</td>
    <td>d01f26d</td>
    <td>Diego Esquivel</td>
    <td>feat: add acceptance test 18</td>
    <td>2023-09-08</td>
  </tr>
  <tr>
    <td>develop</td>
    <td>a9170bb</td>
    <td>Diego Esquivel</td>
    <td>Merge pull request #4 from Web-Applications-SW53-Group-3/feature/epic04</td>
    <td>2023-09-08</td>
  </tr>
  <tr>
    <td>Feature/epic04</td>
    <td>d12a2f6</td>
    <td>Diego Esquivel</td>
    <td>feat: add acceptance test 17</td>
    <td>2023-09-08</td>
  </tr>
  <tr>
    <td>Feature/epic04</td>
    <td>5b04ecd</td>
    <td>Diego Esquivel</td>
    <td>feat: add acceptance test 12</td>
    <td>2023-09-08</td>
  </tr>
  <tr>
    <td>develop</td>
    <td>f2e61ce</td>
    <td>Diego Esquivel</td>
    <td>Merge pull request #3 from Web-Applications-SW53-Group-3/feature/epic03</td>
    <td>2023-09-08</td>
  </tr>
  <tr>
    <td>Feature/epic03</td>
    <td>666ce51</td>
    <td>Diego Esquivel</td>
    <td>feat: add acceptance test 09</td>
    <td>2023-09-08</td>
  </tr>
  <tr>
    <td>Feature/epic03</td>
    <td>95083ad</td>
    <td>Diego Esquivel</td>
    <td>feat: add acceptance test 08</td>
    <td>2023-09-08</td>
  </tr>
  <tr>
    <td>develop</td>
    <td>0574b53</td>
    <td>Diego Esquivel</td>
    <td>Merge pull request #2 from Web-Applications-SW53-Group-3/feature/epic02</td>
    <td>2023-09-08</td>
  </tr>
  <tr>
    <td>Feature/epic02</td>
    <td>6100269</td>
    <td>Diego Esquivel</td>
    <td>feat: add acceptance test 05</td>
    <td>2023-09-08</td>
  </tr>
  <tr>
    <td>Feature/epic02</td>
    <td>eb38512</td>
    <td>Diego Esquivel</td>
    <td>feat: add acceptance test 04</td>
    <td>2023-09-08</td>
  </tr>
  <tr>
    <td>develop</td>
    <td>3816a93</td>
    <td>Jennifer Espinoza</td>
    <td>Merge pull request #1 from Web-Applications-SW53-Group-3/feature/epic01</td>
    <td>2023-09-08</td>
  </tr>
  <tr>
    <td>Feature/epic01</td>
    <td>66f3d97</td>
    <td>Diego Esquivel</td>
    <td>feat: add acceptance test 02</td>
    <td>2023-09-08</td>
  </tr>
  <tr>
    <td>Feature/epic01</td>
    <td>343f096</td>
    <td>Diego Esquivel</td>
    <td>feat: add acceptance test 01</td>
    <td>2023-09-08</td>
  </tr>
  <tr>
    <td>main</td>
    <td>825903c</td>
    <td>Diego Esquivel</td>
    <td>Initial commit</td>
    <td>2023-09-08</td>
  </tr>
</table>


#### 5.2.1.5. Execution Evidence for Sprint Review

En este apartado se verán los resultados de la implementación del Landin Page. donde nos conocerás un poco más y verás a los top usuarios de la plataforma.

<div align=center>
    <img src="https://cdn.discordapp.com/attachments/1145583761182965852/1149750519603155015/parte_01.png" alt="LP-1"  width="70%"/>
</div>
</br>

<div align=center>
    <img src="https://cdn.discordapp.com/attachments/1145583761182965852/1149750517971570769/parte_02.png" alt="LP-2"  width="70%"/>
</div>
</br>

<div align=center>
    <img src="https://cdn.discordapp.com/attachments/1145583761182965852/1149750518361620581/parte_03.png" alt="LP-3"  width="70%"/>
</div>
</br>

<div align=center>
    <img src="https://cdn.discordapp.com/attachments/1145583761182965852/1149750518634266624/parte_04.png" alt="LP-4"  width="70%"/>
</div>
</br>

<div align=center>
    <img src="https://cdn.discordapp.com/attachments/1145583761182965852/1149750518915280986/parte_05.png" alt="LP-5"  width="70%"/>
</div>
</br>

<div align=center>
    <img src="https://cdn.discordapp.com/attachments/1145583761182965852/1149750519271800944/parte_06.png" alt="LP-6"  width="70%"/>
</div>
</br>

#### 5.2.1.6. Services Documentation Evidence for Sprint Review

Durante el primer sprint, se ha creado el landing page como primer paso del proyecto, sin que se haya hecho uso de web services para su funcionamiento.

Para saber más sobre los web services, se le deja un pequeño resumen de lo que son y para qué sirven.

- Un web service es un software que permite la comunicación e intercambio de datos entre distintas aplicaciones, independientemente del lenguaje de programación o la plataforma en la que se hayan desarrollado. Los web services facilitan la integración y la interoperabilidad entre sistemas heterogéneos.

#### 5.2.1.7. Software Deployment Evidence for Sprint Review

Para el presente sprint, se ha desarrollado el landing page. Para el desarrollo del landing page se ha utilizado las siguientes herramientas:

- Git: Sistema de control de versiones que nos ayudó a trabajar en equipo durante el desarrollo del landing page. Git es un software que permite a los desarrolladores crear y mantener un historial de los cambios realizados en el código fuente del proyecto. Con Git, podemos crear ramas para trabajar en diferentes partes del código sin afectar al resto, fusionar los cambios cuando estén listos y revertirlos si hay algún error.

- GitFlow: Flujo de trabajo que no ayudó a controlar el avance de cada integrante del equipo en el desarrollo del landing page. GitFlow es un modelo de ramificación de Git que define una estructura estándar para organizar las diferentes versiones y características del código. Con GitFlow, podemos tener una rama principal (master o main) que contiene el código más estable y seguro, una rama de desarrollo (develop) que contiene el código en progreso, y varias ramas auxiliares (feature, release, hotfix) que sirven para desarrollar nuevas funcionalidades, preparar lanzamientos y corregir errores urgentes respectivamente.

- GitHub: Plataforma que nos ayudó al desarrollo colaborativo del equipo para almacenar las versiones de nuestro proyecto. GitHub es un servicio web que utiliza Git para alojar repositorios remotos y facilitar la colaboración entre los desarrolladores. Con GitHub, podemos subir nuestro código a la nube, compartirlo con otros usuarios, recibir comentarios y sugerencias, hacer seguimiento de las tareas y los problemas, y acceder a miles de proyectos de código abierto.

- Github Pages: Servicio que nos permitió publicar nuestro landing page directamente desde nuestro repositorio de GitHub. GitHub Pages es una forma sencilla de crear sitios web estáticos para nuestros proyectos, usando temas preconfigurados o personalizados. Con GitHub Pages, podemos mostrar nuestro landing page al mundo sin necesidad de contratar un servidor o un dominio.

#### 5.2.1.8. Team Collaboration Insights during Sprint

El landing page fue creado por el equipo usando el modelo de gitflow, que consiste en usar diferentes ramas para trabajar en cada parte, optimizarlo y ponerlo al día. El beneficio de emplear este modelo es que facilita actualizar y hacer cambios para después mostrarlos y verificar que no exista ningún problema al fusionarlos con la rama principal. Seguidamente, se muestra el conocimiento que obtuvo el equipo mediante la plataforma GitHub.

- Nuetro Gitflow se representa de la siguiente manera:

<div align=center>
    <img src="https://cdn.discordapp.com/attachments/1145583761182965852/1149763951350005770/Gitflow.png" alt="gitflow"  width="90%"/>
</div>
</br>

- Las contribuciones de cada integrante del equipo se muestran a continuación:

<div align=center>
    <img src="https://cdn.discordapp.com/attachments/1145583761182965852/1149763951568093245/Contribuciones.png" alt="contributions"  width="90%"/>
</div>
</br><br>

### 5.2.2. Sprint 2
#### 5.2.2.1. Sprint Planning 2

<table align="center"  border="1" width="80%" style="text-align:center;">
    <tr align="left">
        <td>
            <b>Sprint #</b>
        </td>
        <td>
            <b>Sprint 2</b>           
        </td>
    </tr>
    <tr align="left">
        <td colspan="2">
            <b>Sprint Planning Background</b>
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>Date</b>
        </td>
        <td>
            25/09/23         
        </td>
    </tr>
       <tr align="left">
        <td>
            <b>Time</b>
        </td>
        <td>
            16:00 pm         
        </td>
    </tr>
       <tr align="left">
        <td>
            <b>Location</b>
        </td>
        <td>
            Modalidad remota por Discord      
        </td>
    </tr>
     </tr>
       <tr align="left">
        <td>
            <b>Prepared By</b>
        </td>
        <td>
            Digital Dart     
        </td>
    </tr>
    </tr>
       <tr align="left">
        <td>
            <b>Attendess (to planning meeting)</b>
        </td>
        <td>
            Todos los miembros del grupo Digital Dart     
        </td>
    </tr>
      </tr>
       <tr align="left">
        <td>
            <b>Sprint 2</b>
            <b>Review Summary</b>
        </td>
        <td>
            En el Sprint 2, nuestro equipo de desarrollo se centró en implementar mejoras sustanciales en la aplicación ChambeaPe. Logramos completar con éxito todas las historias de usuario y tareas planificadas para este sprint, lo que incluyó la implementación exitosa de funciones clave. Esto abarcó desde la habilitación de un inicio de sesión y registro, permitiendo a los usuarios acceder de manera segura, hasta la visualización de perfiles para que los empleadores puedan evaluar a los chambeadores antes de contratarlos. Además, facilitamos la gestión de anuncios de trabajo, permitiendo a los empleadores crear, editar y eliminar anuncios con facilidad. En resumen, el sprint fue un éxito gracias a la colaboración y comunicación efectiva de nuestro equipo.
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>Sprint 2</b>
            <b>Retrospective Summary</b>
        </td>
        <td>
        Para este sprint se planea desarrollar avances del front-end de la aplicación web. Se planea desarrollar las funcionalidades de inicio de sesión, registro, visualización de perfiles de chambeadores, creación de anuncios de trabajo, cambio de contraseña y recuperación de contraseña. Asimismo hemos organizado las tareas a realizar en el tablero de Trello y hemos asignado a cada miembro del equipo las tareas que le corresponden. Para nuestro despliegue vamos a usar la plataforma de Google Firebase.
        </td>
    </tr>
     <tr align="left">
        <td colspan="2">
            <b>Sprint Goal & User Stories</b>
        </td>
    </tr>
      <tr align="left">
        <td>
            <b>Sprint 2 Velocity</b>
        </td>
        <td>
            4
        </td>
    </tr>
       <tr align="left">
        <td>
            <b>Sum of Story Points</b>
        </td>
        <td>
            15
        </td>
    </tr>
</table>
</br>
<br>

#### 5.2.2.2. Sprint Backlog 2
En esta sección se especifican los detalles del Sprint Backlog.

- [Click aqui para ver el Trello](https://trello.com/invite/b/Gefw1vfY/ATTIacaa4de609b1f27260ebda8a38ba5cf871CA4074/sprint-backlog-02)

<img src="https://media.discordapp.net/attachments/1145421916413366426/1156335087047155813/image.png?ex=65149878&is=651346f8&hm=5903a8e985f805a035c0a12178a047bf1b9ab708a844cc10908782023beee456&=&width=2626&height=1242" alt="Trello-Sprint-2"  width="90%"> <img>

<table align="center" border="1" width="90%" style="text-align:center">
    <tr>
       <td colspan="1"><b>Sprint #</b></td>
       <td colspan="7"><b>Sprint 2</b></td>
     </tr>
     <tr>
       <td colspan="2"><b>User Story</b></td>
       <td colspan="6"><b>Work-Item / Task</b></td>
     </tr>
     <tr>
       <td><b>Id</b></td>
       <td><b>Title</b></td>
       <td><b>Id</b></td>
       <td><b>Title</b></td>
       <td><b>Description</b></td>
       <td><b>Estimation(Hours)</b></td>
       <td><b>Assigned To</b></td>
       <td><b>Status(To-do/ In-Process/ To-Review/ Done)</b></td>
     </tr>
     <tr>
       <td rowspan="3">US01</td>
       <td rowspan="3">Iniciar Sesión</td>
       <td>T01</td>
       <td>Implementar inicio de sesión exitoso</td>
       <td>Desarrollar la funcionalidad para permitir que los usuarios inicien sesión con su correo y contraseña correctamente.</td>
       <td>4</td>
       <td>Diego Castro</td>
       <td>Done</td>
    </tr>
    <tr>
       <td>T02</td>
       <td>Implementar inicio de sesión fallido</td>
       <td>Desarrollar la funcionalidad para mostrar un mensaje de error cuando los usuarios ingresan credenciales incorrectas.</td>
       <td>1.5</td>
       <td>Diego Castro</td>
       <td>Done</td>
    </tr>
    <tr>
       <td>T03</td>
       <td>Implementar recuperación de contraseñas</td>
       <td>Desarrollar la funcionalidad para permitir a los usuarios recuperar su contraseña mediante un proceso de restablecimiento.</td>
       <td>2.5</td>
       <td>Diego Esquivel</td>
       <td>Done</td>
    </tr>
    <tr>
       <td rowspan="3">US02</td>
       <td rowspan="3">Registrar con correo</td>
       <td>T01</td>
       <td>Implementar registro exitoso</td>
       <td>Desarrollar la funcionalidad para que los usuarios puedan registrarse con su correo electrónico y contraseña de manera exitosa.</td>
       <td>3</td>
       <td>Jennifer Espinoza</td>
       <td>Done</td>
    </tr>
    <tr>
       <td>T02</td>
       <td>Implementar registro fallido - Correo Inválido</td>
       <td>Desarrollar la funcionalidad para mostrar un mensaje de error cuando los usuarios ingresan un correo electrónico inválido durante el registro.</td>
       <td>2</td>
       <td>Jennifer Espinoza</td>
       <td>Done</td>
    </tr>
    <tr>
       <td>T03</td>
       <td>Implementar registro fallido - Contraseña Inválida</td>
       <td>Desarrollar la funcionalidad para mostrar un mensaje de error cuando los usuarios ingresan una contraseña inválida durante el registro.</td>
       <td>1</td>
       <td>Diego Castro</td>
       <td>Done</td>
    </tr>
    <tr>
       <td>US14</td>
       <td>Visualizar perfiles de chambeadores</td>
       <td>T01</td>
       <td>Implementar visualización de perfiles</td>
       <td>Desarrollar la funcionalidad para que los empleadores puedan ver los perfiles de los chambeadores y evaluar su experiencia y estilo de trabajo antes de contratarlos.</td>
       <td>4</td>
       <td>Diego Esquivel</td>
       <td>Done</td>
    </tr>
     <tr>
       <td rowspan="4">US15</td>
       <td rowspan="4">Visualizar perfiles de chambeadores</td>
       <td>T01</td>
       <td>Implementar creación de anuncios de trabajo</td>
       <td>Desarrollar la funcionalidad para que los empleadores puedan crear anuncios de trabajo en la aplicación web.</td>
       <td>4</td>
       <td>Jennifer Espinoza</td>
       <td>Done</td>
    </tr>
    <tr>
       <td>T02</td>
       <td>Implementar edición de anuncios de trabajo</td>
       <td>Desarrollar la funcionalidad para permitir a los empleadores filtrar perfiles por antigüedad mínima.</td>
       <td>3</td>
       <td>Steve Castillo</td>
       <td>Done</td>
    </tr>
    <tr>
       <td>T03</td>
       <td>Implementar eliminación de anuncios de trabajo</td>
       <td>Desarrollar la funcionalidad para que los empleadores puedan eliminar sus anuncios de trabajo cuando ya no los necesiten.</td>
       <td>3.5</td>
       <td>Steve Castiilo</td>
       <td>Done</td>
    </tr>
    <tr>
       <td>T04</td>
       <td>Implementar visualización de anuncios de trabajo creados</td>
       <td>Desarrollar la funcionalidad para que los empleadores puedan ver una lista de los anuncios de trabajo que han creado en la aplicación.</td>
       <td>3.5</td>
       <td>Steve Castillo</td>
       <td>Done</td>
    </tr>
   </table>

#### 5.2.2.3. Development Evidence for Sprint Review

A continuación se presentan los commits realizados en el repositorio de la apliación web en GitHub, en el cual se puede observar el trabajo realizado por cada integrante del equipo.

<table align="left" border="1" width="100%">
    <tr>
        <th >Repository</th>
        <th >Branch</th>
        <th>Commit ID</th>
        <th>Author</th>
        <th>Message</th>
        <th>Time ago</th>
    </tr>
    <tr>
        <td rowspan=56 >ChambeaPe-App</td>
        <td>develop</td>
        <td>2e953ff</td>
        <td>Steve Castillo</td>
        <td>Merge pull request #19 from Web-Applications-SW53-Group-3/feature/job-responosive</td>
        <td>2023-09-28</td>
    </tr>
    <tr>
        <td>feature/job-responosive</td>
        <td>af07584</td>
        <td>Steve Castillo</td>
        <td>feat: add responsive</td>
        <td>2023-09-28</td>
    </tr>
    <tr>
        <td>develop</td>
        <td>fc2deef</td>
        <td>Jennifer Espinoza</td>
        <td>Merge pull request #18 from Web-Applications-SW53-Group-3/feature/globalization</td>
        <td>2023-09-28</td>
    </tr>
    <tr>
        <td>feature/globalization</td>
        <td>05b00cc</td>
        <td>Jennifer Espinoza</td>
        <td>Merge branch 'feature/globalization' of https://github.com/Web-Applications-SW53-Group-3/ChambeaPe-App into feature/globalization</td>
        <td>2023-09-28</td>
    </tr>
    <tr>
        <td>feature/globalization</td>
        <td>eceda73</td>
        <td>Jennifer Espinoza</td>
        <td>feat: implement i18n in some components</td>
        <td>2023-09-28</td>
    </tr>
    <tr>
        <td>develop</td>
        <td>0a602c3</td>
        <td>Diego Castro</td>
        <td>Merge pull request #17 from Web-Applications-SW53-Group-3/feature/refactor</td>
        <td>2023-09-27</td>
    </tr>
    <tr>
        <td>feature/refactor</td>
        <td>1a82a5e</td>
        <td>Diego Castro</td>
        <td>feat: add refactoring</td>
        <td>2023-09-27</td>
    </tr>
    <tr>
        <td>feature/refactor</td>
        <td>189f524</td>
        <td>Diego Castro</td>
        <td>feat: add routes</td>
        <td>2023-09-27</td>
    </tr>
    <tr>
        <td>develop</td>
        <td>0a276d4</td>
        <td>Diego Esquivel</td>
        <td>Merge pull request #16 from Web-Applications-SW53-Group-3/Feature/language</td>
        <td>2023-09-27</td>
    </tr>
    <tr>
        <td>Feature/language</td>
        <td>f802154</td>
        <td>Diego Esquivel</td>
        <td>feat: add language-selector</td>
        <td>2023-09-27</td>
    </tr>
    <tr>
        <td>feature/globalization</td>
        <td>d33de95</td>
        <td>Jennifer Espinoza</td>
        <td>feat: change message i18n</td>
        <td>2023-09-27</td>
    </tr>
    <tr>
        <td>develop</td>
        <td>4ca55c7</td>
        <td>Diego Castro</td>
        <td>Merge pull request #15 from Web-Applications-SW53-Group-3/feature/google-login</td>
        <td>2023-09-27</td>
    </tr>
    <tr>
        <td>feature/google-login</td>
        <td>aa15ae7</td>
        <td>Diego Castro</td>
        <td>feat: add login redirection</td>
        <td>2023-09-27</td>
    </tr>
    <tr>
        <td>feature/login-redirection</td>
        <td>263ba33</td>
        <td>Diego Castro</td>
        <td>Merge pull request #14 from Web-Applications-SW53-Group-3/feature/login-redirection</td>
        <td>2023-09-27</td>
    </tr>
    <tr>
        <td>feature/login-redirection</td>
        <td>3976805</td>
        <td>Diego Castro</td>
        <td>feat: add login redirection</td>
        <td>2023-09-27</td>
    </tr>
    <tr>
        <td>develop</td>
        <td>4202da4</td>
        <td>Diego Castro</td>
        <td>Merge pull request #13 from Web-Applications-SW53-Group-3/feature/job-post-http</td>
        <td>2023-09-27</td>
    </tr>
    <tr>
        <td>feature/job-post-http</td>
        <td>c8e4720</td>
        <td>Diego Castro</td>
        <td>feat: add post creation</td>
        <td>2023-09-27</td>
    </tr>
    <tr>
        <td>develop</td>
        <td>16e7d5b</td>
        <td>Steve Castillo</td>
        <td>Merge pull request #12 from Web-Applications-SW53-Group-3/feature/responsive</td>
        <td>2023-09-27</td>
    </tr>
    <tr>
        <td>feature/responsive</td>
        <td>5a14c35</td>
        <td>Steve Castillo</td>
        <td>feat: add responsive</td>
        <td>2023-09-27</td>
    </tr>
    <tr>
        <td>develop</td>
        <td>64ecf29</td>
        <td>Diego Castro</td>
        <td>Merge pull request #11 from Web-Applications-SW53-Group-3/feature/globalization</td>
        <td>2023-09-27</td>
    </tr>
    <tr>
        <td>feature/globalization</td>
        <td>5d27daa</td>
        <td>Jennifer Espinoza</td>
        <td>fix: update i18n</td>
        <td>2023-09-27</td>
    </tr>
    <tr>
        <td>feature/globalization</td>
        <td>1f1ce24</td>
        <td>Jennifer Espinoza</td>
        <td>feat: implement messages i18n</td>
        <td>2023-09-27</td>
    </tr>
    <tr>
        <td>feature/job-post</td>
        <td>89917aa</td>
        <td>Jennifer Espinoza</td>
        <td>Merge pull request #10 from Web-Applications-SW53-Group-3/feature/job-post</td>
        <td>2023-09-27</td>
    </tr>
    <tr>
        <td>develop</td>
        <td>ea054e4</td>
        <td>Steve Castillo</td>
        <td>Merge pull request #9 from Web-Applications-SW53-Group-3/Feature/home</td>
        <td>2023-09-27</td>
    </tr>
    <tr>
        <td>Feature/home</td>
        <td>d7ca8bb</td>
        <td>Diego Esquivel</td>
        <td>feat: add home path</td>
        <td>2023-09-27</td>
    </tr>
    <tr>
        <td>Feature/home</td>
        <td>d02c0a2</td>
        <td>Diego Esquivel</td>
        <td>feat: add top-worker component</td>
        <td>2023-09-27</td>
    </tr>
    <tr>
        <td>Feature/home</td>
        <td>dced036</td>
        <td>Diego Esquivel</td>
        <td>feat: add top-employer component</td>
        <td>2023-09-27</td>
    </tr>
    <tr>
        <td>Feature/home</td>
        <td>2e0049d</td>
        <td>Diego Esquivel</td>
        <td>feat: add seeker component</td>
        <td>2023-09-27</td>
    </tr>
    <tr>
        <td>Feature/home</td>
        <td>31f0517</td>
        <td>Diego Esquivel</td>
        <td>feat: add home component</td>
        <td>2023-09-27</td>
    </tr>
    <tr>
        <td>develop</td>
        <td>296e1c0</td>
        <td>Steve Castillo</td>
        <td>Merge pull request #8 from Web-Applications-SW53-Group-3/Feature/reset_password</td>
        <td>2023-09-27</td>
    </tr>
    <tr>
        <td>Feature/reset_password</td>
        <td>ced37da</td>
        <td>Diego Esquivel</td>
        <td>fix: modify login component</td>
        <td>2023-09-27</td>
    </tr>
    <tr>
        <td>Feature/reset_password</td>
        <td>74ec4db</td>
        <td>Diego Esquivel</td>
        <td>feat: add updated-password component</td>
        <td>2023-09-27</td>
    </tr>
    <tr>
        <td>Feature/reset_password</td>
        <td>c73a181</td>
        <td>Diego Esquivel</td>
        <td>feat: add new-password component</td>
        <td>2023-09-27</td>
    </tr>
    <tr>
        <td>Feature/reset_password</td>
        <td>8f6be48</td>
        <td>Diego Esquivel</td>
        <td>feat: add verification-code component</td>
        <td>2023-09-27</td>
    </tr>
    <tr>
        <td>Feature/reset_password</td>
        <td>c4eb672</td>
        <td>Diego Esquivel</td>
        <td>feat: add forgot-password component</td>
        <td>2023-09-27</td>
    </tr>
    <tr>
        <td>feature/job-post</td>
        <td>803d8da</td>
        <td>Jennifer Espinoza</td>
        <td>feat: implement employer's job posts</td>
        <td>2023-09-27</td>
    </tr>
    <tr>
        <td>develop</td>
        <td>c9b0b34</td>
        <td>Jennifer Espinoza</td>
        <td>Merge pull request #7 from Web-Applications-SW53-Group-3/feature/register</td>
        <td>2023-09-27</td>
    </tr>
    <tr>
        <td>develop</td>
        <td>87064d1</td>
        <td>Jennifer Espinoza</td>
        <td>Merge branch 'develop' into feature/register</td>
        <td>2023-09-27</td>
    </tr>
    <tr>
        <td>feature/register</td>
        <td>2484dec</td>
        <td>Jennifer Espinoza</td>
        <td>fix: change path</td>
        <td>2023-09-27</td>
    </tr>
    <tr>
        <td>feature/register</td>
        <td>e6791b9</td>
        <td>Jennifer Espinoza</td>
        <td>fix: mofidy register form</td>
        <td>2023-09-27</td>
    </tr>
    <tr>
        <td>feature/register</td>
        <td>f1e413b</td>
        <td>Jennifer Espinoza</td>
        <td>feat: add register form</td>
        <td>2023-09-27</td>
    </tr>
    <tr>
        <td>develop</td>
        <td>02cb5cd</td>
        <td>Diego Castro</td>
        <td>Merge pull request #6 from Web-Applications-SW53-Group-3/feature/employer-post-edit</td>
        <td>2023-09-27</td>
    </tr>
    <tr>
        <td>feature/employer-post-edit</td>
        <td>8e390de</td>
        <td>Diego Castro</td>
        <td>feat: add edit and delete employer post</td>
        <td>2023-09-27</td>
    </tr>
    <tr>
        <td>develop</td>
        <td>c20bd2f</td>
        <td>Diego Castro</td>
        <td>Merge pull request #5 from Web-Applications-SW53-Group-3/feature/worker-profile</td>
        <td>2023-09-27</td>
    </tr>
    <tr>
        <td>feature/worker-profile</td>
        <td>2eefb02</td>
        <td>Diego Castro</td>
        <td>feat: add worker-profile component and service</td>
        <td>2023-09-27</td>
    </tr>
    <tr>
        <td>develop</td>
        <td>6e759a9</td>
        <td>Diego Castro</td>
        <td>Merge pull request #4 from Web-Applications-SW53-Group-3/feature/employer-myposts</td>
        <td>2023-09-27</td>
    </tr>
    <tr>
        <td>feature/employer-myposts</td>
        <td>bfb63cf</td>
        <td>Diego Castro</td>
        <td>feat: add employer 'my posts' component</td>
        <td>2023-09-27</td>
    </tr>
    <tr>
        <td>develop</td>
        <td>d1c286b</td>
        <td>Diego Castro</td>
        <td>Merge pull request #3 from Web-Applications-SW53-Group-3/feature/employer-post</td>
        <td>2023-09-25</td>
    </tr>
    <tr>
        <td>feature/employer-post</td>
        <td>c95b741</td>
        <td>Diego Castro</td>
        <td>Merge branch 'develop' into feature/employer-post</td>
        <td>2023-09-25</td>
    </tr>
    <tr>
        <td>feature/employer-post</td>
        <td>4d47427</td>
        <td>Diego Castro</td>
        <td>feat: add employer-post services</td>
        <td>2023-09-25</td>
    </tr>
    <tr>
        <td>develop</td>
        <td>e35953f</td>
        <td>Steve Castillo</td>
        <td>Merge pull request #2 from Web-Applications-SW53-Group-3/feature/navigation</td>
        <td>2023-09-25</td>
    </tr>
    <tr>
        <td>feature/navigation</td>
        <td>af4bdaa</td>
        <td>Steve Castillo</td>
        <td>feat:add nav component</td>
        <td>2023-09-25</td>
    </tr>
    <tr>
        <td>develop</td>
        <td>ee17a89</td>
        <td>Diego Castro</td>
        <td>Merge pull request #1 from Web-Applications-SW53-Group-3/feature/login</td>
        <td>2023-09-24</td>
    </tr>
    <tr>
        <td>feature/login</td>
        <td>a303475</td>
        <td>Diego Castro</td>
        <td>feat: add login services</td>
        <td>2023-09-24</td>
    </tr>
    <tr>
        <td>feature/login</td>
        <td>aedaeb2</td>
        <td>Diego Castro</td>
        <td>feat: add login styles</td>
        <td>2023-09-20</td>
    </tr>
    <tr>
        <td>feature/login</td>
        <td>35be50d</td>
        <td>Diego Castro</td>
        <td>feat: add login component</td>
        <td>2023-09-19</td>
    </tr>
</table>

Repositorio Github: https://github.com/Web-Applications-SW53-Group-3/ChambeaPe-App

#### 5.2.2.4. Testing Suite Evidence for Sprint Review

En el alcance del sprint 2 se ha desarrollado solo nuestro front-end de la aplicación web de ChambeaPe como primera instancia. Por ello no se evidencia el Testing Suite en este spring Boot.

<table align="left" border="1" width="100%">
  <tr>
    <th>Repository</th>
    <th >Branch</th>
    <th>Commit</th>
    <th>Author</th>
    <th>Message</th>
    <th>Date</th>
  </tr>
  <tr>
    <td rowspan=20></td>
    <td> </td>
    <td> </td>
    <td> </td>
    <td> </td>
    <td> </td>
  </tr>
</table>

<br><br>

#### 5.2.2.5. Execution Evidence for Sprint Review

A continuación de presentaran las capturas de las vistas más relevantes que se llebaron a cabo en este segundo sprint. También, se adjunta el enlace de la aplicación web desplegada en Firebase.
- Web Application Deployment: https://chambeapeweb.web.app/#/
- Web Application Repository: https://github.com/Web-Applications-SW53-Group-3/ChambeaPe-App 

<div align=center>
    <img src="https://media.discordapp.net/attachments/1145421916413366426/1157091137186705458/image.png?ex=65175898&is=65160718&hm=de78038d816e778d963a4d93aef485cceaa5e4344afedf0d7184cf9266541e43&=&width=1620&height=798" alt="APP-1"  width="70%"/>
</div>

<div align=center>
    <img src="https://media.discordapp.net/attachments/1145421916413366426/1157091235060789258/image.png?ex=651758b0&is=65160730&hm=c920690b451fa5f33e2708e0112af70de3b8c426d90bf6bbac51f50f03397cb8&=&width=1620&height=801" alt="APP-1"  width="70%"/>
</div>

<div align=center>
    <img src="https://media.discordapp.net/attachments/1145421916413366426/1157091561260199987/image.png?ex=651758fd&is=6516077d&hm=70b86ba6cd15cb51b2ad4d96eba5a1f9438b0972cb7835be19fe6746cfa3b8be&=&width=1620&height=804" alt="APP-1"  width="70%"/>
</div>

<div align=center>
    <img src="https://media.discordapp.net/attachments/1145421916413366426/1157091632202645584/image.png?ex=6517590e&is=6516078e&hm=a1bb29e61535d0bdfb6be5c03f0525f7ac07caf2639d12f23ce72a6eb45ccd12&=&width=1620&height=801" alt="APP-1"  width="70%"/>
</div>

<div align=center>
    <img src="https://media.discordapp.net/attachments/1145421916413366426/1157091702419496971/image.png?ex=6517591f&is=6516079f&hm=e929e86b4fdb5f6a1dca20255e3a5f288747c8ae7b28cadeecff707cd363e4cd&=&width=1620&height=750" alt="APP-1"  width="70%"/>
</div>

<div align=center>
    <img src="https://media.discordapp.net/attachments/1145421916413366426/1157091792844497057/image.png?ex=65175935&is=651607b5&hm=058aa0d840751888e821f5ade35097ff749f480de5b695eba309962bb71a5738&=&width=1620&height=801" alt="APP-1"  width="70%"/>
</div>

<div align=center>
    <img src="https://media.discordapp.net/attachments/1145421916413366426/1157091890190102548/image.png?ex=6517594c&is=651607cc&hm=4e57d420bf338cd3326617c0480bf54e6194fb674539e35ee88b14f5700237f6&=&width=1620&height=807" alt="APP-1"  width="70%"/>
</div>

<div align=center>
    <img src="https://media.discordapp.net/attachments/1145421916413366426/1157091971639283812/image.png?ex=6517595f&is=651607df&hm=aa502b164d317ef692b7f1e0b8e1c39fc06e799ed926028e067092bb735e0298&=&width=1620&height=805" alt="APP-1"  width="70%"/>
</div>

<div align=center>
    <img src="https://media.discordapp.net/attachments/1145421916413366426/1157092095857795102/image.png?ex=6517597d&is=651607fd&hm=4941faf8817a2b3ceedfdb4e5ecfa46c64790a2c77fd46142b0bd76fb4c5d82c&=&width=1620&height=805" alt="APP-1"  width="70%"/>
</div>

<div align=center>
    <img src="https://media.discordapp.net/attachments/1145421916413366426/1157092338930307163/image.png?ex=651759b7&is=65160837&hm=6a51f7b068ea7ae46291dbdd2bd336a367b627044065b478731192f89bb7f51e&=&width=1620&height=807" alt="APP-1"  width="70%"/>
</div>

<div align=center>
    <img src="https://media.discordapp.net/attachments/1145421916413366426/1157102104800940115/image.png?ex=651762cf&is=6516114f&hm=7905b4af026e7dae695650db45f00c560ea8fcf2baf2423acb965fe40e5e8b82&=&width=1392&height=814" alt="APP-1"  width="70%"/>
</div>

<div align=center>
    <img src="https://media.discordapp.net/attachments/1145421916413366426/1157102167656775720/image.png?ex=651762de&is=6516115e&hm=e8f1ccbac5c59f040596d775d2e595db9911304ea83505d91f813f645839c016&=&width=1414&height=814" alt="APP-1"  width="70%"/>
</div>

<div align=center>
    <img src="https://media.discordapp.net/attachments/1145421916413366426/1157102253434478622/image.png?ex=651762f3&is=65161173&hm=60eadc818ef87a59ec18e94bc37df9fd01ad900ec651954a2e3832de9dc410fe&=&width=1419&height=814" alt="APP-1"  width="70%"/>
</div>

</br>

#### 5.2.2.6. Services Documentation Evidence for Sprint Review

A continuación se repsentará la documentación de los servicios que se han desarrollado en este sprint backlog. Para este nuestro front end accedemos a la API de ChambeaPe que creamos para nuestro poyecto con la herramienta mockAPI. Para así realizar el crud de publiaciones, hacer el login y registro de los usuarios.
(https://65110b963ce5d181df5da5df.mockapi.io/api/chambeape/post)

<table align="left" border="1" width="100%">
        <tr>
            <th>Services</th>
            <th>Evidencia</th>
            <th>Descripción</th>
        </tr>
        <tr>
            <th>Url Base</th>
            <td>
            <img src="https://media.discordapp.net/attachments/1145421916413366426/1157103798473465909/image.png?ex=65176463&is=651612e3&hm=96cc668e205eff283f143d6904f9c8533101b101350e0bed5c7ba702282eef1f&=&width=1393&height=814" alt="MockApi"  width="100%"> <img>
            </td>
            <td>MockAPI nos brindó este API con los datos que nosotros ingresamosen formato Json</td>
        </tr>
        <tr>
            <th>EmployerPostService</th>
            <td><img src="https://media.discordapp.net/attachments/1145421916413366426/1157103358058967120/image.png?ex=651763fa&is=6516127a&hm=d23b54e9ee5addceb5befe58478bd407eb7908ccc6080185dc2c2131c3160dbb&=&width=900&height=814"  width="100%"></td>
            <td>En este partado relizamos peticiones a nuestra API a través de nuestor servicio. </td>
        </tr>
        <tr>
            <th>LoginService</th>
            <td><img src="https://media.discordapp.net/attachments/1145421916413366426/1157103417664225320/image.png?ex=65176408&is=65161288&hm=a12d488e3946cfae2cb40e005bf5b33813332f5f60a0ed260a54c60147a1afb8&=&width=1021&height=814"  width="100%"></td>
            <td>En este partado relizamos peticiones a nuestra API a través de nuestor servicio "login".</td>
        </tr>
        <tr>
            <th>WorkerProfileService</th>
            <td><img src="https://media.discordapp.net/attachments/1145421916413366426/1157103472785756251/image.png?ex=65176415&is=65161295&hm=ae0ede76a9757686f963dd7624e4920aaa2714ecdfd5abfecb3543385672df1b&=&width=1362&height=814" alt="Trello-Sprint-2"  width="100%"></td>
            <td>En este partado relizamos peticiones a nuestra API a través de nuestor servicio "worker profile".</td>
        </tr>
    </table>

<br><br>


#### 5.2.2.7. Software Deployment Evidence for Sprint Review

Al igual que en el primer sprint, continuaremos utilizando el servicio de implementación automática de Firebase Hosting. Por lo tanto, seguiremos los mismos pasos mencionados en el sprint anterior, con la única diferencia de que seleccionaremos el nuevo repositorio de la aplicación web en Firebase para desplegarla.

<div align=center>
    <img src="https://media.discordapp.net/attachments/1145421916413366426/1157105372520267947/cufhvx44o66bb32ll2l8.jpg?ex=651765da&is=6516145a&hm=1e2dd3a867284b9cd519b5e8496eb6097fa91522cff92c49d516a2ca787b5431&=&width=1447&height=814" alt="APP-1"  width="70%"/>
</div>

#### 5.2.2.8. Team Collaboration Insights during Sprint.

<div align=center>
    <img src="https://media.discordapp.net/attachments/1145583761182965852/1157089475126628362/image.png?ex=6517570c&is=6516058c&hm=39671935aa79ea7cbdf6dc3886fd7c1e7b64cfa155f090f7561fad61bf4d837e&=&width=1620&height=468" alt="APP-1"  width="70%"/>
</div>

<div align=center>
    <img src="https://media.discordapp.net/attachments/1145583761182965852/1157089374161358899/image.png?ex=651756f4&is=65160574&hm=fbe356035cc2edd6b12a319807902f07c39ce7a1a219e6c500c71aa9cd92d32e&=&width=1620&height=525" alt="APP-1"  width="70%"/>
</div>

### 5.2.3. Sprint 3
#### 5.2.3.1. Sprint Planning 3

<table align="center"  border="1" width="80%" style="text-align:center;">
    <tr align="left">
        <td>
            <b>Sprint #</b>
        </td>
        <td>
            <b>Sprint 3</b>           
        </td>
    </tr>
    <tr align="left">
        <td colspan="2">
            <b>Sprint Planning Background</b>
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>Date</b>
        </td>
        <td>
            24/10/23         
        </td>
    </tr>
       <tr align="left">
        <td>
            <b>Time</b>
        </td>
        <td>
            15:00 pm         
        </td>
    </tr>
       <tr align="left">
        <td>
            <b>Location</b>
        </td>
        <td>
            Modalidad remota por Discord      
        </td>
    </tr>
     </tr>
       <tr align="left">
        <td>
            <b>Prepared By</b>
        </td>
        <td>
            Digital Dart     
        </td>
    </tr>
    </tr>
       <tr align="left">
        <td>
            <b>Attendess (to planning meeting)</b>
        </td>
        <td>
            Todos los miembros del grupo Digital Dart     
        </td>
    </tr>
      </tr>
       <tr align="left">
        <td>
            <b>Sprint 2</b>
            <b>Review Summary</b>
        </td>
        <td>
            En el Sprint 2, se logró desarrollar vistas de front-end y se implemntó un faso RESTful API con la ayuda de la aplicación MockAPI para simular el comportamiento de un servidor. Se logró implementar las funcionalidades de visualización de perfiles de chambeadores, creación de anuncios de trabajo, edición de anuncios de trabajo y eliminación de anuncios de trabajo. También se añadieron las funcionalidades de inicio de sesión, registro, visualización de perfiles de chambeadores, creación de anuncios de trabajo, cambio de contraseña y recuperación de contraseña. Cabe destacar que faltó la valicación en los formularios y la implementación responsive. Por último, desplegamos la aplicación web en google firebase.
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>Sprint3</b>
            <b>Retrospective Summary</b>
        </td>
        <td>
        Para el prsente sprint 3 se plantea avanzar con las vistas core faltantes en el front-end como el manejo de certificados, la implementación del chat con el usuario, el reseñar al chambeador, administrar tarjetas, entre otros. 
        En este spring se planea comenzar a desarrollar el RESTful API con el framework de Spring Boot y la base de datos MySQL. Al finalizar este sprint se espera tener un prototipo funcional de la aplicación web y comenzar a trabajar en el despliegue de la aplicación en un servidor.
        </td>
    </tr>
     <tr align="left">
        <td colspan="2">
            <b>Sprint Goal & User Stories</b>
        </td>
    </tr>
      <tr align="left">
        <td>
            <b>Sprint 3 Velocity</b>
        </td>
        <td>
            6
        </td>
    </tr>
       <tr align="left">
        <td>
            <b>Sum of Story Points</b>
        </td>
        <td>
            28
        </td>
    </tr>
</table>
</br>
<br>

#### 5.2.3.2. Sprint Backlog 3
En esta sección se especifican los detalles del Sprint Backlog.

- [Click aqui para ver el Trello]()

<img src="https://media.discordapp.net/attachments/1145421916413366426/1169717990338600991/image.png?ex=65566bc5&is=6543f6c5&hm=6054e9a707c86c43178da2eb4b37000662a89a7b9e0d36ca92a0264a529a4670&=&width=1620&height=772" alt="Trello-Sprint-3"  width="90%"> <img>


<table align="center" border="1" width="90%" style="text-align:center">
    <tr>
       <td colspan="1"><b>Sprint #</b></td>
       <td colspan="7"><b>Sprint 3</b></td>
     </tr>
     <tr>
       <td colspan="2"><b>User Story</b></td>
       <td colspan="6"><b>Work-Item / Task</b></td>
     </tr>
     <tr>
       <td><b>Id</b></td>
       <td><b>Title</b></td>
       <td><b>Id</b></td>
       <td><b>Title</b></td>
       <td><b>Description</b></td>
       <td><b>Estimation(Hours)</b></td>
       <td><b>Assigned To</b></td>
       <td><b>Status(To-do/ In-Process/ To-Review/ Done)</b></td>
     </tr>
     <tr>
       <td rowspan="4">US-03</td>
       <td rowspan="4">Manejar información del perfil</td>
       <td>T01</td>
       <td>Implementar informacion del perfil</td>
       <td>Desarrollar funcionalidad del Carrusel de trabajos del chambeador </td>
       <td>3</td>
       <td>Diego Castro</td>
       <td>Done</td>
    </tr>
    <tr>
       <td>T02</td>
       <td>Implementar espacio de información del usuario</td>
       <td>Desarrollar funcionalidad que permite al empleador ver el apartado del perfil del usuario  </td>
       <td>1.5</td>
       <td>Diego Castro</td>
       <td>Done</td>
    </tr>
    <tr>
       <td>T03</td>
       <td>Agregar apartado de certificados y comentarios</td>
       <td>Desarrollar la funcionalidad para permitir a los empleadores ver solo el ultimo certificado y ultimo comentario del chambeador.</td>
       <td>1,5</td>
       <td>Diego Castro</td>
       <td>Done</td>
    </tr>
    <tr>
       <td>T03</td>
       <td>Implementar API de perfil</td>
       <td>Desarrollar la funcionalidad para permitir contruir un endpoint para el perfil de los chambeadores</td>
       <td>3</td>
       <td>Diego Castro</td>
       <td>Done</td>
    </tr>
    <tr>
       <td rowspan="3">US12</td>
       <td rowspan="3">Comunicar entre empleado y chambeador</td>
       <td>T01</td>
       <td>Implementar Chat empleador y chambeador</td>
       <td>Desarrollar componentes visuales del chat para que los empleadores y los chambeadores interactuen durante el proyecto a desarrollar.</td>
       <td>4</td>
       <td>Diego Esquivel</td>
       <td>Done</td>
    </tr>
    <tr>
       <td>T02</td>
       <td>Implementar CSS </td></td>
       <td>Desarrollar la funcionalidad para hacer nuestro chat responsive e interactivo.</td>
       <td>2</td>
       <td>Diego Esquivel</td>
       <td>Done</td>
    </tr>
    <tr>
       <td>T03</td>
       <td>Implementar chat con Websocket</td>
       <td>Desarrollar de un sistema de chat que permita la comunicación entre el usuario chambeador y empleador</td>
       <td>4</td>
       <td>Jennifer Espinoza</td>
       <td>In progress</td>
    </tr>
    </tr>
    <tr>
       <td rowspan="2">US-5</td>
       <td rowspan="2">Reseñar empleador al chambeador</td>
        <td>T01</td>
        <td>Implementar crear una reseña</td>
        <td>Desarrollar la funcionalidad para que los empleadores puedan reseñar a los chambeadores con lo que ha trabajado.</td>
        <td>3</td>
        <td>Diego Esquivel</td>
        <td>Done</td>
    </tr>
    <tr>
        <td>T02</td>
        <td>Implementar CSS</td>
        <td>Agregar estilos en los componentes y hacelro responsive</td>
        <td>0,5</td>
        <td>Diego Esquivel</td>
        <td>Done</td>
    </tr> 
    <tr>
       <td rowspan="3">US-18</td>
       <td rowspan="3">Personalizar interface de usuario</td>
        <td>T01</td>
        <td>Configurar apartado apariencia</td>
        <td>Implementar componente de configuracion en el aplicativo.</td>
        <td>1</td>
        <td>Jennifer Espinoza</td>
        <td>Done</td>
    </tr>
    <tr>
        <td>T02</td>
        <td>Adaptar Idioma</td>
        <td>Implementar configuración para tener el idioma de ingles y español en nuestra web</td>
        <td>4</td>
        <td>Steve Castillo</td>
        <td>To do</td>
    </tr> 
    <tr>
        <td>T03</td>
        <td>Implementar tema</td>
        <td>Desarrollar funcionalidad para implementar tema de acuerdo al gusto del usuario, tanto claro como oscuro</td>
        <td>2</td>
        <td>Steve Castillo</td>
        <td>In progress</td>
    </tr> 
    <tr>
       <td rowspan="3">US-23</td>
       <td rowspan="3">Manejar certificados</td>
        <td>T01</td>
        <td>Añadir y editar certificado</td>
        <td>Desarrollar funcionalidad para editar y añadir un certificado con el mismo dialog para comodidad del usuario</td>
        <td>4</td>
        <td>Jennifer Espinoza</td>
        <td>Done</td>
    </tr>
    <tr>
        <td>T02</td>
        <td>Visualizar certificado</td>
        <td>Desarrollar funcionaliad para visualizar un dialog para ver los certificados</td>
        <td>3</td>
        <td>Jennifer Espinoza</td>
        <td>Done</td>
    </tr> 
    <tr>
        <td>T03</td>
        <td>Desarrollo de endpoint</td>
        <td>Implementar endpoint para los certificados en nuestro backend con los servicios, repositorios, entre otros</td></td>
        <td>4</td>
        <td>Jennifer Espinoza</td>
        <td>Done</td>
    </tr> 
    <tr>
       <td rowspan="1">US-24</td>
       <td rowspan="1">Página no encontrada</td>
        <td>T01</td>
        <td>Apartado de "Page not found"</td>
        <td>Implementar vista de página no encuntrada para rutas no existentes. </td>
        <td>0,5</td>
        <td>Steve Castillo</td>
        <td>Done</td>
    </tr>
   </table>

#### 5.2.3.3. Development Evidence for Sprint Review.
A continuación se presentan los commits realizados en el repositorio de la apliación web en GitHub, en el cual se puede observar el trabajo realizado por cada integrante del equipo.

<table  align="left" border="1" width="100%">
    <tr>
        <th >Repository</th>
        <th >Branch</th>
        <th>Commit ID</th>
        <th>Author</th>
        <th>Message</th>
        <th>Time ago</th>
    </tr>
    <tr>
        <td rowspan=42 >ChambeaPe-Backend</td>
        <td>develop</td>
        <td>b16a903</td>
        <td>Diego Castro</td>
        <td>Merge pull request #18 from Web-Applications-SW53-Group-3/feature/business-logic</td>
        <td>2023-11-02</td>
    </tr>
    <tr>
        <td>feature/business-logic</td>
        <td>de1fad5</td>
        <td>Diego Castro</td>
        <td>feat: add post creation logic</td>
        <td>2023-11-02</td>
    </tr>
    <tr>
        <td>feature/business-logic</td>
        <td>c3a1573</td>
        <td>Diego Castro</td>
        <td>feat: add duplicated portfolio business logic</td>
        <td>2023-11-02</td>
    </tr>
    <tr>
        <td>develop</td>
        <td>93f0394</td>
        <td>Steve Castillo</td>
        <td>Merge pull request #17 from Web-Applications-SW53-Group-3/feature/unit-tests-domain</td>
        <td>2023-11-02</td>
    </tr>
    <tr>
        <td>feature/unit-tests-domain</td>
        <td>e7bc2cd</td>
        <td>Steve Castillo</td>
        <td>feat: add employer domain test</td>
        <td>2023-11-02</td>
    </tr>
    <tr>
        <td>develop</td>
        <td>3664eb3</td>
        <td>Steve Castillo</td>
        <td>Merge pull request #16 from Web-Applications-SW53-Group-3/feature/unit-tests-domain</td>
        <td>2023-11-02</td>
    </tr>
    <tr>
        <td>feature/unit-tests-domain</td>
        <td>0c4df14</td>
        <td>Steve Castillo</td>
        <td>feat: add certificate domain tests</td>
        <td>2023-11-02</td>
    </tr>
    <tr>
        <td>develop</td>
        <td>3c7fd37</td>
        <td>Jennifer Espinoza</td>
        <td>Merge pull request #15 from Web-Applications-SW53-Group-3/feature/unit-tests-data</td>
        <td>2023-11-02</td>
    </tr>
    <tr>
        <td>feature/unit-tests-data</td>
        <td>bccaad5</td>
        <td>Jennifer Espinoza</td>
        <td>feat: add skills tests</td>
        <td>2023-11-02</td>
    </tr>
    <tr>
        <td>develop</td>
        <td>fb75a49</td>
        <td>Diego Castro</td>
        <td>Merge pull request #14 from Web-Applications-SW53-Group-3/feature/post</td>
        <td>2023-11-01</td>
    </tr>
    <tr>
        <td>feature/post</td>
        <td>a23268b</td>
        <td>Diego Castro</td>
        <td>feat: add domain validations and exceptions</td>
        <td>2023-11-01</td>
    </tr>
    <tr>
        <td>feature/post</td>
        <td>dc13f8a</td>
        <td>Diego Castro</td>
        <td>feat: add data, domain and api layers</td>
        <td>2023-11-01</td>
    </tr>
    <tr>
        <td>develop</td>
        <td>0eda580</td>
        <td>Jennifer Espinoza</td>
        <td>Merge pull request #13 from Web-Applications-SW53-Group-3/feature/unit-tests-domain</td>
        <td>2023-11-01</td>
    </tr>
    <tr>
        <td>feature/unit-tests-domain</td>
        <td>83fc5e8</td>
        <td>Jennifer Espinoza</td>
        <td>feat: add advertisement domain tests</td>
        <td>2023-11-01</td>
    </tr>
    <tr>
        <td>feature/unit-tests-domain</td>
        <td>3e72c4b</td>
        <td>Jennifer Espinoza</td>
        <td>feat: add worker domain tests</td>
        <td>2023-11-01</td>
    </tr>
    <tr>
        <td>feature/unit-tests-domain</td>
        <td>fc6086a</td>
        <td>Jennifer Espinoza</td>
        <td>feat: add user domain tests</td>
        <td>2023-11-01</td>
    </tr>
    <tr>
        <td>develop</td>
        <td>d7fb212</td>
        <td>Diego Castro</td>
        <td>Merge pull request #12 from Web-Applications-SW53-Group-3/feature/worker-profile-review</td>
        <td>2023-11-01</td>
    </tr>
    <tr>
        <td>feature/worker-profile-review</td>
        <td>0423607</td>
        <td>Diego Castro</td>
        <td>feat: add review to worker profile</td>
        <td>2023-11-01</td>
    </tr>
    <tr>
        <td>develop</td>
        <td>b67b3e9</td>
        <td>Diego Castro</td>
        <td>Merge pull request #11 from Web-Applications-SW53-Group-3/feature/cors-config</td>
        <td>2023-10-31</td>
    </tr>
    <tr>
        <td>feature/cors-config</td>
        <td>89ec0b3</td>
        <td>Diego Castro</td>
        <td>feat: add cors configuration</td>
        <td>2023-10-31</td>
    </tr>
    <tr>
        <td>develop</td>
        <td>7b474d7</td>
        <td>Diego Castro</td>
        <td>Merge pull request #10 from Web-Applications-SW53-Group-3/revert-9-feature/unit-test-domain</td>
        <td>2023-10-31</td>
    </tr>
    <tr>
        <td>revert-9-feature/unit-test-domain</td>
        <td>28c7871</td>
        <td>Diego Castro</td>
        <td>Revert "Feature/unit test domain"</td>
        <td>2023-10-31</td>
    </tr>
    <tr>
        <td>develop</td>
        <td>cf00f73</td>
        <td>Jennifer Espinoza</td>
        <td>Merge pull request #9 from Web-Applications-SW53-Group-3/feature/unit-test-domain</td>
        <td>2023-10-31</td>
    </tr>
    <tr>
        <td>feature/unit-test-domain</td>
        <td>f794686</td>
        <td>Jennifer Espinoza</td>
        <td>feat: add test at worker entity</td>
        <td>2023-10-31</td>
    </tr>
    <tr>
        <td>feature/unit-test-domain</td>
        <td>6caa5f8</td>
        <td>Jennifer Espinoza</td>
        <td>feat: add tests for user domain</td>
        <td>2023-10-31</td>
    </tr>
    <tr>
        <td>develop</td>
        <td>f2cec8c</td>
        <td>Diego Castro</td>
        <td>Merge pull request #8 from Web-Applications-SW53-Group-3/feature/employer</td>
        <td>2023-10-31</td>
    </tr>
    <tr>
        <td>feature/employer</td>
        <td>a240338</td>
        <td>Diego Castro</td>
        <td>Merge branch 'develop' into feature/employer</td>
        <td>2023-10-31</td>
    </tr>
    <tr>
        <td>feature/employer</td>
        <td>ec096c4</td>
        <td>Diego Castro</td>
        <td>feat: add register validations</td>
        <td>2023-10-31</td>
    </tr>
    <tr>
        <td>feature/employer</td>
        <td>0d70440</td>
        <td>Diego Castro</td>
        <td>feat: add requests data annotations</td>
        <td>2023-10-31</td>
    </tr>
    <tr>
        <td>feature/employer</td>
        <td>5b85e19</td>
        <td>Diego Castro</td>
        <td>feat: add exception handling</td>
        <td>2023-10-31</td>
    </tr>
    <tr>
        <td>feature/employer</td>
        <td>38da1af</td>
        <td>Diego Castro</td>
        <td>feat: add employer controller and mapping</td>
        <td>2023-10-31</td>
    </tr>
    <tr>
        <td>feature/employer</td>
        <td>f63c588</td>
        <td>Diego Castro</td>
        <td>feat: add employer domain and data layers</td>
        <td>2023-10-31</td>
    </tr>
    <tr>
        <td>develop</td>
        <td>2db7f0e</td>
        <td>Diego Esquivel</td>
        <td>Merge pull request #7 from Web-Applications-SW53-Group-3/feature/advertisemnt-certificate-portfolio-skill-endpoints</td>
        <td>2023-10-31</td>
    </tr>
    <tr>
        <td>feature/advertisemnt-certificate-portfolio-skill-endpoints</td>
        <td>fcf85da</td>
        <td>Diego Esquivel</td>
        <td>feat: add advertisement, certificate, portfolio and skill entities</td>
        <td>2023-10-31</td>
    </tr>
    <tr>
        <td>feature/advertisemnt-certificate-portfolio-skill-endpoints</td>
        <td>d3eb47f</td>
        <td>Diego Esquivel</td>
        <td>fix: drop files from .gitignore</td>
        <td>2023-10-31</td>
    </tr>
    <tr>
        <td>develop</td>
        <td>b65c9e1</td>
        <td>Diego Castro</td>
        <td>Merge pull request #2 from Web-Applications-SW53-Group-3/feature/review</td>
        <td>2023-10-30</td>
    </tr>
    <tr>
        <td>feature/review</td>
        <td>5cf2431</td>
        <td>Diego Castro</td>
        <td>feat: add reviews rating</td>
        <td>2023-10-30</td>
    </tr>
    <tr>
        <td>develop</td>
        <td>07fa553</td>
        <td>Diego Castro</td>
        <td>Merge pull request #1 from Web-Applications-SW53-Group-3/feature/user</td>
        <td>2023-10-30</td>
    </tr>
    <tr>
        <td>feature/user</td>
        <td>d5bb6cd</td>
        <td>Diego Castro</td>
        <td>feat: implement user update method</td>
        <td>2023-10-30</td>
    </tr>
    <tr>
        <td>develop</td>
        <td>9a86e91</td>
        <td>Diego Castro</td>
        <td>first commit</td>
        <td>2023-10-28</td>
    </tr>
    <tr>
        <td>main</td>
        <td>6ce12a4</td>
        <td>Diego Castro</td>
        <td>first commit</td>
        <td>2023-10-28</td>
    </tr>
</table>

#### 5.2.3.4. Testing Suite Evidence for Sprint Review.

En esta entrega se realizaron pruebas unitarias para las entidades de la aplicación web. En la siguiente tabla se muestran los commits realizados en el repositorio de la aplicación web en GitHub, en el cual se puede observar el trabajo realizado por cada integrante del equipo.
- API ChambeaPe: https://chambeape.azurewebsites.net/api/worker

<table  align="left" border="1" width="100%">
    <tr>
        <th >Repository</th>
        <th >Branch</th>
        <th>Commit ID</th>
        <th>Author</th>
        <th>Message</th>
        <th>Time ago</th>
    </tr>
    <tr>
        <td rowspan=42 >ChambeaPe-Backend</td>
        <td>develop</td>
        <td>b16a903</td>
        <td>Diego Castro</td>
        <td>Merge pull request #18 from Web-Applications-SW53-Group-3/feature/business-logic</td>
        <td>2023-11-02</td>
    </tr>
    <tr>
        <td>develop</td>
        <td>93f0394</td>
        <td>Steve Castillo</td>
        <td>Merge pull request #17 from Web-Applications-SW53-Group-3/feature/unit-tests-domain</td>
        <td>2023-11-02</td>
    </tr>
    <tr>
        <td>feature/unit-tests-domain</td>
        <td>e7bc2cd</td>
        <td>Steve Castillo</td>
        <td>feat: add employer domain test</td>
        <td>2023-11-02</td>
    </tr>
    <tr>
        <td>develop</td>
        <td>3664eb3</td>
        <td>Steve Castillo</td>
        <td>Merge pull request #16 from Web-Applications-SW53-Group-3/feature/unit-tests-domain</td>
        <td>2023-11-02</td>
    </tr>
    <tr>
        <td>feature/unit-tests-domain</td>
        <td>0c4df14</td>
        <td>Steve Castillo</td>
        <td>feat: add certificate domain tests</td>
        <td>2023-11-02</td>
    </tr>
    <tr>
        <td>develop</td>
        <td>3c7fd37</td>
        <td>Jennifer Espinoza</td>
        <td>Merge pull request #15 from Web-Applications-SW53-Group-3/feature/unit-tests-data</td>
        <td>2023-11-02</td>
    </tr>
    <tr>
        <td>feature/unit-tests-data</td>
        <td>bccaad5</td>
        <td>Jennifer Espinoza</td>
        <td>feat: add skills tests</td>
        <td>2023-11-02</td>
    </tr>
    <tr>
        <td>develop</td>
        <td>0eda580</td>
        <td>Jennifer Espinoza</td>
        <td>Merge pull request #13 from Web-Applications-SW53-Group-3/feature/unit-tests-domain</td>
        <td>2023-11-01</td>
    </tr>
    <tr>
        <td>feature/unit-tests-domain</td>
        <td>83fc5e8</td>
        <td>Jennifer Espinoza</td>
        <td>feat: add advertisement domain tests</td>
        <td>2023-11-01</td>
    </tr>
    <tr>
        <td>feature/unit-tests-domain</td>
        <td>3e72c4b</td>
        <td>Jennifer Espinoza</td>
        <td>feat: add worker domain tests</td>
        <td>2023-11-01</td>
    </tr>
    <tr>
        <td>feature/unit-tests-domain</td>
        <td>fc6086a</td>
        <td>Jennifer Espinoza</td>
        <td>feat: add user domain tests</td>
        <td>2023-11-01</td>
    </tr>
    <tr>
        <td>develop</td>
        <td>cf00f73</td>
        <td>Jennifer Espinoza</td>
        <td>Merge pull request #9 from Web-Applications-SW53-Group-3/feature/unit-test-domain</td>
        <td>2023-10-31</td>
    </tr>
    <tr>
        <td>feature/unit-test-domain</td>
        <td>f794686</td>
        <td>Jennifer Espinoza</td>
        <td>feat: add test at worker entity</td>
        <td>2023-10-31</td>
    </tr>
    <tr>
        <td>feature/unit-test-domain</td>
        <td>6caa5f8</td>
        <td>Jennifer Espinoza</td>
        <td>feat: add tests for user domain</td>
        <td>2023-10-31</td>
    </tr>
</table>

#### 5.2.3.5. Execution Evidence for Sprint Review.

A continuación se muestra la implementación del método responsable de la creación del post de un empleador. La regla de negocio que hemos definido es que un empleador solo puede crear un post cada 24 horas.
- API ChambeaPe: https://chambeape.azurewebsites.net/api/worker

<img src="https://media.discordapp.net/attachments/1142626132357828689/1169802731108712468/domainLogicPOST.png?ex=6556bab0&is=654445b0&hm=5920ea52fa0086138488a0d2883e960d504ae25dc0a0f60ff1f1c036e4865181&=&width=1316&height=897" alt="Create Post"  width="100%"> <img>

Aquí se muestra la implementación de los métodos de creación, actualización y eliminación de los certificados de un chambeador, los cuales aparecerán en su perfil.

<img src="https://media.discordapp.net/attachments/1142626132357828689/1169802730529882213/certificateDomain.png?ex=6556bab0&is=654445b0&hm=1cd46476f763ec2471c388be968950c39dfae5f6539ba416ae8b0e925d15956e&=&width=1187&height=897" alt="Certificate Domain"  width="100%"> <img>

Métodos para creación, actualización y comprobación de un chambeador.

<img src="https://media.discordapp.net/attachments/1142626132357828689/1169802730815103076/workerDomain.png?ex=6556bab0&is=654445b0&hm=2d94742b80033bbc9caabbcff6af606a4877b23a1526efcdce936e84d9f00f82&=&width=1036&height=897" alt="Worker Domain"  width="100%"> <img>

JSON de respuesta de un post

<img src="https://media.discordapp.net/attachments/1142626132357828689/1169802730232102932/opera_eiuhcXS5kp.png?ex=6556bab0&is=654445b0&hm=ba27cc0f4ca78d2154efbb432b0614dcd64d81c4eca9b10116e28ed7b7247240&=&width=1297&height=897" alt="JSON Post"  width="100%"> <img>

JSON de respuesta de un certificate

<img src="https://media.discordapp.net/attachments/1142626132357828689/1169802731393908806/opera_XEFscIqW1T.png?ex=6556bab1&is=654445b1&hm=aa0567e9058b082d271f248a7297680992f126e770d06bc34d80dd15f384b1d4&=&width=1185&height=897" alt="JSON Certificate"  width="100%"> <img>

JSON de respuesta de un chambeador

<img src="https://media.discordapp.net/attachments/1142626132357828689/1169802729883967559/opera_Lujn2zewnL.png?ex=6556bab0&is=654445b0&hm=2af46d5142f81766fe053864c9a4da8de0079808a6e8bbbcb6a89ec434040d51&=&width=1266&height=897" alt="JSON Chambeador"  width="100%"> <img>


#### 5.2.3.6. Services Documentation Evidence for Sprint Review.

A continuación se repsentará la documentación de los servicios que se han desarrollado en este sprint backlog. Para este nuestro front end accedemos a la API de ChambeaPe que creamos atraves de azure, cabe destacar que trabajamos con nuestros endpoints.

<img src="https://media.discordapp.net/attachments/1088250517282640072/1169764973631770664/image.png?ex=65569786&is=65442286&hm=66b247f2790077a691016cc856a5fcd33b61344c916a588a8ec683064c880aac&=&width=973&height=814" alt="ChambeapePe API"  width="100%"> <img>


<table align="left" border="1" width="100%">
        <tr>
            <th>Services</th>
            <th>Evidencia</th>
            <th>Descripción</th>
        </tr>
        <tr>
            <th>Url Base</th>
            <td>
            <img src="https://media.discordapp.net/attachments/1088250517282640072/1169764973631770664/image.png?ex=65569786&is=65442286&hm=66b247f2790077a691016cc856a5fcd33b61344c916a588a8ec683064c880aac&=&width=973&height=814" alt="API"  width="100%"> <img>
            </td>
            <td>Es este es nuestro swagger del API de chambea pe que maneja todos los controladores</td>
        </tr>
        <tr>
            <th>Employer</th>
            <td><img src="https://media.discordapp.net/attachments/1088250517282640072/1169789490844409987/image.png?ex=6556ae5c&is=6544395c&hm=e1f15035966d87fa14bdb226783ce968cc149f23c9d335f815a7c7525f5a161b&=&width=1213&height=814"  width="100%"></td>
            <td>Endpoint Employer </td>
        </tr>
        <tr>
            <th>LoginService</th>
            <td><img src="https://media.discordapp.net/attachments/1145421916413366426/1157103417664225320/image.png?ex=65176408&is=65161288&hm=a12d488e3946cfae2cb40e005bf5b33813332f5f60a0ed260a54c60147a1afb8&=&width=1021&height=814"  width="100%"></td>
            <td>En este partado relizamos peticiones a nuestra API a través de nuestor servicio "login".</td>
        </tr>
        <tr>
            <th>WorkerProfileService</th>
            <td><img src="https://media.discordapp.net/attachments/1145421916413366426/1157103472785756251/image.png?ex=65176415&is=65161295&hm=ae0ede76a9757686f963dd7624e4920aaa2714ecdfd5abfecb3543385672df1b&=&width=1362&height=814" alt="Trello-Sprint-2"  width="100%"></td>
            <td>En este partado relizamos peticiones a nuestra API a través de nuestor servicio "worker profile".</td>
        </tr>
    </table>

<br><br>
#### 5.2.3.7. Software Deployment Evidence for Sprint Review.

Nuestro equipo usó Azure para implementar la integración continua y desplegar nuestro backend en Azure Web Apps. este nos da la facilidad de usar nuestro Github para hacer deploy de este.

<div align=center>
    <img src="https://media.discordapp.net/attachments/1088250517282640072/1169731168934047896/opera_FR7CK18jPE.png?ex=6556780b&is=6544030b&hm=acffe18279d28324e3ed5c28e4ff876a6a30b591c002ce7841783480e4f016a6&=&width=1074&height=516" alt="APP-BACKEND-1"  width="90%"/>
</div>

<div align=center>
    <img src="https://media.discordapp.net/attachments/1088250517282640072/1169731168502030451/opera_gbzPZmXRXY.png?ex=6556780b&is=6544030b&hm=17f98bc06e7707ed7e6f57e94662a9a19d2d2beae97186902a738a3afda1dcd4&=&width=1074&height=553" alt="APP-BACKEND-1"  width="90%"/>
</div>

<div align=center>
    <img src="https://media.discordapp.net/attachments/1088250517282640072/1169813566149378098/1.jpg?ex=6556c4c8&is=65444fc8&hm=6d01b8ee34b2719a5fd4b2b738ea383c27f556c7bb5ca6bf323b6df804192cb9&=&width=508&height=302" alt="APP-BACKEND-2"  width="90%"/>
</div>

<div align=center>
    <img src="https://media.discordapp.net/attachments/1088250517282640072/1169813565658632334/2.jpg?ex=6556c4c8&is=65444fc8&hm=a878b8a9c62a86faee6e9ace38fe15bf8485abac6e513032a785170f7f5093cb&=&width=925&height=125" alt="APP-BACKEND-3"  width="90%"/>
</div>

<div align=center>
    <img src="https://media.discordapp.net/attachments/1088250517282640072/1169813565348257792/3.jpg?ex=6556c4c8&is=65444fc8&hm=84f3528755edbedaffe059956df1d9f6bf79d1ac6372fec5cb250d405105d16e&=&width=913&height=565" alt="APP-BACKEND-4"  width="90%"/>
</div>

<div align=center>
    <img src="https://media.discordapp.net/attachments/1088250517282640072/1169813566984044674/4.jpg?ex=6556c4c8&is=65444fc8&hm=dbfdb5c9f3aee0dc181dce4b8dcc714637fee4af540cfdd7884c637e24d2763e&=&width=920&height=570" alt="APP-BACKEND-5"  width="90%"/>
</div>

<div align=center>
    <img src="https://media.discordapp.net/attachments/1088250517282640072/1169813566698819724/5.jpg?ex=6556c4c8&is=65444fc8&hm=b13e6d43747e2bfe680bf71c5d4c35b80ef555935372733ee4a2c91b61d0c442&=&width=886&height=361" alt="APP-BACKEND-6"  width="90%"/>
</div>

<div align=center>
    <img src="https://media.discordapp.net/attachments/1088250517282640072/1169813566426193930/6.jpg?ex=6556c4c8&is=65444fc8&hm=f68fba3a5e8988acf79edfe20f072736aa60799e9eec0f9c5b7ee7487128eb43&=&width=801&height=897" alt="APP-BACKEND-7"  width="90%"/>
</div>



#### 5.2.3.8. Team Collaboration Insights during Sprint.

<div align=center>
    <img src="https://cdn.discordapp.com/attachments/1145421916413366426/1169788574787440691/image.png?ex=6556ad81&is=65443881&hm=b0eb266bf9fbbf1a18b0cef80c25aa524d83fb957dc43a6958408a3c36d333c1&" alt="APP-BACKEND-1"  width="70%"/>
</div>

<div align=center>
    <img src="https://cdn.discordapp.com/attachments/1145421916413366426/1169788574472876072/image.png?ex=6556ad81&is=65443881&hm=f0365d015100df320742449d96f1881df617e5be458082cf63dcda20fdae01c9&" alt="APP-BACKEND-1"  width="70%"/>
</div>

### 5.2.4. Sprint 4
#### 5.2.4.1. Sprint Planning 4
<table align="center"  border="1" width="80%" style="text-align:center;">
    <tr align="left">
        <td>
            <b>Sprint #</b>
        </td>
        <td>
            <b>Sprint 3</b>           
        </td>
    </tr>
    <tr align="left">
        <td colspan="2">
            <b>Sprint Planning Background</b>
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>Date</b>
        </td>
        <td>
            26/10/23         
        </td>
    </tr>
       <tr align="left">
        <td>
            <b>Time</b>
        </td>
        <td>
            15:00 pm         
        </td>
    </tr>
       <tr align="left">
        <td>
            <b>Location</b>
        </td>
        <td>
            Modalidad remota por Discord      
        </td>
    </tr>
     </tr>
       <tr align="left">
        <td>
            <b>Prepared By</b>
        </td>
        <td>
            Digital Dart     
        </td>
    </tr>
    </tr>
       <tr align="left">
        <td>
            <b>Attendess (to planning meeting)</b>
        </td>
        <td>
            Todos los miembros del grupo Digital Dart     
        </td>
    </tr>
      </tr>
       <tr align="left">
        <td>
            <b>Sprint 3</b>
            <b>Review Summary</b>
        </td>
        <td>
            En el Sprint 3, se logró desarrollar e implementar el 
            backend de la aplicación web, usando como base de datos MySQL y .NET.
            Además de eso se logró desarrollar y conectar el frontend de la aplicación web con el backend. Además pudimos implementar una primera versión del chat con el usuario.
        </td>
    </tr>
    <tr align="left">
        <td>
            <b>Sprint 4</b>
            <b>Retrospective Summary</b>
        </td>
        <td>
        Para el Sprint 4, se plantea finalizar la integración entre el frontend y el backend, además de implementar medidas de seguridad en la aplicación web mediante el uso de JSON Web Tokens (JWTs). Estas medidas de seguridad abarcarán aspectos cruciales como autenticación, autorización y protección contra ataques comunes. Adicionalmente, se incorporará la práctica de hashear las contraseñas utilizando la función de hash de contraseñas bCrypt, fortaleciendo así la seguridad del sistema mediante un método reconocido y efectivo de protección de las credenciales de usuario.
        </td>
    </tr>
     <tr align="left">
        <td colspan="2">
            <b>Sprint Goal & User Stories</b>
        </td>
    </tr>
      <tr align="left">
        <td>
            <b>Sprint 4 Velocity</b>
        </td>
        <td>
            5
        </td>
    </tr>
       <tr align="left">
        <td>
            <b>Sum of Story Points</b>
        </td>
        <td>
            35
        </td>
    </tr>
</table>
</br>
<br>

#### 5.2.4.2. Sprint Backlog 4

En esta sección se especifican los detalles del Sprint Backlog.

- [Click aqui para ver el Trello](https://trello.com/invite/b/hHMMLGXR/ATTI49808b196bb44a31a04ddeb483cd27a59B1F055B/sprint-backlog-4)

<img src="https://cdn.discordapp.com/attachments/1120134585896939531/1176591538403422328/image.png?ex=656f6d42&is=655cf842&hm=d1bc97bb57b63e26607ef837744859234451a2429a434398d24872ef028fbea7&" alt="Trello-Sprint-4"  width="90%"> <img>

<table align="center" border="1" width="90%" style="text-align:center">
   <tr>
       <td colspan="1"><b>Sprint #</b></td>
       <td colspan="7"><b>Sprint 4</b></td>
     </tr>
   <tr>
       <td colspan="2"><b>User Story</b></td>
       <td colspan="6"><b>Work-Item / Task</b></td>
     </tr>
   <tr>
       <td><b>Id</b></td>
       <td><b>Title</b></td>
       <td><b>Id</b></td>
       <td><b>Title</b></td>
       <td><b>Description</b></td>
       <td><b>Estimation(Hours)</b></td>
       <td><b>Assigned To</b></td>
       <td><b>Status(To-do/ In-Process/ To-Review/ Done)</b></td>
   </tr>
   <tr>
       <td rowspan="3">US-01</td>
       <td rowspan="3">Inicio de Sesión</td>
       <td>T01</td>
       <td>Crear modelo de usuario de inicio de sesión</td>
       <td>Crear un modelo de datos que almacene los datos de inicio de sesión de un usuario, como correo electrónico y contraseña.</td>
       <td>3</td>
       <td>Diego Castro</td>
       <td>Done</td>
    </tr>
    <tr>
       <td>T02</td>
       <td>Implementar interfaz de usuario de inicio de sesión</td>
       <td>mplementar una interfaz de usuario funcional que verifique y permita a los usuarios iniciar sesión en la aplicación.</td>
       <td>3.5</td>
       <td>Diego Castro</td>
       <td>Done</td>
   </tr>
   <tr>
       <td>T03</td>
       <td>Implementar autenticación de usuarios</td>
       <td>Implementar la autenticación de usuarios utilizando JWT.</td>
       <td>4</td>
       <td>Diego Castro</td>
       <td>Done</td>
   </tr>
   <tr>
       <td rowspan="4">US-02</td>
       <td rowspan="4">Registrarse con correo</td>
       <td>T01</td>
       <td>Crear modelo de usuario de registro en el backend</td>
       <td>Crear un modelo de datos que almacene los datos de registro de un usuario, como correo electrónico, nombre, apellido, contraseña y tipo de usuario. </td> 
       <td>4</td>
       <td>Diego Esquivel</td>
       <td>Done</td>
   </tr>
   <tr>
       <td>T02</td>
       <td>Implementar interfaz de usuario de registro</td>
       <td>Implementar una interfaz de usuario que permita a los usuarios registrarse en la aplicación con su correo electrónico, nombre, apellido, contraseña y tipo de usuario.</td>
       <td>2</td>
       <td>Diego Esquivel</td>
       <td>Done</td>
   </tr>
   <tr>
       <td>T03</td>
       <td> Implementar creación de usuarios en el backend</td>
       <td> Implementar la creación de usuarios en el backend utilizando JWT.</td>
       <td>3</td>
       <td>Jennifer Espinoza</td>
       <td>Done</td>
   </tr>
   <tr>
       <td>T04</td>
       <td>Implementar creación de usuarios en el frontend</td>
       <td>Implementar la creación de usuarios en el frontend utilizando Angular.</td>
       <td>2</td>
       <td>Steve Castillo</td>
       <td>Done</td>
   </tr>
   <tr>
       <td rowspan="2">US-03</td>
       <td rowspan="2">	Manejar información del perfil</td>
       <td>T01</td>
       <td>Implementar JWT para la autenticación del perfil de usuario</td>
       <td>Implementar JSON Web Tokens (JWT) para manejar la autenticación y autorización del perfil de usuario. Esto permitirá a los usuarios mantener sus datos personales actualizados de manera segura.</td> 
       <td>4</td>
       <td>Diego Esquivel</td>
       <td>Done</td>
   </tr>
   <tr>
       <td>T02</td>
       <td>Conectar endpoints para la actualización del perfil de usuario</td>
       <td>Conectar endpoints del backend que permitan al usuario actualizar su información de perfil. Estos endpoints deben estar protegidos con JWT.</td>
       <td>3</td>
       <td>Steve Castillo</td>
       <td>Done</td>
   </tr>

   <tr>
       <td rowspan="2">US-12</td>
       <td rowspan="2">Comunicar entre empleado y chambeador</td>
       <td>T01</td>
       <td>Establecer comunicación segura entre empleador y chambeador</td>
       <td>Implementar seguridad en la aplicación para garantizar una comunicación segura entre el empleador y el chambeador. Esto permitirá a los empleadores definir las características del trabajo directamente con los chambeadores de manera segura.</td> 
       <td>4</td>
       <td>Diego Castro</td>
       <td>Done</td>
   </tr>
   <tr>
       <td>T02</td>
       <td>Conectar endpoints para la comunicación entre empleador y chambeador</td>
       <td>Conectar endpoints del backend que permitan al usuario actualizar su información de perfil. Estos endpoints deben estar protegidos con JWT.</td>
       <td>3</td>
       <td>Steve Castillo</td>
       <td>Done</td>
   </tr>
   <tr>
       <td rowspan="2">US-13</td>
       <td rowspan="2">Reseñar empleador al chambeador</td>
       <td>T01</td>
       <td>Implementar JWT para la reseña del empleador al chambeador</td>
       <td>Implementar JWT para asegurar la reseña del empleador al chambeador. Esto permitirá a los empleadores dejar una reseña sobre la experiencia con el chambeador de manera segura después de que el trabajo se haya completado.</td> 
       <td>4</td>
       <td>Jennifer Espinoza</td>
       <td>Done</td>
   </tr>
   <tr>
       <td>T02</td>
       <td>Conectar endpoints para las reseñas del empleador al chambeador</td>
       <td>Conectar endpoints en el backend que permitan al empleador dejar una reseña sobre la experiencia con el chambeador. Estos endpoints deben estar protegidos con JWT.</td>
       <td>3</td>
       <td>Steve Castillo</td>
       <td>Done</td>
   </tr>

   <tr>
       <td rowspan="3">US-21</td>
       <td rowspan="3">Postular a vacantes de trabajo</td>
        <td>T01</td>
        <td> Implementar restricción de acceso por roles</td>
        <td> Implementar la restricción de acceso a la función de postulación de vacantes a usuarios autenticados con el rol de empleador.</td>
        <td>3</td>
        <td>Diego Esquivel</td>
        <td>Done</td>
   </tr>
   <tr>
        <td>T02</td>
        <td>Implementar la validación de campos</td>
        <td> Implementar la validación de campos en la función de postulación de vacantes.</td>
        <td>2</td>
        <td>Steve Castillo</td>
        <td>Done</td>
   </tr>
   <tr>
        <td>T03</td>
        <td>Implementar la creación de postulaciones en el backend</td>
        <td> Implementar la creación de postulaciones en el backend utilizando JWT.</td>
        <td>2,5</td>
        <td>Diego Esquivel</td>
        <td>Done</td>
   </tr>

   <tr>
       <td rowspan="2">US-23</td>
       <td rowspan="2">Manejar certificados</td>
       <td>T01</td>
       <td>Implementar seguridad para el manejo de certificados</td>
       <td>Implementar seguridad para manejar los certificados del chambeador. Esto permitirá a los chambeadores manejar sus certificados de manera segura, lo que les dará una mejor oportunidad laboral.</td> 
       <td>4</td>
       <td>Jennifer Espinoza</td>
       <td>Done</td>
   </tr>
   <tr>
       <td>T02</td>
       <td>Crear endpoints para el manejo de certificados</td>
       <td>Crear endpoints en el backend que permitan al chambeador manejar sus certificados. Estos endpoints deben estar protegidos.</td>
       <td>3</td>
       <td>Steve Castillo</td>
       <td>Done</td>
   </tr>
</table>

#### 5.2.4.6. Services Documentation Evidence for Sprint Review.

A continuación se muestra el Swagger Documentado de los servicios que se han desarrollado. Para conectar nuestro frontend en Vue con nuestro backend accedemos a la API de ChambeaPe que creamos a través de Azure.

<img src="https://cdn.discordapp.com/attachments/1120134585896939531/1176597684463882311/image.png?ex=656f72fc&is=655cfdfc&hm=e0c40c21d23db6ded7cca7f07a0bfd43956972c61497ffb81982959a3bd3d7f8&" alt="ChambeapePe API"  width="100%">


<table align="left" border="1" width="100%">
    <tr>
        <th>Services</th>
        <th>Evidencia</th>
        <th>Descripción</th>
    </tr>
    <tr>
        <th>Account</th>
        <td><img src="https://cdn.discordapp.com/attachments/1120134585896939531/1176597742320091156/image.png?ex=656f7309&is=655cfe09&hm=54b0ad710a9802849dbb258f1a4cbc90bff6dd97c75ebea5a94e8f3f8824fc21&"  width="100%"></td>
        <td>Endpoint Account</td>
    </tr>
    <tr>
        <th>Advertisement</th>
        <td><img src="https://cdn.discordapp.com/attachments/1120134585896939531/1176597771319517315/image.png?ex=656f7310&is=655cfe10&hm=3db1a1d2ba271d8999f1513aec55e3d342a99ffaadb88a8854214fe9308796f8&"  width="100%"></td>
        <td>Endpoint Advertisement</td>
    </tr>
    <tr>
        <th>Certificate</th>
        <td><img src="https://cdn.discordapp.com/attachments/1120134585896939531/1176597813560361092/image.png?ex=656f731a&is=655cfe1a&hm=e2b3a7fab04a11c43c0b79ac625e20521360441b61acdcbec91457203dacb109&"  width="100%"></td>
        <td>Endpoint Certificate</td>
    </tr>
    <tr>
        <th>Employer</th>
        <td><img src="https://cdn.discordapp.com/attachments/1120134585896939531/1176597847832002641/image.png?ex=656f7323&is=655cfe23&hm=f45ab0f35b5bc11526e33fd4b5db4163fb2e08f8c850527e18f08f7e55e5a7f2&"  width="100%"></td>
        <td>Endpoint Employer</td>
    </tr>
    <tr>
        <th>Portfolio</th>
        <td><img src="https://cdn.discordapp.com/attachments/1120134585896939531/1176597880996372590/image.png?ex=656f732a&is=655cfe2a&hm=0da2755518f66dc348da079de58f525826d5640d5a234aaab0e55eb4aea79a7d&"  width="100%"></td>
        <td>Endpoint Portfolio</td>
    </tr>
    <tr>
        <th>Post</th>
        <td><img src="https://cdn.discordapp.com/attachments/1120134585896939531/1176597915649724506/image.png?ex=656f7333&is=655cfe33&hm=70ef5e3f091cda020ceb618cc2073487883134d1212adbaef525a83f815fe00c&"  width="100%"></td>
        <td>Endpoint Post</td>
    </tr>
    <tr>
        <th>Skill</th>
        <td><img src="https://cdn.discordapp.com/attachments/1120134585896939531/1176597960197406760/image.png?ex=656f733d&is=655cfe3d&hm=e863911c01ef45c51dd214a36941aaf0293e428473b102cdfc1667a0fccd894b&"  width="100%"></td>
        <td>Endpoint Skill</td>
    </tr>
    <tr>
        <th>User</th>
        <td><img src="https://cdn.discordapp.com/attachments/1120134585896939531/1176597989293310085/image.png?ex=656f7344&is=655cfe44&hm=685337b53940e9b3c2ce24d1c589c00d416a9797d9ab9fb364a5574bbcc730df&"  width="100%"></td>
        <td>Endpoint User</td>
    </tr>
    <tr>
        <th>Worker</th>
        <td><img src="https://cdn.discordapp.com/attachments/1120134585896939531/1176598033413197946/image.png?ex=656f734f&is=655cfe4f&hm=51309fd60a6cc5886509f016b558561d59cc5918aa95709268af72ab6bbff504&"  width="100%"></td>
        <td>Endpoint Worker</td>
    </tr>
</table>

#### 5.2.4.7. Software Deployment Evidence for Sprint Review.

El proyecto se encuentra desplegado en Azure, todo esto está documentado en el 3.2.3.7 Software Deployment Evidence for Sprint Review.
Acá el link al documento: [3.2.3.7 Software Deployment Evidence for Sprint Review](#5237-software-deployment-evidence-for-sprint-review)

## 5.3 Validation Interview
A continuación se presentan los resultados de la entrevista de validación realizada a los usuarios de la aplicación web.

### 5.3.1 Diseño de Entrevistas
Para la entrevista se realizaron las siguientes preguntas:

- Preguntas generales:
    - ¿Cómo te llamas?
    - ¿Cuántos años tienes?
    - ¿Dónde vives actualmente?
    - ¿A qué te dedicas?

Segmento: Chambeador
- Después de ver nuestra presentación, ¿crees que la aplicación abordará de manera efectiva los desafíos que enfrentas al buscar trabajos temporales o proyectos?
- ¿Crees que ChambeaPe te ayudará a encontrar trabajos temporales de manera más eficiente?
- ¿Encuentras que la aplicación es didáctica y fácil de entender, o tienes sugerencias para mejorarla?
- ¿Qué opinas sobre la plantilla de diseño y la usabilidad de la aplicación?
- ¿Con qué frecuencia usarías la aplicación para buscar trabajos temporales?
- ¿Qué aspectos te gustan más de ChambeaPe, y hay alguna característica que sientas que falta en la aplicación?
- ¿Estarías dispuesto a recomendar ChambeaPe a otros trabajadores por tus redes sociales?

Segmento: Empleador
- Después de ver nuestra presentación del prototipo, ¿crees que la aplicación te ayudará a encontrar candidatos para trabajos temporales o proyectos de manera efectiva?
- ¿Crees que ChambeaPe facilita la contratación de trabajadores temporales según tus necesidades?
- ¿Encuentras que la aplicación te proporciona candidatos con las cualidades y habilidades que buscas?
- ¿Qué opinas sobre la plantilla de diseño y la usabilidad de la aplicación?
- ¿Con qué frecuencia utilizarías la aplicación para buscar y contratar trabajadores temporales?
- ¿Qué aspectos te gustan más de ChambeaPe, y hay alguna característica que sientas que falta en la aplicación desde la perspectiva del empleador?
- ¿Estarías dispuesto a recomendar ChambeaPe a otros empleadores por tus redes sociales?

### 5.3.2 Registro de Entrevistas

### Segmento 01: (Chambeadores)

**Entrevista 01**

Nombres: Viviana

Apellidos: Huamán Pinedo

Edad: 23 años

Distrito: San Miguel

Evidencia de la reunión:
<div align=center>
<img src="https://media.discordapp.net/attachments/698313102587985970/1169484012318896198/vlc_UImKhahxUv.png?ex=655591dc&is=65431cdc&hm=84ab0df9638c08ebe0db4036db1991e8d56b052d6d4ee0c4b25e2124fb190053&=&width=1678&height=897" alt="Entrevista 2"  width="90%"/>
</div>

Inicio: 00:17

Fin: 03:50

Enlace de entrevista: [Entrevista a Viviana](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202120911_upc_edu_pe/EZEjER7IOvBJr6aBI3Tu4lkBOsksgcCnLUcc8gWWDTvxwQ?e=YTlLSx&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZyIsInJlZmVycmFsQXBwUGxhdGZvcm0iOiJXZWIiLCJyZWZlcnJhbE1vZGUiOiJ2aWV3In0sInBsYXliYWNrT3B0aW9ucyI6eyJzdGFydFRpbWVJblNlY29uZHMiOjUuMDN9fQ%3D%3D)

Resumen de la entrevista:

La entrevista se llevó a cabo con Viviana, una joven de 23 años que reside en el distrito de San Miguel. Actualmente se encuentra estudiando administración de negocios globales en la Universidad Ricardo Palma y trabajando a tiempo parcial. Viviana compartió sus perspectivas sobre la aplicación y expresó que cree que esta podría abordar los desafíos que enfrenta al buscar trabajos temporales, brindando flexibilidad en horarios. Por ello, menciona que se encuentra sumamente interesada en la página presentada.

Ella considera que la página es didáctica y fácil de entender, aunque sugiere algunas mejoras en cuanto a la ubicación de elementos, particularmente en la función de chat, pues indica que debería estar en un lugar más visible. También indicó que tiene la intención de usar la aplicación cuando necesite buscar trabajos temporales o esté a punto de cambiar de trabajo.

Entre los aspectos que más le agradaron de la página se encuentra la plantilla de diseño y la capacidad de copiar imágenes de Internet. Sin embargo, también señaló que sería beneficioso agregar una opción para agregar más imágenes.

Un aspecto destacado de la entrevista es que Viviana está dispuesta a recomendar la aplicación a otros trabajadores interesados en trabajos temporales, ya que considera que esto podría contribuir a la creación de una comunidad más amplia de usuarios.

En síntesis, la entrevistada proporcionó una visión generalmente positiva de la aplicación, destacando su utilidad potencial, facilidad de uso y el valor de una comunidad de usuarios en crecimiento.

**Entrevista 02**

Nombres:  Alanis Gabriela

Apellidos:  Tellez Caceres

Edad: 21 años

Distrito:  Rímac, Lima

Evidencia de la reunión: [Entrevista a Alanis](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202120911_upc_edu_pe/EZEjER7IOvBJr6aBI3Tu4lkBOsksgcCnLUcc8gWWDTvxwQ?e=Ya0fuU&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZyIsInJlZmVycmFsQXBwUGxhdGZvcm0iOiJXZWIiLCJyZWZlcnJhbE1vZGUiOiJ2aWV3In0sInBsYXliYWNrT3B0aW9ucyI6eyJzdGFydFRpbWVJblNlY29uZHMiOjIzMS44M319)

<div align=center>
<img src="https://media.discordapp.net/attachments/1157361311060066345/1167629636742688798/image.png?ex=654ed2d6&is=653c5dd6&hm=9aee625b673963b3dda093dc24a786a7e95296632480fce878583d58c9891545&=&width=1482&height=1118" alt="Entrevista 2"  width="90%"/>
</div>

Inicio: 03:51

Fin: 08:50

Enlace de entrevista: 

Resumen de la entrevista:

En la entrevista, Alanis, una estudiante de turismo con interés en repostería, compartió su visión sobre la aplicación ChambeaPe. Si bien reconoció el potencial de la plataforma para la búsqueda de trabajos temporales, destacó la necesidad de mejoras en la interfaz y la experiencia del usuario. Alanis valoró positivamente la presencia de un chat de soporte y el atractivo diseño de la aplicación, aunque sugirió que la interactividad podría ser una adición valiosa. Planea utilizar ChambeaPe con regularidad durante su búsqueda de empleo temporal y expresó su disposición a recomendar la aplicación a otros trabajadores en busca de oportunidades temporales, subrayando la importancia de las mejoras continuas en la plataforma para satisfacer las necesidades de los usuarios.

En resumen, la entrevista con Alanis revela sus observaciones y sugerencias para mejorar ChambeaPe, destacando su disposición a utilizar la aplicación y promocionarla entre sus colegas si se implementan mejoras que hagan que la experiencia sea aún más efectiva y amigable para los usuarios.

**Entrevista 03**

Nombres: Piero Alessandro

Apellidos: Descalzi Saenz

Edad: 21 años

Distrito:  Cercado, Lima

Evidencia de la reunión: [Entrevista a Piero](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202120911_upc_edu_pe/EZEjER7IOvBJr6aBI3Tu4lkBOsksgcCnLUcc8gWWDTvxwQ?e=VfOfwe&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZyIsInJlZmVycmFsQXBwUGxhdGZvcm0iOiJXZWIiLCJyZWZlcnJhbE1vZGUiOiJ2aWV3In0sInBsYXliYWNrT3B0aW9ucyI6eyJzdGFydFRpbWVJblNlY29uZHMiOjUzMC41Nn19)

<div align=center>
<img src="https://cdn.discordapp.com/attachments/1120134585896939531/1169728181696217139/image.png?ex=65567543&is=65440043&hm=95a002fcee5c198d5b5812729f768e71def374cc3dc18737de259374a97d278e&" alt="Entrevista 2"  width="90%"/>
</div>

Inicio: 08:50

Fin: 12:37

Enlace de entrevista: 

Resumen de la entrevista:

En la entrevista, Piero expresó su confianza en que la aplicación le será de gran ayuda al buscar empleos temporales, destacando su potencial. Consideró que la aplicación es de fácil comprensión, aunque mencionó que le gustaría la capacidad de enviar imágenes a través del chat. Piero afirmó que utilizaría la aplicación con regularidad y apreció la posibilidad de negociar los costos de los trabajos. Además, indicó que recomendaría la aplicación a personas que están ingresando al mundo laboral, ya que la considera una herramienta valiosa.

### SEGMENTO 02: (Empleadores)

**Entrevista 01**

Nombres: Claudia 

Apellidos:  Rios Piña

Edad: 22 años

Distrito:  Jesus María

Evidencia de la reunión: [Entrevista a Claudia](https://upcedupe-my.sharepoint.com/personal/u202120911_upc_edu_pe/_layouts/15/stream.aspx?id=%2Fpersonal%2Fu202120911%5Fupc%5Fedu%5Fpe%2FDocuments%2FEntrevistas%20Web%20TB2%2Emp4&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZyIsInJlZmVycmFsQXBwUGxhdGZvcm0iOiJXZWIiLCJyZWZlcnJhbE1vZGUiOiJ2aWV3In0sInBsYXliYWNrT3B0aW9ucyI6eyJzdGFydFRpbWVJblNlY29uZHMiOjc1Ny4xMX19&ga=1&referrer=StreamWebApp%2EWeb&referrerScenario=AddressBarCopied%2Eview)

<div align=center>
<img src="https://media.discordapp.net/attachments/1157361311060066345/1167619317475573830/image.png?ex=654ec93a&is=653c543a&hm=9e16d4aa2d41a4ca68abd8e26c9253322ec3abd694a58a726450fa16cbcc5947&=&width=2298&height=1242" alt="Entrevista 2"  width="90%"/>
</div>

Inicio: 12:37

Fin: 16:48

Enlace de entrevista: 

Resumen de la entrevista:

En esta entrevista, inicié la conversación presentándome y explorando la opinión de Claudia Ríos acerca de la aplicación ChambeaPe. Claudia, una profesional en repostería, elogió la plataforma por su eficacia en la búsqueda de candidatos para trabajos temporales y proyectos. Destacó la amplitud de la base de datos de chambeadores y las herramientas útiles para la contratación. Aunque Claudia encontró la aplicación útil, ofreció sugerencias para mejorarla. Propuso ajustes en la búsqueda y en los filtros de candidatos, así como una mayor interactividad en el diseño.

Claudia compartió que planea utilizar la aplicación regularmente en su negocio de repostería, especialmente durante los períodos de alta demanda, como festividades. También expresó su disposición a recomendar ChambeaPe a otros empleadores, especialmente si la aplicación continúa evolucionando y mejorando. Al final de la entrevista, expresé mi agradecimiento a Claudia por sus valiosas opiniones y sugerencias, reconociendo su contribución al desarrollo de la aplicación ChambeaPe.

En esta entrevista,  tuve la oportunidad de conversar con Claudia Ríos sobre su experiencia y opiniones con respecto a la aplicación ChambeaPe. Comenzamos con una introducción, en la que me presenté y expliqué el propósito de la entrevista, que era evaluar la aplicación.

Claudia, una profesional de la repostería, compartió su visión positiva de Chambeap, destacando su efectividad en la búsqueda de candidatos para trabajos temporales y proyectos. Mencionó que la plataforma ofrecía una amplia base de datos de chambeadores y herramientas útiles para la contratación, lo que facilitaba su proceso de selección de personal.

Sin embargo, también ofreció valiosas sugerencias de mejora. Señaló la necesidad de ajustes en la búsqueda y los filtros de candidatos, así como la posibilidad de hacer el diseño de la aplicación más interactivo para una experiencia aún más atractiva. Claudia expresó su intención de utilizar la aplicación de manera regular, especialmente durante los períodos de alta demanda en su negocio de repostería, como festividades.

Finalmente, se mostró dispuesta a recomendar ChambeaPe a otros empleadores, subrayando su disposición a hacerlo a medida que la aplicación continúe evolucionando y mejorando. Al concluir la entrevista, agradecí a Claudia por su tiempo y valiosas contribuciones para el desarrollo de la aplicación ChambeaPe.

**Entrevista 02**

Nombres: José Carlos Isaac

Apellidos: Ampudia Flores

Edad: 19

Distrito: Surco

Evidencia de la reunión: [Entrevista a José](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202120911_upc_edu_pe/EZEjER7IOvBJr6aBI3Tu4lkBOsksgcCnLUcc8gWWDTvxwQ?e=bqZKqz&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZyIsInJlZmVycmFsQXBwUGxhdGZvcm0iOiJXZWIiLCJyZWZlcnJhbE1vZGUiOiJ2aWV3In0sInBsYXliYWNrT3B0aW9ucyI6eyJzdGFydFRpbWVJblNlY29uZHMiOjEwMDguNjN9fQ%3D%3D)

<div align=center>
<img src="https://media.discordapp.net/attachments/1145421916413366426/1169796230306603058/image.png?ex=6556b4a3&is=65443fa3&hm=7f7848b10df69afd426090f36a8f201e2e0687080f39f70b21278d4b5981d13e&=&width=1074&height=389" alt="Entrevista 2"  width="90%"/>
</div>

Inicio: 16:48

Fin: 17:

Enlace de entrevista: 

Resumen de la entrevista:

En la entrevista con Isaac, se exploraron sus impresiones sobre la aplicación Chambeap. Isaac expresó su confianza en la versatilidad de la aplicación, considerándola una herramienta eficaz para encontrar candidatos para trabajos temporales o proyectos. Destacó la clasificación de los trabajadores según las necesidades del empleador como un punto fuerte de la plataforma. Isaac elogió el atractivo diseño y la usabilidad de la aplicación, destacando su comodidad durante la navegación. Además, indicó que la aplicación sería de uso frecuente para él, lo que podría facilitar la gestión de tareas en su hogar. Finalmente, se mostró dispuesto a recomendar Chambeap debido a su capacidad para conectar a personas en busca de trabajo con empleadores de manera eficiente y conveniente.

**Entrevista 03**

Nombres: Cristian Andrés

Apellidos: Quito Igreda

Edad: 22 años

Distrito:  Los Olivos

Evidencia de la reunión: [Entrevista a Cristian](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202120911_upc_edu_pe/EZEjER7IOvBJr6aBI3Tu4lkBOsksgcCnLUcc8gWWDTvxwQ?e=FZWOaz&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZyIsInJlZmVycmFsQXBwUGxhdGZvcm0iOiJXZWIiLCJyZWZlcnJhbE1vZGUiOiJ2aWV3In0sInBsYXliYWNrT3B0aW9ucyI6eyJzdGFydFRpbWVJblNlY29uZHMiOjEyMTguNTh9fQ%3D%3D)

<div align=center>
<img src="https://cdn.discordapp.com/attachments/1120134585896939531/1169729220495286283/image.png?ex=6556763a&is=6544013a&hm=1364917fc65c7890fa2d692c7c4e8a1ed18bf92c40034e7e4f7037c3751afd39&" alt="Entrevista 2"  width="90%"/>
</div>

Inicio: 21:48

Fin: 25: 19

Resumen de la entrevista:

En la entrevista con Cristian Quito, se exploraron sus opiniones sobre la aplicación Chambeap. Cristian Quito manifestó su confianza en la versatilidad de la aplicación, considerándola una herramienta eficaz para identificar candidatos para trabajos temporales o proyectos. Resaltó la capacidad de la plataforma para clasificar a los trabajadores según las necesidades del empleador como uno de sus puntos fuertes. Elogió el atractivo diseño y la facilidad de uso de la aplicación, destacando su comodidad durante la navegación. Además, señaló que planeaba utilizar la aplicación de forma frecuente, lo que podría simplificar la gestión de tareas en su hogar. Por último, expresó su disposición a recomendar Chambeap debido a su eficacia y conveniencia en la conexión de personas en busca de empleo con empleadores.

### 5.3.3 Evaluación según heurísticas
#### <div align="center">UX Heuristics & Principles Evaluation</div>

##### <div align="center">Usability – Inclusive Design – Information Architecture</div>

<b> Carrera: </b> Ingeniería de Software
<b> Curso: </b> Aplicaciones Web
<b> Sección: </b> SW53
<b> Profesores: </b> TODOS
<b> Auditor: </b> Digital Dart

<b> <em> SITE O APP A EVALUAR: </em> </b> <br>
ChambeaPe

<b> <em> TAREAS A EVALUAR: </em> </b> <br>
El alcance de esta evaluación incluye la revisión de la usabilidad de las siguientes tareas:

- Crear cuenta
- Crear petición de trabajo
- Buscar trabajos
- Ver perfil de Chambeador
- Ver perfil de Empleador
- Ver petición de trabajo
- Ver trabajos

No están incluídas en esta versión de la evaluación las siguientes tareas:

- Ver mensajes (chat entre Chambeadores y Empleadores)
- Ayuda, términos y condiciones, política de privacidad, información de soporte

<b> <em> ESCALA DE SEVERIDAD: </em> </b> <br>
Los errores serán puntuados tomando en cuenta la siguiente escala de severidad:

<table align="center" border="1" width="100%" style="text-align:center;">
    <tr>
        <th>
            <b>Nivel</b>
        </th>
        <th>
            Descripción
        </th>
    </tr>
    <tr>
        <td>
            <b>1</b>
        </td>
        <td align="left">
            Problema superficial: puede ser fácilmente superador por el usuario ó ocurre con muy poco frecuencia. No necesita ser arreglado a no ser que exista disponibilidad de tiempo.
        </td>
    </tr>
    <tr>
        <td>
            <b>2</b>
        </td>
        <td align="left">
            Problema menor: puede ocurrir un poco más frecuentemente o es un poco más difícil de superar para el usuario. Se le debería asignar una prioridad baja resolverlo de cara al siguiente release.
        </td>
    </tr>
    <tr>
        <td>
            <b>3</b>
        </td>
        <td align="left">
            Problema mayor: ocurre frecuentemente o los usuarios no son capaces de resolverlos. Es importante que sean corregidos y se les debe asignar una prioridad alta.
        </td>
    </tr>
    <tr>
        <td>
            <b>4</b>
        </td>
        <td align="left">
            Problema muy grave: un error de gran impacto que impide al usuario continuar con el uso de la herramienta. Es imperativo que sea corregido antes del lanzamiento.
        </td>
    </tr>
</table>

<b> <em> TABLA DE RESUMEN: </em> </b> <br>
La siguiente tabla resume los resultados de la evaluación:

<table align="center" border="1" width="100%" style="text-align:center;">
    <tr>
        <th>#</th>
        <th>Problema</th>
        <th>Escala de severidad</th>
        <th>Heurística/Principio violada(o)</th>
    </tr>
    <tr>
        <td>1</td>
        <td align="left">El usuario no puede crear un perfil de Chambeador con su cuenta de Google</td>
        <td>3</td>
        <td align="left">Usability: Flexibilidad y eficiencia de uso</td>
    </tr>
    <tr>
        <td>2</td>
        <td align="left">Crear una petición de trabajo es tedioso debido a la cantidad de campos requeridos</td>
        <td>2</td>
        <td align="left">Usability: Consistencia y estándares</td>
    </tr>
    <tr>
        <td>3</td>
        <td align="left">No hay un filtro especializado para encontrar el tipo de trabajo que se requiere</td>
        <td>3</td>
        <td align="left">Usability: Flexibilidad y eficiencia de uso</td>
    </tr>
    <tr>
        <td>4</td>
        <td align="left">El perfil de otros Empleadores o Chambeadores no está completamente habilitado</td>
        <td>2</td>
        <td align="left">Usability: Visibilidad del estado del sistema</td>
    </tr>
    <tr>
        <td>5</td>
        <td align="left">Los trabajos no tienen una categorización específica</td>
        <td>2</td>
        <td align="left">Usability: Consistencia y estándares</td>
    </tr>
    <tr>
        <td>6</td>
        <td align="left">La lista de trabajos no tiene un filtro</td>
        <td>3</td>
        <td align="left">Usability: Flexibilidad y eficiencia de uso</td>
    </tr>
</table>

<b> <em> DESCRIPCIÓN DEL PROBLEMA: </em> </b> <br>

**PROBLEMA #1:** El usuario no puede crear un perfil de Chambeador con su cuenta de Google.
<b>Severidad:</b> 3
<b>Heurística violada:</b> Usability: Flexibilidad y eficiencia de uso.
<b>Problema:</b>
El usuario no puede crear un perfil de Chambeador con su cuenta de Google. A pesar de que la opción de registro con Google está presente, no funciona correctamente, lo que puede causar frustración en los usuarios que prefieren este método de registro.
<b>Recomedación:</b>
Se recomienda que se corrija este error para que los usuarios puedan registrarse con su cuenta de Google. <br>

**PROBLEMA #2:** Crear una petición de trabajo es tedioso debido a la cantidad de campos requeridos
<b>Severidad:</b> 2
<b>Heurística violada:</b> Usability: Consistencia y estándares.
<b>Problema:</b>
Crear una petición de trabajo es tedioso debido a la cantidad de campos requeridos. Este proceso puede ser abrumador y desalentar a los usuarios a completar la tarea.
<b>Recomedación:</b>
Se recomienda que se reduzca la cantidad de campos requeridos para crear una petición de trabajo. <br>

**PROBLEMA #3:** No hay un filtro especializado para encontrar el tipo de trabajo que se requiere.
<b>Severidad:</b> 3
<b>Heurística violada:</b> Usability: Flexibilidad y eficiencia de uso
<b>Problema:</b>
No hay un filtro especializado para encontrar el tipo de trabajo que se requiere. Esto puede hacer que la búsqueda de trabajos sea ineficiente y frustrante para los usuarios.
<b>Recomedación:</b>
Se recomienda que se agregue un filtro especializado para encontrar el tipo de trabajo que se requiere. <br>

**PROBLEMA #4:** El perfil de otros Empleadores o Chambeadores no está completamente habilitado
<b>Severidad:</b> 2
<b>Heurística violada:</b> Usability: Visibilidad del estado del sistema.
<b>Problema:</b>
El perfil de otros Empleadores o Chambeadores no está completamente habilitado. Esto puede limitar la capacidad de los usuarios para obtener información relevante sobre otros usuarios.
<b>Recomedación:</b>
Se recomienda que se habilite la mayor cantidad de información posible en los perfiles de los usuarios. <br>

**PROBLEMA #5:** Los trabajos no tienen una categorización específica
<b>Severidad:</b> 2
<b>Heurística violada:</b> Usability: Consistencia y estándares
<b>Problema:</b>
Los trabajos no tienen una categorización. Esto puede dificultar la búsqueda y el filtrado de trabajos, lo que puede resultar en una experiencia de usuario subóptima.

<b>Recomedación:</b>
Se recomienda que se agregue una categorización a los trabajos. para que así los usuarios puedan filtrarlos y encontrarlos más fácilmente. <br>

**PROBLEMA #6:** La lista de trabajos no tiene un filtro
<b>Severidad:</b> 3
<b>Heurística violada:</b> Usability: Flexibilidad y eficiencia de uso
<b>Problema:</b>
La lista de trabajos no tiene un filtro habilitado. Esto puede hacer que sea difícil para los usuarios encontrar trabajos específicos, lo que puede resultar en una experiencia de usuario frustrante.

<b>Recomedación:</b>
Se recomienda que se habilite un filtro en la lista de trabajos para que los usuarios puedan encontrar trabajos específicos más fácilmente.


## 5.4 Video About the Product

El video que se muestra a continuación es un resumen de las funcionalidades de la aplicación ChambeaPe.

<div align=center>
    <iframe width="560" height="315" src="https://www.youtube.com/embed/VxcCWuWJsR4?si=TDuM-t3K52Sz7UBS" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>    
</div>



# Conclusiones 

- Mediante el análisis de la competencia, hemos obtenido una visión clara de nuestras fortalezas y áreas de mejora, lo que nos ha capacitado para presentar un servicio que satisface plenamente las necesidades del público.

- Las Historias de Usuario nos permiten sumergirnos en la perspectiva de los usuarios, comprendiendo a fondo sus expectativas respecto a un servicio innovador destinado a superar los desafíos que enfrentan.

- Las entrevistas con nuestros segmentos objetivo han sido pilares fundamentales de nuestro proyecto, proporcionándonos información valiosa que nos ha ayudado a entender las necesidades y emociones de nuestros usuarios. Estas conversaciones nos han inspirado a diseñar una aplicación que trasciende las meras funcionalidades esperadas. Nos comprometemos a aplicar estas percepciones para desarrollar una solución que genere un impacto positivo en la vida de nuestros usuarios.

- La incorporación de UXPRESSIA ha sido esencial en nuestra metodología, brindándonos valiosas herramientas como perfiles de usuario y mapas de impacto. Estas herramientas nos han permitido profundizar en las necesidades de nuestros usuarios y mapear de manera efectiva cómo nuestro producto puede influir positivamente en sus vidas.

- La adopción de Notion como plataforma de organización ha proporcionado un espacio versátil y colaborativo para gestionar nuestro proyecto de manera eficiente. Esto ha mejorado sustancialmente nuestra comunicación y seguimiento de tareas en equipo, aumentando nuestra productividad y enfocándonos en los objetivos del proyecto.

- La combinación de GitBash y GitHub como elementos esenciales en nuestro flujo de trabajo ha resultado en una gestión de versiones y colaboración efectiva en el desarrollo de software. Esto ha garantizado un control preciso sobre el código fuente y ha simplificado la colaboración entre desarrolladores, asegurando la estabilidad y calidad de nuestro producto.

- La elección de Vertabelo para la creación de diagramas de base de datos ha demostrado ser acertada. Este enfoque visual ha simplificado la comprensión y comunicación de la estructura de la base de datos tanto para el equipo técnico como para los stakeholders no técnicos, contribuyendo a una toma de decisiones más informada y a un diseño de base de datos más sólido.

- Lucichard, como herramienta para crear diagramas de clases, nos ha permitido modelar y visualizar eficazmente la arquitectura de nuestro sistema, lo que ha sido esencial para garantizar una implementación coherente y una comprensión compartida de la estructura de nuestro software entre los miembros del equipo de desarrollo.

- La adopción de Trello como plataforma para gestionar el backlog de productos ha simplificado la planificación y priorización de tareas. Esto ha facilitado la adaptación continua a las cambiantes necesidades del proyecto y ha asegurado que nuestras entregas sean más eficaces y estén alineadas con los objetivos del negocio.

- Vue.js proporciona una serie de herramientas y funcionalidades para mejorar la experiencia del usuario en aplicaciones web. La reactividad declarativa, la capacidad de composición de componentes y la facilidad de integrar Vue con otras bibliotecas permiten la creación de interfaces de usuario dinámicas y atractivas. Esto contribuye a la retención de usuarios y al éxito general de la aplicación.

- Utilizar Vue.js como framework de desarrollo web ofrece una mayor eficiencia en el proceso de desarrollo. Su enfoque basado en componentes, la simplicidad de su sistema de reactividad y la flexibilidad en la integración con otras bibliotecas y proyectos simplifican la organización y mantenimiento del código. Esto se traduce en un desarrollo más ágil y en la capacidad de mantener y escalar la aplicación de manera más sencilla. 

- Las estimaciones de tiempo se mantuvieron en su mayoría dentro del rango estimado, lo que indica una buena comprensión de los requisitos y una gestión eficiente del tiempo. Sin embargo, hubo algunas desviaciones menores en las estimaciones de tiempo que podrían mejorarse en el futuro.

- La aplicación de los principios de diseño de UX ha sido fundamental para garantizar que la aplicación sea intuitiva y fácil de usar. Esto ha sido posible gracias a la realización de pruebas de usabilidad y a la incorporación de las percepciones de los usuarios en el diseño de la aplicación. Esto ha contribuido a una experiencia de usuario más atractiva y a una mayor retención de usuarios.
  

# Bibliografía
1. Redacción Perú21. (2023, 03 de febrero). *Número de peruanos que
trabajan y estudian crece en 5%*. Perú21. Recuperado el 23 de agosto del
2023, de
<https://peru21.pe/cheka/cursos-online-trabajadores-numero-de-peruanos-que-trabajan-y-estudian-crece-en-5-noticia/#google_vignette>

2. Redacción RPP. (2022, 01 de septiembre). *Empleo: 8 de cada 10 jóvenes
tienen problemas para encontrar trabajo*. Rpp. Recuperado el 23 de
agosto del 2023, de
<https://rpp.pe/economia/economia/empleo-8-de-cada-10-jovenes-dicen-tener-problemas-para-encontrar-trabajo-noticia-1428867?ref=rpp>

3. Redacción RPP. (2022, 01 de septiembre). Empleo: 8 de cada 10 jóvenes tienen problemas para encontrar trabajo. Rpp. Recuperado el 23 de agosto del 2023, de <https://rpp.pe/economia/economia/empleo-8-de-cada-10-jovenes-dicen-tener-problemas-para-encontrar-trabajo-noticia-1428867?ref=rpp>


<br><br>

# Anexos

- Link de la landing page: https: //web-applications-sw53-group-3.github.io/Landing-Page/
- Sprint Backlog: https://trello.com/b/mfAT1Gn2/sprint-backlog
- Criterios de aceptación:
  https://github.com/Web-Applications-SW53-Group-3/Acceptance-Tests/tree/develop
- Organization: https://github.com/Web-Applications-SW53-Group-3
- Landing Page Repository: https://github.com/Web-Applications-SW53-Group-3/Landing-Page
- Report Repository: https://github.com/Web-Applications-SW53-Group-3/Report-Group-03
- Base de datos: https://lucid.app/lucidchart/67216ac7-0bcb-4138-bcaa-72cd86a76871/edit?invitationId=inv_5845fc93-f426-4c3d-94dd-f522c9d4c11f
https://my.vertabelo.com/doc/xCMKKhOAvoi3DjIpzNX6xyP9wZ1JoB7O
- Sprint Backlog: https://trello.com/b/Gefw1vfY/ATTIacaa4de609b1f27260ebda8a38ba5cf871CA4074/sprint-backlog-02
- Aplicación Web: https://chambeapeweb.web.app/#/
- API ChambeaPe: https://chambeape.azurewebsites.net/api/worker