# Análisis Morfológico de Parcelas Urbanas (Madrid y Barcelona)

Este repositorio contiene los scripts y notebooks utilizados para el análisis de cambios en la morfología de las parcelas urbanas en las ciudades de Madrid y Barcelona. Este trabajo forma parte de un Trabajo de Fin de Máster (TFM), que se enfoca en el análisis catastral y los cambios morfológicos observados entre los años 2023 y 2024.

## Estructura del Proyecto

El proyecto se divide en tres componentes principales:

1. **Automatización BDG.ipynb**:
   - Este notebook automatiza la carga y procesamiento de bases de datos geoespaciales utilizando PostgreSQL y PostGIS.
   - Crea carpetas estructuradas automáticamente para la entrega y almacenamiento de los archivos procesados.
   
2. **TFM_barcelona_new.ipynb**:
   - Notebook específico para el análisis morfológico de las parcelas urbanas de Barcelona.
   - Incluye el cálculo de métricas morfológicas como la relación Perímetro-Área (cPA) y la compacidad, además de la clasificación de cambios en las parcelas.

3. **TFM_madrid_new.ipynb**:
   - Similar al notebook anterior, pero enfocado en la ciudad de Madrid.
   - Se lleva a cabo un análisis detallado de las transformaciones geométricas y el uso del suelo.

## Requisitos

Antes de ejecutar los notebooks, asegúrate de tener instalados los siguientes requisitos:

- Python 3.x
- Librerías de Python:
  - `pandas`
  - `geopandas`
  - `shapely`
  - `psycopg2`
  - `sqlalchemy`
  - `matplotlib`
  - `numpy`
  - `os` (incluida en Python)
  
Además, asegúrate de tener configurada una base de datos PostgreSQL con soporte para PostGIS.

## Instalación

1. Clona este repositorio en tu máquina local:

```bash
git clone https://github.com/SebastianUrintive/ANALISIS-DE-CAMBIOS-EN-LA-MORFOLOGIA-DEL-PARCELARIO-URBANO-EN-CIUDADES-ESPANOLAS.git
