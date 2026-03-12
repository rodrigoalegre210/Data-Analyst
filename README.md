<h1 align="center"> ✈️ Siniestros Aéreos: ETL & Business Intelligence </h1>

> **Proyecto Individual Nº3** - Etapa de Laboratorios (Henry Bootcamp)
> 
> **Rol:** Data Analyst

---

## 📄 Descripción del Proyecto

Este repositorio contiene el desarrollo de un análisis sobre accidentes aeronáuticos históricos. El objetivo principal es transformar datos crudos en información estratégica a través de un proceso de **ETL**, almacenamiento en **SQL** y visualización en **Power BI**, haciendo posible la identificación de patrones de seguridad y tasas de mortalidad en la aviación.

### Objetivos del Proyecto:
* **Procesamiento de Datos:** Limpieza y normalización de datasets mediante Python.
* **Ingesta SQL:** Automatización de la carga de datos desde archivos planos (.csv) a una base de datos relacional.
* **Análisis de BI:** Creación de un Dashboard interactivo para el monitoreo de KPIs de seguridad aérea.

---

## 🛠️ Tecnologías Utilizadas

| Categoría | Herramientas |
|-----------|--------------|
| **Lenguaje** | Python (Pandas, NumPy) |
| **Base de Datos** | MySQL |
| **Visualización** | Power BI |
| **Conectividad** | SQLAlchemy / PyMySQL |

---

## ⚙️ Fases del Desarrollo

### 1. Extracción, Transformación y Carga (ETL)
Se realizó un **EDA (Exploratory Data Analysis)** detallado para manejar valores faltantes y normalizar columnas. La limpieza se enfocó en asegurar que las métricas de personas a bordo y fallecidos fueran consistentes para su posterior análisis.

### 2. Arquitectura de Datos (MySQL)
Para garantizar la persistencia y la escalabilidad del análisis, se desarrolló un script en Python que:
- Crea la estructura de la base de datos en **MySQL**.
- Realiza la ingesta de los datos transformados de manera automatizada.

### 3. Dashboard e Insights
El reporte en **Power BI** se conecta a MySQL para visualizar indicadores críticos, tales como:
- **Evolución Anual:** Tendencia de accidentes y fatalidades a través del tiempo.
- **Tasa de Mortalidad:** Calculada mediante la relación entre fallecidos y total de personas a bordo.

> [!IMPORTANT]
> El Dashboard permite filtrar por periodos de tiempo y tipos de aeronaves, facilitando la identificación de los años con mayor tasa de siniestralidad.

---

<h3 align="center">🚀 Desarrollado por Rodrigo - Data Science & AI Engineer 🚀</h3>
