# Alertas_pictogramas

![Orange and Black Illustration World Tuberculosis Day Instagram Post](https://github.com/Ghisbe/Alertas_pictogramas/assets/106556579/a73b5b29-6321-41a7-bf4c-f5ef4b60a894)


1. Introducción
Título de proyecto: "Sistema de alertas meteorologicas para personas con discapacidad sensorial, TDA, TDAH"

2. Integrantes:
- Figueroa	Gisela 
- Valverde	Marcela
- Villareal Barroso	Angel
- Rodriguez	Maria Gabriela
- Rodriguez	Maria Belen

3. Contexto y Problema
Contexto:
Según la Organización Mundial de la Salud para personas con discapacidad sensorial como con autismo o TDAH, la comprensión y respuesta a las señales de alertas puede ser complicada debido a la forma en que procesan la información. En emergencias, la falta de una comunicación efectiva y accesible puede llevar a situaciones peligrosas y aumentar el riesgo de daño.
El propósito es facilitar la comprensión de situaciones de emergencia y promover una respuesta adecuada por parte de las personas con discapacidades sensoriales, mejorando así su seguridad y autonomía en momentos críticos.

4. Objetivos del Proyecto
Objetivo principal:
- Generar pictogramas comprensibles a partir de alertas meteorológicas textuales para personas con discapacidades sensoriales.
Objetivos secundarios:
- Procesar el texto de las alertas mediante técnicas de lenguaje natural.
- Clasificar las alertas utilizando redes neuronales recurrentes.
  Generar pictogramas basados en la clasificación anterior.

5. Descripción del Dataset
Origen del Dataset: Alertas de FEMA. Extraido desde Kaggle.
Contenido del Dataset: Descripciones textuales de alertas, fechas, ubicaciones, categorías de alertas, etc.
En este dataset contiene diferentes tipo de alertas, el equipo eleigio segmentar el materiall y utilizar las alertas meteorologicas.
Link de dataset: https://www.kaggle.com/datasets/vivekvarma23/integrated-public-alert-and-warning-system/data

6. Metodología
- Procesamiento de Texto:
Preprocesamiento: limpieza, normalizacion, eliminación de stopwords, lematización, etc.
Tecnologías Utilizadas: SpaCy y NLTK para procesamiento de texto.
- Predicción de Alertas:
Modelo Utilizado: Redes Neuronales Recurrentes (RNNs).
- Generación de Pictogramas:
Herramientas Utilizadas: OpenCV e imagenes descargadas de https://www.flaticon.es/resultados?word=clima para su procesamiento.

Dataset procesados y usados para el modelo:
1- https://drive.google.com/file/d/1fs7dmydF11O-rw1xX3ZDZd-7dGew73lu/view?usp=drive_link
2- https://drive.google.com/file/d/1E2QjfTk4Ke6u1ZEnmsqWHETproJE5zVK/view?usp=drive_link

PROYECTO REALIZADO PARA ISPC 2024

