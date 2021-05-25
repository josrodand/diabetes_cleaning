# diabetes_cleaning

Proyecto de limpieza y análisis del conjunto de datos Pima Indians Diabetes, obtenido de la plataforma Kaggle.

## Miembros del Equipo

Proyecto desarrollado de manera individual por **José Luis Rodríguez Andreu**.

# Descripción del proyecto

El objetivo de esta proyecto es la realización de un proceso de limpieza de un conjunto de datos. Para ello, se ha escogido el conjunto de datos Pima Indians Diabetes de la plataforma Kaggle (https://www.kaggle.com/uciml/pima-indians-diabetes-database).

Este conjunto de datos contiene información médica sobre mujeres relacionada con el diagnóstico de la diabetes. Consta de 768 observaciones con las siguientes variables:

* `Pregnancies`: Número de embarazos que ha tenido la paciente.
* `Glucose`: Concentración de glucosa en plasma a las 2 horas en una prueba oral de tolerancia a la glucosa.
* `BloodPressure`: Presión arterial diastólica (mm Hg)
* `SkinThickness`: Espesor del pliegue cutáneo del tríceps (mm)
* `Insulin`: Insulina en suero a las 2 horas (mu U/ml)
* `BMI`: Índice de masa corporal
* `DiabetesPedigreeFunction`: Función de pedigrí de la diabetes
* `Age`: Edad
* `Outcome`: Variable indicadora de que si la paciente padece o no de diabetes. La clase 1 indica que padece diabetes. 268 de 768 registros se encuentran etiquetados con 1.

Este conjunto de datos procede del Instituto Nacional de Diabetes y Enfermedades Digestivas y Renales de EEUU. El objetivo del conjunto de datos es realizar un diagnóstico predictivo sobre si un paciente tiene o no diabetes, basándose en determinadas mediciones de índole médica incluidas en el conjunto de datos. En este conjunto de datos, todos los pacientes registrados son mujeres de al menos 21 años de edad de origen "indio Pima". Por lo tanto, el objetivo principal de este proyecto es el de definir unas pautas de limpieza y preprocesado de datos para poder realizar un diagnóstico automático basado en técnicas de aprendizaje automático lo mas preciso posible.

La importancia del diseño de modelos de machine learning capaces de realizar diagnósticos médicos con precisión ayuda a los profesionales de la medicina a la hora de atender pacientes, y desemboca en una mejora del propio sistema sanitario, ya que este tipo de diagnósticos permiten ahorrar costes en análisis y tiempo de los profesionales, permitiendo de esta manera la reinversión de esos gastos sanitarios en promover una atención médica de calidad, además de facilitar el trabajo al personal sanitario que frecuentemente, y mas en época de pandemia, se encuentra saturado por una alta carga de trabajo.

# Descripción del repositorio

* `LICENSE`: Documento de licencia
* **code**: Directorio con el codigo en R
    * `diabetes_cleaning.Rmd`: Fichero Rmarkdown con el código desarrollado.
    * `diabetes_cleaning.html`: Informe HTML generado a partir del código.
* **csv**: Directorio con el fichero del conjunto de datos `diabetes.csv`.
* **pdf**: Directorio con el documento PDF `descripcion_proyecto.pdf` de descripción del proyecto y respuesta a las preguntas.
