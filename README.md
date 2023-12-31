# Python Twitter Text Analysis

Este proyecto tiene como objetivo realizar el análisis de texto de tweets a partir de un archivo CSV sin procesar. El proceso incluye la etapa de preprocesamiento de los tweets, el conteo de palabras y la generación de wordclouds para cada cluster (positivo o negativo).

## Requisitos previos

- Python 3.x
- Librerías: pandas, numpy, matplotlib, wordcloud

## Instalación

1. Clona o descarga el repositorio desde GitHub: [PythonDataAnalysis](https://github.com/RudraFalconer/PythonDataAnalysis).

2. Asegúrate de tener las dependencias necesarias instaladas. Puedes hacerlo ejecutando el siguiente comando en la terminal:

   ```python terminal
   python setup.py install

De no funcionar el archivo setup.py probar
   ```python terminal
   pip install -r requirements.txt

Instrucciones básicas
Asegúrate de tener el archivo CSV de tweets sin procesar.

Abre el archivo main.py en un editor de texto.

Dentro del archivo main.py, busca la variable csv_file_path y actualiza la ruta del archivo CSV con la ubicación correcta en tu sistema.

Ejecuta el archivo main.py en tu entorno de Python.

shell
Copy code
python main.py
El programa realizará el preprocesamiento de los tweets, realizará el conteo de palabras y generará las wordclouds y el histograma correspondientes.

Características y funcionalidades principales
Eliminación de URLs y símbolos no ASCII en los tweets, así como caracteres no alfanuméricos.
Recuento de palabras para mostrar la frecuencia de aparición de cada palabra en todo el dataset.
Generación de dos wordclouds para cada cluster (positivo y negativo) y un histograma de palabras.
Contribuciones
Actualmente no se aceptan contribuciones para este proyecto.

Licencia
Este proyecto se distribuye bajo la licencia CC BY-NC-SA 4.0.

Contacto
Si tienes alguna pregunta o comentario adicional, no dudes en ponerte en contacto conmigo por correo electrónico: daniel.sohm06@gmail.com

Tests:

Run main.py
Then in console write
coverage report