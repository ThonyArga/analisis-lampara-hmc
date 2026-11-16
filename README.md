# Análisis de degradación de lámpara - Heraeus Medevio

Este repositorio contiene los recursos computacionales (código fuente y datos sintéticos) correspondientes al análisis del Capítulo 4 del Proyecto de Graduación de Anthony Roberto Guzmán Agüero, desarrollado en el Instituto Tecnológico de Costa Rica (ITCR) en colaboración con Heraeus Medevio.

## Estructura del repositorio

*   `Analisis_degradacion_lampara_final.ipynb`: Notebook principal en Python. Contiene el procesamiento de datos, ajuste de modelos de degradación, análisis estadísticos (bootstrap y correlaciones) y la generación de tablas y figuras.
*   `datos_sinteticos.xlsx`: Conjunto de datos generados estadísticamente. Su propósito es garantizar la reproducibilidad metodológica del análisis sin comprometer la confidencialidad de la información productiva de la empresa.
*   `requirements.txt`: Declaración de dependencias de Python necesarias para la ejecución del entorno.
*   `.gitignore`: Configuración del control de versiones para excluir archivos con datos originales sensibles.

## Instrucciones de ejecución

1. Importar el archivo `Analisis_degradacion_lampara_final.ipynb` en Google Colab u otro entorno compatible con Jupyter.
2. Ejecutar secuencialmente todas las celdas (`Runtime > Run all`). El algoritmo está programado para buscar archivos de datos locales; en caso de no encontrarlos, descargará automáticamente el conjunto de datos sintéticos alojado en este repositorio.
3. *Nota metodológica:* Las gráficas y métricas derivadas de la ejecución con los datos sintéticos tienen fines demostrativos y de validación del código. No representan la degradación física real del componente, la cual se documenta exclusivamente en el informe final utilizando los datos originales.

## Autor

**Anthony Roberto Guzmán Agüero**
Instituto Tecnológico de Costa Rica
Contacto: anthony.guzman@estudiantec.cr
