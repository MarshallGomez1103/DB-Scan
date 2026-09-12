# DBSCAN — Turismo interno, EGIT IV trimestre 2024

Este repositorio contiene una demostración de DBSCAN con datos reales de turismo interno.

## Contenido

- `01_preparacion_turismo.ipynb`, carga `TURISMO.csv`, filtra los viajes internos, crea las variables noches de viaje y gasto total, revisa su distribución y exporta la base lista.
- `datos_procesados/turismo_interno_dbscan.csv`, base final con 1.399 registros y las dos variables de trabajo.
- `02_dbscan_turismo.ipynb`, carga la base lista, visualiza los datos, prepara las distancias, explica DBSCAN y compara `eps` y `min_samples` mediante gráficos.

## Ejecución

1. Abrir y ejecutar primero `01_preparacion_turismo.ipynb`.
2. Confirmar que se generó `datos_procesados/turismo_interno_dbscan.csv`.
3. Abrir y ejecutar `02_dbscan_turismo.ipynb`.

Los microdatos originales y los archivos locales de consulta no se versionan. El repositorio conserva los notebooks y la base final utilizada en la demostración.
