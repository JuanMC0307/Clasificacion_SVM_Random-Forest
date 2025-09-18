# Crear el contenido del README.md en formato markdown para el proyecto de clasificación

readme_content2 = """# 🌲 Clasificación con SVM y Random Forest – Forest Cover Type  

Este proyecto corresponde a una actividad del máster en Inteligencia Artificial y tiene como objetivo aplicar **máquinas de vectores de soporte (SVM)** y **Random Forest** al dataset **Forest Cover Type** para predecir el tipo de cobertura forestal en base a variables ambientales y geográficas.  

📚 **Tabla de Contenidos**  
- 🧠 ¿Qué incluye este proyecto?  
- 🔍 Análisis realizado  
- 💻 Tecnologías y librerías utilizadas  
- 🚀 Resultados  
- ⚙️ Cómo ejecutar este proyecto  

---

## 🧠 ¿Qué incluye este proyecto?  
✅ Carga del dataset **Forest Cover Type (covtype.csv / .gz)**  
✅ Exploración de datos: identificación de variables categóricas y continuas  
✅ Limpieza y organización del dataset  
✅ Entrenamiento de clasificadores:  
- **Support Vector Machines (SVM)**  
- **Random Forest**  
✅ Evaluación de modelos con métricas de clasificación  
✅ Comparación de desempeño entre ambos algoritmos  

---

## 🔍 Análisis realizado  

1. **Carga del dataset**  
   - Se importó el dataset `covtype.csv` (581,012 instancias).  
   - Contiene **10 variables continuas** (elevación, pendiente, orientación, etc.).  
   - Contiene **45 variables categóricas** relacionadas con áreas silvestres y tipos de suelo.  

2. **Exploración de datos**  
   - Análisis descriptivo de las variables.  
   - Identificación de la variable objetivo: **Cover_Type**.  

3. **Preprocesamiento**  
   - Conversión y tratamiento de variables categóricas.  
   - Normalización de variables continuas.  

4. **Entrenamiento de modelos**  
   - **SVM**: se probaron kernels y se ajustaron hiperparámetros.  
   - **Random Forest**: se ajustaron número de árboles y profundidad máxima.  

5. **Evaluación de modelos**  
   - Cálculo de métricas: **Accuracy, Precision, Recall, F1-score**.  
   - Matriz de confusión para cada clasificador.  
   - Comparación del rendimiento entre SVM y Random Forest.  

---

## 💻 Tecnologías y librerías utilizadas  

- Python 3  
- NumPy  
- Pandas  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

## 🚀 Resultados  

📊 Los resultados muestran diferencias en desempeño:  
- El **Random Forest** logró una mejor **accuracy** en el dataset al manejar bien la gran cantidad de variables categóricas.  
- El **SVM** mostró limitaciones en escalabilidad con este volumen de datos, pero fue útil en la comparación de clasificación.  

El análisis comparativo evidenció cómo distintos modelos se adaptan a datasets grandes y desbalanceados.  

---

## ⚙️ Cómo ejecutar este proyecto  

1. Clona este repositorio en tu máquina:  
   ```bash
   git clone https://github.com/usuario/Clasificacion-SVM_Random-forest.git
