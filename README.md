# ¡Hola! 👋 Soy Jaime Caballero Ponce

**Ingeniero en Sistemas (carrera concluida, titulación en proceso) · Analista multidisciplinario**

Me fascina entender cómo funciona el mundo y usar los datos para resolver problemas reales: los que todavía no tienen solución, o los que la tienen pero no sirve. Me muevo entre datos, software, DevOps, finanzas, ciencia y psicología, porque casi ningún problema real cabe en una sola disciplina.

---

## 🚀 Proyecto principal

### 🧱 [Cimiento](https://github.com/J41M3C4B/Cimiento-Agente-de-Ingenieria-de-Proyectos-) — Datos al servicio de quien no tiene quién los atienda
Nació de mi **servicio social** en instituciones de asistencia privada y es la **inspiración de mi tesis**. Estas instituciones pierden donativos no por falta de necesidad, sino porque las convocatorias llegan en PDF largos y distintos entre sí, y quien las atiende (en buena parte religiosas, sin tiempo ni perfil técnico) no tiene cómo convertirlas en un proyecto bien planteado.

**¿Por qué no implementar un ERP o algo que ya existe?** Porque para ellas no es la herramienta correcta: agregaría complejidad y fricción a quien ya tiene demasiado que hacer. Cimiento hace lo contrario: **reduce fricción**. Lee las convocatorias, acompaña a pensar el problema con un diagnóstico guiado y entrega un presupuesto que cuadra y una guía en Word lista para presentar. Es un problema que casi nadie atiende, y menos sin cobrar.

**Lo que hay detrás, con las decisiones medidas y documentadas:**

| Entender el problema | Resolverlo con rigor técnico |
|---|---|
| Un diagnóstico de "cinco porqués" para llegar a la causa de fondo: lo que se pide casi nunca es el problema, es su consecuencia | Contrato de datos universal (JSON Schema) con citas de página **verificadas por el código**, no por el modelo: 96–99 % de citas verificadas en convocatorias nuevas, evaluadas a ciegas |
| Lenguaje sencillo, un paso a la vez, y errores que nunca inventan una respuesta | Código que calcula y valida; la IA solo propone |
| Privacidad por diseño: todo local y cifrado, y solo agregados hacia la IA | Control de gasto: límites por modelo, tope mensual y un solo proceso de IA por proyecto |
| Experimentos pequeños para decidir, incluidos los que salieron mal | 24 ADRs, 413 pruebas en Rust y 95 en frontend |

* **Uso real:** beta usada por dos instituciones con sus convocatorias del día a día.
* **Stack:** Tauri 2 · Rust · React 19 · TypeScript · SQLite/SQLCipher · FTS5 · sqlite-vec

---

## 📊 Portafolio de análisis de datos

| Proyecto | Qué demuestra | Enlaces |
|---|---|---|
| **🔗 Auditoría de Cadena de Suministro** | ETL en SQL puro (PostgreSQL + Docker), normalización a modelo relacional, CTEs y KPIs de riesgo y costo logístico. Hallazgos: 70.9 % del gasto concentrado en un país y fletes de hasta $50 USD/kg en categorías periféricas. | [Repo](https://github.com/J41M3C4B/auditoria-cadena-suministro-sql) · [Dashboard (Looker Studio)](https://datastudio.google.com/s/pqJ-nfYmpuA) |
| **📊 Incidencia Delictiva en México** *(Avanzado)* | Ciclo ETL de +3 M de registros en PostgreSQL, UNPIVOT, modelo avanzado en Power BI y la métrica "Tasa de delitos por 100k habitantes" con DAX (`TOPN`). | [Repo](https://github.com/J41M3C4B/Incidencia_Delictva_Mexico) · [Dashboard (Power BI)](https://app.powerbi.com/view?r=eyJrIjoiODEzYjNlMzctNWQ2Zi00N2NhLTgyOWYtNDZlZDhjODIzOGE5IiwidCI6ImIwM2EzOWY4LWVlNDAtNDk3My1hNDUwLTIyOGExYzY3YWI0YSJ9) |
| **📈 Ventas E-commerce** *(Intermedio)* | Limpieza de +500 K filas con una vista de PostgreSQL y segmentación de clientes con análisis RFM en Power BI. Identificó $17.07M en ventas y recomendaciones sobre "inventario zombie". | [Repo](https://github.com/J41M3C4B/Ecommerce-Sales-Analysis-SQL-PowerBI) · [Dashboard (Power BI)](https://app.powerbi.com/view?r=eyJrIjoiMDYwY2NmMTMtMGUzNC00YWNlLWI3YWQtYmMyNDJjNzY4ZmZiIiwidCI6ImIwM2EzOWY4LWVlNDAtNDk3My1hNDUwLTIyOGExYzY3YWI0YSJ9) |
| **☕ Ventas de Cafetería** *(Fundamental)* | Ingeniería de características en Excel (`order_id` único) y KPIs como el Ticket Promedio (AOV) con DAX en Power Pivot. | [Repo](https://github.com/J41M3C4B/Cafeteria_data_analysis_Excel) · [Archivo .xlsx](https://github.com/J41M3C4B/Cafeteria_data_analysis_Excel/blob/main/Coffee%20Shop%20Dashboard%20(Presentacion).xlsx) |

---

## 🛠️ Caja de herramientas

<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white" alt="Rust" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" alt="Power BI" />
  <img src="https://img.shields.io/badge/Looker_Studio-4285F4?style=for-the-badge&logo=looker&logoColor=white" alt="Looker Studio" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind CSS" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux" />
</p>

* **Ingeniería de Datos:** pipelines deterministas, contratos de datos (JSON Schema), auditoría y linaje.
* **Ingeniería de Software:** arquitectura por capas, ADRs, pruebas automatizadas, Rust y TypeScript.
* **Ingeniería de IA:** orquestación multi-modelo (LLMs), salidas validadas con JSON Schema, control de costos y gestión de contexto técnico.
* **Business Intelligence:** modelado en esquema estrella, DAX avanzado, análisis RFM, SQL (CTEs, vistas, normalización).
* **Diseño UI/UX:** retícula 8pt, OKLCH, glassmorphism y componentes minimalistas.
* **Infraestructura:** virtualización, configuración de servidores y despliegue de ERPs (Odoo).

---

## 📫 Conectemos

* **LinkedIn:** [jaimecaballero20](https://www.linkedin.com/in/jaimecaballero20)
* **Correo:** [jaime.caballero.ponce@gmail.com](mailto:jaime.caballero.ponce@gmail.com)
