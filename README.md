# competicion_ml_ia

## Objetivo de la competición

El reto consiste en desarrollar un modelo de machine learning para predecir con la mayor precisión posible la collision cross section (CCS) de nuevas moléculas y sus aductos.

# Datos disponibles

- Conjunto de entrenamiento: Archivo public_train.csv que contiene tanto las features como las etiquetas (valores CCS) para entrenar vuestro modelo.
- Conjunto de test: Archivo public_test.csv que contiene únicamente las features. Los valores CCS de este conjunto no se proporcionan y serán utilizados para evaluar vuestro modelo.

## Formato de las predicciones

Debéis generar un archivo CSV con las predicciones de vuestro modelo sobre el conjunto de test. El archivo debe:

- Contener una única columna sin cabecera
- Cada fila debe contener la predicción del valor CCS correspondiente
- El orden de las predicciones debe corresponder con el orden de las muestras en public_test.csv

## Rendimiento de los modelos

El rendimiento de vuestros modelos se evaluará utilizando la métrica MEDAE (Median Absolute Error): Esta métrica es robusta frente a valores atípicos y penaliza las desviaciones en las predicciones de manera uniforme, independientemente de la magnitud del valor CCS.

## Entregables

1. Repositorio GitHub
- Crear un repositorio privado que incluya todo el código del proyecto
- Todos los miembros del equipo deben figurar como colaboradores
- Invitar al profesor (usuario: constantino-garcia) como colaborador
2. Jupyter Notebook Entregar a través del campus virtual un notebook que
contenga, como mínimo, las siguientes secciones:
- Preprocesamiento de datos: Documentación de todas las transformaciones y limpieza realizadas
- Entrenamiento y estimación del error: Desarrollo y validación del modelo
- Generación de predicciones: Proceso de obtención de las predicciones finales
- Conclusiones: Análisis crítico del trabajo realizado, incluyendo:
– Limitaciones identificadas
– Posibles mejoras
– Lecciones aprendidas
3. Predicciones
- Archivo test_preds.csv con las predicciones del modelo sobre el conjunto de test
- Entregar a través del campus virtual
4. Evaluación del trabajo en equipo
- Completar la rúbrica de evaluación del trabajo en equipo
- El enlace a la rúbrica se proporcionará más adelante
- Los alumnos que no completen la rúbrica de todos los demás miembros del equipo no recibirán su nota de prácticas