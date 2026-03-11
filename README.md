# luna
Representación de Imágenes mediante Píxeles en Excel 🖼️📊

Proyecto desarrollado en Python que analiza una imagen digital, extrae los valores de color de cada píxel y los representa visualmente en una hoja de Excel utilizando celdas coloreadas.

Descripción 📖

Las imágenes digitales están compuestas por miles de píxeles, y cada uno contiene información de color representada mediante valores RGB (Red, Green, Blue).

En este proyecto se utiliza Python en Google Colab para cargar una imagen, analizar los valores de color de cada píxel y organizar esa información como datos.

Posteriormente, estos datos se exportan a un archivo de Excel, donde cada celda representa un píxel de la imagen original y se colorea según sus valores RGB.

De esta manera, se demuestra cómo una imagen puede interpretarse como una estructura de datos que puede ser procesada y visualizada mediante programación.

Proceso del programa ⚙️

El notebook realiza el procesamiento de la imagen en diferentes etapas:

Conexión con Google Drive para acceder a los archivos.

Carga de la imagen utilizando librerías de Python.

Lectura de los valores de color de cada píxel de la imagen.

Organización de los datos en una matriz de valores RGB.

Creación de un archivo de Excel.

Representación visual de la imagen coloreando cada celda según su valor RGB.

Tecnologías utilizadas 🧰

Para el desarrollo del proyecto se utilizaron las siguientes herramientas:

Python

Google Colab

Pillow (PIL) para el procesamiento de imágenes

OpenPyXL para generar y editar archivos de Excel

Matplotlib para visualizar la imagen

Estructura del proyecto 📂

El repositorio contiene los siguientes archivos principales:

Pixel_Programing.ipynb → Notebook donde se desarrolla todo el procesamiento de la imagen.

imagen.jpg → Imagen utilizada como ejemplo para el análisis de píxeles.

resultado.xlsx → Archivo generado con la representación de la imagen en Excel.

Cómo ejecutar el proyecto ▶️

Para ejecutar el proyecto se deben seguir los siguientes pasos:

Abrir el notebook en Google Colab.

Conectar la cuenta de Google Drive.

Cargar o seleccionar la imagen que se desea procesar.

Ejecutar las celdas del notebook en orden.

El programa generará un archivo de Excel donde la imagen se representa mediante celdas coloreadas.

Resultado 📊

El resultado final es un archivo de Excel donde cada celda representa un píxel de la imagen original. Las celdas están coloreadas según los valores RGB, recreando visualmente la imagen dentro de la hoja de cálculo.

Este ejercicio permite comprender cómo las imágenes pueden analizarse y transformarse en datos estructurados mediante programación.
