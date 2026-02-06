# Challenge Alura: Telecom X - Análisis de Evasión (Churn)

¡Bienvenido al repositorio del proyecto **Telecom X**! Este desafío forma parte del programa de formación de Alura, donde el objetivo principal es analizar y comprender por qué los clientes están cancelando sus servicios de telecomunicaciones.



## 📌 Descripción del Proyecto
Como asistente de análisis de datos, mi labor ha sido abordar el problema del **Churn de Clientes**. La empresa Telecom X enfrenta una alta tasa de cancelaciones y requiere transformar sus datos crudos en información estratégica para reducir la evasión.

### ¿Qué herramientas utilicé?
* **Lenguaje:** Python 3.12
* **Bibliotecas Clave:** * `Pandas`: Para la manipulación y limpieza de datos.
    * `Requests`: Para la extracción de datos desde una API.
    * `Seaborn` & `Matplotlib`: Para la creación de visualizaciones avanzadas.
    * `NumPy`: Para el manejo de datos numéricos y valores nulos.

---

## 📂 Estructura del Desafío

El proyecto se dividió en 4 fases críticas siguiendo la metodología **ETL**:

### 1. 🔧 Extracción (Extract)
Se realizó la conexión directa con la API de datos de Telecom X, importando la base de datos en formato JSON y normalizándola para su uso en un DataFrame.

### 2. 🧹 Transformación (Transform)
Fase dedicada a la limpieza profunda de los datos:
* Conversión de tipos de datos (de `object` a `float` en cargos financieros).
* Tratamiento de valores nulos y registros vacíos.
* Limpieza de nombres de columnas anidadas (ej: `internet.InternetService`).

### 3. 📊 Carga y Análisis (Load & EDA)
Exploración visual de los datos para encontrar patrones. Se analizaron variables como:
* Tipo de contrato vs. Evasión.
* Impacto de la tecnología de Internet (Fibra Óptica vs. DSL).
* Relación entre la antigüedad del cliente y la fuga.

### 4. 📄 Informe Final
Generación de recomendaciones estratégicas basadas en los *insights* obtenidos para ayudar a la toma de decisiones del equipo de Data Science.

---

## 🚀 Principales Hallazgos
* **El contrato mensual** es el mayor detonante de fuga.
* Los servicios de **Seguridad Online y Soporte Técnico** funcionan como anclas de retención.
* Existe una **fuga crítica en los primeros 6 meses** de vida del cliente.

---

## 🛠️ Cómo ejecutar este proyecto
1. Clonar el repositorio.
2. Abrir el archivo `.ipynb` en **Google Colab** o Jupyter Notebook.
3. Ejecutar las celdas en orden secuencial.

---
**Desarrollado como parte del Alura Challenge - Data Science.**
