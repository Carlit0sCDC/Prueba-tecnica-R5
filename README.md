# Análisis de Calidad de Datos en Dataset de Spotify

Este repositorio contiene los archivos y el código desarrollado para abordar la Prueba Técnica como Data Quality Engineer relacionada con el procesamiento de datos de la API de Spotify y el análisis de calidad de dichos datos.

## Estructura del Repositorio

- **scripts/:** Archivo que contiene el script en Python para procesar el archivo JSON de la API de Spotify y generar el archivo `dataset.csv`.
- **reporte/:** Carpeta donde se almacenan los archivos de datos utilizados y generados durante el proceso.
- **report/:** Archivo PDF que contiene el reporte generado tras el análisis de calidad de datos.

## Archivos Relevantes

- **taylor_swift_spotify.json:** Archivo original obtenido de la API de Spotify con información de Taylor Swift.
- **dataset.csv:** Archivo resultante del procesamiento, contiene los datos estructurados de acuerdo con el formato requerido.
- **data_quality_analysis.ipynb:** Cuaderno Jupyter utilizado para llevar a cabo el análisis de calidad de datos.
- **quality_report.pdf:** Reporte detallado que presenta las anomalías encontradas durante el análisis de calidad de datos.

## Proceso Realizado

### Parte 1: Procesamiento de Datos de la API de Spotify

- **Descripción:** Se desarrolló un script en Python utilizando las librerías Pandas y JSON para procesar el archivo JSON obtenido de la API de Spotify, generando el archivo `dataset.csv` con el formato requerido.

### Parte 2: Análisis de Calidad de Datos

- **Descripción:** Se realizó un análisis detallado del archivo `dataset.csv` para identificar anomalías y problemas de calidad de datos.
- **Cuaderno Jupyter data_quality_analysis.ipynb:** Contiene el código utilizado para identificar y documentar las anomalías encontradas.
- **Reporte quality_report.pdf:** Documenta las anomalías detectadas, incluyendo explicaciones detalladas y hallazgos relevantes.
