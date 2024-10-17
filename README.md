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
- `Eficacia del modelo`: La Regresión Logística destacó por su excelente balance entre precisión y eficiencia, alcanzando un **F1-Score de 0.88** y un **AUC-ROC de 0.95**, lo que lo convierte en una opción confiable para clasificar reseñas.
- `Comparación de modelos`: Aunque la Regresión Logística fue el modelo más efectivo, otros modelos como el LGBMClassifier y Gradient Boosting también mostraron buenos resultados (F1-Scores de 0.86 y 0.82 respectivamente). Esto sugiere que, dependiendo de los requerimientos específicos (como mayor velocidad o interpretabilidad), estos modelos podrían ser alternativas viables.
- `Impacto para el negocio`: La implementación de este sistema permitirá identificar rápidamente reseñas negativas y ajustar sus estrategias de contenido y marketing en función del feedback de los usuarios. Esto optimiza la experiencia del usuario y puede ayudar a aumentar la retención y satisfacción de los miembros de la comunidad.
