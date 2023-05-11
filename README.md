# Proyecto Final - Night Traders

<p align="center">
<img src="https://github.com/Guzz0/NIGHT_TRADERS/blob/main/VISUALIZACION/candle.png" width="40%" style='border-radius:20%'>
</p>





En este proyecto de **Big Data**, nos hemos enfocado en analizar y predecir el cierre de huecos nocturnos bursátiles utilizando diferentes índices bursátiles y variables financieras. Inicialmente, comenzamos utilizando datos de Alpha Advantage, pero debido a complicaciones en la obtención de datos, decidimos descargarlos de Yahoo Finance.

Una vez obtenidos los datos de <font color='purple'>Yahoo Finance</font> , agregamos índices bursátiles y otras variables relevantes para nuestro objetivo. Evaluamos diversas combinaciones de índices y variables para determinar cuáles eran las más importantes y necesarias. Para mejorar nuestras predicciones, implementamos una función que desplaza todos los índices bursátiles un día hacia adelante.

Posteriormente, llevamos a cabo pruebas con diversos modelos de aprendizaje automático, como redes neuronales,  Random Forest y Gradient Boosting, entre otros. Después de compararlos exhaustivamente, seleccionamos el modelo de ensamble Stacking Classifier como nuestro enfoque óptimo.

Aplicamos el modelo de Stacking Classifier en un conjunto de datos final compuesto por los últimos 30 días de movimientos bursátiles, lo que nos permitió obtener predicciones actualizadas y relevantes para el cierre de huecos nocturnos bursátiles. Con estos resultados, creamos un dashboard en Tableau que facilita a los clientes el acceso rápido y eficaz a las predicciones de nuestro modelo.

Este proyecto se ha centrado en predecir el cierre de huecos nocturnos bursátiles utilizando diferentes índices bursátiles y variables financieras. Hemos explorado diversas fuentes de datos, índices, variables y modelos de aprendizaje automático para optimizar nuestras predicciones. **Como resultado**, seleccionamos el modelo Stacking Classifier y lo aplicamos en un conjunto de datos objetivo que contiene los últimos 30 días de movimientos bursátiles. Finalmente, hemos creado un dashboard en *Tableau* que brinda a los clientes un acceso fácil y rápido a las predicciones de nuestro modelo, facilitando la toma de decisiones en el ámbito financiero y bursátil.


## Descripción del proyecto

El objetivo de este proyecto es desarrollar una aplicación para análisis de datos financieros en empresas cotizadas en el IBEX35 con la finalidad de predecir si existirá un cierre del gap en la apertura de la sesión del día siguiente.

<!-- imagen del ibex -->

<!-- tabla de markdown -->

| Archivo | Descripción | 
| --- | --- |
| `README.md` | Archivo con la descripción del proyecto |
| [ARQUITECTURA](https://github.com/Guzz0/NIGHT_TRADERS/tree/main/ARQUITECTURA)| Carpeta con los archivos de la arquitectura del proyecto |
| [NOTEBOOKS](https://github.com/Guzz0/NIGHT_TRADERS/tree/main/NOTEBOOKS) | Carpeta con los notebooks de los análisis realizados |
| [VISUALIZACION](https://github.com/Guzz0/NIGHT_TRADERS/tree/main/VISUALIZACION) | Carpeta con las visualizaciones realizadas |
| [PresentacionTFG.pdf](https://github.com/Guzz0/NIGHT_TRADERS/blob/main/PresentacionTFB.pdf) | Presentación del proyecto |

## Arquitectura

<!-- IMAGE OF ARQUTIECTURA -->
![image.svg](https://github.com/Guzz0/NIGHT_TRADERS/blob/main/ARQUITECTURA/Arquitectura.svg)


