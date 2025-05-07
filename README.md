# DengAI: Predicción de Casos de Dengue con Aprendizaje Supervisado

Este proyecto explora distintos modelos de aprendizaje supervisado para predecir la cantidad de casos de dengue en dos ciudades de Perú: **Iquitos** y **San Juan**, usando variables climáticas y de vegetación.

## 📌 Objetivo
Evaluar el desempeño de modelos de regresión como KNN, Árboles de Decisión, Random Forest y AdaBoost para la predicción de `total_cases`, con un enfoque riguroso en la limpieza, imputación de datos faltantes y tratamiento de outliers.

## 🛠️ Técnicas utilizadas

- Análisis exploratorio de datos (EDA)
- Visualización con `seaborn` y `matplotlib`
- Detección y eliminación de outliers por año y ciudad
- Imputación de valores faltantes con `interpolate` y `fillna`
- Codificación de variables categóricas
- Selección de características mediante correlación
- Normalización con `MinMaxScaler`
- Optimización de hiperparámetros con:
  - Cross Validation
  - RandomizedSearchCV
  - GridSearchCV

## 🧠 Modelos probados

- KNeighborsRegressor
- DecisionTreeRegressor
- RandomForestRegressor (pendiente de evaluación completa)
- AdaBoostRegressor (pendiente de evaluación completa)

## 🧪 Resultados destacados

- **Mejor MAE con KNN (GridSearch):** 19.95 en el conjunto de validación
- Diferencias de comportamiento por ciudad identificadas en las features climáticas y NDVI

## 📂 Archivos

- `DengAI_prediccion_casos_dengue.ipynb`: Notebook principal del proyecto

## 🚀 Abrir en Google Colab

[![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Jesus-Pacheco-Romero/dengue-prediction/blob/main/DengAI_prediccion_casos_dengue.ipynb)

## 📸 Visual

Incluye visualizaciones como boxplots, histogramas, gráficos de regresión y pairplots para facilitar el análisis.

---

### 📩 Autor

**Jesús Iván Pacheco Romero**  
Ingeniero de Yacimientos | Científico de Datos  
👨‍🔬 Máster en Big Data y Ciencia de Datos  
