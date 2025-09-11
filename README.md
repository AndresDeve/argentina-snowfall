# Datos sobre nieve en Argentina

## Español

### Descripción

Este repositorio contiene datasets y scripts para analizar y visualizar tendencias de nevadas en Argentina (1985--2025).

El objetivo del repositorio es explicar como generé las visualizaciones que luego integré en un producto final en forma de **infografía**. Presenté la infografía al concurso [**Contar con Datos 2025**](https://udesa.edu.ar/contarcondatos) organizado por la [Universidad de San Andrés](https://udesa.edu.ar/) durante 2025.

A continuación pueden ver una versión preliminar de la **infografía**.

<p align="center">
  <img src="snowfall_infographic_español.png" alt="Snowfall Infographic" width="1000"/>
</p>

### Dataset

-   **Formato:** Archivos Parquet (`.parquet`)\
-   **Contenido:** Estimaciones diarias e interanuales de acumulación de nieve en Argentina\
-   **Fuente:** Derivados de datos de reanálisis climático (ERA5, ECMWF, Copernicus Climate Data Store)

### Disponibilidad de los datos

Al conjunto de datos lo descargué de: [reanalysis ERA5](https://cds.climate.copernicus.eu/cdsapp#!/dataset/reanalysis-era5-single-levels).  
ERA5 provee estimaciones horarias de un gran número de variables atmosféricas, terrestres y oceánicas.

Para este proyecto descargué datos de nevadas (snowfall) sobre el cuadrante correspondiente de Argentina  y para el período 1986–2025.  

- ERA5 hourly data on single levels from 1940 to present  
- Extensión espacial:  
  - Norte: -21.70°  
  - Oeste: -73.50°  
  - Sur: -55.20°  
  - Este: -53.50° 

**Nota**  
Los datos crudos de ERA5 fueron posteriormente **curados y posprocesados** en el cuaderno de Jupyter (`snowfall_july_2006_2025_ARG-español.ipynb`) para filtrar la región de estudio, agregar valores y generar el conjunto final utilizado en los análisis y visualizaciones.

### Visualizaciones

-   El script produce cuatro **visualizaciones**:
    -   Calendario de nevadas\
    -   Altibajos\
    -   Nieve en el territorio\
    -   Variabilidad en las nevadas\

### Requerimientos

-   Python 3.9+\
-   Librerías principales: `pandas`, `matplotlib`, `geopandas`, `shapely`, `xarray`\
-   Para la integración final: [Inkscape](https://inkscape.org)

### Tipografías

En las visualizaciones use: *Roboto*, *Oswald*, *Intrument serif*, *Lato*, *Inter*, y *Montserrat*.
Todas disponibles en [Google Fonts](https://fonts.google.com).\

### Licencia

-   **Código:** Licencia MIT (ver [LICENSE](LICENSE))\
-   **Figuras e infografías:** Por favor, acreditarme si reutilizas las visualizaciones o infografía.

------------------------------------------------------------------------

# Argentina Snowfall

## English

### Description

This repository contains datasets and a script for analyzing and visualizing snowfall trends in Argentina (1985--2025).

I built the repository to produce an **snowfall infographic** which I submitted to [**Contar con Datos 2025**](https://udesa.edu.ar/contarcondatos) contest organized by [Universidad de San Andrés](https://udesa.edu.ar/) during 2025.

Below you will find a preliminary version of the **snowfall infographic**.

<p align="center">
  <img src="snowfall_infographic1.png" alt="Snowfall Infographic" width="1000"/>
</p>

### Dataset

-   **Format:** Parquet (`.parquet`)\
-   **Content:** Daily to interannual estimates of snowfall accumulation across Argentina\
-   **Source:** Derived from reanalysis climate data (ERA5, ECMWF, Copernicus Climate Data Store)

### Data Availability

I downloaded the dataset from the [ERA5 reanalysis](https://cds.climate.copernicus.eu/cdsapp#!/dataset/reanalysis-era5-single-levels).  
ERA5 provides hourly estimates of a large number of atmospheric, land, and oceanic variables.

For this project, I retrieved snowfall data over Argentina for the period 1986–2025.

- ERA5 hourly data on single levels from 1940 to present  
- Spatial domain:  
  - North: -21.70°  
  - West: -73.50°  
  - South: -55.20°  
  - East: -53.50°

**Note**  
The raw ERA5 data was later **curated and post-processed** in the accompanying Jupyter notebook (`snowfall_july_2006_2025_ARG-english.ipynb`) to filter the study region, aggregate values, and generate the final dataset used for analysis and visualization.

### Visualizations

-   Code produces **individual panels**:
    -   Time series\
    -   Maps\
    -   Waffle charts\
    -   Lollipop plots\
-   Panels are then assembled into **final infographics** (done externally in Inkscape).\

### Requirements

-   Python 3.9+\
-   Libraries: `pandas`, `matplotlib`, `geopandas`, `shapely`, `xarray`\
-   For final assembly: [Inkscape](https://inkscape.org) (manual integration step)

### Fonts

Visualizations rely on fonts from [Google Fonts](https://fonts.google.com).\
- Make sure the fonts are installed locally or linked in the notebook.\
- *Roboto*, *Oswald*, *Intrument serif*, *Lato*, *Inter*, and *Montserrat*

### License

-   **Code:** MIT License (see [LICENSE](LICENSE))\
-   **Figures and visualizations:** Please credit author when reusing outputs.

------------------------------------------------------------------------
