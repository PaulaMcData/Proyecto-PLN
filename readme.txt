# Proyecto Final - Procesamiento del Lenguaje Natural

**🎬 Clasificación de Sentimientos en Reseñas de Películas con Modelos Clásicos y Redes Neuronales Sencillas**

**Asignatura:**
Procesamiento del Lenguaje Natural
Máster en Data Science - IEBS
2025

## 🎯  Objetivo del proyecto:
Desarrollar un sistema de clasificación de sentimientos utilizando el dataset `movie_reviews` de NLTK. Se comparan dos enfoques: un modelo clásico de Naive Bayes y una red neuronal sencilla implementada con Keras. Además, se aplica un preprocesamiento robusto y se analizan métricas de evaluación como precisión, recall, F1-score y curvas ROC. El proyecto incluye visualizaciones relevantes y una reflexión final en Medium.

## 📁 Contenido del repositorio:
- `Proyecto_PLN.ipynb`: Notebook con el desarrollo completo del proyecto
- `Proyecto_PLN.pdf`: Notebook completo en versión PDF
- `requirements.txt`: Lista de dependencias utilizadas en el entorno
- `envNLP`: Entorno virtual (añadido`.gitignore`)
- `readme.txt`: Este archivo con instrucciones y detalles del trabajo
- Artículo en Medium (https://medium.com/@paulamc.data/clasificación-de-sentimientos-en-reseñas-de-películas-naive-bayes-vs-red-neuronal-con-keras-c33c29b24839)

## 🚀 Instrucciones para ejecutar el proyecto:
1. Crear el entorno virtual (si no está creado):  
   `python3 -m venv .venv`
2. Activarlo:  
   `source .venv/bin/activate`
3. Instalar dependencias:  
   `pip install -r requirements.txt`
4. Ejecutar el notebook `Proyecto_PLN.ipynb` paso a paso.
5. (Opcional) Si usas Jupyter fuera de entorno virtual, instalar kernel:  
   `python -m ipykernel install --user --name=pln_env --display-name "Python_PLN"`


## 📊 Resultados destacados
- Naive Bayes: 81% accuracy
- Red Neuronal (Keras v2): 77% accuracy, 85% recall en clase positiva

## 👩‍💻 Autor
Paula Miranda Cerón