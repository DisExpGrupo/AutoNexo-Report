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
    <td>Navarro Chang, Alicia Avril </td>
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
| 1.0 | [Fecha] | [Autor] | Versión inicial |

<div style="page-break-after: always;"></div>

## Project Report Collaboration Insights

[Insertar insights de colaboración]

<div style="page-break-after: always;"></div>

## Contenido

- [ **Carátula** ](#carátula)
- [ **Registro de Versiones del Informe** ](#registro-de-versiones-del-informe)
- [ **Project Report Collaboration Insights** ](#project-report-collaboration-insights)
- [ **Contenido** ](#contenido)
- [ **Student Outcome** ](#student-outcome)
- [ **Part I: As-Is Software Project** ](#part-i-as-is-software-project)
    - [**Capítulo I: Introducción**](#capítulo-i-introducción)
        - [**1.1. Startup Profile**](#11-startup-profile)
            - [**1.1.1. Descripción de la Startup**](#111-descripción-de-la-startup)
            - [**1.1.2. Perfiles de integrantes del equipo**](#112-perfiles-de-integrantes-del-equipo)
        - [**1.2. Solution Profile**](#12-solution-profile)
            - [**1.2.1. Antecedentes y problemática**](#121-antecedentes-y-problemática)
            - [**1.2.2. Lean UX Process**](#122-lean-ux-process)
                - [**1.2.2.1. Lean UX Problem Statements**](#1221-lean-ux-problem-statements)
                - [**1.2.2.2. Lean UX Assumptions**](#1222-lean-ux-assumptions)
                - [**1.2.2.3. Lean UX Hypothesis Statements**](#1223-lean-ux-hypothesis-statements)
                - [**1.2.2.4. Lean UX Canvas**](#1224-lean-ux-canvas)
            - [**1.3. Segmentos objetivo**](#13-segmentos-objetivo)
    - [**Capítulo II: Requirements Elicitation & Analysis**](#capítulo-ii-requirements-elicitation--analysis)
        - [**2.1. Competidores**](#21-competidores)
            - [**2.1.1. Análisis competitivo**](#211-análisis-competitivo)
            - [**2.1.2. Estrategias y tácticas frente a competidores**](#212-estrategias-y-tácticas-frente-a-competidores)
        - [**2.2. Entrevistas**](#22-entrevistas)
            - [**2.2.1. Diseño de entrevistas**](#221-diseño-de-entrevistas)
            - [**2.2.2. Registro de entrevistas**](#222-registro-de-entrevistas)
            - [**2.2.3. Análisis de entrevistas**](#223-análisis-de-entrevistas)
        - [**2.3. Needfinding**](#23-needfinding)
            - [**2.3.1. User Personas**](#231-user-personas)
            - [**2.3.2. User Task Matrix**](#232-user-task-matrix)
            - [**2.3.3. User Journey Mapping**](#233-user-journey-mapping)
            - [**2.3.4. Empathy Mapping**](#234-empathy-mapping)
            - [**2.3.5. As-is Scenario Mapping**](#235-as-is-scenario-mapping)
        - [**2.4. Ubiquitous Language**](#24-ubiquitous-language)
    - [**Capítulo III: Requirements Specification**](#capítulo-iii-requirements-specification)
        - [**3.1. To-Be Scenario Mapping**](#31-to-be-scenario-mapping)
        - [**3.2. User Stories**](#32-user-stories)
        - [**3.3. Product Backlog**](#33-product-backlog)
        - [**3.4. Impact Mapping**](#34-impact-mapping)
    - [**Capítulo IV: Product Design**](#capítulo-iv-product-design)
        - [**4.1. Style Guidelines**](#41-style-guidelines)
            - [**4.1.1. General Style Guidelines**](#411-general-style-guidelines)
            - [**4.1.2. Web Style Guidelines**](#412-web-style-guidelines)
            - [**4.1.3. Mobile Style Guidelines**](#413-mobile-style-guidelines)
                - [**4.1.3.1. iOS Mobile Style Guidelines**](#4131-ios-mobile-style-guidelines)
                - [**4.1.3.2. Android Mobile Style Guidelines**](#4132-android-mobile-style-guidelines)
        - [**4.2. Information Architecture**](#42-information-architecture)
            - [**4.2.1. Organization Systems**](#421-organization-systems)
            - [**4.2.2. Labeling Systems**](#422-labeling-systems)
            - [**4.2.3. SEO Tags and Meta Tags**](#423-seo-tags-and-meta-tags)
            - [**4.2.4. Searching Systems**](#424-searching-systems)
            - [**4.2.5. Navigation Systems**](#425-navigation-systems)
        - [**4.3. Landing Page UI Design**](#43-landing-page-ui-design)
            - [**4.3.1. Landing Page Wireframe**](#431-landing-page-wireframe)
            - [**4.3.2. Landing Page Mock-up**](#432-landing-page-mock-up)
        - [**4.4. Mobile Applications UX/UI Design**](#44-mobile-applications-uxui-design)
            - [**4.4.1. Mobile Applications Wireframes**](#441-mobile-applications-wireframes)
            - [**4.4.2. Mobile Applications Wireflow Diagrams**](#442-mobile-applications-wireflow-diagrams)
            - [**4.4.3. Mobile Applications Mock-ups**](#443-mobile-applications-mock-ups)
            - [**4.4.4. Mobile Applications User Flow Diagrams**](#444-mobile-applications-user-flow-diagrams)
        - [**4.5. Mobile Applications Prototyping**](#45-mobile-applications-prototyping)
            - [**4.5.1. Android Mobile Applications Prototyping**](#451-android-mobile-applications-prototyping)
            - [**4.5.2. iOS Mobile Applications Prototyping**](#452-ios-mobile-applications-prototyping)
        - [**4.6. Web Applications UX/UI Design**](#46-web-applications-uxui-design)
            - [**4.6.1. Web Applications Wireframes**](#461-web-applications-wireframes)
            - [**4.6.2. Web Applications Wireflow Diagrams**](#462-web-applications-wireflow-diagrams)
            - [**4.6.3. Web Applications Mock-ups**](#463-web-applications-mock-ups)
            - [**4.6.4. Web Applications User Flow Diagrams**](#464-web-applications-user-flow-diagrams)
        - [**4.7. Web Applications Prototyping**](#47-web-applications-prototyping)
        - [**4.8. Domain-Driven Software Architecture**](#48-domain-driven-software-architecture)
            - [**4.8.1. Software Architecture Context Diagram**](#481-software-architecture-context-diagram)
            - [**4.8.2. Software Architecture Container Diagrams**](#482-software-architecture-container-diagrams)
            - [**4.8.3. Software Architecture Components Diagrams**](#483-software-architecture-components-diagrams)
        - [**4.9. Software Object-Oriented Design**](#49-software-object-oriented-design)
            - [**4.9.1. Class Diagrams**](#491-class-diagrams)
            - [**4.9.2. Class Dictionary**](#492-class-dictionary)
        - [**4.10. Database Design**](#410-database-design)
            - [**4.10.1. Relational/Non-Relational Database Diagram**](#4101-relationalnon-relational-database-diagram)
    - [**Capítulo V: Product Implementation**](#capítulo-v-product-implementation)
        - [**5.1. Software Configuration Management**](#51-software-configuration-management)
            - [**5.1.1. Software Development Environment Configuration**](#511-software-development-environment-configuration)
            - [**5.1.2. Source Code Management**](#512-source-code-management)
            - [**5.1.3. Source Code Style Guide & Conventions**](#513-source-code-style-guide--conventions)
            - [**5.1.4. Software Deployment Configuration**](#514-software-deployment-configuration)
        - [**5.2. Product Implementation & Deployment**](#52-product-implementation--deployment)
            - [**5.2.1. Sprint Backlogs**](#521-sprint-backlogs)
            - [**5.2.2. Implemented Landing Page Evidence**](#522-implemented-landing-page-evidence)
            - [**5.2.3. Implemented Frontend-Web Application Evidence**](#523-implemented-frontend-web-application-evidence)
            - [**5.2.4. Acuerdo de Servicio - SaaS**](#524-acuerdo-de-servicio---saas)
            - [**5.2.5. Implemented Native-Mobile Application Evidence**](#525-implemented-native-mobile-application-evidence)
            - [**5.2.6. Implemented RESTful API and/or Serverless Backend Evidence**](#526-implemented-restful-api-andor-serverless-backend-evidence)
            - [**5.2.7. RESTful API documentation**](#527-restful-api-documentation)
            - [**5.2.8. Team Collaboration Insights**](#528-team-collaboration-insights)
        - [**5.3. Video About-the-Product**](#53-video-about-the-product)
    - [**Part II: Verification, Validation & Pipeline**](#part-ii-verification-validation--pipeline)
    - [**Capítulo VI: Product Verification & Validation**](#capítulo-vi-product-verification--validation)
        - [**6.1. Testing Suites & Validation**](#61-testing-suites--validation)
            - [**6.1.1. Core Entities Unit Tests**](#611-core-entities-unit-tests)
            - [**6.1.2. Core Integration Tests**](#612-core-integration-tests)
            - [**6.1.3. Core Behavior-Driven Development**](#613-core-behavior-driven-development)
            - [**6.1.4. Core System Tests**](#614-core-system-tests)
        - [**6.2. Static testing & Verification**](#62-static-testing--verification)
            - [**6.2.1. Static Code Analysis**](#621-static-code-analysis)
                - [**6.2.1.1. Coding standard & Code conventions**](#6211-coding-standard--code-conventions)
                - [**6.2.1.2. Code Quality & Code Security**](#6212-code-quality--code-security)
            - [**6.2.2. Reviews**](#622-reviews)
        - [**6.3. Validation Interviews**](#63-validation-interviews)
            - [**6.3.1. Diseño de Entrevistas**](#631-diseño-de-entrevistas)
            - [**6.3.2. Registro de Entrevistas**](#632-registro-de-entrevistas)
            - [**6.3.3. Evaluaciones según heurísticas**](#633-evaluaciones-según-heurísticas)
        - [**6.4. Auditoría de Experiencias de Usuario**](#64-auditoría-de-experiencias-de-usuario)
            - [**6.4.1. Auditoría realizada**](#641-auditoría-realizada)
                - [**6.4.1.1. Información del grupo auditado**](#6411-información-del-grupo-auditado)
                - [**6.4.1.2. Cronograma de auditoría realizada**](#6412-cronograma-de-auditoría-realizada)
                - [**6.4.1.3. Contenido de auditoría realizada**](#6413-contenido-de-auditoría-realizada)
            - [**6.4.2. Auditoría recibida**](#642-auditoría-recibida)
                - [**6.4.2.1. Información del grupo auditor**](#6421-información-del-grupo-auditor)
                - [**6.4.2.2. Cronograma de auditoría recibida**](#6422-cronograma-de-auditoría-recibida)
                - [**6.4.2.3. Contenido de auditoría recibida**](#6423-contenido-de-auditoría-recibida)
                - [**6.4.2.4. Resumen de modificaciones para subsanar hallazgos**](#6424-resumen-de-modificaciones-para-subsanar-hallazgos)
    - [**Capítulo VII: DevOps Practices**](#capítulo-vii-devops-practices)
        - [**7.1. Continuous Integration**](#71-continuous-integration)
            - [**7.1.1. Tools and Practices**](#711-tools-and-practices)
            - [**7.1.2. Build & Test Suite Pipeline Components**](#712-build--test-suite-pipeline-components)
        - [**7.2. Continuous Delivery**](#72-continuous-delivery)
            - [**7.2.1. Tools and Practices**](#721-tools-and-practices)
            - [**7.2.2. Stages Deployment Pipeline Components**](#722-stages-deployment-pipeline-components)
        - [**7.3. Continuous deployment**](#73-continuous-deployment)
            - [**7.3.1. Tools and Practices**](#731-tools-and-practices)
            - [**7.3.2. Production Deployment Pipeline Components**](#732-production-deployment-pipeline-components)
        - [**7.4. Continuous Monitoring**](#74-continuous-monitoring)
            - [**7.4.1. Tools and Practices**](#741-tools-and-practices)
            - [**7.4.2. Monitoring Pipeline Components**](#742-monitoring-pipeline-components)
            - [**7.4.3. Alerting Pipeline Components**](#743-alerting-pipeline-components)
            - [**7.4.4. Notification Pipeline Components**](#744-notification-pipeline-components)
    - [**Part III: Experiment-Driven Lifecycle**](#part-iii-experiment-driven-lifecycle)
    - [**Capítulo VIII: Experiment-Driven Development**](#capítulo-viii-experiment-driven-development)
        - [**8.1. Experiment Planning**](#81-experiment-planning)
            - [**8.1.1. As-Is Summary**](#811-as-is-summary)
            - [**8.1.2. Raw Material: Assumptions, Knowledge Gaps, Ideas, Claims**](#812-raw-material-assumptions-knowledge-gaps-ideas-claims)
            - [**8.1.3. Experiment-Ready Questions**](#813-experiment-ready-questions)
            - [**8.1.4. Question Backlog**](#814-question-backlog)
            - [**8.1.5. Experiment Cards**](#815-experiment-cards)
        - [**8.2. Experiment Design**](#82-experiment-design)
            - [**8.2.1. Hypotheses**](#821-hypotheses)
            - [**8.2.2. Domain Business Metrics**](#822-domain-business-metrics)
            - [**8.2.3. Measures**](#823-measures)
            - [**8.2.4. Conditions**](#824-conditions)
            - [**8.2.5. Scale Calculations and Decisions**](#825-scale-calculations-and-decisions)
            - [**8.2.6. Methods Selection**](#826-methods-selection)
            - [**8.2.7. Data Analytics: Goals, KPIs and Metrics Selection**](#827-data-analytics-goals-kpis-and-metrics-selection)
            - [**8.2.8. Web and Mobile Tracking Plan**](#828-web-and-mobile-tracking-plan)
        - [**8.3. Experimentation**](#83-experimentation)
            - [**8.3.1. To-Be User Stories**](#831-to-be-user-stories)
            - [**8.3.2. To-Be Product Backlog**](#832-to-be-product-backlog)
            - [**8.3.3. Pipeline-supported, Experiment-Driven To-Be Software Platform Lifecycle**](#833-pipeline-supported-experiment-driven-to-be-software-platform-lifecycle)
                - [**8.3.3.1. To-Be Sprint Backlogs**](#8331-to-be-sprint-backlogs)
                - [**8.3.3.2. Implemented To-Be Landing Page Evidence**](#8332-implemented-to-be-landing-page-evidence)
                - [**8.3.3.3. Implemented To-Be Frontend-Web Application Evidence**](#8333-implemented-to-be-frontend-web-application-evidence)
                - [**8.3.3.4. Implemented To-Be Native-Mobile Application Evidence**](#8334-implemented-to-be-native-mobile-application-evidence)
                - [**8.3.3.5. Implemented To-Be RESTful API and/or Serverless Backend Evidence**](#8335-implemented-to-be-restful-api-andor-serverless-backend-evidence)
                - [**8.3.3.6. Team Collaboration Insights**](#8336-team-collaboration-insights)
            - [**8.3.4. To-Be Validation Interviews**](#834-to-be-validation-interviews)
                - [**8.3.4.1. Diseño de Entrevistas**](#8341-diseño-de-entrevistas)
                - [**8.3.4.2. Registro de Entrevistas**](#8342-registro-de-entrevistas)
        - [**8.4. Experiment Aftermath & Analysis**](#84-experiment-aftermath--analysis)
            - [**8.4.1. Analysis and Interpretation of Results**](#841-analysis-and-interpretation-of-results)
            - [**8.4.2. Re-scored and Re-prioritized Question Backlog**](#842-re-scored-and-re-prioritized-question-backlog)
        - [**8.5. Continuous Learning**](#85-continuous-learning)
            - [**8.5.1. Shareback Session Artifacts: Learning Workflow**](#851-shareback-session-artifacts-learning-workflow)
        - [**8.6. To-Be Software Platform Pre-launch**](#86-to-be-software-platform-pre-launch)
            - [**8.6.1. About-the-Product Intro Video**](#861-about-the-product-intro-video)
    - [**Conclusiones**](#conclusiones)
        - [**Conclusiones y recomendaciones**](#conclusiones-y-recomendaciones)
        - [**Video App Validation**](#video-app-validation)
        - [**Video About-the-Team**](#video-about-the-team)
    - [**Bibliografía**](#bibliografía)
    - [**Anexos**](#anexos)

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

[Descripción general del startup]

#### 1.1.2. Perfiles de Integrantes del Equipo

[Perfiles de los integrantes]

### 1.2. Solution Profile

#### 1.2.1. Antecedentes y Problemática

[Antecedentes y descripción de la problemática]

#### 1.2.2. Lean UX Process

##### 1.2.2.1. Lean UX Problem Statements

[Declaraciones de problemas Lean UX]

##### 1.2.2.2. Lean UX Assumptions

[Supuestos Lean UX]

##### 1.2.2.3. Lean UX Hypothesis Statements

[Hipótesis Lean UX]

##### 1.2.2.4. Lean UX Canvas

[Canvas Lean UX]

### 1.3. Segmentos Objetivo

[Descripción de los segmentos objetivo]

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

## Capítulo V: Product Implementation

### 5.1. Software Configuration Management

#### 5.1.1. Software Development Environment Configuration

[Configuración del entorno de desarrollo]

#### 5.1.2. Source Code Management

[Gestión del código fuente]

#### 5.1.3. Source Code Style Guide & Conventions

[Guía de estilo de código]

#### 5.1.4. Software Deployment Configuration

[Configuración de despliegue]

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
