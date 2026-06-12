# Error diagnóstico en endometriosis

Proyecto final de la materia **Visualización de Datos y Narración de Historias**.

## Descripción

Este proyecto analiza patrones asociados a errores diagnósticos en pacientes con endometriosis. El análisis se basa en un dataset sintético reconstruido a partir del estudio *Diagnosing diagnostic error of endometriosis: a secondary analysis of patient experiences from a mixed-methods survey*.

El objetivo fue identificar en qué etapas del proceso clínico se concentran los errores, qué síntomas y desafíos diagnósticos aparecen con mayor frecuencia, y si es posible anticipar la etapa del error mediante técnicas de aprendizaje automático.

## Contenido del repositorio

- `graficos_visualización.py`: código utilizado para generar visualizaciones, modelo Random Forest y PCA.
- `lREPORTE.pdf`: reporte final del proyecto.
- `05_sankey.html`: visualización interactiva Sankey.
- Archivos `.png`: visualizaciones utilizadas en el reporte y presentación.

## Herramientas utilizadas

- Python
- pandas
- numpy
- matplotlib
- plotly
- scikit-learn
- Google Colab
- Canva

## Visualizaciones generadas

- Distribución de errores diagnósticos por etapa.
- Distribución de carga total de síntomas.
- Síntomas más frecuentes.
- Desafíos diagnósticos más frecuentes.
- Diagrama Sankey.
- Matriz de confusión Random Forest.
- PCA de perfiles sintomáticos.

## Resultados principales

Los errores diagnósticos se concentran principalmente en las etapas de **History** y **Assessment**. Además, las pacientes presentan múltiples síntomas simultáneamente, lo que respalda la hipótesis de que la diversidad y superposición sintomática dificulta la identificación temprana de la endometriosis.

## Visualización interactiva

El diagrama Sankey puede consultarse en el archivo:

`05_sankey.html`

## Autoras

- Andrea Citlalli Alcalá Armenta
- Raquel Mireles Aretia
