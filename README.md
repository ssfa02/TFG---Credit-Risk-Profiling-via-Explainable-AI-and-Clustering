# TFG - Segmentación Supervisada de Perfiles de Riesgo Crediticio mediante Valores SHAP

Este repositorio contiene el código desarrollado para el Trabajo de Fin de Grado (TFG) titulado "Segmentación Supervisada de Perfiles de Riesgo Crediticio mediante Valores SHAP". El proyecto propone una metodología de segmentación supervisada orientada al análisis del riesgo crediticio, combinando técnicas de aprendizaje automático, explicabilidad e identificación de perfiles mediante clustering.

El repositorio sirve como apoyo a la metodología, experimentación y resultados presentados en la memoria del TFG.

## Objetivo

El objetivo principal de este proyecto es identificar y caracterizar perfiles de riesgo crediticio a partir de los patrones explicativos generados por un modelo predictivo.

Para ello, se combinan técnicas de clasificación, explicabilidad, reducción de dimensionalidad, clustering y extracción de reglas interpretables.

## Alcance

- Análisis exploratorio de los datos (EDA).
- Entrenamiento de un modelo LightGBM.
- Interpretación mediante valores SHAP.
- Reducción de dimensionalidad con UMAP.
- Identificación de clusters mediante DBSCAN.
- Caracterización de perfiles mediante SkopeRules.
- Análisis descriptivo de los segmentos obtenidos.

## Estructura del repositorio

### Notebook principal

El repositorio contiene un único notebook que desarrolla toda la metodología propuesta:

- EDA
- LightGBM
- SHAP
- UMAP
- DBSCAN
- SkopeRules
- Perfilado descriptivo de clusters

## Dataset

El estudio utiliza el conjunto de datos German Credit Data, ampliamente utilizado en problemas de credit scoring y análisis del riesgo crediticio.

El dataset contiene información financiera, demográfica y relacionada con préstamos de 1.000 solicitantes de crédito.

**Fuente del dataset:**
- [German Credit Data (Kaggle)](https://www.kaggle.com/datasets/uciml/german-credit)

## Resultados

La metodología permite identificar grupos de clientes con patrones explicativos similares y caracterizarlos mediante reglas interpretables.

Los resultados obtenidos muestran diferencias significativas entre los perfiles identificados, permitiendo una mejor comprensión de los factores asociados al riesgo crediticio.

## Tecnologías

- Python
- Pandas
- Scikit-learn
- LightGBM
- SHAP
- UMAP
- DBSCAN
- SkopeRules

## Autora

Sofia González-Montagut Tanure
