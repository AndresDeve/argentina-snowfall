# Datos sobre nieve en Argentina

## Español

### Descripción

Este repositorio contiene datasets y cuadernos Jupyter en Python (`.ipynb`) para analizar y visualizar las tendencias de nevadas en Argentina (1985--2025).

El proyecto fue desarrollado para la producción de una **infografía** presentada al concurso **Contar con Datos 2025**.

El notebook (.ipynb) genera los **paneles individuales de visualización**, que luego los **integré manualmente en una infografía final usando Inkscape**.

El script y la infografía está disponibles en una versión en **español**.

<p align="center">
  <img src="snowfall_infographic_español.png" alt="Snowfall Infographic" width="600"/>
</p>

### Dataset

-   **Formato:** Archivos Parquet (`.parquet`)\
-   **Contenido:** Estimaciones diarias e interanuales de acumulación de nieve en Argentina\
-   **Fuente:** Derivados de datos de reanálisis climático (ERA5, ECMWF, Copernicus Climate Data Store)

### Visualizaciones

-   El código produce **paneles individuales**:
    -   Series temporales\
    -   Mapas\
    -   Gráficos de waffle\
    -   Gráficos de lollipop\
-   Los paneles son luego combinados en **infografías finales** (integradas en Inkscape).\

### Requerimientos

-   Python 3.9+\
-   Librerías principales: `pandas`, `matplotlib`, `geopandas`, `shapely`, `xarray`\
-   Para la integración final: [Inkscape](https://inkscape.org) (paso manual)

### Tipografías

Las visualizaciones utilizan tipografías de [Google Fonts](https://fonts.google.com).\
- Asegurate de instalarlas localmente o enlazarlas en el notebook.\
- *Roboto*, *Oswald*, *Intrument serif*, *Lato*, *Inter*, and *Montserrat*

### Estructura del repositorio

``` text
argentina-snowfall/
├── data/            # Datasets en Parquet
├── notebooks/       # Notebooks Jupyter (.ipynb) en ENG y ESP
├── figures/         # Paneles individuales (.png, .svg)
├── infographics/    # Infografía final (PNG, PDF)
├── README.md        # Documentación del proyecto
├── LICENSE          # Licencia
└── .gitignore        
```

### Licencia

-   **Código:** Licencia MIT (ver [LICENSE](LICENSE))\
-   **Figuras e infografías:** Por favor, acreditarme si reutilizas las visualizaciones o infografía.

------------------------------------------------------------------------

# Argentina Snowfall

## English

### Description

This repository contains datasets and Python Jupyter notebooks (`.ipynb`) for analyzing and visualizing snowfall trends in Argentina (1985--2025).

The project was developed to produce an infographic submitted to the **Contar con Datos 2025** contest.

The Python scripts (.ipynb) generate **individual visualization panels**. Later, I integreted these panels **into a full infographic using Inkscape**.

Scripts and infographic are available in **English** version.

<p align="center">
  <img src="snowfall_infographic1.png" alt="Snowfall Infographic" width="600"/>
</p>

### Dataset

-   **Format:** Parquet (`.parquet`)\
-   **Content:** Daily to interannual estimates of snowfall accumulation across Argentina\
-   **Source:** Derived from reanalysis climate data (ERA5, ECMWF, Copernicus Climate Data Store)

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

### Repository structure

``` text
argentina-snowfall/
├── data/            
├── notebooks/       
├── figures/         
├── infographics/    
├── README.md        
├── LICENSE          
└── .gitignore        
```

### License

-   **Code:** MIT License (see [LICENSE](LICENSE))\
-   **Figures and visualizations:** Please credit author when reusing outputs.

------------------------------------------------------------------------
