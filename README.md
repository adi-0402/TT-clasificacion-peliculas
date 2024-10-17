# Clasificación de Reseñas de Películas
![GitHub](https://img.shields.io/badge/GitHub-Repository-lightgrey)
![Estado](https://img.shields.io/badge/Estado-Terminado-brightgreen)

## 📖 Descripción del Proyecto
El objetivo de este proyecto fue desarrollar un sistema de clasificación automática de reseñas de películas, utilizando un conjunto de datos de reseñas etiquetadas de IMDB. Se probaron múltiples modelos de clasificación para identificar las reseñas negativas y positivas de manera eficiente. Este proyecto se realizo con Tripleten.

## 💻 Funcionalidades
- `Limpieza y Preprocesamiento de Datos`: Vectorización de textos y transformación de los datos para ser usados en modelos de clasificación.
- `Entrenamiento de Modelos`: Implementación y evaluación de tres modelos: Regresión Logística, LGBMClassifier y Gradient Boosting.
- `Evaluación de Rendimiento`: Comparación de los modelos utilizando métricas de F1-score, ROC AUC y APS.

## 🛠 Tecnologías Utilizadas
- Python
- Pandas
- Scikit-learn
- LightGBM

## ✨ Conclusiones
- `Regresión Logística`: Fue el modelo más efectivo, con un **F1-score de 0.88**, un **ROC AUC de 0.95** y un **APS de 0.95** en el conjunto de prueba.
- `LGBMClassifier`: Tuvo un rendimiento ligeramente inferior, alcanzando un **F1-score de 0.86** y un **ROC AUC de 0.94**.
- `Gradient Boosting`: Aunque fue el modelo con menor rendimiento, sigue siendo viable, con un **F1-score de 0.82** y un **ROC AUC de 0.90**.
