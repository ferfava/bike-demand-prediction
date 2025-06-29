# 🚲 Bike Demand Prediction

Predicción de la demanda de alquiler de bicicletas utilizando modelos de Machine Learning en R: regresión lineal, árbol de decisión y red neuronal con Keras.

---

## 📂 Descripción del proyecto

Este proyecto analiza datos horarios de uso de bicicletas para predecir la cantidad de alquileres (`cnt`) en función de variables climáticas, temporales y contextuales. Se comparan distintos enfoques de modelado para evaluar rendimiento y aplicabilidad:

- 🔹 Regresión Lineal  
- 🌳 Árbol de Decisión  
- 🧠 Red Neuronal Multicapa (Keras + TensorFlow)

---

## 🛠 Tecnologías y librerías

- `R`, `tidyverse`, `lubridate`
- `recipes`, `rsample`, `yardstick` (para preprocesamiento y evaluación)
- `keras`, `tensorflow` (para deep learning)
- `vip` (para interpretabilidad vía importancia de variables)

---

## ⚙️ Pre-requisitos

- R >= 4.3  
- Python 3.11  
- TensorFlow 2.15 (no compatible con Python 3.13)  
- Instalar librerías requeridas vía `install.packages()` y `install_tensorflow()`  

⚠️ **Importante:** Para compatibilidad con TensorFlow, se utilizó **Python 3.11**. No funciona con versiones más recientes como 3.13.

---

## 📈 Objetivo

Comparar rendimiento de distintos modelos de regresión para predecir la demanda de bicicletas y analizar el impacto de las variables predictoras.

---

## 📊 Resultados esperados

- Entrenamiento y evaluación de cada modelo
- Métricas de desempeño (R², MAE, etc.)
- Gráfico de comparación entre predicción y valores reales
- Visualización de la importancia de variables

---

## 🧪 Estructura del código

1. Carga y exploración del dataset
2. Ingeniería de variables y normalización
3. Entrenamiento de modelos
4. Evaluación y visualización
5. Interpretabilidad con `vip`

---

## 📁 Dataset

- `hour.csv`: dataset de uso horario de bicicletas
- Fuente: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Bike+Sharing+Dataset)

---

## ✍️ Autor/a

**Fernanda Fava**  
💼 Ciencia de datos · IA · Salesforce  
📎 [LinkedIn](https://www.linkedin.com/in/fernanda-fava-91a453125/) | 📷 [@fer.data.tech](https://www.instagram.com/fer.data.tech)

---

## 📌 Licencia

Este proyecto está bajo licencia MIT. Libre para usar, compartir y mejorar.
