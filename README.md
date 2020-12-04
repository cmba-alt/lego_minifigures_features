# Extracción de características en imágenes de minifiguras LEGO.

**Integrantes**: Carolina Burgos, Edwin Caicedo, William Moreno

### Descripción del proyecto

En el presente proyecto se utiliza el dataset de [‘LEGO Minifigures’][kaggle] para extraer de él 121 imágenes de cuatro clases diferentes, y a partir de estas generar un nuevo dataset donde se encuentren características de la distribución del color en las imágenes con sus respectivas etiquetas, obtenidas a partir de histogramas. Adicionalmente, se realiza un estudio y análisis de los momentos de Hu para diferentes imágenes. Como resultado se obtiene el archivo lego_data.csv con las características de los histogramas y las etiquetas por clase.

## Disclaimer
The [dataset original][kaggle], owned by Yaroslav Isaienkov, with contributors Kostiantyn Isaienkov and Alina Zhuravel, is licensed under
[Creative Commons Attribution 4.0 International License][cc-by]. For this project, we used 121 images from the ones available in Kaggle, modified them by cropping then and extracted our own features with them.

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[kaggle]: https://www.kaggle.com/ihelon/lego-minifigures-classification
