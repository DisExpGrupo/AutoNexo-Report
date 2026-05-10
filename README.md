# INFORME DE TRABAJO FINAL

## Carátula

<p align="center">
    <img src="https://upload.wikimedia.org/wikipedia/commons/f/fc/UPC_logo_transparente.png"></img><br>
    <strong style="font-size: 1.7em;">Universidad Peruana de Ciencias Aplicadas</strong><br>
    <strong style="font-size: 1.7em;">Ingeniería de Software</strong><br>
    <strong>Periodo: 2026-10</strong>
    <strong>1ASI0732 |  Diseño de Experimentos de Ingeniería de Software</strong><br>
    <strong>NRC : 16879</strong>
    <strong>Docente: Alex Humberto Sánchez Ponce</strong><br>
    <br><strong>Informe del Trabajo Final</strong>
</p>

<p align="center">
    <strong>Startup: ATG</strong><br>
    <strong>Producto: Autonexo</strong>
</p>

<div style="text-align:center;">
    <h3>Team Members:</h3>
    <table align="center">
        <tr>
            <th style="text-align:center;">Member</th>
            <th style="text-align:center;">Code</th>
        </tr>
       <tr>
    <td>Cruz Ibarra, Victor Andres</td>
    <td>u202311053</td>
</tr>
<tr>
    <td>Solis Chang, Santiago Valentino</td>
    <td>u20231b475</td>
</tr>
<tr>
    <td>Navarro Chang, Alicia Avril</td>
    <td>u20231d637</td>
</tr>
<tr>
    <td>Vidal Castro, Miguel Angel</td>
    <td>u202314186</td>
</tr>
<tr>
    <td>Castro Sanchez, Amir Gabriel</td>
    <td>u202310680</td>
</tr>
    </table>
</div>

<p align="center">
    <strong>Mayo, 2026</strong>
</p>
<br>

<div style="page-break-after: always;"></div>

## Registro de Versiones del Informe

| Versión | Fecha | Autor | Descripción |
|---------|-------|-------|-------------|
| 1.0 | 11 de mayo | Cruz, V.; Solis, S.; Navarro, A.; Vidal, M.; Castro, A. | • Estructura y esqueleto del informe<br>• Definición de capítulos principales (3 partes)<br>• Carátula con información de startup y equipo<br>• Student Outcome y ABET SO 4<br>• Capítulo I: Introducción, Startup Profile, Solution Profile, Lean UX<br>• Capítulo II: Requirements Elicitation & Analysis<br>• Capítulo III: Requirements Specification<br>• Capítulo IV: Product Design<br>• Capítulo V: Product Implementation<br>• Capítulo VI: Product Verification & Validation<br>• Capítulo VII: DevOps Practices |

<div style="page-break-after: always;"></div>

## Project Report Collaboration Insights

[Insertar insights de colaboración]

<div style="page-break-after: always;"></div>

## Contenido

- [INFORME DE TRABAJO FINAL](#informe-de-trabajo-final)
  - [Carátula](#carátula)
  - [Registro de Versiones del Informe](#registro-de-versiones-del-informe)
  - [Project Report Collaboration Insights](#project-report-collaboration-insights)
  - [Contenido](#contenido)
  - [Student Outcome](#student-outcome)
- [PARTE I: AS-IS SOFTWARE PROJECT](#parte-i-as-is-software-project)
  - [Capítulo I: Introducción](#capítulo-i-introducción)
    - [1.1. Startup Profile](#11-startup-profile)
      - [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
      - [1.1.2. Perfiles de Integrantes del Equipo](#112-perfiles-de-integrantes-del-equipo)
    - [1.2. Solution Profile](#12-solution-profile)
      - [1.2.1. Antecedentes y Problemática](#121-antecedentes-y-problemática)
      - [**Who (¿Quién?)**](#who-quién)
      - [**What (¿Qué?)**](#what-qué)
      - [**Where (¿Dónde?)**](#where-dónde)
      - [**When (¿Cuándo?)**](#when-cuándo)
      - [**Why (¿Por qué?)**](#why-por-qué)
      - [**How (¿Cómo?)**](#how-cómo)
      - [**How Much (¿Cuánto?)**](#how-much-cuánto)
      - [1.2.2. Lean UX Process](#122-lean-ux-process)
        - [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
        - [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
    - [**Business Assumptions**](#business-assumptions)
    - [**User Assumptions**](#user-assumptions)
        - [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
    - [**Hypothesis 01**](#hypothesis-01)
    - [**Hypothesis 02**](#hypothesis-02)
    - [**Hypothesis 03**](#hypothesis-03)
    - [**Hypothesis 04**](#hypothesis-04)
        - [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
    - [1.3. Segmentos Objetivo](#13-segmentos-objetivo)
    - [**Segmento objetivo #1: Propietarios**](#segmento-objetivo-1-propietarios)
    - [**Segmento objetivo #2: Mecánicos**](#segmento-objetivo-2-mecánicos)
  - [Capítulo II: Requirements Elicitation \& Analysis](#capítulo-ii-requirements-elicitation--analysis)
    - [2.1. Competidores](#21-competidores)
      - [2.1.1. Análisis Competitivo](#211-análisis-competitivo)
      - [2.1.2. Estrategias y Tácticas Frente a Competidores](#212-estrategias-y-tácticas-frente-a-competidores)
    - [2.2. Entrevistas](#22-entrevistas)
      - [2.2.1. Diseño de Entrevistas](#221-diseño-de-entrevistas)
      - [2.2.2. Registro de Entrevistas](#222-registro-de-entrevistas)
      - [2.2.3. Análisis de Entrevistas](#223-análisis-de-entrevistas)
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
    - [3.3. Product Backlog](#33-product-backlog)
    - [3.4. Impact Mapping](#34-impact-mapping)
  - [Capítulo IV: Product Design](#capítulo-iv-product-design)
    - [4.1. Style Guidelines](#41-style-guidelines)
      - [4.1.1. General Style Guidelines](#411-general-style-guidelines)
      - [4.1.2. Web Style Guidelines](#412-web-style-guidelines)
      - [4.1.3. Mobile Style Guidelines](#413-mobile-style-guidelines)
        - [4.1.3.1. iOS Mobile Style Guidelines](#4131-ios-mobile-style-guidelines)
        - [4.1.3.2. Android Mobile Style Guidelines](#4132-android-mobile-style-guidelines)
    - [4.2. Information Architecture](#42-information-architecture)
      - [4.2.1. Organization Systems](#421-organization-systems)
      - [4.2.2. Labeling Systems](#422-labeling-systems)
      - [4.2.3. SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
      - [4.2.4. Searching Systems](#424-searching-systems)
      - [4.2.5. Navigation Systems](#425-navigation-systems)
    - [4.3. Landing Page UI Design](#43-landing-page-ui-design)
      - [4.3.1. Landing Page Wireframe](#431-landing-page-wireframe)
      - [4.3.2. Landing Page Mock-up](#432-landing-page-mock-up)
    - [4.4. Mobile Applications UX/UI Design](#44-mobile-applications-uxui-design)
      - [4.4.1. Mobile Applications Wireframes](#441-mobile-applications-wireframes)
      - [4.4.2. Mobile Applications Wireflow Diagrams](#442-mobile-applications-wireflow-diagrams)
      - [4.4.3. Mobile Applications Mock-ups](#443-mobile-applications-mock-ups)
      - [4.4.4. Mobile Applications User Flow Diagrams](#444-mobile-applications-user-flow-diagrams)
    - [4.5. Mobile Applications Prototyping](#45-mobile-applications-prototyping)
      - [4.5.1. Android Mobile Applications Prototyping](#451-android-mobile-applications-prototyping)
      - [4.5.2. iOS Mobile Applications Prototyping](#452-ios-mobile-applications-prototyping)
    - [4.6. Web Applications UX/UI Design](#46-web-applications-uxui-design)
      - [4.6.1. Web Applications Wireframes](#461-web-applications-wireframes)
      - [4.6.2. Web Applications Wireflow Diagrams](#462-web-applications-wireflow-diagrams)
      - [4.6.3. Web Applications Mock-ups](#463-web-applications-mock-ups)
      - [4.6.4. Web Applications User Flow Diagrams](#464-web-applications-user-flow-diagrams)
    - [4.7. Web Applications Prototyping](#47-web-applications-prototyping)
    - [4.8. Domain-Driven Software Architecture](#48-domain-driven-software-architecture)
      - [4.8.1. Software Architecture Context Diagram](#481-software-architecture-context-diagram)
      - [4.8.2. Software Architecture Container Diagrams](#482-software-architecture-container-diagrams)
      - [4.8.3. Software Architecture Components Diagrams](#483-software-architecture-components-diagrams)
    - [4.9. Software Object-Oriented Design](#49-software-object-oriented-design)
      - [4.9.1. Class Diagrams](#491-class-diagrams)
      - [4.9.2. Class Dictionary](#492-class-dictionary)
    - [4.10. Database Design](#410-database-design)
      - [4.10.1. Relational/Non-Relational Database Diagram](#4101-relationalnon-relational-database-diagram)
- [Capítulo V: Product Implementation](#capítulo-v-product-implementation)
  - [5.1. Software Configuration Management](#51-software-configuration-management)
    - [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
    - [5.1.2. Source Code Management](#512-source-code-management)
    - [5.1.3. Source Code Style Guide \& Conventions](#513-source-code-style-guide--conventions)
    - [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
    - [5.2. Product Implementation \& Deployment](#52-product-implementation--deployment)
      - [5.2.1. Sprint Backlogs](#521-sprint-backlogs)
      - [5.2.2. Implemented Landing Page Evidence](#522-implemented-landing-page-evidence)
      - [5.2.3. Implemented Frontend-Web Application Evidence](#523-implemented-frontend-web-application-evidence)
      - [5.2.4. Acuerdo de Servicio - SaaS](#524-acuerdo-de-servicio---saas)
      - [5.2.5. Implemented Native-Mobile Application Evidence](#525-implemented-native-mobile-application-evidence)
      - [5.2.6. Implemented RESTful API and/or Serverless Backend Evidence](#526-implemented-restful-api-andor-serverless-backend-evidence)
      - [5.2.7. RESTful API Documentation](#527-restful-api-documentation)
      - [5.2.8. Team Collaboration Insights](#528-team-collaboration-insights)
    - [5.3. Video About-the-Product](#53-video-about-the-product)
- [PARTE II: VERIFICATION, VALIDATION \& PIPELINE](#parte-ii-verification-validation--pipeline)
  - [Capítulo VI: Product Verification \& Validation](#capítulo-vi-product-verification--validation)
    - [6.1. Testing Suites \& Validation](#61-testing-suites--validation)
      - [6.1.1. Core Entities Unit Tests](#611-core-entities-unit-tests)
      - [6.1.2. Core Integration Tests](#612-core-integration-tests)
      - [6.1.3. Core Behavior-Driven Development](#613-core-behavior-driven-development)
      - [6.1.4. Core System Tests](#614-core-system-tests)
    - [6.2. Static Testing \& Verification](#62-static-testing--verification)
      - [6.2.1. Static Code Analysis](#621-static-code-analysis)
        - [6.2.1.1. Coding Standard \& Code Conventions](#6211-coding-standard--code-conventions)
        - [6.2.1.2. Code Quality \& Code Security](#6212-code-quality--code-security)
      - [6.2.2. Reviews](#622-reviews)
    - [6.3. Validation Interviews](#63-validation-interviews)
      - [6.3.1. Diseño de Entrevistas](#631-diseño-de-entrevistas)
      - [6.3.2. Registro de Entrevistas](#632-registro-de-entrevistas)
      - [6.3.3. Evaluaciones Según Heurísticas](#633-evaluaciones-según-heurísticas)
    - [6.4. Auditoría de Experiencias de Usuario](#64-auditoría-de-experiencias-de-usuario)
      - [6.4.1. Auditoría Realizada](#641-auditoría-realizada)
        - [6.4.1.1. Información del Grupo Auditado](#6411-información-del-grupo-auditado)
        - [6.4.1.2. Cronograma de Auditoría Realizada](#6412-cronograma-de-auditoría-realizada)
        - [6.4.1.3. Contenido de Auditoría Realizada](#6413-contenido-de-auditoría-realizada)
      - [6.4.2. Auditoría Recibida](#642-auditoría-recibida)
        - [6.4.2.1. Información del Grupo Auditor](#6421-información-del-grupo-auditor)
        - [6.4.2.2. Cronograma de Auditoría Recibida](#6422-cronograma-de-auditoría-recibida)
        - [6.4.2.3. Contenido de Auditoría Recibida](#6423-contenido-de-auditoría-recibida)
        - [6.4.2.4. Resumen de Modificaciones para Subsanar Hallazgos](#6424-resumen-de-modificaciones-para-subsanar-hallazgos)
  - [Capítulo VII: DevOps Practices](#capítulo-vii-devops-practices)
    - [7.1. Continuous Integration](#71-continuous-integration)
      - [7.1.1. Tools and Practices](#711-tools-and-practices)
      - [7.1.2. Build \& Test Suite Pipeline Components](#712-build--test-suite-pipeline-components)
    - [7.2. Continuous Delivery](#72-continuous-delivery)
      - [7.2.1. Tools and Practices](#721-tools-and-practices)
      - [7.2.2. Stages Deployment Pipeline Components](#722-stages-deployment-pipeline-components)
    - [7.3. Continuous Deployment](#73-continuous-deployment)
      - [7.3.1. Tools and Practices](#731-tools-and-practices)
      - [7.3.2. Production Deployment Pipeline Components](#732-production-deployment-pipeline-components)
    - [7.4. Continuous Monitoring](#74-continuous-monitoring)
      - [7.4.1. Tools and Practices](#741-tools-and-practices)
      - [7.4.2. Monitoring Pipeline Components](#742-monitoring-pipeline-components)
      - [7.4.3. Alerting Pipeline Components](#743-alerting-pipeline-components)
      - [7.4.4. Notification Pipeline Components](#744-notification-pipeline-components)
- [PARTE III: EXPERIMENT-DRIVEN LIFECYCLE](#parte-iii-experiment-driven-lifecycle)
  - [Capítulo VIII: Experiment-Driven Development](#capítulo-viii-experiment-driven-development)
    - [8.1. Experiment Planning](#81-experiment-planning)
      - [8.1.1. As-Is Summary](#811-as-is-summary)
      - [8.1.2. Raw Material: Assumptions, Knowledge Gaps, Ideas, Claims](#812-raw-material-assumptions-knowledge-gaps-ideas-claims)
      - [8.1.3. Experiment-Ready Questions](#813-experiment-ready-questions)
      - [8.1.4. Question Backlog](#814-question-backlog)
      - [8.1.5. Experiment Cards](#815-experiment-cards)
    - [8.2. Experiment Design](#82-experiment-design)
      - [8.2.1. Hypotheses](#821-hypotheses)
      - [8.2.2. Domain Business Metrics](#822-domain-business-metrics)
      - [8.2.3. Measures](#823-measures)
      - [8.2.4. Conditions](#824-conditions)
      - [8.2.5. Scale Calculations and Decisions](#825-scale-calculations-and-decisions)
      - [8.2.6. Methods Selection](#826-methods-selection)
      - [8.2.7. Data Analytics: Goals, KPIs and Metrics Selection](#827-data-analytics-goals-kpis-and-metrics-selection)
      - [8.2.8. Web and Mobile Tracking Plan](#828-web-and-mobile-tracking-plan)
    - [8.3. Experimentation](#83-experimentation)
      - [8.3.1. To-Be User Stories](#831-to-be-user-stories)
      - [8.3.2. To-Be Product Backlog](#832-to-be-product-backlog)
      - [8.3.3. Pipeline-supported, Experiment-Driven To-Be Software Platform Lifecycle](#833-pipeline-supported-experiment-driven-to-be-software-platform-lifecycle)
        - [8.3.3.1. To-Be Sprint Backlogs](#8331-to-be-sprint-backlogs)
        - [8.3.3.2. Implemented To-Be Landing Page Evidence](#8332-implemented-to-be-landing-page-evidence)
        - [8.3.3.3. Implemented To-Be Frontend-Web Application Evidence](#8333-implemented-to-be-frontend-web-application-evidence)
        - [8.3.3.4. Implemented To-Be Native-Mobile Application Evidence](#8334-implemented-to-be-native-mobile-application-evidence)
        - [8.3.3.5. Implemented To-Be RESTful API and/or Serverless Backend Evidence](#8335-implemented-to-be-restful-api-andor-serverless-backend-evidence)
        - [8.3.3.6. Team Collaboration Insights](#8336-team-collaboration-insights)
      - [8.3.4. To-Be Validation Interviews](#834-to-be-validation-interviews)
        - [8.3.4.1. Diseño de Entrevistas](#8341-diseño-de-entrevistas)
        - [8.3.4.2. Registro de Entrevistas](#8342-registro-de-entrevistas)
      - [8.3.4. Experiment Aftermath \& Analysis](#834-experiment-aftermath--analysis)
    - [8.4. Experiment Aftermath \& Analysis](#84-experiment-aftermath--analysis)
      - [8.4.1. Analysis and Interpretation of Results](#841-analysis-and-interpretation-of-results)
      - [8.4.2. Re-scored and Re-prioritized Question Backlog](#842-re-scored-and-re-prioritized-question-backlog)
    - [8.5. Continuous Learning](#85-continuous-learning)
      - [8.5.1. Shareback Session Artifacts: Learning Workflow](#851-shareback-session-artifacts-learning-workflow)
    - [8.6. To-Be Software Platform Pre-launch](#86-to-be-software-platform-pre-launch)
      - [8.6.1. About-the-Product Intro Video](#861-about-the-product-intro-video)
  - [Conclusiones](#conclusiones)
    - [Conclusiones y Recomendaciones](#conclusiones-y-recomendaciones)
    - [Video App Validation](#video-app-validation)
    - [Video About-the-Team](#video-about-the-team)
  - [Bibliografía](#bibliografía)
  - [Anexos](#anexos)

<div style="page-break-after: always;"></div>

## Student Outcome

**ABET – EAC - Student Outcome 4**
**Criterio:** La capacidad de reconocer responsabilidades éticas y profesionales en situaciones de ingeniería y hacer juicios informados, que deben considerar el impacto de las soluciones de ingeniería en contextos globales, económicos, ambientales y sociales.

En el siguiente cuadro se describe las acciones realizadas y enunciados de conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro del ABET – EAC - Student Outcome 4.

| Criterio específico | Acciones realizadas | Conclusiones |
|---|---|---|
| 4.c.1 Reconoce responsabilidad ética y profesional en situaciones de ingeniería de software | <i>Cruz Ibarra, Victor Andres</i><br><i>TB1</i><br>Participó en la definición del problema y el alcance inicial del proyecto.<br><i>TP1</i><br>Apoyó la validación de requerimientos y la documentación del avance.<br><br><i>Solis Chang, Santiago Valentino</i><br><i>TB1</i><br>Colaboró en el análisis inicial y en la redacción de artefactos base.<br><i>TP1</i><br>Apoyó la mejora de evidencias y la revisión de entregables.<br><br><i>Navarro Chang, Alicia Avril</i><br><i>TB1</i><br>Contribuyó con el levantamiento de información y la organización de materiales.<br><i>TP1</i><br>Participó en la actualización de contenidos y la consolidación de evidencias.<br><br><i>Vidal Castro, Miguel Angel</i><br><i>TB1</i><br>Apoyó la estructuración del informe y la revisión de secciones clave.<br><i>TP1</i><br>Colaboró en la integración de resultados y la verificación de avances.<br><br><i>Castro Sanchez, Amir Gabriel</i><br><i>TB1</i><br>Participó en la organización del contenido y en la síntesis de avances.<br><i>TP1</i><br>Apoyó la consolidación final de capítulos y la revisión de consistencia. | <i>TB1</i><br>El grupo mostró responsabilidad al organizar el trabajo y respetar criterios profesionales.<br><br><i>TP1</i><br>El grupo consolidó una ejecución más ordenada y ética del trabajo técnico. |
| 4.c.2 Emite juicios informados considerando el impacto de las soluciones de ingeniería de software en contextos globales, económicos, ambientales y sociales | <i>Cruz Ibarra, Victor Andres</i><br><i>TB1</i><br>Analizó el contexto de la startup y su impacto inicial en el entorno.<br><i>TP1</i><br>Participó en el análisis de mejoras con enfoque en valor, uso y viabilidad.<br><br><i>Solis Chang, Santiago Valentino</i><br><i>TB1</i><br>Apoyó la identificación de oportunidades y restricciones del proyecto.<br><i>TP1</i><br>Contribuyó a evaluar ajustes del producto según alcance y beneficio.<br><br><i>Navarro Chang, Alicia Avril</i><br><i>TB1</i><br>Revisó información del dominio para sustentar decisiones del equipo.<br><i>TP1</i><br>Colaboró en la valoración de entregables y mejoras del producto.<br><br><i>Vidal Castro, Miguel Angel</i><br><i>TB1</i><br>Apoyó el análisis de viabilidad y coherencia de los entregables.<br><i>TP1</i><br>Participó en la revisión de resultados y su impacto en la propuesta.<br><br><i>Castro Sanchez, Amir Gabriel</i><br><i>TB1</i><br>Sintetizó aportes para sustentar decisiones del informe.<br><i>TP1</i><br>Apoyó la evaluación final de coherencia entre solución y necesidades. | <i>TB1</i><br>El grupo tomó decisiones considerando necesidades reales del negocio y del usuario.<br><br><i>TP1</i><br>El grupo hizo juicios más sólidos sobre el impacto de la solución propuesta. |

<div style="page-break-after: always;"></div>

# PARTE I: AS-IS SOFTWARE PROJECT

<div style="page-break-after: always;"></div>

## Capítulo I: Introducción

### 1.1. Startup Profile

#### 1.1.1. Descripción de la Startup

Autonexo es una aplicación diseñada para conectar a los propietarios de vehículos con mecánicos especializados en todo tipo de mantenimiento vehicular, ya sea preventivo, correctivo o cualquier otro tipo de servicio automotriz. La aplicación actúa como un intermediario eficiente, proporcionando una solución integral que facilita la interacción entre los conductores y los profesionales del sector automotriz.

La plataforma permite a los propietarios acceder a un catálogo de mecánicos certificados y servicios disponibles, con la posibilidad de elegir en función de la especialización, reputación y proximidad del servicio. Por otro lado, los mecánicos tienen la oportunidad de promocionar sus servicios, gestionar su agenda de forma eficiente y recibir solicitudes de mantenimiento en tiempo real, lo que les permite maximizar su tiempo y la eficiencia de sus operaciones.

Según el estudio realizado por Innocar y Roshfrans (2022), solo el 23.5% de los talleres en América Latina utilizan software especializado para gestionar sus operaciones, lo que evidencia una escasa adopción tecnológica en el sector. Esta brecha tecnológica no solo limita la eficiencia interna de los talleres, sino que también reduce la calidad y transparencia percibida por los clientes..

La plataforma no solo mejora la accesibilidad al servicio automotriz, sino que también permite un registro detallado del historial de mantenimiento de cada vehículo, optimizando la gestión preventiva y reduciendo los costos a largo plazo para los conductores. Además, la capacidad de recibir atención personalizada y el acceso a mecánicos especializados en diversas áreas del mantenimiento incrementan la confianza y la satisfacción del usuario.

El objetivo de Autonexo es transformar la experiencia de mantenimiento vehicular, ofreciendo una solución accesible, transparente y efectiva tanto para los conductores como para los mecánicos. Al mismo tiempo, fomenta la adopción de la tecnología en un sector que históricamente ha dependido de métodos tradicionales y manuales, mejorando la eficiencia y el control sobre los costos de mantenimiento.

#### 1.1.2. Perfiles de Integrantes del Equipo

<table border="1">
  <tr>
      <td style="text-align:center;"><img alt="Victor Cruz" src="assets/images/photos/cruz-andres.jpeg" /></td>
      <td><strong>Victor Cruz - u202311053</strong><br>Mi nombre es Victor Cruz, tengo 20 años y estoy cursando mi 7to ciclo de la carrera de Ingeniería de Software en la UPC. Soy una persona entusiasta, creativa y comprometida con cada actividad que realizo. Estoy decidido a dar lo mejor de mí en este proyecto para lograr resultados de calidad.</td>
  </tr>
  <tr>
      <td style="text-align:center;"><img alt="Santiago Solis" src="assets/images/photos/solis-santiago.jpeg" /></td>
      <td><strong>Santiago Solis - u20231b475</strong><br>Mi nombre es Santiago Solis, soy estudiante de Ingeniería de Software en la UPC. Me apasiona la tecnología y todo lo relacionado con el desarrollo de software. En mi tiempo libre disfruto jugar videojuegos, practicar tenis. Me gusta enfrentarme a desafíos complejos y encontrar soluciones creativas. Estoy en constante aprendizaje, siempre buscando mejorar mis habilidades en programación web. Me considero una persona comprometida con mis proyectos y con ganas de crecer tanto profesionalmente como personalmente. Disfruto trabajar en equipo y siempre trato de aportar lo mejor de mí en todo lo que hago.</td>
  </tr>
  <tr>
      <td style="text-align:center;"><img alt="Alicia Navarro" src="assets/images/photos/navarro-alicia.jpeg" /></td>
      <td><strong>Alicia Navarro - u20231d637</strong><br>Mi nombre es Alicia Navarro, tengo 20 años y estoy cursando mi 7to ciclo de la carrera de Ingeniería de Software en la UPC. Soy una persona dedicada, analítica y con gran interés en el desarrollo de soluciones tecnológicas innovadoras. Me caracterizo por mi capacidad de trabajo en equipo y mi compromiso con la excelencia en cada proyecto que realizo. Estoy enfocado en aprender constantemente y aplicar mis conocimientos para crear aplicaciones que generen un impacto positivo en la sociedad.</td>
  </tr>
  <tr>
      <td style="text-align:center;"><img alt="Miguel Vidal" src="assets/images/photos/vidal-miguel.jpeg" /></td>
      <td><strong>Miguel Vidal - u202314186</strong><br>Mi nombre es Miguel Vidal, tengo 20 años y estoy cursando mi 7to ciclo de la carrera de Ingeniería de Software en la UPC. Soy una persona proactiva, creativa y con gran pasión por la tecnología. Me destaco por mi capacidad de resolver problemas de manera eficiente y mi habilidad para trabajar colaborativamente en proyectos complejos. Estoy comprometido con el aprendizaje continuo y siempre busco aplicar las mejores prácticas en el desarrollo de software. Mi objetivo es contribuir significativamente al éxito de este proyecto y crecer profesionalmente en el campo de la ingeniería de software.</td>
  </tr>
  <tr>
      <td style="text-align:center;"><img width="200" height="200" alt="Amir Castro" src="assets/images/photos/castro-amir.jpg" /></td>
      <td><strong>Amir Castro - u202310680</strong><br>Mi nombre es Amir Castro, tengo 20 años y actualmente curso el 7to ciclo de la carrera de Ingeniería de Software en la UPC. Me considero una persona responsable con facilidad para adaptarme a distintos entornos y manejar varias tareas a la vez. Siempre doy lo mejor de mí en cada proyecto, aportando dedicación, esfuerzo y actitud positiva.</td>
  </tr>
</table>

### 1.2. Solution Profile

#### 1.2.1. Antecedentes y Problemática

#### **Who (¿Quién?)**

Afecta principalmente a **mecánicos y propietarios de vehículos**, quienes necesitan gestionar y acceder a servicios de mantenimiento de manera eficiente.

#### **What (¿Qué?)**

Actualmente, los mecánicos enfrentan dificultades para organizar, planificar y dar seguimiento a los mantenimientos de los vehículos. La ausencia de un registro centralizado y estandarizado provoca errores en el control de historial, retrasos en los servicios y decisiones poco informadas. Por su parte, los propietarios tienen dificultad para encontrar mecánicos confiables y servicios adecuados a sus necesidades, lo que genera desconfianza y pérdida de tiempo.

#### **Where (¿Dónde?)**

Esta problemática se observa en **talleres mecánicos tradicionales** y entre propietarios de vehículos que buscan servicios automotrices confiables, especialmente en entornos urbanos donde la demanda de mantenimiento es alta.

#### **When (¿Cuándo?)**

El problema es constante y se intensifica en periodos críticos, como fechas de mantenimiento preventivo recomendado, estaciones de alto uso del vehículo y ante situaciones donde un vehículo requiere reparación inmediata.

#### **Why (¿Por qué?)**

La raíz del problema es la **falta de digitalización y centralización** en la gestión de servicios automotrices. Muchos talleres dependen de métodos manuales como hojas de cálculo, cuadernos o aplicaciones genéricas que no están diseñadas para el sector automotriz. Esto provoca ineficiencia operativa, aumento de costos y baja satisfacción del cliente.

#### **How (¿Cómo?)**

**Autonexo** propone una solución mediante una **aplicación móvil y web** que conecta directamente a propietarios con mecánicos certificados. La app permite registrar vehículos, historial de mantenimiento y servicios solicitados, al mismo tiempo que los mecánicos pueden gestionar sus agendas y responder a solicitudes en tiempo real, optimizando tiempos y recursos.

#### **How Much (¿Cuánto?)**

Uno de los principales desafíos en el sector automotriz es la ineficiencia en la gestión del mantenimiento vehicular, lo que genera sobrecostos y pérdida de productividad. Según UpKeep (2023), el mantenimiento puede representar entre el 15 % y 40 % de los costos totales de producción, lo que evidencia su impacto directo en la sostenibilidad financiera de las organizaciones. De igual forma, Infraspeak (2024) señala que hasta un 50 % de los costos de mantenimiento corresponden a desperdicios, ya sea por trabajos innecesarios, duplicación de esfuerzos o falta de planificación estratégica.

#### 1.2.2. Lean UX Process

##### 1.2.2.1. Lean UX Problem Statements

Autonexo tiene como objetivo ofrecer a talleres mecánicos y propietarios de vehículos una **solución digital integral** que permita centralizar los procesos clave del mantenimiento vehicular, incluyendo el registro de unidades, la planificación de mantenimientos, el control de repuestos, el cálculo de presupuestos y el seguimiento histórico de intervenciones.

Actualmente, la mayoría de talleres y propietarios gestionan el mantenimiento de forma **manual, fragmentada y desorganizada**. Muchos dependen de hojas de Excel, cuadernos o herramientas genéricas que no están adaptadas a las necesidades específicas del sector automotriz. Esto provoca **fallas en el control de registros históricos, mayores costos por mantenimientos correctivos, retrasos en la atención de servicios y decisiones poco informadas** respecto al cuidado de los vehículos.

La falta de estandarización y centralización **limita la eficiencia de los talleres**, reduce la confianza de los propietarios y afecta la calidad del servicio. Además, genera **gastos imprevistos y tiempos muertos** tanto para mecánicos como para propietarios. La ausencia de un sistema unificado impide llevar un seguimiento transparente y ordenado del estado de cada vehículo, impactando negativamente en la productividad de los técnicos y en la satisfacción de los clientes.

**Pregunta clave de diseño:**

> ¿Cómo podríamos centralizar y digitalizar la gestión del mantenimiento vehicular de forma escalable y accesible, permitiendo a mecánicos y propietarios **ahorrar tiempo, reducir costos, mejorar la trazabilidad y asegurar un mantenimiento constante sin complicaciones**?

##### 1.2.2.2. Lean UX Assumptions

### **Business Assumptions**

1. Nuestros clientes necesitan una plataforma digital centralizada que les permita gestionar de manera integral el mantenimiento de sus vehículos y talleres, ya que actualmente dependen de métodos manuales que generan retrasos y errores, y buscan optimizar la eficiencia y control de sus operaciones.

2. Estas necesidades se pueden resolver mediante un software especializado que integre procesos clave como el registro de vehículos, historial de mantenimiento, planificación de servicios preventivos y correctivos, control de repuestos, cálculo de presupuestos y seguimiento de intervenciones en tiempo real, permitiendo centralizar toda la información y mejorar la trazabilidad de los servicios.

3. Los clientes iniciales serán propietarios de vehículos particulares y mecánicos independientes o de talleres pequeños que actualmente utilizan hojas de Excel, cuadernos o aplicaciones genéricas, y que requieren un sistema confiable para organizar sus mantenimientos y brindar un mejor servicio.

4. El valor más importante que buscan nuestros clientes es un control confiable, eficiente y accesible del mantenimiento vehicular y de los servicios del taller, reduciendo errores, retrasos y gastos innecesarios, mientras aumentan la confianza y satisfacción de los usuarios.

5. Adicionalmente, los usuarios pueden obtener beneficios tangibles como ahorro de tiempo y dinero en mantenimientos correctivos y preventivos, presupuestos claros y detallados para cada servicio, así como acceso a una red de mecánicos o propietarios disponibles en tiempo real según proximidad, especialización y reputación.

6. La adquisición de clientes se realizará mediante marketing digital en redes sociales como Facebook, Instagram y TikTok, campañas en Google Ads enfocadas en búsquedas de servicios automotrices, programas de referidos que incentiven la recomendación de la app, así como alianzas estratégicas con talleres automotrices para fomentar la adopción temprana.

7. El modelo de monetización será a través de suscripción mensual para mecánicos y talleres, otorgándoles acceso a herramientas avanzadas de gestión del taller, listado de propietarios y vehículos registrados en la plataforma, funcionalidades de planificación, presupuesto y seguimiento de historial.

8. La competencia principal incluye aplicaciones como Drivvo, Fleetio y otros softwares genéricos de gestión vehicular, pero nuestro diferencial radica en una interfaz amigable, localización precisa y funcionalidades adaptadas tanto para talleres como para propietarios, incluyendo búsqueda de mecánicos en tiempo real, historial completo y trazable de cada vehículo, y agenda optimizada para talleres.

9. Los venceremos gracias a nuestro enfoque local, la facilidad de uso de la plataforma y las funcionalidades específicas diseñadas para satisfacer tanto a propietarios individuales como a técnicos mecánicos, proporcionando eficiencia operativa y trazabilidad completa del mantenimiento vehicular.

10. El mayor riesgo es que los usuarios no adopten la plataforma debido a la preferencia por métodos tradicionales o a la falta de familiaridad con herramientas digitales, lo que podría limitar el crecimiento y uso del sistema.

11. Para mitigar este riesgo, se implementará una interfaz simple e intuitiva, acompañada de capacitaciones básicas y materiales de apoyo para mecánicos y propietarios, demostraciones gratuitas y pruebas piloto, así como testimonios de clientes satisfechos que incentiven la confianza y la adopción de la plataforma, asegurando que Autonexo cumpla con su objetivo de centralizar y digitalizar la gestión del mantenimiento vehicular de manera eficiente, accesible y confiable.

### **User Assumptions**

1. **¿Quién es el usuario?**

Nuestros usuarios son principalmente **propietarios de vehículos particulares** que buscan cuidar su inversión y optimizar los costos de mantenimiento, así como **mecánicos independientes o de talleres pequeños** que desean llevar un control digital eficiente de múltiples mantenimientos y agendas de servicio, ya que actualmente dependen de métodos manuales o herramientas poco integradas.

2. **¿Qué problema tiene nuestro producto que debe resolver?**

El problema principal que Autonexo debe resolver es la **desorganización y fragmentación en la gestión del mantenimiento vehicular**, que genera sobrecostos, retrasos, fallas mecánicas evitables y pérdida de tiempo en tareas repetitivas o manuales, afectando tanto la eficiencia de los talleres como la satisfacción de los propietarios.

3. **¿Qué características son importantes?**

Para cubrir estas necesidades, el producto debe ofrecer **registro integral de vehículos y usuarios**, una **plataforma de búsqueda de mecánico en tiempo real**, **cálculo de presupuestos de mantenimientos**, **historial detallado de intervenciones por vehículo** y **servicio de mensajería directa entre usuario y mecánico**, todo accesible desde dispositivos móviles para gestionar mantenimientos de manera centralizada y eficiente.

4. **¿Dónde encaja nuestro producto en su trabajo o vida?**

El producto encaja directamente en el **día a día de los propietarios y mecánicos**: los propietarios lo utilizan para planificar, registrar y dar seguimiento a los mantenimientos de sus vehículos, mientras que los mecánicos gestionan múltiples unidades y presupuestos desde un solo lugar, optimizando su tiempo y reduciendo errores operativos.

5. **¿Cuándo y cómo es usado nuestro producto?**

Autonexo será utilizado **cada vez que un usuario necesite planificar, registrar o dar seguimiento a un mantenimiento**, accediendo principalmente desde dispositivos móviles para garantizar flexibilidad, disponibilidad inmediata y control en tiempo real, sin importar si se encuentran en el taller, en ruta o en casa.

6. **¿Cómo debe verse nuestro producto y cómo debe comportarse?**

El diseño y comportamiento del producto deben reflejar un **diseño moderno, limpio y amigable**, con menús intuitivos y fáciles de navegar, garantizando que el sistema responda rápidamente, evite interrupciones y proporcione una **experiencia fluida y confiable**, apta tanto para usuarios con experiencia digital como para aquellos que prefieren soluciones sencillas y accesibles.

##### 1.2.2.3. Lean UX Hypothesis Statements

### **Hypothesis 01**

**Creemos que** al ofrecer una plataforma centralizada para registrar vehículos, usuarios y mantenimientos, ayudaremos a los usuarios a organizar sus procesos de mantenimiento de manera más eficiente y reducir errores o pérdidas de información.

**Sabremos que hemos tenido éxito**

**Cuando al menos** el 70% de los usuarios registre y mantenga actualizado el historial de sus vehículos y mantenimientos durante el primer mes de uso.

### **Hypothesis 02**

**Creemos que** al integrar herramientas de registro de mantenimiento y cálculo automático de presupuestos, facilitaremos la gestión operativa y financiera de los mecánicos y propietarios de vehículos, permitiéndoles planificar y ejecutar mantenimientos con mayor precisión.

**Sabremos que hemos tenido éxito**

**Cuando al menos** el 60% de los usuarios utilicen estas funciones para planificar o ejecutar mantenimientos dentro de la plataforma.

### **Hypothesis 03**

**Creemos que** al diseñar una interfaz móvil intuitiva, clara y accesible, incentivaremos el uso constante de Autonexo incluso por usuarios con poca experiencia digital.

**Sabremos que hemos tenido éxito**

**Cuando al menos** el 75% de los usuarios activos utilicen la plataforma semanalmente para gestionar sus vehículos.

### **Hypothesis 04**

**Creemos que** al permitir el acceso al historial completo de mantenimiento de cada vehículo, incrementaremos la confianza de los usuarios en sus decisiones de reparación, mantenimiento preventivo o venta de vehículos.

**Sabremos que hemos tenido éxito**

**Cuando al menos** el 50% de los usuarios consulten el historial como parte del proceso de evaluación del estado de sus vehículos.

##### 1.2.2.4. Lean UX Canvas

- Lean Ux Canvas
<img alt="Lean Ux Canvas" src="assets/lean-ux/lean-ux-canvas.jpg"/>

### 1.3. Segmentos Objetivo

Con el propósito de llegar de manera efectiva a posibles clientes, Autonexo ha definido dos segmentos principales como público objetivo.

---

### **Segmento objetivo #1: Propietarios**

Personas que poseen uno o más vehículos personales y desean gestionar de forma eficiente el mantenimiento, control de gastos y estado general de su unidad, evitando olvidos o problemas mecánicos por falta de seguimiento.

**Aspectos demográficos:**

Sexo: Masculino y femenino,

Rango de edad: 25–50 años,

Nivel socioeconómico: Clases B y C (media-alta y media).

**Aspectos geográficos:**

Nacionalidad: Perú,

Zona geográfica: Urbana (principalmente Lima Metropolitana y otras ciudades con alta concentración vehicular).

**Aspectos psicográficos:**

Intereses: Cuidado del vehículo, control financiero, tecnología práctica, seguridad vial, soluciones digitales simples,

Estilo de vida: Conducen regularmente, valoran la comodidad y buscan evitar gastos imprevistos o pérdidas de tiempo por fallas mecánicas,

Actitudes: Son conscientes de la importancia del mantenimiento vehicular y están abiertos a herramientas digitales que les faciliten llevar un control ordenado y accesible desde su celular.

**Necesidades clave:**

Recordatorios de mantenimiento, historial de mantenimiento accesible, planificación de servicios, reducción de costos por mantenimientos imprevistos.

**Comportamiento digital:**

Uso de apps móviles, notificaciones y alertas, búsqueda de información y servicios de manera digital y rápida.

---

### **Segmento objetivo #2: Mecánicos**

Profesionales que trabajan en talleres y desean gestionar mejor sus servicios y acceder a historiales de mantenimiento para brindar un mejor servicio a sus clientes.

**Aspectos demográficos:**

Sexo: Masculino (en su mayoría),

Rango de edad: 20–50 años,

Nivel socioeconómico: Clases C y D (media y media-baja).

**Aspectos geográficos:**

Nacionalidad: Perú,

Zona geográfica: Urbana (distritos con concentración de talleres y servicios automotrices).

**Aspectos psicográficos:**

Intereses: Reparación automotriz, optimización de tiempo, atención al cliente, soluciones digitales simples,

Estilo de vida: Profesionales prácticos, con un enfoque técnico, acostumbrados al trabajo manual, pero abiertos a soluciones tecnológicas si son simples y funcionales,

Actitudes: Desean mejorar la calidad de su servicio y organización interna, valoran plataformas que les permitan brindar un servicio más profesional sin complicaciones adicionales.

**Necesidades clave:**

Gestión eficiente de mantenimientos, acceso rápido a historiales de vehículos, reducción de errores en la planificación de servicios, optimización del tiempo de trabajo.

**Comportamiento digital:**

Familiaridad básica con smartphones, uso de aplicaciones simples y rápidas, disposición a digitalizar procesos si la herramienta es intuitiva y confiable.

<div style="page-break-after: always;"></div>

## Capítulo II: Requirements Elicitation & Analysis

### 2.1. Competidores

#### 2.1.1. Análisis Competitivo

[Análisis de competidores]

#### 2.1.2. Estrategias y Tácticas Frente a Competidores

[Estrategias competitivas]

### 2.2. Entrevistas

#### 2.2.1. Diseño de Entrevistas

[Diseño del proceso de entrevistas]

#### 2.2.2. Registro de Entrevistas

[Registro detallado de entrevistas]

#### 2.2.3. Análisis de Entrevistas

[Análisis de resultados]

### 2.3. Needfinding

#### 2.3.1. User Personas

[Descripción de personas de usuario]

#### 2.3.2. User Task Matrix

[Matriz de tareas de usuario]

#### 2.3.3. User Journey Mapping

[Mapeo de viaje del usuario]

#### 2.3.4. Empathy Mapping

[Mapa de empatía]

#### 2.3.5. As-is Scenario Mapping

[Mapeo de escenarios actual]

### 2.4. Ubiquitous Language

[Lenguaje ubicuo del dominio]

<div style="page-break-after: always;"></div>

## Capítulo III: Requirements Specification

### 3.1. To-Be Scenario Mapping

[Mapeo de escenarios deseados]

### 3.2. User Stories

[User stories principales]

### 3.3. Product Backlog

[Backlog de producto]

### 3.4. Impact Mapping

[Mapa de impacto]

<div style="page-break-after: always;"></div>

## Capítulo IV: Product Design

### 4.1. Style Guidelines

#### 4.1.1. General Style Guidelines

[Guías de estilo general]

#### 4.1.2. Web Style Guidelines

[Guías de estilo para web]

#### 4.1.3. Mobile Style Guidelines

##### 4.1.3.1. iOS Mobile Style Guidelines

[Guías de estilo iOS]

##### 4.1.3.2. Android Mobile Style Guidelines

[Guías de estilo Android]

### 4.2. Information Architecture

#### 4.2.1. Organization Systems

[Sistemas de organización]

#### 4.2.2. Labeling Systems

[Sistemas de etiquetado]

#### 4.2.3. SEO Tags and Meta Tags

[Tags SEO y meta tags]

#### 4.2.4. Searching Systems

[Sistemas de búsqueda]

#### 4.2.5. Navigation Systems

[Sistemas de navegación]

### 4.3. Landing Page UI Design

#### 4.3.1. Landing Page Wireframe

[Wireframes de landing page]

#### 4.3.2. Landing Page Mock-up

[Mockups de landing page]

### 4.4. Mobile Applications UX/UI Design

#### 4.4.1. Mobile Applications Wireframes

[Wireframes de aplicaciones móviles]

#### 4.4.2. Mobile Applications Wireflow Diagrams

[Diagramas de wireflow]

#### 4.4.3. Mobile Applications Mock-ups

[Mockups de aplicaciones móviles]

#### 4.4.4. Mobile Applications User Flow Diagrams

[Diagramas de flujo de usuario]

### 4.5. Mobile Applications Prototyping

#### 4.5.1. Android Mobile Applications Prototyping

[Prototipos Android]

#### 4.5.2. iOS Mobile Applications Prototyping

[Prototipos iOS]

### 4.6. Web Applications UX/UI Design

#### 4.6.1. Web Applications Wireframes

[Wireframes de aplicaciones web]

#### 4.6.2. Web Applications Wireflow Diagrams

[Diagramas de wireflow web]

#### 4.6.3. Web Applications Mock-ups

[Mockups de aplicaciones web]

#### 4.6.4. Web Applications User Flow Diagrams

[Diagramas de flujo web]

### 4.7. Web Applications Prototyping

[Prototipos web]

### 4.8. Domain-Driven Software Architecture

#### 4.8.1. Software Architecture Context Diagram

[Diagrama de contexto]

#### 4.8.2. Software Architecture Container Diagrams

[Diagramas de contenedores]

#### 4.8.3. Software Architecture Components Diagrams

[Diagramas de componentes]

### 4.9. Software Object-Oriented Design

#### 4.9.1. Class Diagrams

[Diagramas de clases]

#### 4.9.2. Class Dictionary

[Diccionario de clases]

### 4.10. Database Design

#### 4.10.1. Relational/Non-Relational Database Diagram

[Diagrama de base de datos]

<div style="page-break-after: always;"></div>

# Capítulo V: Product Implementation

## 5.1. Software Configuration Management

El equipo ha establecido un ecosistema de desarrollo estandarizado para garantizar la trazabilidad, colaboración y calidad del software. Se detallan a continuación las herramientas y normativas que rigen el ciclo de vida del producto.

### 5.1.1. Software Development Environment Configuration

Se han seleccionado herramientas líderes en la industria para cubrir cada etapa del desarrollo del producto:

*   **Project Management:** **Trello** para la gestión ágil de tareas y **Discord** como eje central de comunicación técnica y coordinación en tiempo real.
*   **Product UX/UI Design:** **Figma** para el prototipado interactivo y **UXPressia** para el mapeo de la experiencia de usuario (User Personas y Journey Maps).
*   **Software Development:** **Android Studio** como IDE principal para la construcción y depuración de la aplicación móvil nativa.
*   **Software Testing:** **Gherkin** (Cucumber) para la definición de criterios de aceptación bajo el enfoque BDD, asegurando que las funcionalidades cumplan con los requerimientos de negocio.

### 5.1.2. Source Code Management

El proyecto implementa el modelo **GitFlow** para gestionar el flujo de trabajo en los repositorios de la organización [ATG-UPC](https://github.com/ATG-UPC).

**Repositorios del Proyecto:**
*   **Landing Page:** [AutoNexo-Landing-Page](https://github.com/ATG-UPC/AutoNexo-Landing-Page)
*   **Frontend Mobile:** [AutoNexo-Android](https://github.com/ATG-UPC/AutoNexo-Android)
*   **Backend Service:** [AutoNexo-Backend](https://github.com/ATG-UPC/AutoNexo-Backend)

**Estrategia de Ramificación:**
1.  **Main:** Contiene el código productivo y versiones estables.
2.  **Develop:** Base de integración para nuevas funcionalidades validadas.
3.  **Feature branches:** Ramas temporales para el desarrollo de tareas específicas (derivadas de `develop`).
4.  **Release branches:** Preparación y ajuste de versiones previas al despliegue final.
5.  **Hotfix branches:** Correcciones urgentes aplicadas directamente sobre `main`.

**Versionamiento y Commits:**
*   **Semantic Versioning 2.0.0:** Uso del estándar `MAJOR.MINOR.PATCH`.
*   **Conventional Commits:** Formato obligatorio `type(scope): description` para mantener un historial legible.

### 5.1.3. Source Code Style Guide & Conventions

Para asegurar un código limpio, mantenible y profesional, se siguen las siguientes directrices:

*   **Kotlin/Java (Android):**
    *   Uso de `camelCase` para variables/métodos y `PascalCase` para clases.
    *   Indentación de 4 espacios y límite de 100 caracteres por línea.
    *   Recursos XML (layouts, drawables) nombrados en `snake_case` (ej. `item_user_profile.xml`).
    *   Arquitectura basada en separación de responsabilidades: `ui/`, `data/`, y `domain/`.
*   **Gherkin:** Redacción estandarizada mediante `Given/When/Then` para asegurar que los escenarios de prueba sean comprensibles tanto para desarrolladores como para stakeholders.

### 5.1.4. Software Deployment Configuration

La estrategia de despliegue se divide según el componente del sistema para maximizar la disponibilidad:

*   **Landing Page:** Desplegada a través de **GitHub Pages**. El flujo de publicación se automatiza desde la carpeta `/docs` de la rama `main`.
*   **Backend:** Alojado en la plataforma nube **Azure**, utilizando **App Services** para la ejecución de la API y **Azure SQL** para la gestión de la base de datos, garantizando escalabilidad y seguridad.

### 5.2. Product Implementation & Deployment

#### 5.2.1. Sprint Backlogs

[Backlogs de sprints]

#### 5.2.2. Implemented Landing Page Evidence

[Evidencia de landing page implementada]

#### 5.2.3. Implemented Frontend-Web Application Evidence

[Evidencia de aplicación web frontend]

#### 5.2.4. Acuerdo de Servicio - SaaS

[Acuerdo de servicio SaaS]

#### 5.2.5. Implemented Native-Mobile Application Evidence

[Evidencia de aplicación móvil nativa]

#### 5.2.6. Implemented RESTful API and/or Serverless Backend Evidence

[Evidencia de API RESTful y backend]

#### 5.2.7. RESTful API Documentation

[Documentación de API RESTful]

#### 5.2.8. Team Collaboration Insights

[Insights de colaboración del equipo]

### 5.3. Video About-the-Product

[Enlace o descripción del video sobre el producto]

<div style="page-break-after: always;"></div>

# PARTE II: VERIFICATION, VALIDATION & PIPELINE

<div style="page-break-after: always;"></div>

## Capítulo VI: Product Verification & Validation

### 6.1. Testing Suites & Validation

#### 6.1.1. Core Entities Unit Tests

[Pruebas unitarias]

#### 6.1.2. Core Integration Tests

[Pruebas de integración]

#### 6.1.3. Core Behavior-Driven Development

[Pruebas BDD]

#### 6.1.4. Core System Tests

[Pruebas de sistema]

### 6.2. Static Testing & Verification

#### 6.2.1. Static Code Analysis

##### 6.2.1.1. Coding Standard & Code Conventions

[Estándares de codificación]

##### 6.2.1.2. Code Quality & Code Security

[Calidad y seguridad de código]

#### 6.2.2. Reviews

[Revisiones de código]

### 6.3. Validation Interviews

#### 6.3.1. Diseño de Entrevistas

[Diseño de entrevistas de validación]

#### 6.3.2. Registro de Entrevistas

[Registro de entrevistas]

#### 6.3.3. Evaluaciones Según Heurísticas

[Evaluaciones heurísticas]

### 6.4. Auditoría de Experiencias de Usuario

#### 6.4.1. Auditoría Realizada

##### 6.4.1.1. Información del Grupo Auditado

[Información del grupo]

##### 6.4.1.2. Cronograma de Auditoría Realizada

[Cronograma]

##### 6.4.1.3. Contenido de Auditoría Realizada

[Contenido de auditoría]

#### 6.4.2. Auditoría Recibida

##### 6.4.2.1. Información del Grupo Auditor

[Información del auditor]

##### 6.4.2.2. Cronograma de Auditoría Recibida

[Cronograma recibido]

##### 6.4.2.3. Contenido de Auditoría Recibida

[Contenido recibido]

##### 6.4.2.4. Resumen de Modificaciones para Subsanar Hallazgos

[Resumen de cambios]

<div style="page-break-after: always;"></div>

## Capítulo VII: DevOps Practices

### 7.1. Continuous Integration

#### 7.1.1. Tools and Practices

[Herramientas y prácticas CI]

#### 7.1.2. Build & Test Suite Pipeline Components

[Componentes de pipeline]

### 7.2. Continuous Delivery

#### 7.2.1. Tools and Practices

[Herramientas y prácticas CD]

#### 7.2.2. Stages Deployment Pipeline Components

[Componentes de despliegue]

### 7.3. Continuous Deployment

#### 7.3.1. Tools and Practices

[Herramientas y prácticas de despliegue continuo]

#### 7.3.2. Production Deployment Pipeline Components

[Componentes de despliegue en producción]

### 7.4. Continuous Monitoring

#### 7.4.1. Tools and Practices

[Herramientas y prácticas de monitoreo]

#### 7.4.2. Monitoring Pipeline Components

[Componentes de monitoreo]

#### 7.4.3. Alerting Pipeline Components

[Componentes de alertas]

#### 7.4.4. Notification Pipeline Components

[Componentes de notificación]

<div style="page-break-after: always;"></div>

# PARTE III: EXPERIMENT-DRIVEN LIFECYCLE

<div style="page-break-after: always;"></div>

## Capítulo VIII: Experiment-Driven Development

### 8.1. Experiment Planning

#### 8.1.1. As-Is Summary

[Resumen del estado actual]

#### 8.1.2. Raw Material: Assumptions, Knowledge Gaps, Ideas, Claims

[Material bruto: supuestos, brechas de conocimiento, ideas, afirmaciones]

#### 8.1.3. Experiment-Ready Questions

[Preguntas listas para experimento]

#### 8.1.4. Question Backlog

[Backlog de preguntas]

#### 8.1.5. Experiment Cards

[Tarjetas de experimento]

### 8.2. Experiment Design

#### 8.2.1. Hypotheses

[Hipótesis]

#### 8.2.2. Domain Business Metrics

[Métricas de negocio del dominio]

#### 8.2.3. Measures

[Medidas]

#### 8.2.4. Conditions

[Condiciones]

#### 8.2.5. Scale Calculations and Decisions

[Cálculos y decisiones de escala]

#### 8.2.6. Methods Selection

[Selección de métodos]

#### 8.2.7. Data Analytics: Goals, KPIs and Metrics Selection

[Análisis de datos: objetivos, KPIs y métricas]

#### 8.2.8. Web and Mobile Tracking Plan

[Plan de seguimiento web y móvil]

### 8.3. Experimentation

#### 8.3.1. To-Be User Stories

[User stories deseadas]

#### 8.3.2. To-Be Product Backlog

[Backlog de producto deseado]

#### 8.3.3. Pipeline-supported, Experiment-Driven To-Be Software Platform Lifecycle

[Ciclo de vida de plataforma de software dirigida por experimentos]

##### 8.3.3.1. To-Be Sprint Backlogs

[Backlogs de sprints]

##### 8.3.3.2. Implemented To-Be Landing Page Evidence

[Evidencia de landing page implementada]

##### 8.3.3.3. Implemented To-Be Frontend-Web Application Evidence

[Evidencia de aplicación web frontend]

##### 8.3.3.4. Implemented To-Be Native-Mobile Application Evidence

[Evidencia de aplicación móvil nativa]

##### 8.3.3.5. Implemented To-Be RESTful API and/or Serverless Backend Evidence

[Evidencia de API RESTful y backend]

##### 8.3.3.6. Team Collaboration Insights

[Insights de colaboración del equipo]

#### 8.3.4. To-Be Validation Interviews

[Entrevistas de validación]

##### 8.3.4.1. Diseño de Entrevistas

[Diseño de entrevistas]

##### 8.3.4.2. Registro de Entrevistas

[Registro de entrevistas]

#### 8.3.4. Experiment Aftermath & Analysis

[Análisis posterior al experimento]

### 8.4. Experiment Aftermath & Analysis

#### 8.4.1. Analysis and Interpretation of Results

[Análisis e interpretación de resultados]

#### 8.4.2. Re-scored and Re-prioritized Question Backlog

[Backlog de preguntas re-puntuado y re-priorizado]

### 8.5. Continuous Learning

#### 8.5.1. Shareback Session Artifacts: Learning Workflow

[Artefactos de sesión de aprendizaje compartido]

### 8.6. To-Be Software Platform Pre-launch

#### 8.6.1. About-the-Product Intro Video

[Video introductorio del producto]

<div style="page-break-after: always;"></div>

## Conclusiones

### Conclusiones y Recomendaciones

[Conclusiones del proyecto]

### Video App Validation

[Enlace o descripción del video de validación]

### Video About-the-Team

[Enlace o descripción del video del equipo]

<div style="page-break-after: always;"></div>

## Bibliografía

[Referencias bibliográficas]

<div style="page-break-after: always;"></div>

## Anexos

[Documentos anexos]
