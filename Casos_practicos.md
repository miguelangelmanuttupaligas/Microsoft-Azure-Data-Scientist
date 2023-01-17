Emplear modelo de ML, que usa una BD PostgreSQL y necesita
procesar en GPU para pronosticar precios. Está creando una VM que
tenga las herramientas necesarioas integradas.

1. Edición de Windows de Geo AI Data Science Virtual Machine (Geo-DSVM). **NO**
2. Edición de Windows de Deep Learning Virtual Machine (DLVM). **NO**
3. Edición de Windows de Data Science Virtual Machine (DSVM). **YES**

Evaluar su modelo en una muestra de datos parciales a través de K-Fold.
Ha configurado un parámetro k como N° splits. Configurar "k" para
la validación cruzada con la opción de valor habitual.
> Usualmente es k = 5 o 10

1. Configure el uso del valor k = 3. **NO**
2. Configure el uso del valor k = 10. **YES**
3. Configure el uso del valor k = 1. **NO**

Está creando un modelo de ML. Su dataset incluye valores nulos y faltantes.
Planea usar módulo Limpiar datos en Azure ML Studio para detectar y corregir

1. Hacer uso de opción Reemplazar con mediana. **YES**
2. Hacer uso de opción Sustitución customizada. **YES**
3. Hacer uso de opción Remover fila entera. **YES OR NO**

Está en el proceso de llevar a cabo la ingeniería de características en un conjunto de datos.
Desea agregar una característica al conjunto de datos y completar el valor de la columna.

1. Debe hacer uso del módulo Group Categorical Values ​​Azure Machine Learning Studio. **NO**
2. Debe hacer uso del módulo Join Data Azure Machine Learning Studio. **NO**
3. Debe hacer uso del módulo Editar metadatos de Azure Machine Learning Studio. **NO**

Tarea de construir un modelo de aprendizaje automático que traduzca el texto de un idioma a un texto de otro idioma.
El modelo de aprendizaje automático debe construirse y entrenarse.

1. Utiliza neuronales convolucionales (CNN). **NO**
2. Utiliza redes neuronales recurrentes (RNN). **YES**
3. Utiliza redes generativas antagónicas (GAN). **NO**

Tiene previsto utilizar el diseñador de Azure Machine Learning para entrenar modelos.
Debe elegir un tipo de cálculo adecuado.

1. Elige Computación adjunta. **NO**
2. Elige Cluster de inferencia. **NO**
3. Elige Cluster de computo. **YES**

Utiliza Azure Machine Learning Studio para realizar la ingeniería de características en un conjunto de datos.
Debe normalizar los valores para producir una columna de características agrupada en contenedores.

1. Aplica Entropy Minimum Description Length (MDL) binning mode. **NO**
2. Aplica Quantiles normalization with a QuantileIndex normalization. **YES**

Está creando un nuevo experimento en Azure Machine Learning Studio.
Una clase tiene un número mucho menor de observaciones que las otras clases en el conjunto de entrenamiento.
Debe seleccionar una estrategia de muestreo de datos adecuada para compensar el desequilibrio de clases.

1. Utiliza el modo de muestreo Scale and Reduce. **NO**

Está analizando un conjunto de datos numéricos que contiene valores faltantes en varias columnas.
Debe limpiar los valores que faltan mediante una operación adecuada sin afectar la dimensionalidad del conjunto de características.
Debe analizar un conjunto de datos completo para incluir todos los valores.

1. Utilice el método de la última observación realizada (LOCF) para imputar los puntos de datos que faltan. **YES**
2. Reemplace cada valor faltante utilizando el método de imputación múltiple por ecuaciones encadenadas (MICE). **YES**
3. Elimine toda la columna que contiene el punto de datos que falta. **NO**
4. Calcule el valor de la mediana de la columna y use el valor de la mediana como reemplazo de cualquier valor faltante en la columna. **YES**

Es un científico de datos que usa Azure Machine Learning Studio.
Debe normalizar los valores para producir una columna de salida en contenedores para predecir una columna de destino.

1. Aplique un ancho igual con el modo de agrupamiento personalizado de inicio y detención. **NO**
2. Aplique un modo de binning de cuantiles con una normalización de PQuantile. **YES**