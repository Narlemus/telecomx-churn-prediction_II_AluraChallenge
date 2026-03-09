# 📊 Telecom X — Predicción de Cancelación de Clientes (Churn)

## 📌 Descripción del Proyecto

Este proyecto tiene como objetivo analizar y predecir la cancelación de clientes (**Churn**) en la empresa **Telecom X** utilizando técnicas de **Machine Learning**.

La cancelación de clientes es un problema importante para las empresas de telecomunicaciones, ya que adquirir nuevos clientes suele ser más costoso que retener a los existentes. A través del análisis de datos y modelos predictivos, es posible identificar clientes con alto riesgo de cancelación y desarrollar estrategias de retención más efectivas.

---

## 🎯 Objetivo

Desarrollar modelos de clasificación capaces de **predecir qué clientes tienen mayor probabilidad de cancelar el servicio**, así como identificar los factores que influyen en este comportamiento.

---

## 📊 Dataset

El conjunto de datos contiene información sobre clientes de Telecom X, incluyendo variables como:

- Antigüedad del cliente
- Tipo de contrato
- Servicio de internet
- Cargos mensuales
- Método de pago
- Servicios adicionales contratados
- Cancelación del servicio (variable objetivo)

La variable **`Churn`** indica si el cliente canceló el servicio.

---

## 🧠 Metodología

El proyecto se desarrolló en varias etapas:

### 1️⃣ Preparación de Datos

- Carga del dataset
- Exploración de la estructura de los datos
- Identificación de valores faltantes
- Eliminación de variables irrelevantes
- Transformación de variables categóricas a variables numéricas
- Normalización de variables numéricas
- División del dataset en conjuntos de entrenamiento y prueba

---

### 2️⃣ Análisis Exploratorio de Datos (EDA)

Se realizaron visualizaciones para comprender mejor la relación entre diferentes variables y la cancelación de clientes.

Entre los análisis realizados se encuentran:

- Distribución de cancelación de clientes
- Antigüedad del cliente vs cancelación
- Cargos mensuales vs cancelación
- Tipo de contrato vs cancelación
- Matriz de correlación entre variables

---

### 3️⃣ Modelado Predictivo

Se implementaron modelos de clasificación para predecir la cancelación de clientes.

Modelos utilizados:

- **Regresión Logística**
- **Árbol de Decisión**

Estos modelos permiten identificar patrones en los datos y estimar la probabilidad de cancelación de los clientes.

---

## 📈 Evaluación de Modelos

Los modelos se evaluaron utilizando las siguientes métricas:

- **Accuracy (Exactitud)**
- **Precision**
- **Recall**
- **F1 Score**
- **Matriz de Confusión**

Estas métricas permiten analizar qué tan bien el modelo identifica a los clientes que cancelan el servicio.

---

## 🔎 Principales Hallazgos

A partir del análisis exploratorio y los modelos predictivos se identificaron varios factores importantes asociados a la cancelación de clientes:

- Los **clientes con menor antigüedad** tienen mayor probabilidad de cancelar.
- Los **contratos de corto plazo** presentan mayor tasa de cancelación que los contratos de largo plazo.
- Los **cargos mensuales más altos** están asociados con mayor probabilidad de churn.
- Algunos **métodos de pago** muestran mayor relación con la cancelación.
- Los **clientes con contratos de uno o dos años** tienden a permanecer más tiempo en la empresa.

---

## 💡 Recomendaciones de Negocio

Basado en los resultados obtenidos, la empresa Telecom X podría implementar las siguientes estrategias para reducir la cancelación de clientes:

- Implementar **programas de fidelización para clientes nuevos**.
- Incentivar **contratos de mayor duración** mediante descuentos o beneficios.
- Revisar la **estructura de precios de servicios con cargos mensuales elevados**.
- Identificar clientes con **alto riesgo de cancelación** mediante modelos predictivos y aplicar estrategias de retención.

---

## 🛠️ Tecnologías Utilizadas

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- Google Colab
  

## 👩‍💻 Autor

Proyecto desarrollado como parte de un ejercicio práctico de **Análisis de Datos y Machine Learning aplicado a la predicción de cancelación de clientes**.
