# Análisis de Clustering para Segmentación de Productos Vanish

Este repositorio contiene un análisis de segmentación del portafolio de productos **Vanish** mediante técnicas de **Machine Learning No Supervisado**, específicamente el algoritmo **K-Means**. El objetivo es identificar grupos homogéneos de productos con base en ventas, precios y atributos para optimizar decisiones comerciales y de marketing.

## 📊 Objetivo

Identificar clusters de productos Vanish con características similares para:

- Detectar segmentos estrella y premium
- Evaluar productos de bajo rendimiento
- Proponer estrategias diferenciadas por grupo

## 🧠 Metodología

1. **Filtrado de datos** de productos Vanish
2. **Estandarización de variables**
3. **Codificación One-Hot** para variables categóricas
4. **Aplicación de K-Means**
5. **Evaluación con el método del codo**
6. **Visualización de clusters con PCA**


## 📌 Resultados

Se identificaron 5 clusters con características diferenciadas. Los clusters clave incluyen productos de alto volumen y precios accesibles, así como un grupo premium con buen desempeño económico.

## 📄 Reporte

El análisis detallado está disponible en clustering_vanish.pdf.

## 🛠 Requisitos

- Python 3.10+
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter

Puedes instalar todo con:

```bash
pip install -r requirements.txt
