---

# Clasificación de Reseñas de Películas en Film Junky Union

---

## 🔖 Descripción del Proyecto
Este proyecto tiene como objetivo desarrollar un modelo que clasifique automáticamente las reseñas de películas como positivas o negativas. Para ello, utilizamos un conjunto de datos de IMDB con textos etiquetados. El modelo es parte del sistema de categoría de reseñas de Film Junky Union, una comunidad para entusiastas de las películas clásicas. Este proyecto se realizo con TripleTen.

---

## 💻 Funcionalidades
- **Limpieza y Normalización de Textos:**
  - Eliminación de caracteres no deseados y normalización de palabras mediante lematización.
- **Construcción de Representaciones Textuales:**
  - Uso de TF-IDF para transformar las reseñas en representaciones numéricas.
- **Modelos Predictivos:**
  - Implementación de tres modelos principales:
    - Regresión Logística
    - Gradient Boosting
    - LightGBM
- **Evaluación del Desempeño:**
  - Métricas como F1-score, ROC AUC y APS para evaluar y comparar los modelos.

---

## 🛠️ Tecnologías Utilizadas
- Python
- Pandas
- NumPy 
- Scikit-learn
- LightGBM
- Matplotlib
- Seaborn
- SpaCy
- NLTK

---

## 🔢 Resultados
- **Mejor Modelo:** Regresión Logística
  - F1-score en conjunto de prueba: **0.88**.
  - Valores altos de ROC AUC (0.95) y APS (0.95).
- Otros modelos (LGBM y Gradient Boosting) también mostraron desempeño competitivo, pero ligeramente inferior a la Regresión Logística.

---

## ✨ Conclusiones
- **Impacto del Proyecto:**
  Este modelo permite categorizar automáticamente reseñas de películas, ahorrando tiempo a los administradores de la comunidad y mejorando la experiencia de los usuarios.
- **Escalabilidad:**
  Las técnicas utilizadas pueden ampliarse fácilmente para incluir otras categorías de reseñas o tipos de datos.
- **Valor Comercial:**
  La clasificación automática puede ser integrada en sistemas en tiempo real para filtrar contenido y recomendar películas basadas en las opiniones de los usuarios.

---

