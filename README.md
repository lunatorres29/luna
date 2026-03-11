# luna
Representación de Imágenes con Píxeles en Excel 🖼️📊

Las imágenes digitales están formadas por miles de pequeños puntos llamados píxeles, y cada uno de ellos contiene información de color. Este proyecto busca mostrar cómo una imagen puede analizarse desde la programación, identificando los valores de color de cada píxel y organizándolos como datos.

Para esto se utiliza Python en Google Colab, donde una imagen es procesada y sus valores de color RGB (Red, Green, Blue) son extraídos y transformados en una representación dentro de una hoja de Excel.

Idea principal del proyecto

El propósito del programa es demostrar que una imagen no solo es algo visual, sino también una estructura de datos que puede manipularse mediante código.

A través del análisis de píxeles, el programa toma la información de color de la imagen y la organiza en una hoja de cálculo, permitiendo observar cómo cada píxel puede representarse como una celda con su color correspondiente.

Proceso del programa

El notebook sigue una serie de pasos para lograr esta transformación:

Acceder a los archivos almacenados en Google Drive.

Abrir la imagen utilizando librerías de procesamiento de imágenes en Python.

Leer los valores de color de cada píxel.

Organizar estos valores en una estructura de datos.

Generar un archivo de Excel donde cada celda se colorea según el valor RGB del píxel.

Herramientas utilizadas

Para desarrollar este proyecto se utilizaron las siguientes tecnologías:

Python

Google Colab

Pillow (PIL) para el manejo de imágenes

OpenPyXL para crear y editar archivos de Excel

Matplotlib para visualizar la imagen

Resultado

El resultado final es un archivo de Excel que reproduce visualmente la imagen original utilizando celdas coloreadas. De esta forma se puede observar cómo los píxeles de una imagen pueden transformarse en datos organizados dentro de una hoja de cálculo.


