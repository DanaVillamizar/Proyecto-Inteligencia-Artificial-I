<div align="center">

# Diagnóstico de diabetes basado en datos clínicos

## Autores  
[Dana Villamizar](https://github.com/DanaVillamizar)  [Sneider Sánchez](https://github.com/Sneider-exe)  [Diego Guerrero](https://github.com/DanaVillamizar)

</div>

## Objetivo  
Desarrollar un sistema de predicción de diabetes tipo 2 mediante algoritmos de inteligencia artificial, entrenados con datos clínicos como edad, glucosa, BMI, insulina, presión sanguínea, etc.
El sistema incorpora técnicas de aprendizaje supervisado y no supervisado, incluyendo algoritmos genéticos para la selección automática de características, así como métodos de reducción de dimensionalidad (PCA y t-SNE) que fueron evaluados como insumo para modelos de clasificación.
Se busca optimizar la precisión diagnóstica y explorar la viabilidad de su aplicación como herramienta de apoyo en entornos clínicos reales.

## Dataset Utilizado

###  [Pima Indians Diabetes Database](https://www.kaggle.com/code/mragpavank/pima-indians-diabetes-database)
El Pima Indians Diabetes Database es un conjunto de datos clínicos recolectado por el Instituto Nacional de Diabetes y Enfermedades Digestivas y Renales de EE. UU., que contiene información médica de mujeres de etnia Pima, mayores de 21 años.
Incluye variables como número de embarazos, concentración de glucosa en plasma, presión arterial, espesor del pliegue cutáneo, insulina, IMC, función hereditaria de la diabetes y edad.

##  Modelos Utilizados

- **Random Forest, SVM y MLP (Red Neuronal Multicapa):**  
  Implementados y comparados con y sin reducción de dimensionalidad mediante PCA.

- **PCA y t-SNE:**  
  Técnicas de reducción de dimensionalidad utilizadas para visualización y exploración de estructuras internas en los datos.

- **K-Means y DBSCAN:**  
  Algoritmos de clustering no supervisado empleados para identificar agrupaciones de pacientes con características similares.

- **Algoritmo Genético:**  
  Aplicado para selección automática de características relevantes, mejorando la interpretabilidad y el rendimiento de los modelos supervisados.

## 🔗 Enlaces del Proyecto

- 🎥 [Video resumen en YouTube](https://youtu.be/l61ppLkPrUE)  
- 📓 [Notebook en Google Colab](https://colab.research.google.com/drive/1fyvP4pEY_R4zRbl12tPezxp2lcpBygCm?usp=sharing)  
- 📊 [Presentación en Canva](https://www.canva.com/design/DAGmHHSToas/U3WqjFRi_VsY8ahnyw-ZuQ/edit?utm_content=DAGmHHSToas&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)

