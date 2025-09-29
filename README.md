# Pronóstico del Índice Nacional de Precios al Consumidor (INPC)
El propósito del proyecto es implementar un modelo que permita analizar un pronóstico del Índice Nacional de Precios al Consumidor (INPC). En este sentido, se abordan los modelos SARIMA, VAR/VEC y de Factores Dinámicos, con el objetivo de pronosticar doce periodos de este índice, correspondientes al año 2022, a través de datos (y variables) del Indicador Oportuno de la Actividad Económica en México (IOAE). A lo largo de este análisis, se presenta el desarrollo de cada uno de los modelos mencionados con anterioridad para compararlos a partir del cálculo de sus respectivos errores de predicción mediante el error cuadrático medio (MSE por sus siglas en inglés); para con ello, finalmente elegir el mejor modelo y concluir si a mayor cantidad de información valiosa en los modelos ajustados, se obtiene una mejor precisión en los pronósticos.
## Contenido del repositorio

1. `Pronosticos_INPC_MAJ.RMD`: archivo principal en R Markdown, donde se desarrolla el modelo.
2. `Pronosticos_INPC_MAJ.pdf`: versión en PDF del archivo anterior, lista para consulta o difusión.
3. `functions.R`: archivo en R que contiene funciones que se utilizaron durante el desarrollo del modelo.
4. `IOAE`: base de datos con las 28 series temporales que conforman al IOAE, descargadas del portal de INEGI.
5. `IOAE2`: base de datos que contiene las 28 series temporales que integran el IOAE, incluyendo una estimación del último dato faltante en la serie de tiempo del IGAE.
6. `Pronosticos INPC`: Contiene los pronósticos realizados a 12 meses del INPC con los tres modelos aplicados 
5. `INEGI.png`: logotipo institucional del INEGI en el documento.

Información de contacto Autora: Martha Aguilar Jiménez, Correo electrónico:martha.aguilar@cimat.mx
