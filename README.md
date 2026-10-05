# ¡Hola! 👋 Soy Jaime Caballero Ponce

**Analista de Datos · Inteligencia de Negocios**
Ingeniero en Sistemas (carrera concluida, titulación en proceso) · México 🇲🇽

🌐 [English version](README.en.md)

Me fascina entender cómo funciona el mundo y usar los datos para resolver problemas reales: los que todavía no tienen solución, o los que la tienen pero no sirve. Soy un analista multidisciplinario: combino datos, finanzas, psicología, ciencia e ingeniería porque casi ningún problema de negocio cabe en una sola disciplina. Mi trabajo favorito es traducir lo que pasa en los datos a decisiones que una persona sin perfil técnico pueda tomar.

> 🔎 **Busco mi primera oportunidad como Analista de Datos / Inteligencia de Negocios.**

---

## 🧭 Cómo trabajo

* **Entender antes de construir.** Hablo con quien vive el problema y busco la causa de fondo, porque lo que se pide casi nunca es el problema: es su consecuencia (método de los "cinco porqués").
* **Convertir datos en decisiones.** Cada análisis termina en una pregunta de negocio respondida y una recomendación concreta, no solo en un dashboard.
* **Medir antes de decidir.** Pruebo con experimentos pequeños, documento lo que funcionó y lo que no, y valido con usuarios reales.
* **Estructurar proyectos grandes.** Divido el trabajo en fases con criterios de terminado, registro cada decisión importante y su porqué, y cuido costos, riesgos y privacidad desde el inicio.

---

## 🚀 Proyecto principal

### 🧱 [Cimiento](https://github.com/J41M3C4B/Cimiento-Agente-de-Ingenieria-de-Proyectos-) — Datos al servicio de quien no tiene quién los atienda

**El problema.** Las instituciones de asistencia privada (asilos, casas hogar) pierden donativos, no por falta de necesidad, sino porque cada donante publica sus reglas en PDF largos y distintos, y quien los atiende (en buena parte religiosas, sin tiempo ni perfil técnico) no tiene cómo convertirlos en un proyecto bien planteado.

**Mi enfoque.** Lo conocí en mi **servicio social** y hoy es la **inspiración de mi tesis**. Un ERP o un sistema que ya exista no era la respuesta: para ellas agrega complejidad y fricción. Así que diseñé una herramienta que hace lo contrario: **reduce fricción**. Lee las convocatorias, acompaña a la persona a encontrar la causa de fondo de su necesidad y entrega un presupuesto que cuadra y una guía lista para presentar.

**Resultados**
* ✅ **Uso real:** dos instituciones la usan con sus convocatorias del día a día.
* 📉 **Menos carga de trabajo:** lo que más les sorprendió, según su retroalimentación (percepción cualitativa; aún no se midieron tiempos).
* 🎯 **Lectura confiable:** 96–99 % de las citas verificadas en convocatorias nuevas, evaluadas a ciegas.
* 💰 **Costo controlado:** un proyecto completo con IA cuesta alrededor de $18 MXN, con tope mensual configurable.
* 🔒 **Datos sensibles protegidos:** todo local y cifrado, y solo agregados hacia la IA.

**Habilidades que demuestra:** levantamiento de requerimientos con usuarios reales · análisis de procesos · diseño de métricas y validaciones · análisis de costos · documentación de decisiones · comunicación con perfiles no técnicos.

<details>
<summary>🔧 Detalle técnico (si te interesa)</summary>

* **Pipeline:** PDF/Word/Excel → extracción por página → escáner de datos sensibles → lectura con un esquema canónico (JSON Schema) → verificación de citas hecha por el código → diagnóstico guiado → presupuesto calculado en código → guía en Word.
* **Principio:** el código calcula y valida; la IA solo propone.
* **Proceso:** 24 decisiones de arquitectura documentadas (ADRs), 413 pruebas en Rust y 95 en frontend.
* **Stack:** Tauri 2 · Rust · React 19 · TypeScript · SQLite/SQLCipher.

</details>

---

## 📊 Portafolio de análisis de datos

| Proyecto | Pregunta de negocio | Hallazgo y recomendación | Herramientas |
|---|---|---|---|
| **🔗 [Auditoría de Cadena de Suministro](https://github.com/J41M3C4B/auditoria-cadena-suministro-sql)** · [Dashboard](https://datastudio.google.com/s/pqJ-nfYmpuA) | ¿Dónde están el riesgo y el costo oculto de la cadena de suministro? | El 70.9 % del gasto se concentra en un país y algunas categorías superan los $50 USD/kg de flete. Recomendé homologar proveedores alternos y consolidar fletes. | PostgreSQL · SQL · Looker Studio |
| **📊 [Incidencia Delictiva en México](https://github.com/J41M3C4B/Incidencia_Delictva_Mexico)** · [Dashboard](https://app.powerbi.com/view?r=eyJrIjoiODEzYjNlMzctNWQ2Zi00N2NhLTgyOWYtNDZlZDhjODIzOGE5IiwidCI6ImIwM2EzOWY4LWVlNDAtNDk3My1hNDUwLTIyOGExYzY3YWI0YSJ9) | ¿Cuál es la tasa *real* de delitos por 100k habitantes, y no solo el total? | +3 millones de registros transformados para comparar estados y municipios de forma justa y encontrar "puntos calientes" y tendencias. | PostgreSQL · Power BI · DAX |
| **📈 [Ventas E-commerce](https://github.com/J41M3C4B/Ecommerce-Sales-Analysis-SQL-PowerBI)** · [Dashboard](https://app.powerbi.com/view?r=eyJrIjoiMDYwY2NmMTMtMGUzNC00YWNlLWI3YWQtYmMyNDJjNzY4ZmZiIiwidCI6ImIwM2EzOWY4LWVlNDAtNDk3My1hNDUwLTIyOGExYzY3YWI0YSJ9) | ¿Qué productos y qué clientes sostienen el negocio? | $17.07 M en ventas analizadas; segmentación RFM de 5,861 clientes y propuesta de reactivar a los "clientes en riesgo" y depurar el "inventario zombie". | PostgreSQL · Power BI · RFM |
| **☕ [Ventas de Cafetería](https://github.com/J41M3C4B/Cafeteria_data_analysis_Excel)** · [Archivo .xlsx](https://github.com/J41M3C4B/Cafeteria_data_analysis_Excel/blob/main/Coffee%20Shop%20Dashboard%20(Presentacion).xlsx) | ¿Cuándo y qué se vende más? ¿Cuál es el ticket promedio? | Las horas pico son de 8 a 10 a.m. y el café lidera los ingresos. Dashboard interactivo solo con Excel. | Excel · Power Pivot · DAX |

Cada repositorio explica su propósito y las habilidades que practica.

---

## 🛠️ Caja de herramientas

<p align="left">
  <img src="https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" alt="Power BI" />
  <img src="https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white" alt="Excel" />
  <img src="https://img.shields.io/badge/Looker_Studio-4285F4?style=for-the-badge&logo=looker&logoColor=white" alt="Looker Studio" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux" />
</p>

* **Analítica y BI:** SQL (CTEs, vistas, normalización), Power BI, DAX avanzado, modelado en esquema estrella, análisis RFM, KPIs y storytelling con datos.
* **Negocio:** levantamiento de requerimientos, análisis de procesos, finanzas y costos, y comunicación de hallazgos a perfiles no técnicos.
* **Metodología:** diagnóstico de causa raíz, experimentos pequeños, documentación de decisiones y gestión de proyectos por fases.
* **Complementarias:** Rust, TypeScript, DevOps básico, virtualización y despliegue de ERPs (Odoo).

---

## 📫 Conectemos

* **LinkedIn:** [jaimecaballero20](https://www.linkedin.com/in/jaimecaballero20)
* **Correo:** [jaime.caballero.ponce@gmail.com](mailto:jaime.caballero.ponce@gmail.com)
