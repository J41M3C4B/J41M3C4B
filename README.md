# ¡Hola! 👋 Soy Jaime Caballero Ponce

Soy un **Estudiante de Ingeniería** y **Arquitecto de Datos** enfocado en la democratización de la información, el desarrollo de ecosistemas SaaS y la Inteligencia de Negocios.

Evolucioné del análisis tradicional a la **Ingeniería de Datos y orquestación de IA**. Me apasiona construir desde la infraestructura y la arquitectura de bases de datos multi-inquilino, hasta el diseño de interfaces minimalistas de alto rendimiento, transformando información cruda en ecosistemas corporativos escalables y decisiones estratégicas.

---

## 🚀 Innovación y Desarrollo Principal

### 🌐 Datset | Ecosistema SaaS de Datos Empresariales (Fundador & Arquitecto)
## 🏗️ Arquitectura y Flujo E2E
El sistema procesa archivos (CSV, XLSX, XML) mediante una arquitectura orientada a eventos, aplicando pipelines de limpieza con auditoría forense completa.
1. **Fase 0 (Ingesta):** FastAPI recibe el payload, verifica cuotas y delega la tarea en background mediante Dramatiq y Redis. Se normaliza el archivo hacia la capa Bronze (Parquet) en Supabase Storage.
2. **Fase 1 (Limpieza):** Orquestación de motores vectorizados (Polars) para la limpieza de nulos y strings, guardando el resultado en la capa Silver (Parquet) y escribiendo los logs atómicamente en PostgreSQL.

## 🛠️ Stack Tecnológico
* **Framework API:** FastAPI (Python 3.12)
* **Procesamiento de Datos:** Polars (DataFrames en columnar)
* **Background Workers:** Dramatiq + Redis
* **Base de Datos & ORM:** PostgreSQL (Supabase) + SQLAlchemy 2.0
* **Storage:** Supabase Storage (S3-compatible)

## 📜 Reglas de Oro para el Desarrollo
Este repositorio sigue reglas arquitectónicas estrictas. **Antes de hacer un PR, verifica lo siguiente:**
* ❌ **Cero Pandas:** El procesamiento es 100% vectorizado con Polars para garantizar el máximo rendimiento.
* ❌ **Inmutabilidad Forense:** El registro de auditoría (`AuditRecord`) tiene `frozen=True`. No se muta bajo ninguna circunstancia.
* ❌ **Control Atómico de Contratos:** Nunca se sobreescribe el campo `ingestion_logs.metadata` por completo; se debe utilizar `jsonb_set` anidado.
* ✅ **Manejo Atómico de Base de Datos:** Solo el `ContractWriter` está autorizado para ejecutar el `db.commit()`.

---

## 📂 Proyectos de Portafolio

Aquí puedes encontrar mis proyectos principales. Cada repositorio contiene un `README` detallado, el código y un enlace al dashboard interactivo.

### 1. 📊 Análisis de Incidencia Delictiva en México (Avanzado)
* Gestión del ciclo **ETL** de **+3 millones de registros** usando **PostgreSQL**.
* Transformación de datos (UNPIVOT) y diseño de un **modelo de datos avanzado** en Power BI.
* Creación de la métrica maestra "**Tasa de Delitos por 100k Habitantes**" y KPIs dinámicos con DAX (`TOPN`).
* **Ver el Repositorio**(https://github.com/J41M3C4B/Incidencia_Delictva_Mexico) | **Ver Dashboard Interactivo (Power BI Public)**(https://app.powerbi.com/view?r=eyJrIjoiODEzYjNlMzctNWQ2Zi00N2NhLTgyOWYtNDZlZDhjODIzOGE5IiwidCI6ImIwM2EzOWY4LWVlNDAtNDk3My1hNDUwLTIyOGExYzY3YWI0YSJ9)

### 2. 📈 Análisis de Ventas E-commerce (Intermedio)
* Procesamiento y limpieza de un dataset de **+500,000 filas** usando una Vista de **PostgreSQL**.
* Desarrollo de un **Análisis RFM** (Recencia, Frecuencia, Monetario) en Power BI (`SUMMARIZE`) para segmentar clientes.
* Identificación de $17.07M en ventas y recomendaciones para optimizar el "inventario zombie".
* **Ver el Repositorio**(https://github.com/J41M3C4B/Ecommerce-Sales-Analysis-SQL-PowerBI) | **Ver Dashboard Interactivo (Power BI Public)**(https://app.powerbi.com/view?r=eyJrIjoiMDYwY2NmMTMtMGUzNC00YWNlLWI3YWQtYmMyNDJjNzY4ZmZiIiwidCI6ImIwM2EzOWY4LWVlNDAtNDk3My1hNDUwLTIyOGExYzY3YWI0YSJ9)

### 3. ☕ Análisis de Ventas de Cafetería (Fundamental)
* **Ingeniería de características** en **Excel** para crear un `order_id` único.
* Cálculo de KPIs clave como el Ticket Promedio (AOV) usando **DAX** en **Power Pivot**.
* **Ver el Repositorio**(https://github.com/J41M3C4B/Cafeteria_data_analysis_Excel) | **Ver Archivo .xlsx**(https://github.com/J41M3C4B/Cafeteria_data_analysis_Excel/blob/main/Coffee%20Shop%20Dashboard%20(Presentacion).xlsx)

---

## 🛠️ Mi Caja de Herramientas (Toolbelt)

### Tecnologías Principales
<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Polars-CD792C?style=for-the-badge&logo=polars&logoColor=white" alt="Polars" />
  <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white" alt="Supabase" />
  <img src="https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind CSS" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux" />
  <img src="https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" alt="Power BI" />
</p>

### Conceptos y Habilidades Clave
* **Data Engineering:** Pipelines Deterministas, Arquitectura Lakehouse, Lógica N+1.
* **Desarrollo SaaS & Backend:** Bases de datos Multi-tenant, Row Level Security (RLS).
* **AI Engineering:** Orquestación Multi-Modelo (LLMs), Gestión de Contexto Técnico.
* **Diseño UI/UX:** Retícula 8pt, OKLCH, Glassmorphism, Componentes Minimalistas.
* **Business Intelligence:** Modelado (Esquema Estrella), DAX Avanzado, Análisis RFM.
* **Infraestructura:** Virtualización, Configuración de Servidores, Despliegue de ERPs (Odoo).

---

## 📫 ¡Conectemos!

* **LinkedIn:** [www.linkedin.com/in/jaimecaballero20](https://www.linkedin.com/in/jaimecaballero20)
* **Correo:** [jaime.caballero.ponce@gmail.com](mailto:jaime.caballero.ponce@gmail.com)
