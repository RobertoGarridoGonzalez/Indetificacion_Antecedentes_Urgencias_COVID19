# Extracción y codificación de enfermedades previas de los pacientes que ingresan por COVID-19 en urgencias mediante el uso de PLN

Los hospitales tienen su historia clínica digital donde se incorporan diagnósticos, trámites y seguimientos de enfermería. La mayor parte de la historia clínica se compone de texto libre. Este año de la pandemia Covid-19 ha exigido que los registros fueran rápidos y agiles para poder tratar en el menor tiempo posible a los pacientes y el uso del texto libre ha sido lo más utilizado por su rapidez. El reto está en extraer información estructurada de estos textos libres. 

El objetivo es el diseño y puesta en marcha de una arquitectura de NLP (elementos, corpus, modelos, etc) con el objetivo de extraer los códigos CIE-10 de las comorbilidades más relevantes en pacientes diagnosticados de COVID-19 a partir de las notas clínicas en texto libre registradas en una unidad de urgencias de un hospital intermedio.

Utilizaremos esta recolección de informes de urgencias exitentes para posterior entrenamiento del modelo (son 1000 informes que he bajado de aquí: https://zenodo.org/record/3837305#.YEn0Kmj0nRZ)

Está dividido en 3 partes: 
- conjunto de train para entrenar el modelo (500 archivos)
- conjunto de dev para afinarlo (250 archivos)
- conjunto de test para validar (250 archivos)

Los resultados de extraer y codificar las comorbilidades previas de los pacientes con COVID-19 en los informes de urgencias reales se pueden ver aqui:

[Idenficacion de Antecedentes y codificación CEI10 en informes de Urgencias](Idenficacion_Antecedentes_CEI10_Urgencias.ipynb)
