# ¡Hola! 👋 Soy Jaime Caballero Ponce

**Estudiante de Ingeniería · Ingeniería de Datos · Inteligencia de Negocios**

Construyo sistemas que convierten información cruda y desordenada en decisiones confiables: desde pipelines de ingestión y bases de datos multi-inquilino hasta dashboards ejecutivos. Vengo del análisis tradicional (SQL, Excel, Power BI) y evolucioné hacia la **ingeniería de datos y la orquestación de IA**, con una regla que repito en todo lo que hago: **el código calcula y valida; la IA propone.**

---

## 🚀 Proyectos destacados

### 🧱 [Cimiento](https://github.com/J41M3C4B/Cimiento-Agente-de-Ingenieria-de-Proyectos-) — Pipeline de datos para el tercer sector
App de escritorio *local-first* que convierte convocatorias de donativos (PDF no estructurados) en un proyecto bien planteado, con presupuesto que cuadra y una guía en Word lista para entregar.

* **Contrato de datos universal:** un JSON Schema canónico que cualquier modelo rellena con citas de página que **el código verifica**, no el modelo. Resultado a ciegas: 96–99 % de citas verificadas en convocatorias nuevas.
* **Gasto de IA acotado:** diagnóstico de "cinco porqués" con peor caso calculable, límites por modelo, tope mensual y un solo proceso de IA por proyecto.
* **Privacidad por diseño:** SQLite cifrado (SQLCipher), escáner de datos sensibles antes y después del modelo, y solo agregados hacia la IA.
* **Decisiones medidas y documentadas:** 24 ADRs, 413 pruebas en Rust y 95 en frontend.
* **Uso real:** beta usada por dos instituciones de asistencia privada.
* **Stack:** Tauri 2 · Rust · React 19 · TypeScript · SQLite/SQLCipher · FTS5 · sqlite-vec

### 🌐 Datset — Ecosistema SaaS de Datos Empresariales *(Fundador & Arquitecto)*
Plataforma que procesa archivos (CSV, XLSX, XML) con una arquitectura orientada a eventos y **auditoría forense completa** de cada transformación.

* **Ingesta (Bronce):** FastAPI valida el archivo, verifica cuotas y delega el trabajo a workers (Dramatiq + Redis); el archivo se normaliza a Parquet en Supabase Storage.
* **Limpieza (Plata):** motores vectorizados con Polars; el resultado se guarda en Parquet y los logs se escriben de forma atómica en PostgreSQL.
* **Principios:** auditoría inmutable, contratos de ingestión actualizados con `jsonb_set` (nunca sobrescritos) y un único punto autorizado para el `commit`.
* **Stack:** Python 3.12 · FastAPI · Polars · Dramatiq + Redis · PostgreSQL (Supabase) · SQLAlchemy 2.0
* 🔎 [Demo de arquitectura](https://github.com/J41M3C4B/Datset_Dev_Data_Engineering): refactorización de ingestión para archivos de más de 2 GB, con validación por *magic bytes*, procesamiento por chunks sobre Parquet y **−80 % de consumo de RAM**.

---

## 📊 Portafolio de análisis de datos

| Proyecto | Qué demuestra | Enlaces |
|---|---|---|
| **🔗 Auditoría de Cadena de Suministro** | ETL en SQL puro (PostgreSQL + Docker), normalización a modelo relacional, CTEs y KPIs de riesgo y costo logístico. Hallazgos: 70.9 % del gasto concentrado en un país y fletes de hasta $50 USD/kg en categorías periféricas. | [Repo](https://github.com/J41M3C4B/auditoria-cadena-suministro-sql) · [Dashboard (Looker Studio)](https://datastudio.google.com/s/pqJ-nfYmpuA) |
| **📊 Incidencia Delictiva en México** *(Avanzado)* | Ciclo ETL de +3 M de registros en PostgreSQL, UNPIVOT, modelo avanzado en Power BI y la métrica "Tasa de delitos por 100k habitantes" con DAX (`TOPN`). | [Repo](https://github.com/J41M3C4B/Incidencia_Delictva_Mexico) · [Dashboard (Power BI)](https://app.powerbi.com/view?r=eyJrIjoiODEzYjNlMzctNWQ2Zi00N2NhLTgyOWYtNDZlZDhjODIzOGE5IiwidCI6ImIwM2EzOWY4LWVlNDAtNDk3My1hNDUwLTIyOGExYzY3YWI0YSJ9) |
| **📈 Ventas E-commerce** *(Intermedio)* | Limpieza de +500 K filas con una vista de PostgreSQL y segmentación de clientes con análisis RFM en Power BI. Identificó $17.07M en ventas y recomendaciones sobre "inventario zombie". | [Repo](https://github.com/J41M3C4B/Ecommerce-Sales-Analysis-SQL-PowerBI) · [Dashboard (Power BI)](https://app.powerbi.com/view?r=eyJrIjoiMDYwY2NmMTMtMGUzNC00YWNlLWI3YWQtYmMyNDJjNzY4ZmZiIiwidCI6ImIwM2EzOWY4LWVlNDAtNDk3My1hNDUwLTIyOGExYzY3YWI0YSJ9) |
| **🚚 Optimización Logística** *(Intermedio)* | Validación lógica de datos, imputación ponderada y medida de Costo por Milla (CPM) con DAX en Power Pivot. Detectó la falla de un transportista con paquetes pesados y un cuello de botella de ruta. | [Repo](https://github.com/J41M3C4B/Logistics-Supply-Chain-Optimization-Reducing-Dealays-and-Costs) |
| **☕ Ventas de Cafetería** *(Fundamental)* | Ingeniería de características en Excel (`order_id` único) y KPIs como el Ticket Promedio (AOV) con DAX en Power Pivot. | [Repo](https://github.com/J41M3C4B/Cafeteria_data_analysis_Excel) · [Archivo .xlsx](https://github.com/J41M3C4B/Cafeteria_data_analysis_Excel/blob/main/Coffee%20Shop%20Dashboard%20(Presentacion).xlsx) |

---

## 🛠️ Caja de herramientas

<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white" alt="Rust" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/Polars-CD792C?style=for-the-badge&logo=polars&logoColor=white" alt="Polars" />
  <img src="https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white" alt="Supabase" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" alt="Power BI" />
  <img src="https://img.shields.io/badge/Looker_Studio-4285F4?style=for-the-badge&logo=looker&logoColor=white" alt="Looker Studio" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind CSS" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux" />
</p>

* **Ingeniería de Datos:** pipelines deterministas, arquitectura Lakehouse (Bronce/Plata), Parquet, contratos de datos, auditoría y linaje.
* **Backend & SaaS:** bases de datos multi-tenant, Row Level Security (RLS), colas de trabajo asíncronas.
* **Ingeniería de IA:** orquestación multi-modelo (LLMs), salidas validadas con JSON Schema, control de costos y gestión de contexto técnico.
* **Business Intelligence:** modelado en esquema estrella, DAX avanzado, análisis RFM, SQL (CTEs, vistas, normalización).
* **Diseño UI/UX:** retícula 8pt, OKLCH, glassmorphism y componentes minimalistas.
* **Infraestructura:** virtualización, configuración de servidores y despliegue de ERPs (Odoo).

---

## 📫 Conectemos

* **LinkedIn:** [jaimecaballero20](https://www.linkedin.com/in/jaimecaballero20)
* **Correo:** [jaime.caballero.ponce@gmail.com](mailto:jaime.caballero.ponce@gmail.com)
