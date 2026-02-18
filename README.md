# water-stress-forecast-spain
Time-series modeling and early drought risk detection using Spanish reservoir data (1988–present).

## Datos

Los datos históricos de embalses provienen del Ministerio para la Transición Ecológica:

- URL del ZIP: [BD-Embalses.zip](https://www.miteco.gob.es/content/dam/miteco/es/agua/temas/evaluacion-de-los-recursos-hidricos/boletin-hidrologico/Historico-de-embalses/BD-Embalses.zip)

### Instrucciones para reproducir los datos

1. Descargar el ZIP desde la URL oficial.
2. Extraer el archivo `BD-Embalses.mdb` en `data/embalses_data/`.
3. Ejecutar el notebook `01_pipeline_embalses.ipynb` para convertir la base de datos a CSV y hacer la limpieza inicial.
4. Todos los CSV generados se guardarán en la carpeta `files/`.