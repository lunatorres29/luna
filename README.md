# luna
# Representación de Imágenes mediante Píxeles en Excel 🖼️📊

Proyecto desarrollado en **Python** que analiza una imagen digital, extrae los valores de color de cada píxel y los representa visualmente en una hoja de **Excel** utilizando celdas coloreadas.

---

## Descripción 📖

Las imágenes digitales están compuestas por miles de píxeles, y cada uno contiene información de color representada mediante valores **RGB (Red, Green, Blue)**.

En este proyecto se utiliza **Python en Google Colab** para cargar una imagen, analizar los valores de color de cada píxel y organizar esa información como datos.

Posteriormente, estos datos se exportan a un archivo de **Excel**, donde cada celda representa un píxel de la imagen original y se colorea según sus valores RGB.

---

## Proceso del programa ⚙️

El notebook realiza el procesamiento de la imagen en diferentes etapas:

- Conectar **Google Drive** para acceder a los archivos  
- Cargar la imagen utilizando librerías de Python  
- Leer los valores de color de cada píxel  
- Organizar los datos en una matriz de valores RGB  
- Crear un archivo de **Excel**  
- Colorear cada celda según el valor RGB del píxel  

---

## Tecnologías utilizadas 🧰

- Python  
- Google Colab  
- Pillow (PIL)  
- OpenPyXL  
- Matplotlib  

---

## Resultado 📊

El resultado final es un archivo de Excel donde cada celda representa un píxel de la imagen original. Las celdas están coloreadas según los valores RGB, recreando visualmente la imagen dentro de la hoja de cálculo.

---
