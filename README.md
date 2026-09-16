# DBSCAN — Turismo interno, EGIT IV trimestre 2024

Este repositorio contiene una demostración de DBSCAN con datos reales de turismo interno.

## Contenido

- `Base de datos-EGIT-Base Anonimizada-IV trim2024/TURISMO.csv`, microdatos anonimizados del archivo Turismo usados como fuente del ejercicio.
- `01_preparacion_turismo.ipynb`, carga `TURISMO.csv`, filtra los viajes internos, crea las variables noches de viaje y gasto total, revisa su distribución y exporta la base lista.
- `datos_procesados/turismo_interno_dbscan.csv`, base final con 1.399 registros y las dos variables de trabajo.
- `02_dbscan_turismo.ipynb`, carga la base lista, visualiza los datos, prepara las distancias, explica DBSCAN y compara `eps` y `min_samples` mediante gráficos.

## Fuente de datos

Los datos provienen de la **Encuesta de Gasto Interno en Turismo (EGIT) 2024**, IV trimestre, del Departamento Administrativo Nacional de Estadística (DANE). Se utiliza el archivo de datos **Turismo**, publicado por el DANE como base anonimizada.

- [Catálogo y diccionario de datos: archivo Turismo, EGIT 2024](https://microdatos.dane.gov.co/index.php/catalog/864/data-dictionary/F17?file_name=Turismo)
- [Descarga de microdatos EGIT 2024](https://microdatos.dane.gov.co/index.php/catalog/864/get-microdata)

## Ejecución

1. Abrir y ejecutar primero `01_preparacion_turismo.ipynb`.
2. Confirmar que se generó `datos_procesados/turismo_interno_dbscan.csv`.
3. Abrir y ejecutar `02_dbscan_turismo.ipynb`.

El repositorio conserva únicamente el archivo anonimizado `TURISMO.csv`, los notebooks y la base final utilizada en la demostración. Los demás archivos originales de EGIT y los materiales locales de consulta no se versionan.
