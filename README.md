# Process Control Across 7 Diaper and Training Pants Production Lines
 
🌐 [English](#english) | [Español](#español)
 
---
 
<a name="english"></a>
## 🇬🇧 English
 
Digitization and monitoring of process audits for a manufacturing operation, using Google Sheets, Google Apps Script, and Power BI.
 
### 1. Context / Problem
This project was developed for the **Production and Quality areas** at **Softys**, a manufacturing company. Process audits across 7 production lines were being performed on paper, which was:
 
- Prone to human error
- Difficult to trace (no historical record of who audited what, when)
- Impossible to monitor in real time
- Tedious and time-consuming for operators and auditors
The objective was to eliminate the paper-based process and replace it with a digital system that would provide traceability, real-time visibility, and easier detection of process anomalies.
 
### 2. My Contribution
I was responsible for the full scope of the work, from designing the digital audit forms to building the final monitoring dashboards — including data architecture, automation, data cleaning, and visualization.
 
### 3. Process and Decisions
- **Design:** I standardized the audit form design in Google Sheets to keep the experience simple and tablet-friendly for shop-floor operators, prioritizing ease of use over a more complex custom app, since the goal was fast adoption across 7 lines.
- **Digitalization:** I built a centralized, real-time database and used Google Apps Script to automate data storage, send confirmation notifications, flag incomplete entries, and alert when an audit could not be performed — reducing the need for manual follow-up.
- **Data Preprocessing:** In Power BI, I cleaned and prepared the data (removing duplicates, standardizing formats, transforming data types, merging datasets, creating calculated columns, and handling missing values) to ensure the dashboards were reliable.
- **Data Visualization:** I designed dynamic Power BI dashboards to monitor over 300 critical process variables, using statistical techniques to establish operational baselines so that process drift and out-of-control conditions could be identified faster.
### 4. Outcome / Learning
- Digitized process tracking across **7 production lines** by deploying tablet-based data capture forms via Google Sheets and Google Apps Script, establishing full data traceability and real-time availability.
- Analyzed **300+ critical process variables** using statistical techniques to set operational baselines, enabling faster identification of process drift and anomalies.
- Built dynamic Power BI dashboards to continuously monitor production indicators, converting complex shop-floor data into clear trends for operational leadership.
- The paper-based audit process was fully eliminated.
### 5. Tools Used
- Google Sheets
- Google Apps Script
- Power BI (Power Query, DAX)
### 6. Evidence
- 📊 Dashboard screenshots: see `/screenshots` in this repository
- 🎥 Demo video: *https://youtu.be/yf5NKughtNE?si=ETKFsETe8lIyms36*
---
 
<a name="español"></a>
## 🇪🇸 Español
 
Digitalización y monitoreo de auditorías de proceso para una operación de manufactura, utilizando Google Sheets, Google Apps Script y Power BI.
 
### 1. Contexto / Problema
Este proyecto se desarrolló para las áreas de **Producción y Calidad** de **Softys**, una empresa manufacturera. Las auditorías de proceso en 7 líneas de producción se realizaban en papel, lo cual era:
 
- Propenso a errores humanos
- Difícil de rastrear (sin historial de quién auditó qué y cuándo)
- Imposible de monitorear en tiempo real
- Tedioso y demandante en tiempo para operadores y auditores
El objetivo era eliminar el proceso en papel y reemplazarlo por un sistema digital que brindara trazabilidad, visibilidad en tiempo real y una detección más ágil de anomalías en el proceso.
 
### 2. Mi Contribución
Fui responsable de todo el alcance del trabajo, desde el diseño de los formularios digitales de auditoría hasta la construcción de los dashboards finales de monitoreo, incluyendo la arquitectura de datos, la automatización, la limpieza de datos y la visualización.
 
### 3. Proceso y Decisiones
- **Diseño:** Estandaricé el diseño del formulario de auditoría en Google Sheets para mantener una experiencia simple y adecuada para tablets, priorizando la facilidad de uso sobre una app personalizada más compleja, ya que el objetivo era una adopción rápida en las 7 líneas.
- **Digitalización:** Construí una base de datos centralizada en tiempo real y utilicé Google Apps Script para automatizar el almacenamiento de datos, enviar notificaciones de confirmación, marcar entradas incompletas y alertar cuando una auditoría no podía realizarse, reduciendo la necesidad de seguimiento manual.
- **Preprocesamiento de datos:** En Power BI, limpié y preparé los datos (eliminación de duplicados, estandarización de formatos, transformación de tipos de datos, combinación de conjuntos de datos, creación de columnas calculadas y manejo de valores faltantes) para asegurar que los dashboards fueran confiables.
- **Visualización de datos:** Diseñé dashboards dinámicos en Power BI para monitorear más de 300 variables críticas del proceso, utilizando técnicas estadísticas para establecer líneas base operativas y así identificar más rápido las desviaciones y condiciones fuera de control.
### 4. Resultado / Aprendizaje
- Se digitalizó el seguimiento de procesos en **7 líneas de producción** mediante la implementación de formularios de captura de datos en tablet, usando Google Sheets y Google Apps Script, logrando trazabilidad completa de los datos y disponibilidad en tiempo real.
- Se analizaron **más de 300 variables críticas** del proceso utilizando técnicas estadísticas para establecer líneas base operativas, permitiendo identificar más rápido las desviaciones y anomalías del proceso.
- Se construyeron dashboards dinámicos en Power BI para monitorear de forma continua los indicadores de producción, convirtiendo datos complejos de piso de planta en tendencias claras para el liderazgo operativo.
- El proceso de auditoría en papel fue eliminado por completo.
### 5. Herramientas Utilizadas
- Google Sheets
- Google Apps Script
- Power BI (Power Query, DAX)
### 6. Evidencias
- 📊 Capturas de pantalla del dashboard: ver carpeta `/screenshots` en este repositorio
- 🎥 Video demo: *https://youtu.be/yf5NKughtNE?si=ETKFsETe8lIyms36*
