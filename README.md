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

| Versión | Fecha   | Autor   | Descripción     |
| ------- | ------- | ------- | --------------- |
| 1.0     | [Fecha] | [Autor] | Versión inicial |

<div style="page-break-after: always;"></div>

## Project Report Collaboration Insights

[Insertar insights de colaboración]

<div style="page-break-after: always;"></div>

## Contenido

<<<<<<< HEAD
1. [INFORME DE TRABAJO FINAL](#informe-de-trabajo-final)
   1. [Carátula](#carátula)
   2. [Registro de Versiones del Informe](#registro-de-versiones-del-informe)
   3. [Project Report Collaboration Insights](#project-report-collaboration-insights)
   4. [Contenido](#contenido)
   5. [Student Outcome](#student-outcome)
2. [PARTE I: AS-IS SOFTWARE PROJECT](#parte-i-as-is-software-project)
   1. [Capítulo I: Introducción](#capítulo-i-introducción)
      1. [1.1. Startup Profile](#11-startup-profile)
         1. [1.1.1. Descripción de la Startup](#111-descripción-de-la-startup)
         2. [1.1.2. Perfiles de Integrantes del Equipo](#112-perfiles-de-integrantes-del-equipo)
      2. [1.2. Solution Profile](#12-solution-profile)
         1. [1.2.1. Antecedentes y Problemática](#121-antecedentes-y-problemática)
         2. [**Who (¿Quién?)**](#who-quién)
         3. [**What (¿Qué?)**](#what-qué)
         4. [**Where (¿Dónde?)**](#where-dónde)
         5. [**When (¿Cuándo?)**](#when-cuándo)
         6. [**Why (¿Por qué?)**](#why-por-qué)
         7. [**How (¿Cómo?)**](#how-cómo)
         8. [**How Much (¿Cuánto?)**](#how-much-cuánto)
         9. [1.2.2. Lean UX Process](#122-lean-ux-process)
            1. [1.2.2.1. Lean UX Problem Statements](#1221-lean-ux-problem-statements)
            2. [1.2.2.2. Lean UX Assumptions](#1222-lean-ux-assumptions)
      3. [**Business Assumptions**](#business-assumptions)
      4. [**User Assumptions**](#user-assumptions)
            1. [1.2.2.3. Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
      5. [**Hypothesis 01**](#hypothesis-01)
      6. [**Hypothesis 02**](#hypothesis-02)
      7. [**Hypothesis 03**](#hypothesis-03)
      8. [**Hypothesis 04**](#hypothesis-04)
            1. [1.2.2.4. Lean UX Canvas](#1224-lean-ux-canvas)
      9. [1.3. Segmentos Objetivo](#13-segmentos-objetivo)
      10. [**Segmento objetivo #1: Propietarios**](#segmento-objetivo-1-propietarios)
      11. [**Segmento objetivo #2: Mecánicos**](#segmento-objetivo-2-mecánicos)
   2. [Capítulo II: Requirements Elicitation \& Analysis](#capítulo-ii-requirements-elicitation--analysis)
      1. [2.1. Competidores](#21-competidores)
         1. [2.1.1. Análisis Competitivo](#211-análisis-competitivo)
         2. [2.1.2. Estrategias y Tácticas Frente a Competidores](#212-estrategias-y-tácticas-frente-a-competidores)
      2. [2.2. Entrevistas](#22-entrevistas)
         1. [2.2.1. Diseño de Entrevistas](#221-diseño-de-entrevistas)
         2. [2.2.2. Registro de Entrevistas](#222-registro-de-entrevistas)
         3. [2.2.3. Análisis de Entrevistas](#223-análisis-de-entrevistas)
      3. [2.3. Needfinding](#23-needfinding)
         1. [2.3.1. User Personas](#231-user-personas)
         2. [2.3.2. User Task Matrix](#232-user-task-matrix)
         3. [2.3.3. User Journey Mapping](#233-user-journey-mapping)
         4. [2.3.4. Empathy Mapping](#234-empathy-mapping)
         5. [2.3.5. As-is Scenario Mapping](#235-as-is-scenario-mapping)
      4. [2.4. Ubiquitous Language](#24-ubiquitous-language)
   3. [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
      1. [3.1. To-Be Scenario Mapping](#31-to-be-scenario-mapping)
      2. [3.2. User Stories](#32-user-stories)
      3. [3.3. Product Backlog](#33-product-backlog)
      4. [3.4. Impact Mapping](#34-impact-mapping)
   4. [Capítulo IV: Product Design](#capítulo-iv-product-design)
      1. [4.1. Style Guidelines](#41-style-guidelines)
         1. [4.1.1. General Style Guidelines](#411-general-style-guidelines)
         2. [4.1.2. Web Style Guidelines](#412-web-style-guidelines)
         3. [4.1.3. Mobile Style Guidelines](#413-mobile-style-guidelines)
            1. [4.1.3.1. iOS Mobile Style Guidelines](#4131-ios-mobile-style-guidelines)
            2. [4.1.3.2. Android Mobile Style Guidelines](#4132-android-mobile-style-guidelines)
      2. [4.2. Information Architecture](#42-information-architecture)
         1. [4.2.1. Organization Systems](#421-organization-systems)
         2. [4.2.2. Labeling Systems](#422-labeling-systems)
         3. [4.2.3. SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
         4. [4.2.4. Searching Systems](#424-searching-systems)
         5. [4.2.5. Navigation Systems](#425-navigation-systems)
      3. [4.3. Landing Page UI Design](#43-landing-page-ui-design)
         1. [4.3.1. Landing Page Wireframe](#431-landing-page-wireframe)
         2. [4.3.2. Landing Page Mock-up](#432-landing-page-mock-up)
      4. [4.4. Mobile Applications UX/UI Design](#44-mobile-applications-uxui-design)
         1. [4.4.1. Mobile Applications Wireframes](#441-mobile-applications-wireframes)
         2. [4.4.2. Mobile Applications Wireflow Diagrams](#442-mobile-applications-wireflow-diagrams)
         3. [4.4.3. Mobile Applications Mock-ups](#443-mobile-applications-mock-ups)
         4. [4.4.4. Mobile Applications User Flow Diagrams](#444-mobile-applications-user-flow-diagrams)
      5. [4.5. Mobile Applications Prototyping](#45-mobile-applications-prototyping)
         1. [4.5.1. Android Mobile Applications Prototyping](#451-android-mobile-applications-prototyping)
         2. [4.5.2. iOS Mobile Applications Prototyping](#452-ios-mobile-applications-prototyping)
      6. [4.6. Web Applications UX/UI Design](#46-web-applications-uxui-design)
         1. [4.6.1. Web Applications Wireframes](#461-web-applications-wireframes)
         2. [4.6.2. Web Applications Wireflow Diagrams](#462-web-applications-wireflow-diagrams)
         3. [4.6.3. Web Applications Mock-ups](#463-web-applications-mock-ups)
         4. [4.6.4. Web Applications User Flow Diagrams](#464-web-applications-user-flow-diagrams)
      7. [4.7. Web Applications Prototyping](#47-web-applications-prototyping)
      8. [4.8. Domain-Driven Software Architecture](#48-domain-driven-software-architecture)
      9. [4.8.1. Event Storming](#481-event-storming)
         1. [4.8.1.1. Candidate Context Discovery](#4811-candidate-context-discovery)
         2. [4.8.1.2. Domain Message Flows Modeling](#4812-domain-message-flows-modeling)
         3. [4.8.1.3 Bounded Context Canvases](#4813-bounded-context-canvases)
      10. [4.8.2. Context Mapping](#482-context-mapping)
      11. [4.8.3. Software Architecture Context Diagram](#483-software-architecture-context-diagram)
      12. [4.8.4. Software Architecture Container Diagrams](#484-software-architecture-container-diagrams)
      13. [4.8.5. Software Architecture Components Diagrams](#485-software-architecture-components-diagrams)
      14. [4.9. Software Object-Oriented Design](#49-software-object-oriented-design)
          1. [4.9.1. Class Diagrams](#491-class-diagrams)
      15. [4.10. Database Design](#410-database-design)
          1. [4.10.1. Relational/Non-Relational Database Diagram](#4101-relationalnon-relational-database-diagram)
   5. [Capítulo V: Product Implementation](#capítulo-v-product-implementation)
      1. [5.1. Software Configuration Management](#51-software-configuration-management)
         1. [5.1.1. Software Development Environment Configuration](#511-software-development-environment-configuration)
         2. [5.1.2. Source Code Management](#512-source-code-management)
         3. [5.1.3. Source Code Style Guide \& Conventions](#513-source-code-style-guide--conventions)
         4. [5.1.4. Software Deployment Configuration](#514-software-deployment-configuration)
      2. [5.2. Product Implementation \& Deployment](#52-product-implementation--deployment)
         1. [5.2.1. Sprint Backlogs](#521-sprint-backlogs)
         2. [5.2.2. Implemented Landing Page Evidence](#522-implemented-landing-page-evidence)
         3. [5.2.3. Implemented Frontend-Web Application Evidence](#523-implemented-frontend-web-application-evidence)
         4. [5.2.4. Acuerdo de Servicio - SaaS](#524-acuerdo-de-servicio---saas)
         5. [5.2.5. Implemented Native-Mobile Application Evidence](#525-implemented-native-mobile-application-evidence)
         6. [5.2.6. Implemented RESTful API and/or Serverless Backend Evidence](#526-implemented-restful-api-andor-serverless-backend-evidence)
         7. [5.2.7. RESTful API Documentation](#527-restful-api-documentation)
         8. [5.2.8. Team Collaboration Insights](#528-team-collaboration-insights)
      3. [5.3. Video About-the-Product](#53-video-about-the-product)
3. [PARTE II: VERIFICATION, VALIDATION \& PIPELINE](#parte-ii-verification-validation--pipeline)
   1. [Capítulo VI: Product Verification \& Validation](#capítulo-vi-product-verification--validation)
      1. [6.1. Testing Suites \& Validation](#61-testing-suites--validation)
         1. [6.1.1. Core Entities Unit Tests](#611-core-entities-unit-tests)
         2. [6.1.2. Core Integration Tests](#612-core-integration-tests)
         3. [6.1.3. Core Behavior-Driven Development](#613-core-behavior-driven-development)
         4. [6.1.4. Core System Tests](#614-core-system-tests)
      2. [6.2. Static Testing \& Verification](#62-static-testing--verification)
         1. [6.2.1. Static Code Analysis](#621-static-code-analysis)
            1. [6.2.1.1. Coding Standard \& Code Conventions](#6211-coding-standard--code-conventions)
            2. [6.2.1.2. Code Quality \& Code Security](#6212-code-quality--code-security)
         2. [6.2.2. Reviews](#622-reviews)
      3. [6.3. Validation Interviews](#63-validation-interviews)
         1. [6.3.1. Diseño de Entrevistas](#631-diseño-de-entrevistas)
         2. [6.3.2. Registro de Entrevistas](#632-registro-de-entrevistas)
         3. [6.3.3. Evaluaciones Según Heurísticas](#633-evaluaciones-según-heurísticas)
      4. [6.4. Auditoría de Experiencias de Usuario](#64-auditoría-de-experiencias-de-usuario)
         1. [6.4.1. Auditoría Realizada](#641-auditoría-realizada)
            1. [6.4.1.1. Información del Grupo Auditado](#6411-información-del-grupo-auditado)
            2. [6.4.1.2. Cronograma de Auditoría Realizada](#6412-cronograma-de-auditoría-realizada)
            3. [6.4.1.3. Contenido de Auditoría Realizada](#6413-contenido-de-auditoría-realizada)
         2. [6.4.2. Auditoría Recibida](#642-auditoría-recibida)
            1. [6.4.2.1. Información del Grupo Auditor](#6421-información-del-grupo-auditor)
            2. [6.4.2.2. Cronograma de Auditoría Recibida](#6422-cronograma-de-auditoría-recibida)
            3. [6.4.2.3. Contenido de Auditoría Recibida](#6423-contenido-de-auditoría-recibida)
            4. [6.4.2.4. Resumen de Modificaciones para Subsanar Hallazgos](#6424-resumen-de-modificaciones-para-subsanar-hallazgos)
   2. [Capítulo VII: DevOps Practices](#capítulo-vii-devops-practices)
      1. [7.1. Continuous Integration](#71-continuous-integration)
         1. [7.1.1. Tools and Practices](#711-tools-and-practices)
         2. [7.1.2. Build \& Test Suite Pipeline Components](#712-build--test-suite-pipeline-components)
      2. [7.2. Continuous Delivery](#72-continuous-delivery)
         1. [7.2.1. Tools and Practices](#721-tools-and-practices)
         2. [7.2.2. Stages Deployment Pipeline Components](#722-stages-deployment-pipeline-components)
      3. [7.3. Continuous Deployment](#73-continuous-deployment)
         1. [7.3.1. Tools and Practices](#731-tools-and-practices)
         2. [7.3.2. Production Deployment Pipeline Components](#732-production-deployment-pipeline-components)
      4. [7.4. Continuous Monitoring](#74-continuous-monitoring)
         1. [7.4.1. Tools and Practices](#741-tools-and-practices)
         2. [7.4.2. Monitoring Pipeline Components](#742-monitoring-pipeline-components)
         3. [7.4.3. Alerting Pipeline Components](#743-alerting-pipeline-components)
         4. [7.4.4. Notification Pipeline Components](#744-notification-pipeline-components)
4. [PARTE III: EXPERIMENT-DRIVEN LIFECYCLE](#parte-iii-experiment-driven-lifecycle)
   1. [Capítulo VIII: Experiment-Driven Development](#capítulo-viii-experiment-driven-development)
      1. [8.1. Experiment Planning](#81-experiment-planning)
         1. [8.1.1. As-Is Summary](#811-as-is-summary)
         2. [8.1.2. Raw Material: Assumptions, Knowledge Gaps, Ideas, Claims](#812-raw-material-assumptions-knowledge-gaps-ideas-claims)
         3. [8.1.3. Experiment-Ready Questions](#813-experiment-ready-questions)
         4. [8.1.4. Question Backlog](#814-question-backlog)
         5. [8.1.5. Experiment Cards](#815-experiment-cards)
      2. [8.2. Experiment Design](#82-experiment-design)
         1. [8.2.1. Hypotheses](#821-hypotheses)
         2. [8.2.2. Domain Business Metrics](#822-domain-business-metrics)
         3. [8.2.3. Measures](#823-measures)
         4. [8.2.4. Conditions](#824-conditions)
         5. [8.2.5. Scale Calculations and Decisions](#825-scale-calculations-and-decisions)
         6. [8.2.6. Methods Selection](#826-methods-selection)
         7. [8.2.7. Data Analytics: Goals, KPIs and Metrics Selection](#827-data-analytics-goals-kpis-and-metrics-selection)
         8. [8.2.8. Web and Mobile Tracking Plan](#828-web-and-mobile-tracking-plan)
      3. [8.3. Experimentation](#83-experimentation)
         1. [8.3.1. To-Be User Stories](#831-to-be-user-stories)
         2. [8.3.2. To-Be Product Backlog](#832-to-be-product-backlog)
         3. [8.3.3. Pipeline-supported, Experiment-Driven To-Be Software Platform Lifecycle](#833-pipeline-supported-experiment-driven-to-be-software-platform-lifecycle)
            1. [8.3.3.1. To-Be Sprint Backlogs](#8331-to-be-sprint-backlogs)
            2. [8.3.3.2. Implemented To-Be Landing Page Evidence](#8332-implemented-to-be-landing-page-evidence)
            3. [8.3.3.3. Implemented To-Be Frontend-Web Application Evidence](#8333-implemented-to-be-frontend-web-application-evidence)
            4. [8.3.3.4. Implemented To-Be Native-Mobile Application Evidence](#8334-implemented-to-be-native-mobile-application-evidence)
            5. [8.3.3.5. Implemented To-Be RESTful API and/or Serverless Backend Evidence](#8335-implemented-to-be-restful-api-andor-serverless-backend-evidence)
            6. [8.3.3.6. Team Collaboration Insights](#8336-team-collaboration-insights)
         4. [8.3.4. To-Be Validation Interviews](#834-to-be-validation-interviews)
            1. [8.3.4.1. Diseño de Entrevistas](#8341-diseño-de-entrevistas)
            2. [8.3.4.2. Registro de Entrevistas](#8342-registro-de-entrevistas)
         5. [8.3.4. Experiment Aftermath \& Analysis](#834-experiment-aftermath--analysis)
      4. [8.4. Experiment Aftermath \& Analysis](#84-experiment-aftermath--analysis)
         1. [8.4.1. Analysis and Interpretation of Results](#841-analysis-and-interpretation-of-results)
         2. [8.4.2. Re-scored and Re-prioritized Question Backlog](#842-re-scored-and-re-prioritized-question-backlog)
      5. [8.5. Continuous Learning](#85-continuous-learning)
         1. [8.5.1. Shareback Session Artifacts: Learning Workflow](#851-shareback-session-artifacts-learning-workflow)
      6. [8.6. To-Be Software Platform Pre-launch](#86-to-be-software-platform-pre-launch)
         1. [8.6.1. About-the-Product Intro Video](#861-about-the-product-intro-video)
   2. [Conclusiones](#conclusiones)
      1. [Conclusiones y Recomendaciones](#conclusiones-y-recomendaciones)
      2. [Video App Validation](#video-app-validation)
      3. [Video About-the-Team](#video-about-the-team)
   3. [Bibliografía](#bibliografía)
   4. [Anexos](#anexos)
=======
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
    - [5.2.1. Sprint Backlogs (Continuación)](#521-sprint-backlogs-continuación)
      - [Sprint 3](#sprint-3)
    - [5.2.5. Implemented Mobile Application Evidence (Sprint 3)](#525-implemented-mobile-application-evidence-sprint-3)
    - [5.2.6. Implemented RESTful API Evidence (Sprint 3)](#526-implemented-restful-api-evidence-sprint-3)
    - [5.2.7. RESTful API Documentation \& Deployment](#527-restful-api-documentation--deployment)
    - [5.2.8. Team Collaboration Insights](#528-team-collaboration-insights)
      - [Participación en Repositorios:](#participación-en-repositorios)
    - [Final Deployment Summary](#final-deployment-summary)
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
>>>>>>> 5793ca2 (docs: define SCM, branching strategy, style guides and deployment for chapter V)

<div style="page-break-after: always;"></div>

## Student Outcome

**ABET – EAC - Student Outcome 4**
**Criterio:** La capacidad de reconocer responsabilidades éticas y profesionales en situaciones de ingeniería y hacer juicios informados, que deben considerar el impacto de las soluciones de ingeniería en contextos globales, económicos, ambientales y sociales.

En el siguiente cuadro se describe las acciones realizadas y enunciados de conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro del ABET – EAC - Student Outcome 4.

| Criterio específico                                                                                                                                          | Acciones realizadas                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | Conclusiones                                                                                                                                                                                              |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 4.c.1 Reconoce responsabilidad ética y profesional en situaciones de ingeniería de software                                                                  | <i>Cruz Ibarra, Victor Andres</i><br><i>TB1</i><br>Participó en la definición del problema y el alcance inicial del proyecto.<br><i>TP1</i><br>Apoyó la validación de requerimientos y la documentación del avance.<br><br><i>Solis Chang, Santiago Valentino</i><br><i>TB1</i><br>Colaboró en el análisis inicial y en la redacción de artefactos base.<br><i>TP1</i><br>Apoyó la mejora de evidencias y la revisión de entregables.<br><br><i>Navarro Chang, Alicia Avril</i><br><i>TB1</i><br>Contribuyó con el levantamiento de información y la organización de materiales.<br><i>TP1</i><br>Participó en la actualización de contenidos y la consolidación de evidencias.<br><br><i>Vidal Castro, Miguel Angel</i><br><i>TB1</i><br>Apoyó la estructuración del informe y la revisión de secciones clave.<br><i>TP1</i><br>Colaboró en la integración de resultados y la verificación de avances.<br><br><i>Castro Sanchez, Amir Gabriel</i><br><i>TB1</i><br>Participó en la organización del contenido y en la síntesis de avances.<br><i>TP1</i><br>Apoyó la consolidación final de capítulos y la revisión de consistencia. | <i>TB1</i><br>El grupo mostró responsabilidad al organizar el trabajo y respetar criterios profesionales.<br><br><i>TP1</i><br>El grupo consolidó una ejecución más ordenada y ética del trabajo técnico. |
| 4.c.2 Emite juicios informados considerando el impacto de las soluciones de ingeniería de software en contextos globales, económicos, ambientales y sociales | <i>Cruz Ibarra, Victor Andres</i><br><i>TB1</i><br>Analizó el contexto de la startup y su impacto inicial en el entorno.<br><i>TP1</i><br>Participó en el análisis de mejoras con enfoque en valor, uso y viabilidad.<br><br><i>Solis Chang, Santiago Valentino</i><br><i>TB1</i><br>Apoyó la identificación de oportunidades y restricciones del proyecto.<br><i>TP1</i><br>Contribuyó a evaluar ajustes del producto según alcance y beneficio.<br><br><i>Navarro Chang, Alicia Avril</i><br><i>TB1</i><br>Revisó información del dominio para sustentar decisiones del equipo.<br><i>TP1</i><br>Colaboró en la valoración de entregables y mejoras del producto.<br><br><i>Vidal Castro, Miguel Angel</i><br><i>TB1</i><br>Apoyó el análisis de viabilidad y coherencia de los entregables.<br><i>TP1</i><br>Participó en la revisión de resultados y su impacto en la propuesta.<br><br><i>Castro Sanchez, Amir Gabriel</i><br><i>TB1</i><br>Sintetizó aportes para sustentar decisiones del informe.<br><i>TP1</i><br>Apoyó la evaluación final de coherencia entre solución y necesidades.                                      | <i>TB1</i><br>El grupo tomó decisiones considerando necesidades reales del negocio y del usuario.<br><br><i>TP1</i><br>El grupo hizo juicios más sólidos sobre el impacto de la solución propuesta.       |

<div style="page-break-after: always;"></div>

# PARTE I: AS-IS SOFTWARE PROJECT

<div style="page-break-after: always;"></div>

## Capítulo I: Introducción

### 1.1. Startup Profile

#### 1.1.1. Descripción de la Startup

Autonexo es una aplicación diseñada para conectar a los propietarios de vehículos con mecánicos especializados en distintos tipos de mantenimiento vehicular, ya sea preventivo o correctivo. La plataforma funciona como un intermediario digital que centraliza la oferta y demanda de servicios automotrices, facilitando la interacción entre usuarios y profesionales del sector.

Este modelo se basa en plataformas digitales de dos lados (two-sided markets), donde la tecnología mejora la eficiencia del mercado y reduce fricciones en la contratación de servicios (Rochet & Tirole, 2003). En la actualidad, la digitalización del sector automotriz ha crecido significativamente, impulsada por la adopción de soluciones móviles y sistemas en la nube.

La plataforma permite a los usuarios acceder a un catálogo de mecánicos certificados, seleccionando según reputación, especialización y cercanía. Este tipo de soluciones responde a una tendencia global, donde aproximadamente el 73% de usuarios ya utiliza canales digitales para gestionar servicios automotrices (WorldMetrics, 2026).

Por otro lado, los mecánicos pueden gestionar su agenda y servicios en tiempo real, lo que mejora la eficiencia operativa. Estudios recientes indican que la digitalización puede reducir costos operativos hasta en un 28% y aumentar la satisfacción del cliente en más del 60% (Gitnux, 2026).

En América Latina, la adopción tecnológica sigue siendo limitada, ya que solo el 23.5% de talleres mecánicos utiliza software especializado, lo que evidencia una importante brecha digital en el sector (Innocar & Roshfrans, 2024). Además, más del 30% aún no utiliza plataformas digitales, lo que refuerza la necesidad de soluciones como Autonexo.

La plataforma también permite registrar el historial de mantenimiento del vehículo, facilitando estrategias de mantenimiento predictivo, lo que puede reducir fallas hasta en un 40% y disminuir costos de reparación en un 20% a 30% (WorldMetrics, 2026).

El objetivo de Autonexo es modernizar el mantenimiento vehicular mediante una solución digital accesible, eficiente y transparente, reduciendo la brecha tecnológica en el sector automotriz.

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

Un “style guideline” o guía de estilo es un conjunto de reglas y pautas que establecen la forma en que se deben diseñar, redactar y presentar los elementos visuales y funcionales de un proyecto digital. Estas guías garantizan consistencia, coherencia y una identidad sólida a lo largo de todas las interfaces y materiales del producto.

A continuación, se detallan los parámetros implementados en la estructura visual y conceptual del proyecto AutoNexo, una aplicación móvil desarrollada por el equipo ATG, como parte de una iniciativa tecnológica orientada a optimizar la gestión y conexión entre talleres mecánicos y propietarios de vehículos.

**Branding**

Brand Overview

AutoNexo es una aplicación móvil desarrollada por el equipo ATG, enfocada en conectar talleres mecánicos, técnicos independientes y propietarios de vehículos dentro de un ecosistema digital integral. Su propósito principal es optimizar la gestión, comunicación y trazabilidad de los servicios automotrices, ofreciendo una experiencia más eficiente tanto para los clientes como para los talleres.

La aplicación permite administrar servicios, citas, historial de mantenimiento, inventario y facturación, todo desde una misma plataforma. A través de sus módulos, los talleres pueden organizar el flujo de trabajo, comunicarse directamente con los propietarios y analizar su rendimiento operativo mediante reportes visuales.

Una de las principales fortalezas de AutoNexo es su capacidad de adaptación a distintos tipos de talleres y mecánicos, integrando tecnologías móviles y notificaciones inteligentes para mejorar la atención al cliente. Además, su diseño modular facilita la expansión a nuevas funciones como recordatorios automáticos, integración con seguros y análisis de desempeño.

**Misión**

Digitalizar y optimizar la gestión de servicios automotrices mediante una plataforma móvil inteligente que conecte talleres, técnicos y propietarios, garantizando eficiencia, transparencia y satisfacción del cliente.

**Visión**

Convertirse en la aplicación líder en gestión automotriz en Latinoamérica, ofreciendo soluciones tecnológicas que impulsen la productividad de los talleres y fortalezcan la confianza entre clientes y mecánicos.

**Logo de ATG**

El logotipo de ATG representa innovación, colaboración y tecnología aplicada al sector automotriz. Sus elementos visuales refuerzan la idea de conexión y dinamismo, pilares fundamentales de la identidad de AutoNexo.

<p align="center">
  <img src="assets/logos/ATG/Logo de ATG.png" alt="Logo de ATG" width="250px" />
</p>

**Brand Name**

El nombre AutoNexo combina los términos “Auto” (vehículo) y “Nexo” (conexión, enlace), simbolizando su función principal como punto de unión digital entre los actores del ecosistema automotriz. Representa agilidad, confianza y control sobre los procesos de mantenimiento y servicio.

El nombre refleja también su visión de comunidad, en la que cada interacción entre taller, técnico y cliente contribuye a un sistema más inteligente, ordenado y conectado.

<p align="center">
  <img src="assets/logos/ATG/logo-1.png.jpg" alt="Logo de ATG" width="250px" />
</p>

**Colores**

La identidad visual de AutoNexo se fundamenta en una paleta cromática que transmite confianza, tecnología y conexión. Cada color ha sido seleccionado para reflejar la esencia de la marca: profesionalismo, precisión y cercanía con el usuario.

El azul primario (#202D36) simboliza solidez y tecnología, siendo el color principal de la interfaz y de los elementos de navegación. Este tono refuerza la percepción de confianza y modernidad que caracteriza a la aplicación.

El blanco primario (#FFFFFF) proporciona equilibrio y claridad visual, garantizando una lectura limpia y una experiencia de usuario fluida.

Los colores secundarios complementan la identidad principal con acentos de energía y contraste. El crimson (#800C1F) y el dark red (#3C0007) representan fuerza, determinación y energía mecánica, ideales para destacar alertas o secciones relacionadas con acciones importantes.

Por su parte, los tonos metálicos como el steel blue y el light blue-gray aportan una sensación de modernidad industrial, evocando el entorno técnico de los talleres y la conexión digital entre sistemas. (Nota: falta definir sus códigos HEX exactos.)

En los prototipos y wireframes, se emplean tonos neutros que garantizan jerarquía visual sin distraer al usuario: gris claro (#D9D9D9) para contenedores, gris medio (#8E8E8E) para texto auxiliar, y negro (#282828) para íconos y tipografía principal sobre fondos claros.

Los colores de texto mantienen un alto contraste para asegurar legibilidad: negro (#000000) sobre fondos claros y blanco grisáceo (#D9D9D9) sobre fondos oscuros.

En conjunto, esta paleta cromática refuerza la identidad moderna, confiable y funcional de AutoNexo, creando una experiencia visual coherente con su propósito tecnológico y su enfoque en la eficiencia del servicio automotriz.

<p align="center">
  <img src="assets/images/screenshots/Paleta de colores.png" alt="Paleta de colores ATG" width="600px" />
</p>

<section id="typography">
  <h2>Tipografía</h2>
  <p>
    La tipografía seleccionada para <strong>AutoNexo</strong> es <strong>Inter</strong>, en sus variantes <em>Medium</em> y <em>Bold</em>. 
    Esta fuente <em>sans-serif</em> fue elegida por su modernidad, claridad visual y excelente legibilidad en pantallas móviles, 
    características esenciales para una experiencia de usuario fluida y profesional.
  </p>
  <p>
    Su estructura geométrica y balanceada refuerza la identidad tecnológica y confiable de la aplicación, 
    manteniendo coherencia en todos los componentes de la interfaz.
  </p>

  <p>Se aplica de forma jerarquizada en los siguientes niveles:</p>

  <table border="1" cellspacing="0" cellpadding="8">
    <thead>
      <tr>
        <th>Nivel</th>
        <th>Uso principal</th>
        <th>Estilo</th>
        <th>Tamaño</th>
        <th>Line Height</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>Heading 01</td>
        <td>Títulos principales, encabezados generales</td>
        <td>Roboto Flex</td>
        <td>70 px</td>
        <td>84 px</td>
      </tr>
      <tr>
        <td>Heading 02</td>
        <td>Secciones destacadas y subtítulos</td>
        <td>Roboto Flex</td>
        <td>40 px</td>
        <td>52 px</td>
      </tr>
      <tr>
        <td>Heading 03</td>
        <td>Bloques de contenido intermedio</td>
        <td>Roboto Flex</td>
        <td>25 px</td>
        <td>34 px</td>
      </tr>
      <tr>
        <td>Large Text Bold</td>
        <td>Textos de énfasis o botones principales</td>
        <td>Roboto</td>
        <td>25 px</td>
        <td>34 px</td>
      </tr>
      <tr>
        <td>Medium Text Bold</td>
        <td>Subtítulos o texto destacado secundario</td>
        <td>Roboto</td>
        <td>18 px</td>
        <td>30 px</td>
      </tr>
      <tr>
        <td>Normal Text Bold</td>
        <td>Texto informativo o párrafos breves</td>
        <td>Roboto</td>
        <td>16 px</td>
        <td>24 px</td>
      </tr>
      <tr>
        <td>Small Text Bold</td>
        <td>Etiquetas, menús o elementos de interfaz compactos</td>
        <td>Roboto</td>
        <td>14 px</td>
        <td>21 px</td>
      </tr>
    </tbody>
  </table>

<p align="center">
  <img src="assets/images/screenshots/typo-b.png" alt="Tipografía AutoNexo" width="600px" />
</p>

  <p>
    La jerarquía tipográfica de <strong>AutoNexo</strong> busca mantener consistencia visual y equilibrio, 
    permitiendo una lectura fluida y una clara diferenciación entre niveles de información.
  </p>
  <p>
    De este modo, la aplicación proyecta una imagen moderna, estructurada y profesional, 
    coherente con su enfoque tecnológico y su propósito de conectar digitalmente a talleres y propietarios de vehículos.
  </p>
</section>

#### 4.1.2. Web Style Guidelines

[Guías de estilo para web]

#### 4.1.3. Mobile Style Guidelines

##### 4.1.3.1. iOS Mobile Style Guidelines

[Guías de estilo iOS]

##### 4.1.3.2. Android Mobile Style Guidelines

[Guías de estilo Android]

### 4.2. Information Architecture

#### 4.2.1. Organization Systems

El sistema de navegación de AutoNexo está diseñado para ofrecer una experiencia intuitiva, fluida y centrada en la usabilidad móvil, asegurando que tanto mecánicos como propietarios puedan acceder fácilmente a las funciones principales sin perder el contexto de su actividad.

**Estructura de Navegación Principal**

En la pantalla Home, la navegación parte de una estructura principal de barra inferior (bottom navigation bar) que contiene los accesos directos a las secciones más utilizadas:

- **Home**: Vista principal con el estado actual de citas y agenda, proporcionando una visión general del día y las actividades pendientes.

- **Request**: Permite gestionar solicitudes de servicio de los clientes, facilitando la comunicación bidireccional entre taller y propietarios.

- **Offer**: Muestra promociones o servicios destacados del taller, permitiendo a los mecánicos promocionar sus especialidades.

- **Workshop**: Acceso directo al perfil del taller y a las funciones administrativas, incluyendo gestión de inventario y configuración.

- **Service**: Historial y seguimiento de servicios realizados, proporcionando trazabilidad completa de las intervenciones.

Cada icono cuenta con una etiqueta breve y un color activo que destaca la sección seleccionada, reforzando la claridad del recorrido visual y manteniendo al usuario orientado en todo momento.

**Navegación Superior y Menú Lateral**

En la parte superior de la interfaz se ubica una barra de encabezado (App Bar) con el nombre del usuario, ícono de notificaciones y un menú lateral desplegable (hamburger menu). Este último ofrece accesos secundarios organizados en categorías lógicas:

**Gestión de Perfil:**

- Profile
- Support and Assistance

**Configuración y Legal:**

- Terms of Use
- Privacy Policy
- Logout

**Personalización:**

- Cambio de idioma (Español / English)
- Modo de tema (oscuro o claro)

Esta estructura brinda al usuario flexibilidad y control sobre su experiencia de uso, manteniendo las opciones de configuración accesibles pero no intrusivas.

**Navegación Contextual en Pantallas de Detalle**

En las pantallas de detalle, como la vista de Workshop, la navegación mantiene la misma coherencia visual y funcional. El encabezado superior permite regresar a la vista anterior mediante una flecha de retroceso (Back Arrow), mientras que los botones inferiores ("Generate Code", "Edit Workshop") proporcionan acceso directo a las acciones específicas de gestión.

**Principios de Usabilidad**

Cada transición entre pantallas es suave y contextual, evitando recargar al usuario con demasiada información. Se prioriza la simplicidad y la eficiencia: los usuarios pueden moverse entre módulos con un número mínimo de toques, manteniendo siempre visibles los elementos de navegación principales.

**Consistencia y Accesibilidad**

En conjunto, este sistema de navegación garantiza que AutoNexo mantenga una experiencia uniforme, clara y accesible, adaptada tanto a la operatividad técnica del mecánico como a la practicidad del usuario final. La organización de la información sigue principios de jerarquía visual, agrupación lógica y feedback inmediato, asegurando que cada usuario pueda encontrar rápidamente lo que necesita.

#### 4.2.2. Labeling Systems

El sistema de etiquetado de AutoNexo está diseñado para proporcionar claridad, consistencia y comprensión inmediata de las funciones y contenidos de la aplicación. Cada etiqueta ha sido cuidadosamente seleccionada para reflejar la terminología del sector automotriz mientras mantiene accesibilidad para usuarios de diferentes niveles técnicos.

**Principios de Etiquetado**

**Claridad y Precisión:**

- Cada etiqueta comunica exactamente su función sin ambigüedad
- Se evita jerga técnica innecesaria que pueda confundir a usuarios no especializados
- Se utilizan términos familiares del contexto automotriz cuando es apropiado

**Consistencia Terminológica:**

- Mismo término para la misma función en toda la aplicación
- Vocabulario unificado entre mecánicos y propietarios de vehículos
- Mantenimiento de convenciones establecidas en la industria

**Jerarquía Visual:**

- Etiquetas principales en tipografía más prominente
- Etiquetas secundarias con menor peso visual
- Uso de colores y tamaños para establecer prioridad informativa

**Estructura de Etiquetado por Módulos**

**Navegación Principal:**

- **Home**: Término universalmente reconocido para la pantalla principal
- **Request**: Indica claramente la gestión de solicitudes de servicio
- **Offer**: Comunica promociones y ofertas especiales
- **Workshop**: Identifica el perfil y gestión del taller
- **Service**: Refiere al historial y seguimiento de servicios

**Gestión de Servicios:**

- **Schedule Appointment**: Programar cita de manera clara y directa
- **Service History**: Historial de servicios con terminología estándar
- **Maintenance Reminder**: Recordatorio de mantenimiento
- **Quote Request**: Solicitud de cotización
- **Service Status**: Estado del servicio en tiempo real

**Perfil y Configuración:**

- **Profile Settings**: Configuración de perfil
- **Workshop Information**: Información del taller
- **Notification Preferences**: Preferencias de notificaciones
- **Language Settings**: Configuración de idioma
- **Theme Selection**: Selección de tema visual

**Comunicación y Soporte:**

- **Contact Support**: Contactar soporte
- **Help Center**: Centro de ayuda
- **FAQ**: Preguntas frecuentes
- **Report Issue**: Reportar problema
- **Feedback**: Retroalimentación

**Estados y Acciones:**

- **Pending**: Pendiente
- **In Progress**: En progreso
- **Completed**: Completado
- **Cancelled**: Cancelado
- **Rescheduled**: Reprogramado

**Etiquetado de Formularios**

**Campos de Entrada:**

- **Vehicle Make**: Marca del vehículo
- **Vehicle Model**: Modelo del vehículo
- **Year**: Año
- **License Plate**: Placa de matrícula
- **VIN Number**: Número de VIN
- **Service Type**: Tipo de servicio
- **Estimated Duration**: Duración estimada
- **Service Description**: Descripción del servicio

**Botones de Acción:**

- **Save**: Guardar
- **Cancel**: Cancelar
- **Submit**: Enviar
- **Edit**: Editar
- **Delete**: Eliminar
- **Confirm**: Confirmar
- **Back**: Atrás
- **Next**: Siguiente

**Mensajes y Alertas:**

- **Success**: Éxito
- **Warning**: Advertencia
- **Error**: Error
- **Information**: Información
- **Confirmation Required**: Confirmación requerida

**Localización y Accesibilidad**

**Soporte Multilingüe:**

- Etiquetas disponibles en español e inglés
- Adaptación cultural de términos técnicos
- Mantenimiento de consistencia entre idiomas

**Accesibilidad:**

- Etiquetas descriptivas para lectores de pantalla
- Texto alternativo para iconos y elementos gráficos
- Contraste adecuado para legibilidad
- Tamaños de fuente accesibles

**Convenciones de Nomenclatura**

**CamelCase para IDs técnicos:**

- `serviceHistory`
- `workshopProfile`
- `maintenanceReminder`

**kebab-case para URLs:**

- `/service-history`
- `/workshop-profile`
- `/maintenance-reminder`

**PascalCase para componentes:**

- `ServiceCard`
- `WorkshopProfile`
- `MaintenanceReminder`

Este sistema de etiquetado asegura que AutoNexo mantenga una comunicación clara y efectiva con sus usuarios, facilitando la adopción de la aplicación y reduciendo la curva de aprendizaje tanto para mecánicos como para propietarios de vehículos.

#### 4.2.3. SEO Tags and Meta Tags

La estrategia de SEO y Meta Tags para AutoNexo está diseñada para optimizar la visibilidad en motores de búsqueda y mejorar la experiencia del usuario tanto en la Landing Page como en la Web Application. Además, se incluyen elementos de ASO (App Store Optimization) para maximizar la descarga y adopción de la aplicación móvil.

**Landing Page - SEO Tags y Meta Tags**

**Página Principal:**

```html
<title>
  AutoNexo - Servicio Rápido de Mecánicos Especializados | Reserva Instantánea
</title>
<meta
  name="description"
  content="Conectamos mecánicos certificados con propietarios de vehículos de manera rápida y confiable. Reserva tu servicio de mantenimiento o reparación en minutos. Servicio automotriz completo con reserva instantánea."
/>
<meta
  name="keywords"
  content="servicio rápido, mecánicos certificados, reserva instantánea, mantenimiento vehicular, reparación automotriz, AutoNexo, servicio automotriz completo, mecánicos especializados, citas automotrices"
/>
<meta name="author" content="ATG - AutoNexo Team" />
<meta name="robots" content="index, follow" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<meta
  property="og:title"
  content="AutoNexo - Servicio Rápido de Mecánicos Especializados"
/>
<meta
  property="og:description"
  content="Conectamos mecánicos certificados con propietarios de vehículos. Reserva tu servicio de mantenimiento o reparación en minutos con nuestro sistema de reserva instantánea."
/>
<meta property="og:type" content="website" />
<meta property="og:url" content="https://autonexo.com" />
<meta property="og:image" content="https://autonexo.com/assets/og-image.jpg" />
<meta name="twitter:card" content="summary_large_image" />
<meta name="twitter:title" content="AutoNexo - Servicio Rápido de Mecánicos" />
<meta
  name="twitter:description"
  content="Reserva instantánea de servicios automotrices con mecánicos certificados. Servicio rápido y confiable."
/>
```

**Página de Características:**

```html
<title>
  Características - AutoNexo | Todo para Servicio Automotriz Completo
</title>
<meta
  name="description"
  content="Descubre todas las características de AutoNexo. Reserva instantánea, servicio automotriz completo, conexión con mecánicos certificados y más funcionalidades."
/>
<meta
  name="keywords"
  content="características AutoNexo, reserva instantánea, servicio automotriz completo, funcionalidades, mecánicos certificados, sistema automático"
/>
<meta name="author" content="ATG - AutoNexo Team" />
```

**Página de Precios:**

```html
<title>Precios - AutoNexo | Planes Básico y Pro para Mecánicos</title>
<meta
  name="description"
  content="Elige tu plan en AutoNexo. Plan Básico $10/mes para comenzar o Plan Pro $30/mes para profesionales. Actualiza cuando tus necesidades crezcan."
/>
<meta
  name="keywords"
  content="precios AutoNexo, plan básico, plan pro, planes mensuales, profesionales mecánicos, actualización planes"
/>
<meta name="author" content="ATG - AutoNexo Team" />
```

**Página de Testimonios:**

```html
<title>Testimonios - AutoNexo | Lo que Dicen Nuestros Usuarios</title>
<meta
  name="description"
  content="Lee testimonios reales de usuarios de AutoNexo. Descubre cómo nuestra app se ha convertido en herramienta esencial para usuarios alrededor del mundo."
/>
<meta
  name="keywords"
  content="testimonios AutoNexo, opiniones usuarios, reseñas, experiencia usuarios, herramienta esencial, usuarios mundo"
/>
<meta name="author" content="ATG - AutoNexo Team" />
```

**Página de Equipo:**

```html
<title>Equipo - AutoNexo | Conoce a los Creadores del Proyecto</title>
<meta
  name="description"
  content="Conoce al equipo ATG creador de AutoNexo. Profesionales dedicados y adaptables que aportan dedicación y actitud positiva al proyecto."
/>
<meta
  name="keywords"
  content="equipo AutoNexo, creadores proyecto, equipo ATG, profesionales dedicados, actitud positiva, desarrolladores"
/>
<meta name="author" content="ATG - AutoNexo Team" />
```

**Página de Contacto:**

```html
<title>Contacto - AutoNexo | ¿Necesitas Ayuda? Estamos Aquí</title>
<meta
  name="description"
  content="¿Necesitas ayuda? Contacta con AutoNexo. Estamos aquí para ayudarte con cualquier pregunta o problema. Teléfono, email y dirección disponibles."
/>
<meta
  name="keywords"
  content="contacto AutoNexo, ayuda, soporte, preguntas, problemas, teléfono, email, dirección, atención al cliente"
/>
<meta name="author" content="ATG - AutoNexo Team" />
```

**Web Application - SEO Tags y Meta Tags**

**Dashboard Principal:**

```html
<title>Dashboard - AutoNexo | Panel de Control</title>
<meta
  name="description"
  content="Panel de control de AutoNexo. Gestiona tus citas, servicios y comunicación con mecánicos especializados."
/>
<meta
  name="keywords"
  content="dashboard AutoNexo, panel de control, gestión automotriz, citas programadas"
/>
<meta name="author" content="ATG - AutoNexo Team" />
<meta name="robots" content="noindex, nofollow" />
```

**Perfil de Usuario:**

```html
<title>Mi Perfil - AutoNexo | Configuración de Cuenta</title>
<meta
  name="description"
  content="Gestiona tu perfil en AutoNexo. Configura tus datos, preferencias y configuración de cuenta."
/>
<meta
  name="keywords"
  content="perfil usuario, configuración cuenta, AutoNexo, datos personales"
/>
<meta name="author" content="ATG - AutoNexo Team" />
<meta name="robots" content="noindex, nofollow" />
```

**Historial de Servicios:**

```html
<title>Historial de Servicios - AutoNexo | Registro de Mantenimiento</title>
<meta
  name="description"
  content="Consulta tu historial completo de servicios automotrices en AutoNexo. Mantén un registro detallado de todos los mantenimientos realizados."
/>
<meta
  name="keywords"
  content="historial servicios, registro mantenimiento, AutoNexo, servicios automotrices"
/>
<meta name="author" content="ATG - AutoNexo Team" />
<meta name="robots" content="noindex, nofollow" />
```

**App Store Optimization (ASO) - Elementos para Aplicación Móvil**

**Google Play Store:**

**App Title:**

```
AutoNexo - Mecánicos y Talleres
```

**App Subtitle:**

```
Conecta con mecánicos especializados y gestiona el mantenimiento de tu vehículo
```

**App Description:**

```
AutoNexo es la aplicación móvil que revoluciona la gestión automotriz, conectando propietarios de vehículos con mecánicos especializados y talleres certificados.

 FUNCIONALIDADES PRINCIPALES:
• Conecta con mecánicos especializados en tu zona
• Programa citas de mantenimiento de forma fácil
• Gestiona el historial completo de tu vehículo
• Recibe recordatorios de mantenimiento automático
• Comunícate directamente con tu taller
• Accede a promociones y ofertas especiales
• Sistema de calificaciones y reseñas

 PARA MECÁNICOS Y TALLERES:
• Gestiona tu agenda de citas
• Administra tu perfil y servicios
• Comunícate con clientes
• Genera reportes de servicios
• Accede a herramientas de gestión

 BENEFICIOS:
• Ahorro de tiempo en la gestión de citas
• Transparencia en precios y servicios
• Historial completo de mantenimiento
• Acceso a mecánicos certificados
• Comunicación directa y eficiente

Descarga AutoNexo y transforma tu experiencia automotriz. Disponible para propietarios de vehículos y profesionales del sector automotriz.

Desarrollado por el equipo ATG.
```

**App Keywords:**

```
mecánico, taller automotriz, mantenimiento vehicular, citas automotrices, servicios automotrices, reparación automotriz, gestión de vehículos, AutoNexo, taller mecánico, mantenimiento preventivo, diagnóstico automotriz, mecánicos especializados, talleres cerca, servicios de reparación, gestión automotriz, app automotriz, citas programadas, historial vehicular, recordatorios mantenimiento, comunicación taller
```

**Apple App Store:**

**App Title:**

```
AutoNexo - Mecánicos y Talleres
```

**App Subtitle:**

```
Conecta con mecánicos especializados
```

**App Description:**

```
AutoNexo conecta propietarios de vehículos con mecánicos especializados, ofreciendo una plataforma integral para la gestión automotriz.

CARACTERÍSTICAS:
• Conexión directa con mecánicos certificados
• Programación de citas simplificada
• Historial completo de mantenimiento
• Recordatorios automáticos de servicio
• Comunicación en tiempo real
• Sistema de calificaciones
• Promociones y ofertas especiales

PARA MECÁNICOS:
• Gestión de agenda y citas
• Administración de perfil
• Comunicación con clientes
• Herramientas de gestión

Transforma tu experiencia automotriz con AutoNexo.

Desarrollado por ATG.
```

**App Keywords:**

```
mecánico, taller, automotriz, mantenimiento, citas, servicios, reparación, vehículo, AutoNexo, diagnóstico, especializado, gestión, app, móvil
```

**Estrategia de Keywords y Posicionamiento**

**Keywords Primarias:**

- AutoNexo
- servicio rápido mecánicos
- reserva instantánea
- mecánicos certificados
- servicio automotriz completo

**Keywords Secundarias:**

- mantenimiento vehicular
- planes básico pro
- testimonios usuarios
- equipo ATG

**Keywords de Cola Larga:**

- "reserva instantánea servicios automotrices"
- "servicio rápido mecánicos certificados"
- "planes básico pro AutoNexo"
- "testimonios usuarios AutoNexo"
- "equipo creadores proyecto AutoNexo"
- "características servicio automotriz completo"
- "conecta mecánicos propietarios vehículos"

Esta estrategia de SEO y ASO asegura que AutoNexo sea fácilmente encontrable tanto en motores de búsqueda como en las tiendas de aplicaciones, maximizando la visibilidad y adopción de la plataforma.

#### 4.2.4. Searching Systems

El sistema de búsqueda de AutoNexo está diseñado para proporcionar a los usuarios herramientas eficientes y precisas para encontrar mecánicos, talleres y servicios específicos, evitando que se sientan perdidos entre el volumen de información disponible. El sistema combina búsqueda textual, filtros avanzados y navegación por tags para optimizar la experiencia de descubrimiento.

**Opciones de Búsqueda Disponibles**

**Búsqueda por Texto Libre:**

- **Campo de búsqueda principal:** Permite a los usuarios escribir términos relacionados con servicios, ubicaciones o nombres de talleres
- **Búsqueda inteligente:** Sistema que sugiere autocompletado basado en servicios populares, ubicaciones y talleres registrados
- **Búsqueda por voz:** Opción de dictado para facilitar la búsqueda en dispositivos móviles

**Búsqueda por Ubicación:**

- **Búsqueda geográfica:** Filtro por ciudad, distrito o proximidad (radio en kilómetros)
- **Detección automática:** Utiliza GPS para sugerir talleres cercanos automáticamente
- **Mapa interactivo:** Visualización de talleres disponibles en un mapa con marcadores

**Búsqueda por Servicios Específicos:**

- **Tags de servicios:** Sistema de etiquetas como "Tire change", "Oil change", "Gas System", "Car wash"
- **Categorías principales:** Mantenimiento preventivo, reparaciones, diagnósticos, servicios especializados
- **Búsqueda por marca/modelo:** Filtros específicos para vehículos (Ford, Toyota, etc.)

**Filtros Avanzados Disponibles**

**Filtros por Calificación y Reputación:**

- **Rating mínimo:** Filtro por calificación de talleres (ej: 4.0 ★ o superior)
- **Número de reseñas:** Filtrar por talleres con mínimo de reseñas para mayor confiabilidad
- **Certificaciones:** Mostrar solo talleres con certificaciones específicas

**Filtros por Disponibilidad:**

- **Horarios de atención:** Filtrar por talleres abiertos en horario específico
- **Disponibilidad inmediata:** Mostrar talleres con disponibilidad para el mismo día
- **Citas programadas:** Filtro por fechas específicas disponibles

**Filtros por Precio y Servicios:**

- **Rango de precios:** Filtro por presupuesto estimado
- **Servicios incluidos:** Selección múltiple de servicios requeridos
- **Tipo de servicio:** Urgente, programado, mantenimiento preventivo

**Filtros por Características del Taller:**

- **Tamaño del taller:** Individual, pequeño, mediano, grande
- **Especialización:** General, especializado en marca específica, servicios premium
- **Facilidades:** Estacionamiento, sala de espera, Wi-Fi, café

**Sistema de Tags y Etiquetado**

**Tags de Servicios (Filtros Rápidos):**

- **Mantenimiento Básico:** "Oil change", "Filter change", "Brake check"
- **Reparaciones:** "Engine repair", "Transmission", "Electrical system"
- **Servicios Especializados:** "Tire change", "Gas System", "Car wash", "Diagnostics"
- **Emergencias:** "24/7 service", "Roadside assistance", "Emergency repair"

**Tags de Ubicación:**

- **Distritos:** "Surco", "Miraflores", "San Isidro", "La Molina"
- **Ciudades:** "Lima", "Arequipa", "Cusco", "Trujillo"
- **Zonas comerciales:** "Centro", "Zona residencial", "Zona industrial"

**Tags de Características:**

- **Horarios:** "24/7", "Fines de semana", "Solo citas"
- **Certificaciones:** "Certificado", "Especializado", "Premium"
- **Facilidades:** "Estacionamiento", "Sala de espera", "Wi-Fi"

**Presentación de Resultados de Búsqueda**

**Vista de Lista (Resultados Principales):**

- **Tarjeta de taller:** Nombre del taller, calificación (4.0 ★), ubicación (Surco, Lima)
- **Servicios destacados:** Tags de servicios más relevantes para la búsqueda
- **Información clave:** Dirección, horarios, disponibilidad inmediata
- **Acciones rápidas:** "Ver perfil", "Contactar", "Agendar cita"

**Vista de Mapa:**

- **Marcadores interactivos:** Ubicación exacta de cada taller
- **Clusters:** Agrupación de talleres cercanos para mejor visualización
- **Información emergente:** Vista previa al hacer clic en marcador

**Vista de Detalle del Taller:**

- **Información completa:** Nombre, calificación, dirección específica (Av. Arequipa 1234)
- **Galería de imágenes:** Fotos del taller, equipos y vehículos en servicio
- **Servicios disponibles:** Lista completa con tags clickeables
- **Personal del taller:** Mecánicos disponibles con roles (Workshop owner, Workshop member)
- **Reseñas y testimonios:** Opiniones de clientes anteriores

**Funcionalidades de Búsqueda Avanzada**

**Búsqueda Combinada:**

- **Múltiples filtros simultáneos:** Combinar ubicación + servicios + precio + disponibilidad
- **Búsqueda guardada:** Permitir guardar combinaciones de filtros frecuentes
- **Historial de búsquedas:** Recordar búsquedas anteriores para facilitar repetición

**Resultados Inteligentes:**

- **Relevancia personalizada:** Priorizar resultados basados en historial del usuario
- **Sugerencias contextuales:** Recomendar servicios complementarios
- **Alertas de disponibilidad:** Notificar cuando talleres favoritos tengan disponibilidad

**Herramientas de Comparación:**

- **Comparar talleres:** Selección múltiple para comparar precios, servicios y calificaciones
- **Tabla comparativa:** Vista lado a lado de características principales
- **Recomendación inteligente:** Sugerir el mejor taller basado en criterios del usuario

Este sistema de búsqueda integral asegura que los usuarios de AutoNexo puedan encontrar rápidamente el taller y los servicios que necesitan, proporcionando múltiples vías de descubrimiento y filtrado para optimizar su experiencia de búsqueda.

#### 4.2.5. Navigation Systems

El sistema de navegación de AutoNexo está diseñado para guiar eficientemente a los usuarios a través de la Landing Page y las aplicaciones móviles, permitiéndoles cumplir sus objetivos de manera intuitiva y satisfactoria. La navegación se estructura en múltiples niveles para adaptarse a diferentes contextos de uso y necesidades del usuario.

**Navegación de Landing Page**

**Header Navigation (Navegación Superior):**

- **Logo AutoNexo:** Elemento principal que lleva siempre al inicio de la página
- **Menú de navegación horizontal:** "Valores", "Características", "Precios", "Testimonios", "Preguntas", "Equipo"
- **Botones de acción:** "REGISTRARSE" (destacado en rojo) y selector de idioma "ES"
- **Comportamiento:** Menú fijo que permanece visible durante el scroll para acceso constante

**Navegación por Secciones:**

- **Scroll suave:** Transiciones fluidas entre secciones sin recargas de página
- **Enlaces de ancla:** Cada elemento del menú superior lleva directamente a la sección correspondiente
- **Indicadores visuales:** Resaltado del elemento activo en el menú según la sección visible

**Navegación de Contenido:**

- **Hero Section:** Botón "Comenzar" que lleva a registro o descarga de app
- **Sección Valores:** Navegación por cards con información de confiabilidad
- **Sección Características:** Cards interactivos que expanden información al hover
- **Sección Precios:** Botones de selección de planes que llevan a proceso de registro
- **Sección Testimonios:** Carrusel de testimonios con navegación por puntos
- **Sección Equipo:** Tarjetas de perfil con información expandible
- **Sección Contacto:** Formulario directo con validación en tiempo real

**Navegación de Aplicación Móvil**

**Bottom Navigation Bar (Navegación Inferior):**

- **Home:** Vista principal con dashboard de citas y agenda del día
- **Request:** Gestión de solicitudes de servicio y comunicación con clientes
- **Offer:** Promociones, ofertas especiales y servicios destacados
- **Workshop:** Perfil del taller, configuración y herramientas administrativas
- **Service:** Historial completo de servicios y seguimiento de intervenciones

**Top Navigation (App Bar):**

- **Flecha de retroceso:** Navegación hacia atrás contextual
- **Título de sección:** Indica ubicación actual en la aplicación
- **Icono de notificaciones:** Acceso directo a alertas y mensajes
- **Menú hamburguesa:** Acceso a funciones secundarias y configuración

**Menú Lateral (Drawer Navigation):**

- **Perfil de usuario:** Acceso a configuración personal y datos del taller
- **Soporte y asistencia:** Centro de ayuda y contacto técnico
- **Términos de uso:** Información legal y políticas
- **Política de privacidad:** Documentación de protección de datos
- **Configuración de idioma:** Cambio entre español e inglés
- **Selección de tema:** Modo claro u oscuro
- **Cerrar sesión:** Logout seguro de la aplicación

**Navegación Contextual**

**Navegación por Breadcrumbs:**

- **Ruta de navegación:** Indica la ubicación actual dentro de la jerarquía
- **Navegación rápida:** Permite regresar a niveles superiores con un toque
- **Ejemplo:** Home > Workshop > Adonz Automotive > Mechanics

**Navegación por Gestos:**

- **Swipe horizontal:** Navegación entre pestañas en la misma pantalla
- **Swipe vertical:** Scroll en listas y contenido extenso
- **Pinch to zoom:** Ampliación de imágenes en galerías de talleres
- **Pull to refresh:** Actualización de contenido en listas y feeds

**Navegación por Acciones:**

**Botones de Acción Primaria:**

- **"Comenzar":** Inicio del proceso de registro o descarga
- **"Registrarse":** Acceso directo al formulario de creación de cuenta
- **"Generate Code":** Generación de código para compartir taller
- **"Edit Workshop":** Edición de información del taller

**Botones de Acción Secundaria:**

- **"Ver perfil":** Acceso al detalle completo del taller
- **"Contactar":** Inicio de comunicación directa
- **"Agendar cita":** Programación de servicios
- **"Copy to Clipboard":** Copia de información para compartir

**Flujos de Navegación Principales**

**Flujo de Registro:**

1. Landing Page → Botón "Comenzar"
2. Formulario de registro → Validación
3. Verificación de email → Confirmación
4. Onboarding → Configuración inicial
5. Dashboard principal → Primera experiencia

**Flujo de Búsqueda de Taller:**

1. Home → Búsqueda o filtros
2. Lista de resultados → Vista previa
3. Detalle del taller → Información completa
4. Contacto o agendado → Acción final

**Flujo de Gestión de Taller:**

1. Workshop → Perfil del taller
2. Edición → Modificación de datos
3. Servicios → Gestión de ofertas
4. Mecánicos → Administración de personal
5. Guardar cambios → Confirmación

**Principios de Navegación**

**Consistencia:**

- Mismos patrones de navegación en toda la aplicación
- Iconografía uniforme y reconocible
- Colores y tipografías consistentes

**Accesibilidad:**

- Navegación por teclado en web
- Lectores de pantalla compatibles
- Contraste adecuado para visibilidad
- Tamaños de toque apropiados (mínimo 44px)

**Feedback Visual:**

- Estados hover y active claramente definidos
- Animaciones suaves en transiciones
- Indicadores de carga durante procesos
- Confirmaciones visuales de acciones

**Eficiencia:**

- Acceso directo a funciones principales
- Número mínimo de toques para tareas comunes
- Navegación contextual basada en el flujo de trabajo
- Búsqueda rápida y filtros accesibles

**Recuperación de Errores:**

- Botones de retroceso siempre disponibles
- Mensajes de error claros y accionables
- Opciones de cancelación en procesos largos
- Historial de navegación para regresar fácilmente

Este sistema de navegación integral asegura que los usuarios puedan moverse de manera intuitiva y eficiente a través de AutoNexo, cumpliendo sus objetivos sin fricción y manteniendo una experiencia satisfactoria tanto en la Landing Page como en las aplicaciones móviles.

### 4.3. Landing Page UI Design

#### 4.3.1. Landing Page Wireframe

<section id="wireframes-landing-autonexo">
  <h2>Wireframes del Landing Page (Desktop & Mobile) – AutoNexo</h2>
  <p>
    Esta sección presenta y explica los <strong>wireframes</strong> del Landing Page para
    <em>Desktop Web Browser</em> y <em>Mobile Web Browser</em>, evidenciando la aplicación de
    <strong>principios de diseño</strong>, <strong>elementos de diseño</strong>, 
    <strong>diseño inclusivo</strong> y <strong>arquitectura de información</strong>.
  </p>

  <!-- Resumen estructural -->
  <h3>Resumen estructural</h3>
  <ul>
    <li><strong>Header fijo:</strong> logo, menú (Inicio, Características, Beneficios, Equipo, Testimonios, Contacto), selector ES/EN y CTA “Solicitar Demo”.</li>
    <li><strong>Hero:</strong> eslogan + párrafo de valor + botón primario (CTA) y visual del producto.</li>
    <li><strong>Características:</strong> 3–6 tarjetas con icono, título y texto breve.</li>
    <li><strong>Beneficios:</strong> grid de tarjetas con evidencia/valor.</li>
    <li><strong>Equipo (ATG):</strong> fotos/íconos, rol y breve bio.</li>
    <li><strong>Testimonios/Partners:</strong> carrusel o grid de logos/opiniones.</li>
    <li><strong>Formulario de contacto/solicitud de demo:</strong> campos básicos y confirmación.</li>
    <li><strong>Footer:</strong> Términos, Privacidad, Soporte y redes.</li>
  </ul>

  <!-- Diferencias Desktop vs Mobile -->
  <h3>Wireframes · Desktop vs Mobile</h3>
  <ul>
    <li><strong>Desktop:</strong> secciones en <em>grid</em> (2–3 columnas); texto e imagen en paralelo; navegación superior visible siempre.</li>
    <li><strong>Mobile:</strong> disposición <em>vertical</em> y apilada; bloques con mayor separación; CTAs centrados; navegación accesible desde el menú.</li>
  </ul>

  <!-- Principios de diseño -->
  <h3>Principios de diseño aplicados</h3>
  <ul>
    <li><strong>Jerarquía visual:</strong> títulos Inter/Medium (H1&gt;H2&gt;H3), CTA destacado, uso consistente de tamaños (70/40/25 px).</li>
    <li><strong>Contraste y énfasis:</strong> primario #202D36 vs fondos #FFFFFF; CTAs con acento (crimson #800C1F).</li>
    <li><strong>Alineación y ritmo:</strong> rejilla base de 8 px; alineación izquierda para texto, centrado para CTAs.</li>
    <li><strong>Proximidad y repetición:</strong> tarjetas con patrón consistente (icono &gt; título &gt; texto &gt; CTA).</li>
    <li><strong>Equilibrio:</strong> distribución homogénea de texto/imagen para evitar sobrecarga cognitiva.</li>
  </ul>

  <!-- Elementos de diseño -->
  <h3>Elementos de diseño evidenciados</h3>
  <ul>
    <li><strong>Tipografía:</strong> Inter (Medium/Bold) por legibilidad y coherencia móvil.</li>
    <li><strong>Color:</strong> primario #202D36, fondo #FFFFFF, grises #D9D9D9/#8E8E8E; acentos #800C1F/#3C0007.</li>
    <li><strong>Espacio:</strong> márgenes/padding 16–24 px; white space para escaneabilidad.</li>
    <li><strong>Iconografía:</strong> pictogramas simples y consistentes para features/beneficios.</li>
    <li><strong>Tamaño/Disposición:</strong> tarjetas modulares; imágenes responsivas (max-width:100%).</li>
  </ul>

  <!-- Diseño inclusivo / Accesibilidad -->
  <h3>Diseño inclusivo y accesibilidad</h3>
  <ul>
    <li><strong>Contraste:</strong> texto oscuro sobre claro y viceversa; metas AA para cuerpo (≥4.5:1) y títulos grandes (≥3:1).</li>
    <li><strong>Legibilidad:</strong> tamaños base 16–18 px; line-height 1.5–1.6; párrafos breves.</li>
    <li><strong>Interacción:</strong> blancos táctiles ≥44×44 px; estados de foco/hover/active visibles.</li>
    <li><strong>Lenguaje claro:</strong> microcopys directos en CTAs (“Solicitar Demo”, “Ver más”).</li>
    <li><strong>Internacionalización:</strong> selector ES/EN desde el header; textos preparados para longitud variable.</li>
    <li><strong>Responsive first:</strong> breakpoints típicos (≤480, ≤768, ≤1024, &gt;=1280); contenido refluye sin pérdida.</li>
  </ul>

  <!-- Arquitectura de información -->
  <h3>Arquitectura de información</h3>
  <ul>
    <li><strong>Organización:</strong> estructura jerárquica por secciones (hero → features → benefits → trust → form → footer).</li>
    <li><strong>Navegación:</strong> menú superior con anclas; CTA persistente en hero; breadcrumb implícito por orden lineal.</li>
    <li><strong>Etiquetado:</strong> nombres claros y consistentes (“Características”, “Beneficios”, “Equipo”, “Contacto”).</li>
    <li><strong>Flujo:</strong> descubrimiento (hero) → valor (features/benefits) → prueba social (testimonios/partners) → conversión (formulario).</li>
  </ul>

  <!-- Criterios de aceptación (concreto) -->
  <h3>Criterios de aceptación (cumplimiento)</h3>
  <ol>
    <li>El header muestra logo, menú y selector ES/EN en Desktop; en Mobile, menú accesible y CTA visible en el primer pantallazo.</li>
    <li>Todos los CTAs tienen tamaño mínimo táctil, contraste suficiente y texto accionable.</li>
    <li>La misma jerarquía se conserva en Mobile con bloques apilados y espaciado adecuado.</li>
    <li>Tarjetas de características y beneficios mantienen patrón visual y lectura en Z/F.</li>
    <li>El formulario captura nombre, correo, mensaje y confirma envío; campos con etiquetas visibles y validación básica.</li>
    <li>Footer incluye Términos, Privacidad, Soporte y redes; accesible en ambas vistas.</li>
  </ol>

  <!-- Nota final -->
  <p><em>
    Con lo anterior, los wireframes del Landing Page demuestran aplicación de principios visuales, elementos de diseño,
    criterios de inclusión/accesibilidad y una arquitectura de información clara que guía hacia la conversión (“Solicitar Demo”).
  </em></p>
</section>

<div>
  <p align="center"><img src="assets/ux-ui/wireframes/Landing page wireframes.png" alt="open-landing-wireframe.png" width="700px" /></p>
</div>

#### 4.3.2. Landing Page Mock-up

<section id="landing-mockups-autonexo">
  <h2>Landing Page Mock-up (Desktop & Mobile) – AutoNexo</h2>
  <p>
    Esta sección presenta los <strong>mock-ups</strong> finales del Landing Page para
    <em>Desktop Web Browser</em> y <em>Mobile Web Browser</em>. La propuesta evidencia la aplicación de
    <strong>principios y elementos de diseño</strong>, <strong>diseño inclusivo</strong>,
    <strong>arquitectura de información</strong> y la alineación con el <strong>Design System</strong> de AutoNexo.
  </p>

  <!-- Resumen visual -->
  <h3>Resumen visual</h3>
  <ul>
    <li><strong>Hero</strong> con eslogan, párrafo de valor y CTA primario “Solicitar demo”.</li>
    <li><strong>Valores</strong> y <strong>Características</strong> en tarjetas con icono + título + texto.</li>
    <li><strong>Precios/Planes</strong> con comparación Básico vs. Pro.</li>
    <li><strong>Testimonios</strong> en tarjetas compactas de una sola línea.</li>
    <li><strong>FAQs</strong> con acordeones (+) expandibles.</li>
    <li><strong>Equipo (ATG)</strong> con fichas de miembros.</li>
    <li><strong>Contacto</strong> con formulario y datos directos.</li>
    <li><strong>Footer</strong> con Términos, Privacidad, Soporte y redes sociales.</li>
  </ul>

  <!-- Desktop vs Mobile -->
  <h3>Distribución · Desktop vs Mobile</h3>
  <ul>
    <li><strong>Desktop:</strong> secciones en grid (2–3 columnas), pares texto/imagen en paralelo, navegación fija en header.</li>
    <li><strong>Mobile:</strong> flujo vertical apilado; CTAs centrados; tarjetas a 1 columna; acordeones ocupan ancho completo.</li>
  </ul>

  <!-- Principios y elementos -->
  <h3>Principios y elementos de diseño aplicados</h3>
  <ul>
    <li><strong>Jerarquía visual:</strong> Inter Medium para H1/H2/H3 (70/40/25 px); contraste de CTAs para énfasis.</li>
    <li><strong>Contraste:</strong> primario <code>#202D36</code> sobre fondos claros <code>#FFFFFF</code>; acentos <code>#800C1F</code>/<code>#3C0007</code>.</li>
    <li><strong>Alineación y ritmo:</strong> rejilla base de 8 px; alineación izquierda para texto, centrado para acciones.</li>
    <li><strong>Proximidad/repetición:</strong> patrón consistente de tarjeta (icono &gt; título &gt; texto &gt; acción).</li>
    <li><strong>Espacio en blanco:</strong> márgenes/padding 16–24 px para escaneabilidad sin sobrecarga.</li>
  </ul>

  <!-- Inclusión / Accesibilidad -->
  <h3>Diseño inclusivo y accesibilidad</h3>
  <ul>
    <li><strong>Contraste AA:</strong> texto normal ≥ 4.5:1; títulos grandes ≥ 3:1.</li>
    <li><strong>Tipografía legible:</strong> base 16–18 px, line-height 1.5–1.6.</li>
    <li><strong>Targets táctiles:</strong> mínimos de 44×44 px; estados <em>hover/focus/active</em> visibles.</li>
    <li><strong>Lenguaje claro:</strong> microcopys directos (p. ej., “Solicitar demo”, “Ver detalles”).</li>
    <li><strong>Internacionalización:</strong> selector ES/EN en header; textos preparados para distinta longitud.</li>
    <li><strong>Responsive first:</strong> breakpoints ≤480, ≤768, ≤1024, ≥1280; imágenes fluidas (max-width:100%).</li>
  </ul>

  <!-- Arquitectura de Información -->
  <h3>Arquitectura de información (mapeo de secciones)</h3>
  <ol>
    <li><strong>Hero</strong> → Descubrimiento y CTA principal.</li>
    <li><strong>Valores</strong> → Principios de marca que guían el servicio.</li>
    <li><strong>Características</strong> → Qué hace el producto (evidencia funcional).</li>
    <li><strong>Precios/Planes</strong> → Decisión informada (Básico vs Pro).</li>
    <li><strong>Testimonios</strong> → Prueba social y confianza.</li>
    <li><strong>FAQs</strong> → Objeciones comunes y soporte inmediato.</li>
    <li><strong>Equipo</strong> → Credibilidad del grupo ATG.</li>
    <li><strong>Contacto</strong> → Conversión secundaria (formulario y datos directos).</li>
    <li><strong>Footer</strong> → Enlaces legales y canales de soporte.</li>
  </ol>

  <!-- Design System -->
  <h3>Alineación con el Design System de AutoNexo</h3>
  <ul>
    <li><strong>Colores:</strong> Primary Blue <code>#202D36</code>, Primary White <code>#FFFFFF</code>, Grays <code>#D9D9D9</code>/<code>#8E8E8E</code>, Acentos <code>#800C1F</code>/<code>#3C0007</code>.</li>
    <li><strong>Tipografía:</strong> Inter (Medium/Bold) con escalas 70/40/25 y 16–18 px para cuerpo.</li>
    <li><strong>Componentes:</strong> botones primarios/secundarios, tarjetas, acordeones, chips, formularios, navbar y footer.</li>
    <li><strong>Tokens:</strong> espaciado 8 px, radios 10–12 px, sombras sutiles para elevación de tarjetas.</li>
  </ul>

  <!-- Criterios de aceptación -->
  <h3>Criterios de aceptación</h3>
  <ol>
    <li>Header con logo, navegación y selector ES/EN en Desktop; menú accesible en Mobile.</li>
    <li>CTA “Solicitar demo” visible en el primer pantallazo (ambas vistas) y con contraste AA.</li>
    <li>Tarjetas de características/beneficios mantienen patrón y ritmo vertical/columnas según viewport.</li>
    <li>Sección de planes presenta comparación clara (precio, beneficios, acción).</li>
    <li>FAQs con acordeones expandibles; foco/teclado navegable.</li>
    <li>Formulario con validación básica y confirmación de envío; campos etiquetados.</li>
    <li>Footer con Términos, Privacidad, Soporte y redes sociales.</li>
  </ol>

  <p><em>
    Los mock-ups consolidan la propuesta visual y funcional del Landing Page de AutoNexo, demostrando consistencia con el Design System,
    cumplimiento de accesibilidad y una arquitectura de información orientada a la conversión.
  </em></p>
</section>

<div>
  <p align="center"><img src="assets/ux-ui/mockups/Landing page Mockup.png" alt="open-landing-wireframe.png" width="700px" /></p>
</div>

### 4.4. Mobile Applications UX/UI Design

#### 4.4.1. Mobile Applications Wireframes

**Register Mechanic**

<div>
  <p align="center"><img src="assets/ux-ui/wireframes/mechanic/Register Mechanic W.png" alt="wireframe-desktop-1.png" width="700px" /></p>
</div>

**Recover password**

<div>
  <p align="center"><img src="assets/ux-ui/wireframes/mechanic/Recover password Mechanic W.png" alt="wireframe-desktop-1.png" width="700px" /></p>
</div>

**Register Workshop**

<div>
  <p align="center"><img src="assets/ux-ui/wireframes/mechanic/Register Workshop W.png" alt="wireframe-desktop-1.png" width="700px" /></p>
</div>

**Home Mechanic**

<div>
  <p align="center"><img src="assets/ux-ui/wireframes/mechanic/Home Mechanic W.png" alt="wireframe-desktop-1.png" width="700px" /></p>
</div>

**Profile Mechanic and Edit**

<div>
  <p align="center"><img src="assets/ux-ui/wireframes/mechanic/Profile Mechanic and Edit W.png" alt="wireframe-desktop-1.png" width="700px" /></p>
</div>

**Support and Assistance Mechanic**

<div>
  <p align="center"><img src="assets/ux-ui/wireframes/mechanic/Support and Assitance Mechanic W.png" alt="wireframe-desktop-1.png" width="700px" /></p>
</div>

**Request Mechanic**

<div>
  <p align="center"><img src="assets/ux-ui/wireframes/mechanic/Request Mechanic W.png" alt="wireframe-desktop-1.png" width="700px" /></p>
</div>

**Offer Mechanic**

<div>
  <p align="center"><img src="assets/ux-ui/wireframes/mechanic/Offer W.png" alt="wireframe-desktop-1.png" width="700px" /></p>
</div>

**Service Mechanic**

<div>
  <p align="center"><img src="assets/ux-ui/wireframes/mechanic/Service Mechanic W.png" alt="wireframe-desktop-1.png" width="700px" /></p>
</div>

**Payment Mechanic**

<div>
  <p align="center"><img src="assets/ux-ui/wireframes/mechanic/Payment Mechanic W.png" alt="wireframe-desktop-1.png" width="700px" /></p>
</div>

<!--__Subscription payment__

<div>
  <p align="center"><img src="assets/chapter-III-assets/Subscription payment.png" alt="wireframe-desktop-1.png" width="700px" /></p>
</div>
-->

**Register Owner**

<div>
  <p align="center"><img src="assets/ux-ui/wireframes/owner/Register Owner W.png" alt="wireframe-desktop-1.png" width="700px" /></p>
</div>

**Recover Password Owner**

<div>
  <p align="center"><img src="assets/ux-ui/wireframes/owner/Recover Password Owner W.png" alt="wireframe-desktop-1.png" width="700px" /></p>
</div>

**Profile and Edit Owner**

<div>
  <p align="center"><img src="assets/ux-ui/wireframes/owner/Profile and Edit Owner W.png" alt="wireframe-desktop-1.png" width="700px" /></p>
</div>

**Support and Assistance Owner**

<div>
  <p align="center"><img src="assets/ux-ui/wireframes/owner/Support and Assistance Owner W.png" alt="wireframe-desktop-1.png" width="700px" /></p>
</div>

**Home Owner**

<div>
  <p align="center"><img src="assets/ux-ui/wireframes/owner/Home Owner W.png" alt="wireframe-desktop-1.png" width="700px" /></p>
</div>

**Vehicles**

<div>
  <p align="center"><img src="assets/ux-ui/wireframes/owner/Vehicles W.png" alt="wireframe-desktop-1.png" width="700px" /></p>
</div>

**Register Vehicle**

<div>
  <p align="center"><img src="assets/ux-ui/wireframes/owner/Register Vehicle W.png" alt="wireframe-desktop-1.png" width="700px" /></p>
</div>

**Edit Vehicle**

<div>
  <p align="center"><img src="assets/ux-ui/wireframes/owner/Edit Vehicle W.png" alt="wireframe-desktop-1.png" width="700px" /></p>
</div>

**Maintenance Log**

<div>
  <p align="center"><img src="assets/ux-ui/wireframes/owner/Maintenance Log W.png" alt="wireframe-desktop-1.png" width="700px" /></p>
</div>

**Add Maintenance**

<div>
  <p align="center"><img src="assets/ux-ui/wireframes/owner/Add Maintenance W.png" alt="wireframe-desktop-1.png" width="700px" /></p>
</div>

**Edit Maintenance**

<div>
  <p align="center"><img src="assets/ux-ui/wireframes/owner/Edit Maintenance W.png" alt="wireframe-desktop-1.png" width="700px" /></p>
</div>

**Workshop Details Owner**

<div>
  <p align="center"><img src="assets/ux-ui/wireframes/owner/Workshop Details Owner W.png" alt="wireframe-desktop-1.png" width="700px" /></p>
</div>

**Offer Owner**

<div>
  <p align="center"><img src="assets/ux-ui/wireframes/owner/Offer Owner W.png" alt="wireframe-desktop-1.png" width="700px" /></p>
</div>

**Request Owner**

<div>
  <p align="center"><img src="assets/ux-ui/wireframes/owner/Request Owner W.png" alt="wireframe-desktop-1.png" width="700px" /></p>
</div>

**Payment Owner**

<div>
  <p align="center"><img src="assets/ux-ui/wireframes/owner/Payment Owner W.png" alt="wireframe-desktop-1.png" width="700px" /></p>
</div>

#### 4.4.2. Mobile Applications Wireflow Diagrams

**User goal: Iniciar sesión y acceder al panel principal**

**User persona: Mecánico o jefe de taller**

El usuario inicia en la pantalla Login, donde introduce su correo electrónico y contraseña. En caso de error, el sistema muestra un mensaje de validación ("Invalid credentials").
Al presionar "Login", se redirige al Home, que muestra las citas programadas, solicitudes pendientes y accesos rápidos a los módulos principales (Request, Offer, Workshop y Service).
El flujo contempla el acceso al menú lateral mediante el ícono "hamburguesa", desde el cual se pueden abrir secciones secundarias como Profile, Payment, Support and Assistance o Logout.

<p align="center">
  <img src="assets/diagrams/wireflow/Login.png" alt="Wireflow - Iniciar sesión y acceder al panel principal" width="800px" />
</p>

**User goal: Crear una nueva solicitud de servicio**

**User persona: Propietario de vehículo**

Desde la pantalla principal Home, el usuario selecciona la pestaña Request, accediendo al formulario de solicitud.
Debe ingresar los datos del vehículo, seleccionar el tipo de servicio (Oil change, Brake check, Tire replacement, etc.) y añadir una breve descripción.
Al presionar "Send Request", la solicitud se registra y aparece una pantalla de confirmación con el mensaje "Request sent successfully".
Desde ahí, el flujo continúa hacia el estado Pending, donde el usuario puede visualizar el estado de respuesta de los talleres.

<p align="center">
  <img src="assets/diagrams/wireflow/Request-owner.png" alt="Wireflow - Crear una nueva solicitud de servicio" width="800px" />
</p>

**User goal: Enviar una oferta de servicio**

**User persona: Mecánico o jefe de taller**

En la pestaña Request, el mecánico visualiza todas las solicitudes recibidas.
Al seleccionar una, accede al detalle del vehículo y presiona "Make an Offer".
El sistema muestra un formulario donde ingresa el precio estimado, fecha y hora de cita, y observaciones adicionales.
Finalmente, al presionar "Send Offer", aparece la confirmación "Offer sent successfully" y el flujo retorna a la lista de solicitudes actualizada.

<p align="center">
  <img src="assets/diagrams/wireflow/Request-Mechanic.png" alt="Wireflow - Enviar una oferta de servicio" width="800px" />
</p>

**User goal: Registrar mantenimiento completado**

**User persona: Mecánico o jefe de taller**

Desde la pantalla Service, el usuario selecciona "Register Service Order", visualizando un formulario con los campos del vehículo, tipo de mantenimiento, costo y observaciones.
Tras completar los datos y presionar "Register", el flujo conduce a una pantalla de validación con el mensaje "Service successfully registered".
Posteriormente, el servicio aparece en la lista de Done, permitiendo revisar los detalles del trabajo finalizado.

<p align="center">
  <img src="assets/diagrams/wireflow/Maintenance.png" alt="Wireflow - Registrar mantenimiento completado" width="800px" />
</p>

**User goal: Consultar historial de mantenimiento**

**User persona: Propietario de vehículo**

El usuario accede desde el menú inferior a la pestaña Service, donde se muestra el historial de mantenimientos realizados.
Cada tarjeta contiene información resumida del servicio (fecha, taller, costo y estado).
Al seleccionar una tarjeta, se despliega la vista Service Detail, con datos completos y la opción "Add Maintenance" para registrar nuevas intervenciones.
El flujo cierra con una confirmación visual ("Maintenance added successfully") y regresa a la vista principal del historial.

<p align="center">
  <img src="assets/diagrams/wireflow/Service.png" alt="Wireflow - Consultar historial de mantenimiento" width="800px" />
</p>

**User goal: Gestionar perfil de usuario y taller**

**User persona: Mecánico o jefe de taller**

Desde el menú lateral, el usuario ingresa a Profile, donde puede editar sus datos personales, cambiar contraseña o acceder a la configuración del taller (Workshop Information).
En la vista Edit Profile, el wireflow incluye las acciones "Save" y "Cancel", que redirigen respectivamente al perfil actualizado o al estado anterior.
Si selecciona "Edit Workshop", se despliega el formulario de información comercial y servicios disponibles.
Al guardar, el flujo muestra el mensaje "Workshop updated successfully", completando la iteración de configuración.

<p align="center">
  <img src="assets/diagrams/wireflow/Profile.png" alt="Wireflow - Gestionar perfil de usuario y taller" width="800px" />
</p>

#### 4.4.3. Mobile Applications Mock-ups

**Register Mechanic**

<div>
  <p align="center"><img src="assets/ux-ui/mockups/mechanic/Register Mechanic.png" alt="wireframe-desktop-1.png" width="700px" /></p>
</div>

**Recover password**

<div>
  <p align="center"><img src="assets/ux-ui/mockups/mechanic/Recover password Mechanic.png" alt="wireframe-desktop-1.png" width="700px" /></p>
</div>

**Register Workshop**

<div>
  <p align="center"><img src="assets/ux-ui/mockups/mechanic/Register Workshop.png" alt="wireframe-desktop-1.png" width="700px" /></p>
</div>

**Home Mechanic**

<div>
  <p align="center"><img src="assets/ux-ui/mockups/mechanic/Home Mechanic.png" alt="wireframe-desktop-1.png" width="700px" /></p>
</div>

**Profile Mechanic and Edit**

<div>
  <p align="center"><img src="assets/ux-ui/mockups/mechanic/Profile Mechanic and Edit.png" alt="wireframe-desktop-1.png" width="700px" /></p>
</div>

**Support and Assitance Mechanic**

<div>
  <p align="center"><img src="assets/ux-ui/mockups/mechanic/Support and Assitance Mechanic.png" alt="wireframe-desktop-1.png" width="700px" /></p>
</div>

**Request Mechanic**

<div>
  <p align="center"><img src="assets/ux-ui/mockups/mechanic/Request Mechanic.png" alt="wireframe-desktop-1.png" width="700px" /></p>
</div>

**Offer Mechanic**

<div>
  <p align="center"><img src="assets/ux-ui/mockups/mechanic/Offer Mechanic.png" alt="wireframe-desktop-1.png" width="700px" /></p>
</div>

**Service Mechanic**

<div>
  <p align="center"><img src="assets/ux-ui/mockups/mechanic/Service Mechanic.png" alt="wireframe-desktop-1.png" width="700px" /></p>
</div>

**Payment Mechanic**

<div>
  <p align="center"><img src="assets/ux-ui/mockups/mechanic/Payment Mechanic.png" alt="wireframe-desktop-1.png" width="700px" /></p>
</div>

<!--__Subscription payment__

<div>
  <p align="center"><img src="assets/chapter-III-assets/Subscription payment.png" alt="wireframe-desktop-1.png" width="700px" /></p>
</div>
-->

**Register Owner**

<div>
  <p align="center"><img src="assets/ux-ui/mockups/owner/Register Owner.png" alt="wireframe-desktop-1.png" width="700px" /></p>
</div>

**Recover Password Owner**

<div>
  <p align="center"><img src="assets/ux-ui/mockups/owner/Recover Password Owner.png" alt="wireframe-desktop-1.png" width="700px" /></p>
</div>

**Profile and Edit Owner**

<div>
  <p align="center"><img src="assets/ux-ui/mockups/owner/Profile and Edit Owner.png" alt="wireframe-desktop-1.png" width="700px" /></p>
</div>

**Support and Assistance Owner**

<div>
  <p align="center"><img src="assets/ux-ui/mockups/owner/Support and Assistance Owner.png" alt="wireframe-desktop-1.png" width="700px" /></p>
</div>

**Home Owner**

<div>
  <p align="center"><img src="assets/ux-ui/mockups/owner/Home Owner.png" alt="wireframe-desktop-1.png" width="700px" /></p>
</div>

**Vehicles**

<div>
  <p align="center"><img src="assets/ux-ui/mockups/owner/Vehicles.png" alt="wireframe-desktop-1.png" width="700px" /></p>
</div>

**Register Vehicle**

<div>
  <p align="center"><img src="assets/ux-ui/mockups/owner/Register Vehicle.png" alt="wireframe-desktop-1.png" width="700px" /></p>
</div>

**Edit Vehicle**

<div>
  <p align="center"><img src="assets/ux-ui/mockups/owner/Edit Vehicle.png" alt="wireframe-desktop-1.png" width="700px" /></p>
</div>

**Maintenance Log**

<div>
  <p align="center"><img src="assets/ux-ui/mockups/owner/Maintenance Log.png" alt="wireframe-desktop-1.png" width="700px" /></p>
</div>

**Add Maintenance**

<div>
  <p align="center"><img src="assets/ux-ui/mockups/owner/Add Maintenance.png" alt="wireframe-desktop-1.png" width="700px" /></p>
</div>

**Edit Maintenance**

<div>
  <p align="center"><img src="assets/ux-ui/mockups/owner/Edit Maintenance.png" alt="wireframe-desktop-1.png" width="700px" /></p>
</div>

**Workshop Details Owner**

<div>
  <p align="center"><img src="assets/ux-ui/mockups/owner/Workshop Details Owner.png" alt="wireframe-desktop-1.png" width="700px" /></p>
</div>

**Offer Owner**

<div>
  <p align="center"><img src="assets/ux-ui/mockups/owner/Offer Owner.png" alt="wireframe-desktop-1.png" width="700px" /></p>
</div>

**Request Owner**

<div>
  <p align="center"><img src="assets/ux-ui/mockups/owner/Request Owner.png" alt="wireframe-desktop-1.png" width="700px" /></p>
</div>

**Payment Owner**

<div>
  <p align="center"><img src="assets/ux-ui/mockups/owner/Payment Owner.png" alt="wireframe-desktop-1.png" width="700px" /></p>
</div>

#### 4.4.4. Mobile Applications User Flow Diagrams

**User goal: Registrarse como nuevo usuario**

**User persona: Mecánico o jefe de taller**

Al ingresar a la aplicación móvil, los usuarios pueden acceder con su correo y contraseña desde la pantalla Login. Si no tienen una cuenta, pueden seleccionar “Register”, pasando a la pantalla de Registro, donde deberán ingresar su nombre, correo, número de teléfono y contraseña.

De manera opcional, pueden incluir un Workshop Code para asociarse a un taller existente. Si no saben qué es, pueden consultar la opción “What’s this?”, que muestra una breve explicación visual.

Antes de finalizar, los usuarios deben aceptar los Términos y Condiciones y luego presionar “Register” para completar su registro. Una vez creado el usuario, la aplicación los redirige a su pantalla principal Home.

<p align="center">
  <img src="assets/diagrams/wireflow/Flujo 1.jpg" alt="Registro del mecanico" width="720px" />
</p>

**User goal: Recuperar contraseña**

**User persona: Mecánico o jefe de taller**

Al ingresar a la aplicación, el usuario puede seleccionar la opción “Forgot Password?” desde la pantalla de Login. Luego, se le solicita ingresar su número de teléfono registrado para recibir un código de verificación (OTP).

En la pantalla de OTP Verification, el usuario ingresa el código recibido por mensaje y selecciona “Verify & Proceed”. Una vez validado, pasa a la pantalla donde podrá establecer una nueva contraseña, confirmarla y presionar “Submit” para completar el proceso.

Finalmente, el sistema confirma el cambio y redirige al usuario nuevamente a la pantalla de Login para acceder con sus nuevas credenciales.

<p align="center">
  <img src="assets/diagrams/wireflow/Flujo 2.jpg" alt="Recuperar Contraseña" width="720px" />
</p>

**User goal: Iniciar sesión y acceder al panel principal**

**User persona: Mecánico o Jefe de taller**

Al ingresar a la aplicación, el usuario visualiza la pantalla de Login, donde puede acceder ingresando su correo y contraseña. Una vez autenticado, la aplicación lo redirige a la pantalla principal Home, donde se muestra su nombre, próximas citas y el calendario de trabajo con las solicitudes programadas.

Desde el ícono de menú, el usuario puede abrir el panel lateral y acceder a diferentes secciones como Profile, Payment, Support and Assistance, Terms of use, Privacy Policy o Logout, además de cambiar el idioma y el tema de la aplicación.

<p align="center">
  <img src="assets/diagrams/wireflow/Flujo 3.jpg" alt="Ingresar a la aplicación" width="720px" />
</p>

**User goal: Registrar y configurar un taller**

**User persona: Mecánico o Jefe de taller**

Al ingresar a la sección Workshop, el usuario puede registrar la información de su taller completando los campos de nombre comercial, RUC, distrito, ciudad y dirección. También puede añadir el logo, una imagen representativa y los servicios disponibles.

En la siguiente pantalla, el usuario define los horarios de atención para cada día de la semana y, si lo desea, marca los días libres o la opción de atención las 24 horas.

Finalmente, al presionar “Save”, la aplicación guarda la información y registra el taller correctamente dentro del sistema, quedando listo para ser visualizado o editado posteriormente.

<p align="center">
  <img src="assets/diagrams/wireflow/Flujo 4.jpg" alt="Registrar taller" width="720px" />
</p>

**User goal: Visualizar y compartir el código del taller**

**User persona: Propietario o jefe de taller**

Desde la pantalla principal Home, el usuario puede acceder a la sección Workshop, donde visualiza la información completa de su taller, incluyendo nombre, ubicación, servicios y miembros del equipo.

En esta vista, el usuario puede seleccionar la opción “Generate Code” para crear un Workshop Code, el cual se muestra en una ventana emergente con la opción de copiarlo para compartirlo con nuevos mecánicos que deseen unirse al taller.

Una vez generado, el código puede ser utilizado por un solo usuario y posteriormente caduca. El propietario también puede editar los datos del taller seleccionando “Edit Workshop”.

<p align="center">
  <img src="assets/diagrams/wireflow/Flujo 5.jpg" alt="Registrar taller" width="720px" />
</p>

**User goal: Visualizar y editar perfil de usuario**

**User persona: Propietario o jefe de taller**

Desde el menú lateral, el usuario puede acceder a la sección Profile, donde visualiza su información personal, como nombre, correo, número de teléfono y taller actual. También puede gestionar las notificaciones de mensajes y ofertas.

Al seleccionar el ícono de edición, el usuario ingresa a la pantalla Edit Profile, donde puede actualizar sus datos personales o modificar su contraseña seleccionando la opción “Change Password”.

En la pantalla New Password, debe ingresar y confirmar la nueva contraseña. Finalmente, al presionar “Save”, los cambios se guardan y el usuario regresa a su perfil actualizado.

<p align="center">
  <img src="assets/diagrams/wireflow/Flujo 6.jpg" alt="Editar Perfil" width="720px" />
</p>

**User goal: Contactar con soporte técnico**

**User persona: Propietario o jefe de taller**

Desde el menú lateral, el usuario puede acceder a la sección Support and Assistance, donde se presentan distintas opciones de ayuda como Call Us, Mail Us, Frequently Asked Questions, Terms and Conditions y un tutorial en video.

Al seleccionar Mail Us, se abre la pantalla Contact us via Gmail, donde el usuario puede escribir el asunto y el mensaje dirigido al equipo de soporte de Autonexo.

Finalmente, al presionar “Send Email”, aparece una ventana de confirmación con el mensaje “Success!”, indicando que el correo fue enviado correctamente.

<p align="center">
  <img src="assets/diagrams/wireflow/Flujo 7.jpg" alt="Asistencia y Soporte" width="720px" />
</p>

**User goal: Enviar una oferta al propietario del vehículo**

**User persona: Propietario o jefe de taller**

Desde la pantalla principal Home, el usuario puede ingresar a la sección Request, donde se muestran las solicitudes de mantenimiento enviadas por los propietarios de vehículos.

Al seleccionar Offer en una solicitud, el mecánico puede revisar los detalles del vehículo y completar el formulario Make an Offer, indicando el precio estimado, fecha y hora de cita, además de observaciones adicionales sobre el servicio.

Finalmente, al presionar “Send Offer”, aparece una ventana emergente con el mensaje “Success!”, confirmando que la oferta fue enviada exitosamente al cliente.

<p align="center">
  <img src="assets/diagrams/wireflow/Flujo 8.jpg" alt="Oferta" width="720px" />
</p>

**User goal: Visualizar ofertas pendientes y realizadas**

**User persona: Mecánico o jefe de taller**

Desde la pantalla principal Home, el usuario puede acceder a la sección Offer, donde se muestran las ofertas enviadas a los propietarios de vehículos.

En esta pantalla, las ofertas se organizan en dos categorías: Pending, que agrupa las propuestas aún no respondidas, y Realized, que muestra las ofertas aceptadas o completadas.

De esta forma, el usuario puede realizar un seguimiento de sus propuestas y gestionar de manera eficiente sus servicios dentro de la plataforma.

<p align="center">
  <img src="assets/diagrams/wireflow/Flujo 9.jpg" alt="Visualizar ofertas" width="720px" />
</p>

**User goal: Registrar y gestionar órdenes de servicio**

**User persona: Mecánico o jefe de taller**

Desde la pantalla principal Home, el usuario puede ingresar a la sección Service, donde se muestran las órdenes de servicio clasificadas como In progress, Done o Canceled.

Al seleccionar Register Service Order, el mecánico puede crear una nueva orden, eligiendo la oferta asociada, la fecha y hora de entrega, y agregando las tareas específicas del mantenimiento.

Finalmente, al presionar “Register”, la orden se guarda en el sistema y queda disponible para seguimiento dentro del listado de servicios activos.

<p align="center">
  <img src="assets/diagrams/wireflow/Flujo 10.jpg" alt="Registrar y gestionar servicios" width="720px" />
</p>

**User goal: Suscribirse a un plan de pago**

**User persona: Mecánico o jefe de taller**

Desde el menú lateral, el usuario puede acceder a la sección Payment, donde visualiza los planes disponibles (Monthly y Annual) con sus respectivos precios y beneficios.

Tras seleccionar el plan deseado, se muestra la pantalla Billing address, donde el usuario completa los datos de facturación. Luego, pasa a la pantalla Add Payment, en la que debe ingresar la información de su tarjeta o método de pago preferido.

Finalmente, al presionar “Pay”, aparece una ventana de confirmación con el mensaje “Success!”, indicando que la suscripción se realizó correctamente.

<p align="center">
  <img src="assets/diagrams/wireflow/Flujo 11.jpg" alt="Suscribirse a un plan" width="720px" />
</p>

**User goal: Registrarse como propietario de vehículo**

**User persona: Propietario de vehículo**

Al ingresar a la aplicación, el usuario propietario accede a la pantalla Login, donde puede iniciar sesión con su correo y contraseña. Si no tiene una cuenta, puede seleccionar la opción “Register” para continuar con el proceso de registro.

En la pantalla Registration, el usuario debe completar los campos con su nombre, correo electrónico, número de teléfono y contraseña, la cual debe ser confirmada. Antes de finalizar, debe aceptar los Términos y Condiciones mostrados en una ventana emergente.

Finalmente, al presionar “Register”, su cuenta se crea exitosamente, quedando listo para acceder a las funciones principales de la aplicación.

<p align="center">
  <img src="assets/diagrams/wireflow/Flujo 1 Owner.jpg" alt="Registrarse como propietario de vehículo" width="720px" />
</p>

**User goal: Recuperar contraseña**

**User persona: Propietario de vehículo**

Desde la pantalla Login, el usuario selecciona la opción “Forgot Password?”, lo que lo dirige a una pantalla donde debe ingresar su número de teléfono registrado.

A continuación, recibe un código de verificación (OTP) que debe ingresar en la pantalla OTP Verification para validar su identidad. Una vez verificado, se habilita la pantalla para establecer una nueva contraseña, la cual debe ser confirmada antes de presionar “Submit”.

Finalmente, el sistema confirma la actualización de la contraseña, permitiendo al usuario volver al inicio de sesión con sus nuevas credenciales.

<p align="center">
  <img src="assets/diagrams/wireflow/Flujo 2 Owner.jpg" alt="Recuperar contraseña" width="720px" />
</p>

**User goal: Iniciar sesión y acceder al panel principal**

**User persona: Propietario de vehículo**

Al ingresar a la aplicación, el usuario visualiza la pantalla Login, donde puede acceder ingresando su correo electrónico y contraseña. Una vez autenticado, es redirigido al Home, donde se muestra la información de su cita actual, el taller asignado y el mecánico encargado.

Desde el menú lateral, el usuario puede acceder a secciones como Profile, Payment, Support and Assistance, Terms of use, Privacy Policy y Logout, además de cambiar el idioma y el tema de la aplicación.

<p align="center">
  <img src="assets/diagrams/wireflow/Flujo 3 Owner.jpg" alt="Iniciar sesión y acceder al panel principal" width="720px" />
</p>

**User goal: Visualizar y editar perfil de usuario**

**User persona: Propietario de vehículo**

Desde el menú lateral, el usuario accede a la sección Profile, donde puede visualizar su información personal, como nombre, correo electrónico, número de teléfono, talleres favoritos y configuración de notificaciones.

Al presionar el ícono de edición, se abre la pantalla Edit Profile, que permite modificar los datos personales o cambiar la contraseña seleccionando “Change Password”.

En la pantalla New Password, el usuario ingresa y confirma su nueva contraseña. Finalmente, al presionar “Save”, los cambios se guardan correctamente, actualizando su perfil.

<p align="center">
  <img src="assets/diagrams/wireflow/Flujo 4 Owner.jpg" alt="Visualizar y editar perfil de usuario" width="720px" />
</p>

**User goal: Contactar con soporte técnico**

**User persona: Propietario de vehículo**

Desde el menú lateral, el usuario puede acceder a la sección Support and Assistance, donde se muestran opciones de ayuda como Call Us, Mail Us, Frequently Asked Questions, Terms and Conditions y un tutorial en video.

Al seleccionar Mail Us, se abre la pantalla Contact us via Gmail, donde el usuario puede escribir el asunto y el mensaje para comunicarse con el equipo de soporte.

Finalmente, al presionar “Send Email”, aparece una ventana de confirmación con el mensaje “Success!”, indicando que el correo fue enviado correctamente.

<p align="center">
  <img src="assets/diagrams/wireflow/Flujo 5 Owner.jpg" alt="Contactar con soporte técnico" width="720px" />
</p>

**User goal: Eliminar un vehículo registrado**

**User persona: Propietario de vehículo**

Desde el Home, el usuario selecciona la pestaña Vehicles, donde puede visualizar todos los vehículos registrados en su cuenta. Cada vehículo muestra las opciones Edit y Delete.

Al presionar Delete, se muestra un mensaje de confirmación indicando “Success! Vehicle deleted successfully”, confirmando que la eliminación del vehículo se realizó correctamente.

Este flujo permite mantener actualizada la información de los vehículos asociados a la cuenta del usuario, brindando un control fácil y rápido desde la aplicación.

<p align="center">
  <img src="assets/diagrams/wireflow/Flujo 6 Owner.jpg" alt="Eliminar un vehículo registrado" width="720px" />
</p>

**User goal: Registrar un nuevo vehículo**

**User persona: Propietario de vehículo**

Desde la sección Vehicles, el usuario selecciona la opción Add New Vehicle para registrar un nuevo automóvil.
En la pantalla Register Vehicle, ingresa la información del vehículo, incluyendo marca, modelo, año, placa, fotografía, y una breve descripción del estado o características del vehículo.

Tras completar los campos requeridos, el usuario presiona Register, y el sistema confirma la operación con el mensaje:
“Success! Vehicle registered successfully”, indicando que el vehículo se añadió correctamente a su cuenta.

<p align="center">
  <img src="assets/diagrams/wireflow/Flujo 7 Owner.jpg" alt="Registrar un nuevo vehículo" width="720px" />
</p>

**User goal: Editar la información de un vehículo registrado**

**User persona: Propietario de vehículo**

Desde la sección Vehicles, el usuario selecciona la opción Edit en el vehículo que desea actualizar.
En la pantalla Edit Vehicle, puede modificar los campos disponibles como marca, modelo, año, fotografía, placa y descripción.

Una vez realizados los cambios, el usuario presiona Save, y el sistema muestra el mensaje de confirmación:
“Success! Vehicle edited successfully”, indicando que la información fue actualizada correctamente.

<p align="center">
  <img src="assets/diagrams/wireflow/Flujo 8 Owner.jpg" alt="Editar la información de un vehículo registrado" width="720px" />
</p>

**User goal: Registrar o editar un mantenimiento del vehículo**

**User persona: Propietario de vehículo**

Desde la pantalla Maintenance Log, el usuario puede visualizar el historial de mantenimientos realizados a su vehículo, con información como fecha y tipo de servicio.

Al seleccionar Add Maintenance, se abre la pantalla Maintenance, donde el usuario puede ingresar o actualizar los datos del mantenimiento: nombre del servicio, fecha, costo, mecánico responsable y una breve descripción.

Tras guardar los cambios con el botón Add Maintenance, el sistema muestra el mensaje de confirmación:
“Success! Maintenance edited successfully”, indicando que el registro fue actualizado correctamente.

<p align="center">
  <img src="assets/diagrams/wireflow/Flujo 9 Owner.jpg" alt="Registrar o editar un mantenimiento del vehículo" width="720px" />
</p>

**User goal: Buscar y visualizar información de talleres**

**User persona: Propietario de vehículo**

Desde la pantalla principal, el usuario selecciona la opción Workshop en la barra de navegación inferior.
En la pantalla Workshop, puede aplicar filtros por departamento, provincia y distrito para visualizar los talleres disponibles cercanos a su ubicación.

Al seleccionar un taller, se muestra la pantalla con su información detallada: nombre, dirección, teléfono, servicios ofrecidos, calificación promedio y la lista de mecánicos asociados.

De esta manera, el usuario puede elegir el taller más conveniente antes de realizar una solicitud de servicio.

<p align="center">
  <img src="assets/diagrams/wireflow/Flujo 10 Owner.jpg" alt="Buscar y visualizar información de talleres" width="720px" />
</p>

### 4.5. Mobile Applications Prototyping

#### 4.5.1. Android Mobile Applications Prototyping

[Mechanic Prototype](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202311064_upc_edu_pe/EUX747Y09zxIpXmVbkCaNYoBnK8niDY1xkbvNpeWkuXdHQ?e=sJjhMF&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)

<p align="center">
  <img src="assets/ux-ui/proto/mechanic-prototype.png" alt="Prototipo de la app del mecánico" width="720px" />
</p>

[Owner Prototype](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202311064_upc_edu_pe/EbKcPfyzVzVEjt88tIi2edYBGt9elB7THGxPFwt44bkgxg?e=W0wZ8G&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)

<p align="center">
  <img src="assets/ux-ui/proto/owner-prototype.png" alt="Prototipo de la app del propietario" width="720px" />
</p>

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

### 4.8.1. Event Storming

El objetivo de la sesión de EventStorming fue realizar una exploración amplia y colaborativa del dominio del problema de Autonexo. Mediante esta técnica buscamos representar de manera visual y comprensible los distintos eventos que ocurren dentro del flujo de interacción entre usuarios (propietarios de vehículos) y mecánicos, con el fin de identificar oportunidades de mejora, puntos críticos y posibles cambios de estado en el sistema.
<br>

- Step 1 – Unstructured Exploration: El equipo colocó en Miro todos los eventos relevantes sin ningún orden, con el fin de vaciar conocimiento y asegurar que ninguna parte del dominio quedara fuera.

<img alt="step1_UnstructuredExploration" src="assets\diagrams\storming\step1_UnsExp.png" />
<br>

- Step 2 – Timelines: Los eventos fueron organizados en una línea de tiempo, lo que permitió identificar la secuencia lógica de las acciones

<img alt="step2_Timelines" src="assets\diagrams\storming\step2_Timelines.png" />
<br>

- Step 3 – Pain Points: Se marcaron las dificultades que enfrentan los usuarios, como la demora en la asignación de mecánicos o la falta de transparencia en los precios.

<img alt="step3_PaintPoints" src="assets\diagrams\storming\step3_PaintPoints.png" />
<br>

- Step 4 – Pivotal Points: Finalmente, se destacaron los eventos clave que generan cambios de estado.
  <br>

<img alt="step4_PivotalPoints" src="assets\diagrams\storming\step4_PivotalPoints.png" />
<br>
<br>

Esta dinámica permitió al equipo obtener una visión compartida del proceso, detectar problemas reales y reconocer eventos centrales que posteriormente servirían para delimitar los bounded contexts.
<br>

#### 4.8.1.1. Candidate Context Discovery

El objetivo de la sesión de Candidate Context Discovery fue identificar y delimitar los bounded contexts del dominio a partir del EventStorming, con el fin de proponer una primera aproximación modular al sistema. Esto asegura que cada parte del dominio tenga responsabilidades claras, evitando la complejidad innecesaria y permitiendo un diseño más mantenible y escalable.
<br>

Se partió del resultado del EventStorming y se aplicó la técnica Look-for-pivotal-events, donde se tomaron como referencia los eventos clave mediante lineas secantes en los post-its (“Service request submitted”, “Offer accepted”, “Service completed”, etc) para determinar los límites naturales entre contextos.

<img alt="step4_PivotalPoints" src="assets\diagrams\storming\step4_PivotalPoints.png" />

<br>

A partir de esto, se definieron los bounded contexts:

- IAM Context: Abarca la lógica de registro/autenticación de usuario
- Subscription context: Hace referencia al sistema de suscripción para acceder a las funcionalidades, mediante el cual la aplicación generará ingresos.
- Workshop Context: Engloba la lógica de los mecánicos dentro de las talleres.
- Trust: Hace referencia al sistema de calificación a los usuarios.
- Maintenance: Engloba la lógica acerca de los vehículos y sus mantenimientos.
- Booking Context: Engloba el proceso de búsqueda, booking y ejecución del servicio.
- Notifications: Hace referencia a las notificaciones del sistema.

#### 4.8.1.2. Domain Message Flows Modeling

**Scenario 1**
<img alt="scenario-1" src="assets\diagrams\scenario\scenario-1.jpg" />
<br> <br>

**Scenario 2**
<img alt="scenario-2" src="assets\diagrams\scenario\scenario-2.jpg" />
<br> <br>

**Scenario 3**
<img alt="scenario-3" src="assets\diagrams\scenario\scenario-3.jpg" />
<br> <br>

**Scenario 4**
<img alt="scenario-4" src="assets\diagrams\scenario\scenario-4.jpg" />
<br> <br>

#### 4.8.1.3 Bounded Context Canvases

**IAM bounded context canvas**

<img alt="IAM" src="assets\diagrams\context-canvases\canvases-IAM-c.png" />
<br> <br>

**Booking bounded context canvas**

<img alt="Matching" src="assets\diagrams\context-canvases\canvases-matching-c.png" />
<br> <br>
 
**Notifications bounded context canvas**

<img alt="Notification" src="assets\diagrams\context-canvases\canvases-notification-c.png" />
<br> <br>

**Payment bounded context canvas**

<img alt="Payment" src="assets\diagrams\context-canvases\canvases-payment-c.png" />
<br> <br>

**Trust bounded context canvas**

<img alt="Trust" src="assets\diagrams\context-canvases\canvases-trust-c.png" />
<br> <br>

**Maintenance bounded context canvas**

<img alt="Vehicle" src="assets\diagrams\context-canvases\canvases-vehicle-c.png" />
<br> <br>

**Workshop bounded context canvas**

<img alt="Workshop" src="assets\diagrams\context-canvases\canvases-workshop-c.png" />
<br> <br>

### 4.8.2. Context Mapping

El Context Mapping en Domain-Driven Design (DDD) representa explícitamente cómo interactúan los bounded contexts entre sí, definiendo contratos, direcciones de influencia (upstream/downstream) y patrones de integración. Este mapeo permite identificar qué contextos requieren estandarización, cuáles deben protegerse mediante traducción (Anti-Corruption Layer), y dónde preservar independencia para asegurar que cada contexto pueda evolucionar de forma predecible y segura.

En Autonexo, los contexts se organizaron considerando los siguientes patrones:

**Context Map Patterns**

**1. Open Host Service (OHS)**
Un contexto upstream expone servicios mediante contratos estables (APIs, endpoints o eventos), de forma que múltiples consumidores downstream pueden integrarse sin conocer su modelo interno.

Uso en Autonexo:
El IAM Context actúa como OHS, proveyendo autenticación, autorización y gestión de roles. Todos los contexts (Matching & Booking, Vehicle & Maintenance, Workshop, Subscription, Trust & Reputation, Notification) consumen estos servicios para validar identidad y permisos.

<img alt="OHS" src="assets\diagrams\ctx-map\ctxMapPatt_OHS.png" />

**2. Customer/Supplier (C/S)**
Relación proveedor–cliente entre contextos. El Supplier prioriza parte de su backlog en función de las necesidades del Customer, adaptando sus capacidades para habilitar los objetivos del cliente.

Uso en Autonexo:
Matching & Booking (Customer) – Workshop (Supplier): el Workshop Context provee disponibilidad de agenda y catálogo de servicios, mientras el Booking Context depende de esos datos para confirmar reservas de manera confiable.

Subscription (Customer) – Workshop (Supplier): las suscripciones otorgan beneficios como prioridad de agenda o descuentos, los cuales dependen de la configuración y condiciones publicadas por los talleres en el Workshop Context.

<img alt="Customer/Supplier" src="assets\diagrams\ctx-map\ctxMapPatt_CS.png" />

**3. Shared Kernel (SK)**
Dos contexts comparten un submodelo común, usualmente entidades o identificadores críticos, que deben mantenerse consistentes para evitar duplicación y divergencia.

Uso en Autonexo:
El Matching & Booking Context y el Vehicle & Maintenance Context comparten identificadores de vehículos y mantenimientos confirmados, de modo que ambos contexts operan sobre la misma referencia, garantizando consistencia y evitando duplicación de datos.

<img alt="ctxMapPatt_SharedKernel" src="assets\diagrams\ctx-map\ctxMapPatt_SK.png" />

**4. Conformist (CF)**
El downstream adopta el modelo del upstream sin traducción, lo que facilita una integración rápida, pero sacrifica independencia, ya que hereda sus decisiones de diseño.

Uso en Autonexo:
El Subscription Context se adapta directamente al modelo de Matching and Booking Context (ejemplo: estados de reserva como activa, cancelada, finalizada) sin redefinirlos ni transformarlos. Esto agiliza la integración, pero obliga a Subscription a depender de los cambios en Booking.

<img alt="ctxMapPatt_Conformist" src="assets\diagrams\ctx-map\ctxMapPatt_CF.png" />

**5. Publisher/Subscriber (Event-Driven)**
Un contexto upstream publica eventos que otros contextos downstream consumen de manera asíncrona, desacoplando la integración. Esto permite que el publisher no dependa de los consumidores y que múltiples contexts reaccionen a un mismo evento.

Uso en Autonexo:
El Notification Context actúa como subscriber de eventos generados por otros contexts:
-Matching and Booking Context → publica el evento Reserva Creada.
-Vehicle and Maintenance Context → publica el evento Mantenimiento Finalizado.
-Trust and Reputation Context → publica el evento Calificación Registrada.

El Notification Context escucha estos eventos y envía notificaciones push a los usuarios afectados.

<img alt="ctxMapPatt_Publisher/Subscriber" src="assets\diagrams\ctx-map\ctxMapPatt_PS.png" />

### 4.8.3. Software Architecture Context Diagram

El siguiente diagrama muestra de manera general Autonexo conectado con los sistemas externos y los usuarios que intervienen
<br>
<img alt="Context-Diagram" src="assets\diagrams\c4\structurizr-101398-SystemContext-001.png" />

### 4.8.4. Software Architecture Container Diagrams

El diagrama C2 profundiza en el sistema y representa la arquitectura general del software, destacando las principales tecnologías empleadas y la manera en que estas se interconectan.
<br>
<img alt="Container-Diagram" src="assets\diagrams\c4\structurizr-101398-Container-001.png" />

### 4.8.5. Software Architecture Components Diagrams

El siguiente diagrama muestra los contenedores del sistema Autonexo desplegados en el entorno de desarrollo y producción. Además, se muestran los servicios externos, la base de datos y el storage.
<br>

- Sistema en entorno de desarrollo:
  <br>
  <img alt="Deployment-Diagram-1" src="assets\diagrams\c4\structurizr-101398-SystemContext-001.png" />

<br>

- Sistema en entorno de producción:
  <br>
  <img alt="Deployment-Diagram-2" src="assets\diagrams\c4\structurizr-101398-Deployment-002.png" />

### 4.9. Software Object-Oriented Design

#### 4.9.1. Class Diagrams

**IAM:**

- Context Class Diagram:

<img alt="IAM Context Class Diagram" src="assets\diagrams\classes\class-iam.png" />

- Context DB Diagram:

<img alt="IAM Context DB Diagram" src="assets\diagrams\db\contexts\db-iam.png" />

**Matching:**

- Context Class Diagram:
  <img alt="Matching Context Class Diagram" src="assets\diagrams\classes\class-matching.png" />

- Context DB Diagram:
  <img alt="Matching Context DB Diagram" src="assets\diagrams\db\contexts\db-matching.png" />

**Notification:**

- Context Class Diagram:
  <img alt="Notification Context Class Diagram" src="assets\diagrams\classes\class-notification.png" />

- Context DB Diagram:
  <img alt="Notification Context DB Diagram" src="assets\diagrams\db\contexts\db-notifications.png" />

**Payment:**

- Context Class Diagram:
  <img alt="Payment Context Class Diagram" src="assets\diagrams\classes\class-payment.png" />

- Context DB Diagram:
  <img alt="Payment Context DB Diagram" src="assets\diagrams\db\contexts\db-payment.png" />

**Trusting:**

- Context Class Diagram:
  <img alt="Trusting Context Class Diagram" src="assets\diagrams\classes\class-trusting.png" />

- Context DB Diagram:
  <img alt="Trusting Context DB Diagram" src="assets\diagrams\db\contexts\db-trusting.png" />

**Vehicle:**

- Context Class Diagram:
  <img alt="Vehicle Context Class Diagram" src="assets\diagrams\classes\class-vehicle.png" />

- Context DB Diagram:
  <img alt="Vehicle Context DB Diagram" src="assets\diagrams\db\contexts\db-vehicle.png" />

**Workshop:**

- Context Class Diagram:
  <img alt="Workshop Context Class Diagram" src="assets\diagrams\classes\class-workshop.png" />

- Context DB Diagram:
  <img alt="Workshop Context DB Diagram" src="assets\diagrams\db\contexts\db-workshop.png" />

### 4.10. Database Design

#### 4.10.1. Relational/Non-Relational Database Diagram

<div>
  <p align="center"><img src="assets/diagrams/db/db.jpeg" alt="db diagram.png" width="700px" /></p>
</div>

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

El proyecto implementa el modelo **GitFlow** para gestionar el flujo de trabajo en los repositorios de la organización [DisExpGrupo](https://github.com/DisExpGrupo).

**Repositorios del Proyecto:**
*   **Landing Page:** [AutoNexo-Landing-Page](https://github.com/DisExpGrupo/AutoNexo-Landing-Page)
*   **Frontend Mobile:** [AutoNexo-Android](https://github.com/DisExpGrupo/AutoNexo-Android)
*   **Backend Service:** [AutoNexo-Backend](https://github.com/DisExpGrupo/AutoNexo-Backend)

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

## 5.2. Product Implementation & Deployment

### 5.2.1. Sprint Backlogs (Continuación)

#### Sprint 3
*   **Sprint Goal:** Finalizar los Bounded Contexts críticos (Offer, Request, Booking, Payment), alcanzar la fidelidad visual total en Android y establecer la paridad funcional multiplataforma con Flutter.
*   **Velocity:** 42 story points.

**Sprint Backlog Table:**
| ID | Title | Estimation (h) | Assigned To | Status | Story Points |
|----|-------|----------------|-------------|--------|--------------|
| US04 | Bounded Context: Offer Management | 5 | Victor Cruz | Done | 5 |
| US05 | Bounded Context: Service Requests | 5 | Santiago Solis | Done | 5 |
| US11 | Bounded Context: Service Booking | 6 | Amir Castro | Done | 8 |
| US15 | Payment & Subscription System | 5 | Miguel Vidal | Done | 5 |
| US17 | Workshop Management (Employees/Invites) | 6 | Alicia Navarro | Done | 8 |
| US18 | UI/UX Final: Auth & Profile (Android) | 4 | Victor Cruz | Done | 5 |
| US19 | Dashboard & Navigation UI (Android) | 3 | Santiago Solis | Done | 3 |
| US20 | Request-Offer Matching Engine | 4 | Amir Castro | Done | 5 |
| FL01 | Flutter Core Implementation | 8 | Miguel Vidal | Done | 8 |

---

### 5.2.5. Implemented Mobile Application Evidence (Sprint 3)

En esta fase, la aplicación alcanzó su estado operativo final, integrando pasarelas de pago y el sistema de matching.

| Funcionalidad | Descripción | Evidencia Visual |
|---------------|-------------|------------------|
| **Autenticación Final** | Flujo de acceso y registro con diseño pulido y validaciones. | ![Login](./assets/ux-ui/chapter-V/Iniciar.png) |
| **Dashboard Principal** | Centro de control con navegación optimizada para el usuario. | ![Home](./assets/ux-ui/chapter-V/Home.png) |
| **Gestión de Perfil** | Configuración completa de datos de usuario y taller. | ![Perfil](./assets/ux-ui/chapter-V/Perfil.png) |
| **Módulo de Pagos** | Sistema de suscripciones para talleres y gestión de pagos. | ![Pagos](./assets/ux-ui/chapter-V/Pagos.png) |

*   **Video de Demostración Final:** [AutoNexo Sprint 3 Demo](https://drive.google.com/drive/folders/1rQoI7fwtVrntl1jeGQ1cc_cXpP7fWdzK?usp=sharing)

---

### 5.2.6. Implemented RESTful API Evidence (Sprint 3)

Se expandió el backend para soportar la lógica de negocio avanzada del ecosistema.

*   **OfferController:** Gestión de presupuestos y propuestas comerciales de talleres.
*   **RequestController:** Centralización de solicitudes de mantenimiento de conductores.
*   **BookingController:** Orquestación de citas y reservas de servicios.
*   **PaymentController:** Procesamiento de transacciones y membresías.
*   **Workshop (Extended):** Control de empleados, activaciones y códigos de invitación.

---

### 5.2.7. RESTful API Documentation & Deployment

La documentación técnica fue actualizada para reflejar los nuevos Bounded Contexts y asegurar la integración con los clientes Android y Flutter.

*   **URL de Swagger UI:** [AutoNexo API Documentation](https://autonexo-backend-zcy7.onrender.com/swagger-ui/index.html#/)
*   **Entorno de Producción:** Render (Oregon. US West).

**Evidencia de Documentación:**
![Swagger](./assets/ux-ui/chapter-V/Swagger1.png)

![Swagger](./assets/ux-ui/chapter-V/Swagger2.png)

![Swagger](./assets/ux-ui/chapter-V/Swagger3.png)

![Swagger](./assets/ux-ui/chapter-V/Swagger4.png)

---

### 5.2.8. Team Collaboration Insights

El equipo operó en un modelo de desarrollo paralelo para cubrir tres frentes: Backend, Android Nativo y Flutter.

*   **Victor Cruz:** Lideró la implementación de **Offer Context** y el diseño de alta fidelidad para los flujos de identidad en Android.
*   **Santiago Solis:** Responsable del **Request Context** y la arquitectura de navegación central de la aplicación móvil.
*   **Alicia Navarro:** Especialista en **Workshop Operations**, desarrollando la lógica de gestión de personal y seguridad de invitaciones.
*   **Miguel Vidal:** Encargado del **Payment Engine** y la implementación de la base de código multiplataforma en Flutter.
*   **Amir Castro:** Desarrolló el **Matching System**, permitiendo la conexión inteligente entre necesidades del usuario y ofertas de talleres.

#### Participación en Repositorios:
| Repositorio | Evidencia de Contribución |
|-------------|---------------------------|
| **Backend** | ![Backend Participation](./assets/ux-ui/chapter-V/Backend.png) |
| **Android** | ![Android Participation](./assets/ux-ui/chapter-V/Android.png) |
| **Flutter** | ![Flutter Participation](./assets/ux-ui/chapter-V/Flutter.png) |

---

### Final Deployment Summary

El proyecto se encuentra desplegado y operativo en los siguientes puntos de acceso:

1.  **API Backend:** [Render](https://autonexo-backend-zcy7.onrender.com/swagger-ui/index.html#/)
2.  **Landing Page:** [Netlify App](https://splendorous-mooncake-980604.netlify.app/)
3.  **App Distribution:** Firebase App Distribution para pruebas Alpha/Beta.

---

## 5.3. Video About-the-Product

**Enlace al video:** [About the Product: https://drive.google.com/file/d/1jgXDsMEV_bvpwjJ2y6HXbz6BG4oDxSfh/view?usp=sharing](https://drive.google.com/file/d/1jgXDsMEV_bvpwjJ2y6HXbz6BG4oDxSfh/view?usp=sharing)

<div style="page-break-after: always;"></div>

# PARTE II: VERIFICATION, VALIDATION & PIPELINE

<div style="page-break-after: always;"></div>

## Capítulo VI: Product Verification & Validation

### 6.1. Testing Suites & Validation

## 6.1.1 Core Entities Unit Tests

En esta sección se documentan las pruebas unitarias del bounded context Workshop, implementadas en la clase `WorkshopDomainUnitTest`. Estas pruebas validan el comportamiento de los aggregates, entities y value objects del dominio de forma aislada, sin depender de base de datos, red ni ningún sistema externo. Cada prueba ejercita directamente las reglas de negocio codificadas en los objetos de dominio.

### Relación de Unit Tests

| Clase bajo prueba | Método de prueba | Comportamiento validado |
|---|---|---|
| Workshop | `createWorkshop_WhenOwnerUserIdIsNull_ShouldThrowIllegalArgumentException` | Se rechaza la creación de un taller si el identificador del propietario es null |
| Workshop | `createWorkshop_WhenNameIsNullOrBlank_ShouldThrowIllegalArgumentException` | Se rechaza la creación si el nombre es null, vacío o solo contiene espacios/tabulaciones (4 casos vía @ParameterizedTest) |
| Workshop | `createWorkshop_WithValidData_ShouldCreateActiveWorkshopWithExpectedInitialState` | Un taller creado con datos válidos arranca activo, sin fotos, sin staff, con estado TRIAL y tier FREE |
| Workshop | `addPhoto_WhenExceedingTenPhotoLimit_ShouldThrowIllegalStateException` | Se rechaza agregar una undécima foto y el contador permanece en 10 |
| Workshop | `isSubscriptionActive_WhenStatusIsTerminated_ShouldReturnFalse` | Una suscripción CANCELLED o EXPIRED se evalúa como inactiva aunque la fecha de vencimiento sea futura (2 casos vía @ParameterizedTest) |
| Workshop | `isSubscriptionActive_WhenExpirationDateHasPassed_ShouldReturnFalse` | Una suscripción con fecha de vencimiento en el pasado se evalúa como inactiva aunque el estado sea ACTIVE |
| Workshop | `isSubscriptionActive_WhenStatusIsActiveWithNoExpiry_ShouldReturnTrue` | Una suscripción ACTIVE sin fecha de vencimiento se evalúa correctamente como activa |
| Workshop | `canAccessPremiumFeatures_WhenTierIsFreeAndSubscriptionIsActive_ShouldReturnFalse` | El tier FREE no concede acceso a funciones premium, aun con suscripción activa |
| Workshop | `canAccessPremiumFeatures_WhenTierIsBasicOrPremiumAndActive_ShouldReturnTrue` | Los tiers BASIC y PREMIUM con suscripción activa conceden acceso a funciones premium (2 casos vía @ParameterizedTest) |
| Workshop | `removeLocation_WhenLocationDoesNotExist_ShouldThrowLocationNotFoundException` | Intentar eliminar una sucursal con ID inexistente lanza LocationNotFoundException |
| Invitation | `markAsUsed_WhenInvitationAlreadyUsed_ShouldThrowIllegalStateException` | Una invitación ya utilizada no puede marcarse como usada por segunda vez |
| Invitation | `markAsUsed_WhenInvitationIsExpired_ShouldThrowIllegalStateException` | Una invitación con fecha de expiración pasada no puede marcarse como usada |
| Invitation | `isForEmail_WhenEmailDiffersByCase_ShouldMatchCaseInsensitively` | La comparación de email en la invitación es insensible a mayúsculas/minúsculas |
| ServiceTemplate | `createServiceTemplate_WhenDurationIsNotPositive_ShouldThrowIllegalArgumentException` | Se rechaza crear una plantilla de servicio con duración 0, negativa o Integer.MIN_VALUE (4 casos vía @ParameterizedTest) |
| BusinessRegistration | `createBusinessRegistration_WhenRucIsInvalid_ShouldThrowIllegalArgumentException` | Se rechazan RUCs null, vacíos, con menos de 11 dígitos, con más de 11 dígitos o con caracteres no numéricos (5 casos vía @ParameterizedTest) |
| OpeningHours | `createOpeningHours_WhenOpeningTimeIsAfterClosingTime_ShouldThrowIllegalArgumentException` | Se rechaza un horario donde la hora de apertura es posterior a la de cierre |
| OpeningHours | `createOpeningHours_WhenOpeningTimeEqualsClosingTime_ShouldThrowIllegalArgumentException` | Se rechaza un horario donde la hora de apertura es igual a la de cierre |

### Evidencia de ejecución

Panel de resultados de `WorkshopDomainUnitTest` mostrando **29 tests passed** con árbol de pruebas expandido. Se aprecia la clase `Workshop BC — Domain Unit Tests` con todos los métodos en verde y el paquete `com.atg.autonexo.backend.workshop.domain` en la barra inferior.

![unit-test-1](assets/images/screenshots/unit-test-1.png)

Árbol expandido mostrando los tests paramétricos desplegados — parte superior. Se aprecian los 4 sub-casos de `createWorkshop_WhenNameIsNullOrBlank` con sus valores: null, "", "   " y "". También se muestran los 2 sub-casos de `canAccessPremiumFeatures_WhenTierIsBasicOrPremium` con Tier BASIC y Tier PREMIUM.

![unit-test-2_1](assets/images/screenshots/unit-test-2.1.png)

Árbol expandido mostrando los tests paramétricos desplegados — parte inferior. Se aprecian los 5 sub-casos de `createBusinessRegistration_WhenRucIsInvalid` con valores: "null", "12345", "123456789012", "ABCDE678901" y "".

![unit-test-2_2](assets/images/screenshots/unit-test-2.2.png)

Código fuente de `WorkshopDomainUnitTest.java` con el método `setUp()` anotado con `@BeforeEach` visible, junto con los comentarios `ES: Riesgo cubierto` y `EN: Risk covered` del primer test. Se aprecia la ruta del archivo en la barra superior del editor.

![unit-test-3](assets/images/screenshots/unit-test-3.png)

### Testing Suite Evidence for Sprint Review

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Commited on |
|---|---|---|---|---|---|
| AutoNexo-Backend | feature/workshop-testing | 082c906 | test(workshop): add unit and integration tests for Workshop bounded context | — | 2026-05-11 |

---

## 6.1.2 Core Integration Tests

En esta sección se documentan las pruebas de integración del bounded context Workshop, implementadas en la clase `WorkshopApplicationIntegrationTest`. A diferencia de las pruebas unitarias, estas validan que los servicios de aplicación (`WorkshopCommandServiceImpl` e `InvitationCommandServiceImpl`) orquestan correctamente la lógica de dominio con las dependencias de infraestructura. Los repositorios, el facade ACL y los servicios externos son sustituidos por mocks de Mockito, permitiendo verificar los flujos completos sin base de datos ni red.

### Relación de Integration Tests

| Servicio bajo prueba | Método de prueba | Comportamiento validado |
|---|---|---|
| WorkshopCommandServiceImpl | `handle_CreateWorkshopCommand_WhenValidNewOwner_ShouldSaveWorkshopAndAssociateUserInAcl` | La creación exitosa de un taller persiste el aggregate en el repositorio y dispara la asociación en el ACL del contexto IAM |
| WorkshopCommandServiceImpl | `handle_CreateWorkshopCommand_WhenOwnerAlreadyHasWorkshop_ShouldThrowAndNeverSave` | Si el propietario ya tiene un taller registrado, se lanza WorkshopAlreadyExistsException sin persistir ni llamar al ACL |
| WorkshopCommandServiceImpl | `handle_CreateWorkshopCommand_WhenAclAssociationFails_ShouldRollbackByDeletingWorkshop` | Si el ACL falla después de persistir el taller, el servicio ejecuta rollback eliminando el taller del repositorio |
| InvitationCommandServiceImpl | `handle_AcceptInvitationCommand_WhenInvitationIsExpired_ShouldThrowIllegalStateException` | El servicio delega en el aggregate Invitation real la verificación de expiración y propaga correctamente la excepción, sin persistir nada |
| InvitationCommandServiceImpl | `handle_AcceptInvitationCommand_WhenValidInvitation_ShouldCreateStaffMemberAndMarkInvitationUsed` | La aceptación de una invitación válida crea un StaffMember en el aggregate Workshop, marca la Invitation como usada y persiste ambos aggregates |

### Evidencia de ejecución

Panel de resultados de `WorkshopApplicationIntegrationTest` mostrando **5 tests passed** en 3 seg 8 ms. Se aprecia el árbol con los 5 métodos de integración con check verde bajo `Workshop BC — Application Integration Tests` y `Process finished with exit code 0` en la consola.

![integration-test-1](assets/images/screenshots/integration-test-1.png)

Ejecución conjunta de todo el bounded context Workshop mostrando **34 tests passed** — vista con árbol completo expandido. Se aprecian ambas clases: `Workshop BC — Application Integration Tests` (5 pruebas) y `Workshop BC — Domain Unit Tests` (29 pruebas), todas en verde.

![integration-test-2_1](assets/images/screenshots/integration-test-2.1.png)

Ejecución conjunta de todo el bounded context Workshop mostrando **34 tests passed** — vista con consola de ejecución visible. Se aprecia el `Process finished with exit code 0` confirmando que todas las pruebas pasaron correctamente.

![integration-test-2_2](assets/images/screenshots/integration-test-2.2.png)

Código fuente de `WorkshopApplicationIntegrationTest.java` mostrando las anotaciones `@Mock` de los repositorios e infraestructura (`WorkshopRepository`, `WorkshopContextFacade`, `InvitationRepository`, `NotificationService`, `UserRepository`, `WorkshopReferenceRepository`) y el método `setUp()` con `@BeforeEach` realizando la inyección manual de dependencias via constructor.

![integration-test-3](assets/images/screenshots/integration-test-3.png)

### Testing Suite Evidence for Sprint Review

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Commited on |
|---|---|---|---|---|---|
| AutoNexo-Backend | feature/workshop-testing | 082c906 | test(workshop): add unit and integration tests for Workshop bounded context | — | 2026-05-11 |


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

La Integración Continua (Continuous Integration - CI) es una práctica de desarrollo de software que permite integrar cambios de código de manera frecuente en un repositorio compartido. Cada integración es verificada automáticamente mediante procesos de compilación, ejecución de pruebas y validaciones, con el objetivo de detectar errores tempranamente y garantizar la estabilidad del sistema.

En el desarrollo del proyecto se emplearon diversas herramientas y metodologías que permitieron automatizar el proceso de construcción y validación del software, mejorando la calidad del código y facilitando el trabajo colaborativo del equipo.

Asimismo, se aplicaron prácticas de Desarrollo Orientado por Comportamiento (BDD) y  Desarrollo Orientado por Pruebas (TDD) y pruebas automatizadas para asegurar que los componentes implementados funcionen correctamente antes de integrarse al entorno principal del proyecto.

<img alt="test img" src="/assets/images/screenshots/devops-ci1.png"/>
<br>
<img alt="test img" src="/assets/images/screenshots/devops-ci2.png"/>

#### 7.1.2. Build & Test Suite Pipeline Components

[Componentes de pipeline]

### 7.2. Continuous Delivery

La Entrega Continua (Continuous Delivery - CD) tiene como objetivo automatizar el proceso de preparación y validación del software para que siempre se encuentre en un estado listo para ser desplegado. Esta práctica permite reducir errores durante las entregas y agilizar la publicación de nuevas funcionalidades, manteniendo un flujo constante y controlado de integración y validación del código.

En el proyecto se implementaron herramientas y prácticas que permitieron automatizar procesos de compilación, pruebas y validaciones previas al despliegue, asegurando la estabilidad del sistema antes de su publicación en entornos de producción.

#### 7.2.1. Tools and Practices

| Herramienta    | Tipo                 | Descripción                                                                                                          | Propósito                                                                                   |
| -------------- | -------------------- | -------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------- |
| GitHub Actions | Automatización CI/CD | Plataforma utilizada para automatizar procesos de compilación, pruebas y validación del proyecto mediante workflows. | Preparar automáticamente el sistema para su despliegue luego de cada integración de código. |
| GitHub         | Control de versiones | Plataforma utilizada para gestionar ramas, pull requests y colaboración entre integrantes del equipo.                | Mantener control y trazabilidad sobre los cambios realizados en el proyecto.                |
| Docker         | Contenedorización    | Herramienta utilizada para empaquetar la aplicación junto con sus dependencias en contenedores portables.            | Garantizar consistencia entre entornos de desarrollo, pruebas y despliegue.                 |
| Trello         | Gestión de proyecto  | Herramienta utilizada para organizar tareas, seguimiento de avances y control del flujo de trabajo.                  | Coordinar aprobaciones y seguimiento del proceso de despliegue.                             |



### Prácticas Implementadas
#### Feature Branching y Pull Requests

Las nuevas funcionalidades y correcciones fueron desarrolladas en ramas independientes, permitiendo trabajar de manera aislada sin afectar la estabilidad de la rama principal. Posteriormente, los cambios eran integrados mediante Pull Requests luego de superar validaciones automáticas y revisiones del equipo.

#### Pipeline de Validación

Cada vez que se realizaba un commit o merge request, el pipeline ejecutaba automáticamente procesos de compilación y pruebas, verificando que el sistema se mantuviera estable y libre de errores antes de continuar con el flujo de entrega.

#### Validación en Entornos de Staging

Antes de un despliegue final, la aplicación podía ser validada en entornos similares a producción, permitiendo realizar pruebas funcionales, revisiones manuales y verificaciones adicionales del comportamiento del sistema.

#### Despliegue Semiautomático

El pipeline automatizaba la preparación del despliegue, incluyendo compilación, validación y generación de artefactos. Sin embargo, el despliegue final requería aprobación manual del equipo responsable, asegurando mayor control sobre las versiones publicadas.

#### Rollback Controlado

En caso de detectar errores críticos posteriores a una actualización, el equipo podía revertir manualmente la versión desplegada para restaurar la estabilidad del sistema.

#### 7.2.2. Stages Deployment Pipeline Components

El pipeline de Continuous Delivery estuvo compuesto por diversas etapas automatizadas que permitieron validar y preparar la aplicación antes de su despliegue.

| Etapa                   | Descripción                                                          | Objetivo                                                     |
| ----------------------- | -------------------------------------------------------------------- | ------------------------------------------------------------ |
| Source Control          | Gestión del código mediante ramas y repositorios Git.                | Facilitar el trabajo colaborativo y el control de versiones. |
| Build Stage             | Compilación automática del proyecto luego de cada integración.       | Detectar errores de compilación tempranamente.               |
| Automated Testing       | Ejecución de pruebas unitarias y pruebas automatizadas.              | Validar el correcto funcionamiento del sistema.              |
| Staging Validation      | Validación del sistema en un entorno similar a producción.           | Realizar pruebas finales antes del despliegue.               |
| Deployment Approval     | Aprobación manual previa al despliegue final.                        | Asegurar control y supervisión sobre las entregas.           |
| Deployment Preparation  | Generación y empaquetado de artefactos desplegables.                 | Mantener la aplicación lista para producción.                |
| Monitoring and Feedback | Supervisión básica del comportamiento del sistema tras validaciones. | Detectar posibles errores o problemas de rendimiento.        |


### 7.3. Continuous Deployment

El Despliegue Continuo (Continuous Deployment) permite automatizar la publicación de nuevas versiones del sistema hacia producción una vez que las validaciones y pruebas han sido superadas satisfactoriamente. Esta práctica reduce la intervención manual durante el despliegue, mejora la rapidez de entrega y disminuye la probabilidad de errores humanos.

En el proyecto se implementaron diversas herramientas y prácticas orientadas a automatizar el despliegue del backend, frontend y servicios asociados, asegurando estabilidad, disponibilidad y consistencia entre entornos.

#### 7.3.1. Tools and Practices

| Herramienta      | Tipo                            | Descripción                                                                                               | Propósito                                                                           |
| ---------------- | ------------------------------- | --------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------- |
| GitHub Actions   | Automatización CI/CD            | Plataforma utilizada para ejecutar workflows automáticos de integración, pruebas y despliegue.            | Automatizar el pipeline completo de construcción y despliegue del sistema.          |
| Docker           | Contenedorización               | Herramienta utilizada para empaquetar la aplicación backend junto con sus dependencias.                   | Garantizar consistencia entre entornos de desarrollo y producción.                  |
| Railway          | Plataforma de base de datos     | Servicio utilizado para alojar y gestionar la base de datos MySQL del proyecto.                           | Facilitar migraciones, backups y disponibilidad del servicio de base de datos.      |
| Render           | Hosting backend                 | Plataforma utilizada para desplegar automáticamente el backend desarrollado con Spring Boot.              | Gestionar el despliegue y monitoreo continuo del backend.                           |
| Firebase Hosting | Hosting frontend                | Servicio utilizado para desplegar la aplicación frontend y distribuir contenido de forma segura y rápida. | Automatizar la publicación de la aplicación web en producción.                      |
| Netlify          | Hosting frontend y landing page | Plataforma utilizada para desplegar la landing page del proyecto.                                         | Facilitar despliegues rápidos y automatizados de la página informativa del sistema. |

### Prácticas Implementadas
#### Feature Branching

El equipo utilizó una estrategia de ramas basada en Git, donde cada funcionalidad o corrección era desarrollada en ramas independientes. Posteriormente, los cambios eran integrados a ramas principales mediante procesos de revisión y validación.

#### Commit-Based Deployment

Cada vez que se realizaba un commit o merge hacia la rama principal de integración, el pipeline CI/CD se ejecutaba automáticamente, iniciando procesos de compilación, pruebas y despliegue del sistema.

#### Despliegue Automatizado

Una vez superadas las pruebas automáticas, las plataformas de hosting desplegaban automáticamente las nuevas versiones del backend y frontend, reduciendo tiempos de entrega y errores manuales.

#### Rollback Controlado

En caso de detectarse errores críticos posteriores al despliegue, el sistema permitía restaurar versiones previas de manera controlada para garantizar la continuidad del servicio.

#### Monitoreo Posterior al Despliegue

Después de cada despliegue, las plataformas utilizadas proporcionaban herramientas de monitoreo y verificación para detectar posibles fallos de rendimiento o disponibilidad.

#### 7.3.2. Production Deployment Pipeline Components

El pipeline de despliegue en producción estuvo compuesto por distintos componentes encargados de automatizar la actualización del backend, frontend y base de datos del sistema.

#### Componentes del Pipeline de Base de Datos (Railway)

| Componente                 | Descripción                                                                                                                         |
| -------------------------- | ----------------------------------------------------------------------------------------------------------------------------------- |
| Gestión de Migraciones     | Spring Boot gestionaba automáticamente las migraciones y sincronización de entidades con la base de datos MySQL alojada en Railway. |
| Backup Automático          | Railway realizaba copias de seguridad automáticas antes de aplicar cambios críticos en la base de datos.                            |
| Monitoreo de Base de Datos | La plataforma permitía supervisar el estado y rendimiento de la base de datos en tiempo real.                                       |
| Validación de Esquema      | Se verificaba que las migraciones aplicadas mantuvieran correctamente la estructura y relaciones de la base de datos.               |
| Actualización Continua     | Los cambios aprobados eran reflejados automáticamente en el entorno de producción.                                                  |

<img alt="railway" src="/assets/logos/railway-logo.png"/>

#### Componentes del Pipeline del Backend (Render + Spring Boot)

| Componente            | Descripción                                                                              |
| --------------------- | ---------------------------------------------------------------------------------------- |
| Integración Continua  | Render obtenía automáticamente el código actualizado desde el repositorio remoto.        |
| Build del Backend     | El proyecto Spring Boot era compilado utilizando Maven.                                  |
| Construcción Docker   | Se generaba automáticamente una imagen Docker del backend con todas sus dependencias.    |
| Despliegue Automático | Render desplegaba la nueva versión del backend en producción.                            |
| Monitoreo y Alertas   | La plataforma supervisaba el estado del servicio y notificaba posibles errores o caídas. |

<img alt="render" src="/assets/logos/render-logo.png"/>

#### Componentes del Pipeline del Frontend (Firebase Hosting)

| Componente            | Descripción                                                                                          |
| --------------------- | ---------------------------------------------------------------------------------------------------- |
| Compilación Frontend  | La aplicación Angular era compilada automáticamente en modo producción.                              |
| Ejecución de Pruebas  | Se ejecutaban pruebas automatizadas para validar el correcto funcionamiento de la interfaz.          |
| Despliegue Automático | Firebase Hosting publicaba automáticamente la nueva versión del frontend.                            |
| Distribución CDN      | El contenido era distribuido mediante una red CDN para mejorar el rendimiento global.                |
| Invalidación de Caché | Firebase actualizaba automáticamente la caché para garantizar acceso a la última versión disponible. |

<img alt="firebase" src="/assets/logos/firebase-logo.png"/>

#### Componentes del Pipeline de Landing Page (Netlify)

| Componente          | Descripción                                                                                    |
| ------------------- | ---------------------------------------------------------------------------------------------- |
| Build Automático    | Netlify compilaba automáticamente la landing page luego de detectar cambios en el repositorio. |
| Despliegue Continuo | La landing page era publicada automáticamente en producción.                                   |
| CDN Global          | Netlify distribuía el contenido mediante una red CDN para optimizar tiempos de carga.          |
| Monitoreo Básico    | La plataforma permitía verificar el estado y disponibilidad de la página desplegada.           |

<img alt="netlify" src="/assets/logos/netlify-logo.png"/>

### 7.4. Continuous Monitoring

El Monitoreo Continuo (Continuous Monitoring) permite supervisar constantemente el comportamiento y rendimiento de la aplicación luego de su despliegue. Su objetivo principal es detectar errores, degradaciones de rendimiento o problemas de disponibilidad de manera temprana, garantizando una experiencia estable y confiable para los usuarios.

Para el desarrollo del proyecto se emplearon diversas herramientas y prácticas orientadas al análisis del rendimiento, supervisión de servicios, monitoreo de experiencia de usuario y generación de alertas automáticas.

#### 7.4.1. Tools and Practices

Con el fin de mantener un monitoreo eficiente de la aplicación y de sus distintos componentes, se utilizaron herramientas especializadas para análisis de rendimiento, supervisión de APIs y evaluación de experiencia de usuario.

| Herramienta       | Tipo                               | Descripción                                                                                     | Propósito                                                                  |
| ----------------- | ---------------------------------- | ----------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------- |
| Apache JMeter     | Pruebas de carga y estrés          | Herramienta utilizada para simular múltiples usuarios y escenarios de alta demanda.             | Evaluar la estabilidad y rendimiento del sistema bajo cargas elevadas.     |
| Google Analytics  | Analítica y experiencia de usuario | Plataforma utilizada para recopilar métricas de navegación e interacción de usuarios.           | Analizar el comportamiento de usuarios y mejorar la experiencia de uso.    |
| Datadog           | Monitoreo de rendimiento           | Servicio de monitoreo en tiempo real que permite supervisar métricas de rendimiento y latencia. | Detectar problemas de rendimiento y monitorear la experiencia del usuario. |
| Postman           | Supervisión de APIs                | Herramienta utilizada para validar y monitorear endpoints y servicios REST.                     | Verificar disponibilidad y correcto funcionamiento de APIs.                |
| Pingdom           | Monitoreo de disponibilidad        | Plataforma utilizada para monitorear tiempos de respuesta y disponibilidad del sistema.         | Detectar interrupciones o degradaciones del servicio.                      |
| Google Lighthouse | Auditoría de calidad web           | Herramienta utilizada para evaluar rendimiento, accesibilidad y buenas prácticas web.           | Mejorar la calidad general y optimización de la aplicación web.            |
| Catchpoint        | Monitoreo de experiencia digital   | Plataforma enfocada en medir experiencia de usuario desde distintas ubicaciones y dispositivos. | Analizar rendimiento y disponibilidad en diferentes entornos.              |


#### 7.4.2. Monitoring Pipeline Components

El pipeline de monitoreo implementado estuvo conformado por diferentes etapas orientadas a recopilar, analizar y visualizar información relacionada con el estado y rendimiento del sistema.

| Componente                          | Descripción                                                                                          |
| ----------------------------------- | ---------------------------------------------------------------------------------------------------- |
| Recolección de Métricas             | Obtención automática de datos de rendimiento, tiempos de respuesta y uso de recursos.                |
| Monitoreo de Experiencia de Usuario | Supervisión del comportamiento de navegación y tiempos de carga experimentados por usuarios finales. |
| Supervisión de APIs                 | Verificación continua de disponibilidad y funcionamiento de servicios y endpoints REST.              |
| Auditoría de Calidad Web            | Evaluación de rendimiento, accesibilidad, SEO y buenas prácticas de la aplicación web.               |
| Visualización de Datos              | Presentación de métricas y estadísticas mediante paneles de monitoreo en tiempo real.                |
| Detección de Problemas              | Identificación temprana de errores, cuellos de botella y degradaciones de rendimiento.               |

Además, herramientas como Google Lighthouse permitieron realizar auditorías periódicas para evaluar la optimización de la interfaz web, mientras que Catchpoint proporcionó monitoreo desde diferentes ubicaciones geográficas y dispositivos para garantizar una experiencia consistente para los usuarios.

#### 7.4.3. Alerting Pipeline Components

El sistema de alertas constituye un componente fundamental dentro del monitoreo continuo, ya que permite detectar incidentes y notificar al equipo de desarrollo de manera inmediata ante posibles fallos o anomalías.

Para la implementación de alertas automáticas se consideraron herramientas especializadas de monitoreo y visualización.

| Herramienta  | Funcionalidad                                                             |
| ------------ | ------------------------------------------------------------------------- |
| Prometheus   | Recolección y almacenamiento de métricas de rendimiento en tiempo real.   |
| Alertmanager | Gestión, agrupamiento y distribución de alertas generadas por Prometheus. |
| Grafana      | Visualización avanzada de métricas y configuración de alertas visuales.   |

El sistema de alertas fue configurado para detectar situaciones críticas como:

- Alto consumo de CPU o memoria.
- Incremento excesivo de latencia.
- Caídas de servicios o APIs.
- Fallos durante despliegues o ejecuciones automáticas.
- Problemas de disponibilidad del sistema.

Asimismo, las alertas podían ser enviadas mediante distintos canales de comunicación para permitir una respuesta rápida ante incidentes y reducir tiempos de inactividad.

#### 7.4.4. Notification Pipeline Components

El pipeline de notificaciones permitió informar automáticamente al equipo sobre el estado de las ejecuciones del pipeline, resultados de pruebas y eventos importantes relacionados con la calidad del software.

| Componente              | Descripción                                                               |
| ----------------------- | ------------------------------------------------------------------------- |
| Notificaciones de Build | Avisos automáticos sobre éxito o fallo de compilaciones.                  |
| Reportes de Ejecución   | Generación de resúmenes con resultados de pruebas y validaciones.         |
| Alertas de Incidentes   | Notificaciones relacionadas con errores críticos o fallos de despliegue.  |
| Seguimiento de Pipeline | Supervisión continua del estado de workflows y tareas automatizadas.      |
| Comunicación del Equipo | Distribución de información relevante hacia los integrantes del proyecto. |

Herramientas como Jenkins permitieron automatizar el envío de notificaciones luego de cada ejecución del pipeline, proporcionando información detallada sobre errores detectados, tiempos de ejecución y estado general de las pruebas.

De esta manera, el equipo pudo responder rápidamente ante incidentes y mantener un seguimiento continuo de la calidad y estabilidad del sistema.


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

### Conclusiones y Recomendaciones

## Conclusiones

El desarrollo de Autonexo permite evidenciar el impacto positivo de la transformación digital en sectores tradicionales como el automotriz, donde aún existe una baja adopción de herramientas tecnológicas. A través de la implementación de una plataforma centralizada, se logra mejorar significativamente la conexión entre propietarios de vehículos y mecánicos, optimizando la búsqueda, selección y gestión de servicios de mantenimiento.

Se concluye que la solución propuesta cumple un rol importante como intermediario digital, reduciendo las fricciones existentes en el mercado de servicios automotrices y mejorando la eficiencia del proceso de contratación. Además, la plataforma contribuye a la transparencia del servicio al permitir la evaluación de mecánicos, la gestión de solicitudes en tiempo real y el registro del historial de mantenimiento de los vehículos.

Desde una perspectiva operativa, Autonexo demuestra que la digitalización de procesos puede generar mejoras en la eficiencia tanto para usuarios como para proveedores de servicio. Para los mecánicos, la posibilidad de gestionar su agenda digitalmente y recibir solicitudes en tiempo real permite una mejor organización del trabajo, mayor aprovechamiento del tiempo y potencial incremento de ingresos. Para los usuarios, la plataforma reduce tiempos de búsqueda, mejora la toma de decisiones y aumenta la confianza en el servicio contratado.

Asimismo, la incorporación del historial de mantenimiento representa un valor agregado importante, ya que permite una gestión preventiva del vehículo. Esto no solo contribuye a la reducción de fallas inesperadas, sino que también optimiza los costos a largo plazo asociados al mantenimiento vehicular. En este sentido, el sistema se alinea con tendencias actuales de mantenimiento predictivo y digitalización de activos.

En términos generales, el proyecto demuestra que existe una oportunidad clara para la modernización del sector automotriz en América Latina, donde la adopción tecnológica aún es limitada. Autonexo aporta una solución viable que responde a esta necesidad, integrando tecnologías modernas como plataformas web, móviles y servicios en la nube.

## Recomendaciones

A partir del desarrollo y análisis del sistema, se proponen las siguientes recomendaciones para la mejora y evolución futura del proyecto:

Implementar un sistema de calificación y reputación más avanzado, basado en métricas como puntualidad, calidad del servicio y tasa de respuesta, con el fin de mejorar la confianza dentro de la plataforma.
Integrar un sistema de pagos en línea seguro que permita cerrar el ciclo completo del servicio dentro de la aplicación, reduciendo la dependencia de procesos externos y mejorando la experiencia del usuario.
Incorporar algoritmos de recomendación basados en datos, que sugieran mecánicos según historial del usuario, tipo de vehículo, ubicación y comportamiento previo dentro de la plataforma.
Escalar la arquitectura del sistema para soportar un mayor volumen de usuarios concurrentes, considerando el crecimiento progresivo de la plataforma en entornos productivos.
Mejorar el sistema de notificaciones en tiempo real para optimizar la comunicación entre mecánicos y usuarios, asegurando una respuesta más rápida a las solicitudes de servicio.
Implementar analítica de datos para identificar patrones de fallas vehiculares, permitiendo evolucionar hacia un sistema de mantenimiento predictivo más robusto.
Fortalecer la seguridad de la plataforma mediante autenticación multifactor, control de roles y protección de APIs para garantizar la integridad de la información.
Expandir la cobertura geográfica del servicio, con el objetivo de aumentar la disponibilidad de mecánicos y mejorar la accesibilidad en distintas regiones.

## Bibliografía

Innocar & Roshfrans. (2024). *Adopción de software en talleres mecánicos en América Latina*.

WorldMetrics. (2026). *Automotive Aftermarket Digital Transformation Statistics*. https://worldmetrics.org/digital-transformation-in-the-automotive-aftermarket-industry-statistics/

Gitnux. (2026). *Digital Transformation Automotive Report*. https://gitnux.org/digital-transformation-in-the-automotive-aftermarket-industry-statistics/

Rochet, J. C., & Tirole, J. (2003). Platform competition in two-sided markets. *Journal of the European Economic Association*, 1(4), 990–1029. https://doi.org/10.1162/154247603322493212

Porter, M. E., & Heppelmann, J. E. (2014). How smart, connected products are transforming competition. *Harvard Business Review*, 92(11), 64–88.

International Organization for Standardization. (2022). *ISO 55000: Asset management — Overview, principles and terminology*. https://www.iso.org/standard/55088.html

<div style="page-break-after: always;"></div>

## Anexos
