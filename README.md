# 🐶 Proyecto Final - Clasificación de Resultados de Animales en el Centro de Adopción de Austin

### 👨‍💻 Autor: Facundo Gonzalo Arce  
### 🏫 Curso: Python - CoderHouse  
### 📁 Archivo principal: `ProyectoParteIII-ArceFacundo.ipynb`

---

## 📌 Objetivo del proyecto

Este notebook tiene como objetivo aplicar conceptos vistos durante la cursada, incluyendo:

- Reducción de la dimensionalidad del dataset mediante **selección de variables**
- Entrenamiento de un modelo de **clasificación**
- Evaluación del modelo usando **métricas básicas**
- Extracción de **conclusiones** a partir de los resultados obtenidos

Todo esto se realizó utilizando un dataset real sobre animales ingresados y egresados del Centro de Adopción de Austin (Texas, EE.UU.).

---

## 📊 Dataset utilizado

- Fuente: [Kaggle - Austin Animal Center](https://www.kaggle.com/datasets/aaronschlegel/austin-animal-center-shelter-intakes-and-outcomes)
- Archivo incluido: `DataSet-ArceFacundo.csv`
- Contiene registros de animales (tipo, raza, edad, color, sexo) y el tipo de resultado (adopción, traslado, fallecido, etc.)

---

## 🧰 Librerías utilizadas

- `pandas`
- `numpy`
- `sklearn` (para selección de features, modelos de ML y métricas)
- `matplotlib` y `seaborn` (opcional para visualización)

---

## ⚙️ Cómo ejecutar el notebook

1. Cloná este repositorio o descargá el archivo `.ipynb` y el CSV.
2. Abrí el notebook en Google Colab o Jupyter Notebook.
3. Verificá que el archivo `DataSet-ArceFacundo.csv` esté en la misma ruta del notebook.
4. Ejecutá todas las celdas desde el principio. No requiere configuración adicional.

---

## ✅ Resultado

Se entrenó un modelo de clasificación `RandomForestClassifier` que logró una precisión aceptable para predecir el tipo de resultado de los animales. Se aplicó selección de variables con `SelectKBest` y se evaluaron las predicciones con métricas estándar.

---

## 📚 Referencias

- Kaggle Dataset: https://www.kaggle.com/datasets/aaronschlegel/austin-animal-center-shelter-intakes-and-outcomes
- Documentación Scikit-learn: https://scikit-learn.org/stable/
