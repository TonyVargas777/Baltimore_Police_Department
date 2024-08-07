# Baltimore_Police_Department
<table><tr>
<td> <img src=https://www.baltimorepolice.org/themes/custom/bpd/images/bpd_logo.png alt="Drawing" style="height: 250px;"/> </td>
<td> <img src=https://beam-images.warnermediacdn.com/BEAM_LWM_DELIVERABLES/1bc3aff5-0d6a-4c0b-8ed0-5716ca30ab3b/fbbc7a604f327cfa8a7bbe614a89be13a246d266.jpg?host=wbd-images.prod-vod.h264.io&partner=beamcom style="height: 250px;"/> </td>
</tr></table>
# Análisis y Modelado del Dataset de Detenidos del Departamento de Policía de Baltimore (2013-2016)

Este repositorio contiene un análisis exhaustivo del dataset de detenidos por el Departamento de Policía de Baltimore entre 2013 y 2016. El proyecto se enfoca en tres áreas clave: limpieza de datos, visualización de datos y machine learning. A continuación, se describe el enfoque y los resultados obtenidos en cada una de estas áreas.

## 1. Limpieza de Datos

La limpieza de datos es un paso fundamental para garantizar la calidad y precisión del análisis. En esta etapa, se llevaron a cabo las siguientes actividades:

- **Eliminación de Duplicados:** Se identificaron y eliminaron registros duplicados en el dataset para asegurar que cada entrada fuera única.
- **Tratamiento de Valores Faltantes:** Se manejaron los valores faltantes en las columnas críticas utilizando técnicas de imputación o eliminación, según fuera apropiado.
- **Normalización de Datos:** Se estandarizaron las categorías y se convirtieron los datos en un formato uniforme para facilitar el análisis. Esto incluyó la conversión de datos categóricos a formatos numéricos y la normalización de texto.
- **Corrección de Errores:** Se corrigieron errores y inconsistencias en los datos, tales como errores tipográficos y formatos incorrectos.

## 2. Visualización de Datos

La visualización de datos es esencial para entender la distribución y las tendencias en el dataset. Se realizaron las siguientes visualizaciones:

- **Distribución de Delitos:** Se crearon gráficos de barras para mostrar la frecuencia de diferentes tipos de delitos, como delitos de drogas, crímenes violentos, y delitos de propiedad.
- **Tendencias Temporales:** Se generaron gráficos de líneas para analizar cómo la cantidad de arrestos varió a lo largo del tiempo, identificando posibles tendencias estacionales o anuales.
- **Distribución Geográfica:** Se utilizaron mapas de calor para visualizar la distribución geográfica de los arrestos, identificando áreas con alta incidencia de delitos.
- **Análisis Comparativo:** Se realizaron gráficos de dispersión y diagramas de caja para comparar diferentes variables, como la relación entre el tipo de delito y la hora del día o el día de la semana.

## 3. Machine Learning

En la etapa de machine learning, se aplicaron modelos predictivos para extraer información útil y hacer predicciones basadas en el dataset. Las actividades realizadas incluyeron:

- **Preparación de Datos para Modelado:** Se dividió el dataset en conjuntos de entrenamiento y prueba, y se realizaron técnicas de ingeniería de características para mejorar el rendimiento de los modelos.
- **Modelos Predictivos:** Se implementaron y evaluaron varios modelos de machine learning, incluyendo:
  - **Regresión Logística:** Utilizada para predecir la probabilidad de ciertos tipos de delitos basados en características específicas.
  - **Árboles de Decisión:** Aplicados para clasificar los tipos de delitos y evaluar la importancia de diferentes características.
  - **Random Forests:** Usado para mejorar la precisión de las predicciones mediante el uso de múltiples árboles de decisión.
  - **Máquinas de Soporte Vectorial (SVM):** Implementadas para clasificar los datos y encontrar el margen óptimo entre diferentes clases de delitos.
- **Evaluación de Modelos:** Se utilizaron métricas de evaluación como la matriz de confusión, la precisión, el recall, y la F1-score para medir el rendimiento de los modelos y ajustar los hiperparámetros según fuera necesario.

## Conclusión

El análisis del dataset de detenidos del Departamento de Policía de Baltimore ha proporcionado valiosos conocimientos sobre la distribución y las tendencias de los delitos en la ciudad durante el periodo de estudio. La limpieza de datos y la visualización permitieron una comprensión profunda del dataset, mientras que los modelos de machine learning ofrecieron perspectivas predictivas que pueden ayudar a mejorar la toma de decisiones y la planificación estratégica en la aplicación de la ley.

Para más detalles sobre el código y los resultados, por favor, consulta los archivos en el repositorio.

## Instalación y Uso

Para reproducir el análisis y los resultados, sigue estos pasos:

1. Clona el repositorio:
   ```bash
   git clone https://github.com/TonyVargas777/Baltimore_Police_Department
