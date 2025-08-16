# 📊 Telecom X - Análisis de Evasión de Clientes

## 📝 Descripción del Proyecto
Este proyecto forma parte de la iniciativa **"Churn de Clientes"** de **Telecom X**, una compañía que enfrenta una alta tasa de cancelaciones de servicio.  
El objetivo principal es **analizar el comportamiento de los clientes** y detectar patrones que puedan explicar la evasión, con el fin de proponer estrategias de retención más efectivas.  

A través de este análisis exploratorio de datos (**EDA**), se busca proporcionar información valiosa que sirva como base para futuros modelos predictivos desarrollados por el equipo de Data Science.

---

## 🎯 Objetivos
- Obtener y procesar datos directamente desde una **API**.
- Limpiar, transformar y preparar la información siguiendo principios **ETL**.
- Visualizar patrones y tendencias relacionados con la evasión de clientes.
- Generar un **informe de insights** que apoye la toma de decisiones estratégicas.

---

## 🛠 Tecnologías Utilizadas
- **Python** 🐍
- **Pandas** (Manipulación y análisis de datos)
- **NumPy** (Operaciones numéricas)
- **Matplotlib** y **Seaborn** (Visualización de datos)
- **Requests** (Consumo de API)
- **Jupyter Notebook** (Entorno interactivo para análisis)

---

## 📂 Flujo de Trabajo

### 1️⃣ Obtención de Datos
- Se consume la API pública de **Telecom X** (formato JSON).
- Los datos se convierten en un **DataFrame** de Pandas para su manipulación.

### 2️⃣ Exploración Inicial
- Revisión de columnas y tipos de datos.
- Consulta de diccionario de datos para comprender el significado de cada variable.

### 3️⃣ Limpieza y Preparación
- Detección y tratamiento de valores nulos y duplicados.
- Corrección de formatos e inconsistencias en variables categóricas.
- Creación de nuevas variables como **Cuentas_Diarias** para mayor granularidad.

### 4️⃣ Transformación de Datos
- Conversión de valores textuales a binarios para análisis numérico.
- Renombrado y traducción de columnas para mayor claridad.

### 5️⃣ Análisis Exploratorio (EDA)
- Métricas descriptivas (media, mediana, desviación estándar).
- Distribución general de la variable **Churn** (evasión).
- Análisis por variables categóricas (género, tipo de contrato, método de pago, etc.).
- Análisis por variables numéricas (tiempo de contrato, gasto total, etc.).

### 6️⃣ Visualizaciones Clave
- Gráficos de barras y proporciones para variables categóricas.
- Histogramas y boxplots para variables numéricas.
- Uso de paleta de colores consistente (**turquesa y rosado**) para claridad visual.

---

## 📈 Ejemplo de Visualización

<img width="1165" height="590" alt="image" src="https://github.com/user-attachments/assets/a0482ede-d22e-4989-ab21-7782c5f72aad" />

---

## 🚀 Resultados Esperados
- Identificar segmentos de clientes con mayor propensión a cancelar el servicio.
- Generar hipótesis sobre factores clave que influyen en la evasión.
- Sentar las bases para un modelo predictivo de **churn**.

---

## ✒ Autor
- 👤 [arruenicol](https://github.com/arruenicol) 
- **Desafío**: Telecom X - Análisis de Evasión de Clientes
- **Fecha**: 08/2025
