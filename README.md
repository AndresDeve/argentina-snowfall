# Argentina Snowfall

## English

### Description

This repository contains datasets and Python Jupyter notebooks (`.ipynb`) for analyzing and visualizing snowfall trends in Argentina (1985--2025).

The project was developed to produce an infographic submitted to the **Contar con Datos 2025** contest.

The Python scripts generate **individual visualization panels**. These panels were later **manually integrated into a full infographic using Inkscape**.

Scripts and outputs are available in both **English** and **Spanish**. The final infographics are provided as PNG files.

### Dataset

-   **Format:** Parquet files (`.parquet`)\
-   **Content:** Daily to interannual estimates of snowfall accumulation across Argentina\
-   **Source:** Derived from reanalysis climate data (ERA5, ECMWF, Copernicus Climate Data Store)

To run the notebooks, you must **link or upload the dataset(s) in Parquet format** into your environment.

### Visualizations

-   Code produces **individual panels**:
    -   Time series\
    -   Maps\
    -   Waffle charts\
    -   Lollipop plots\
-   Panels are then assembled into **final infographics** (done externally in Inkscape).\
-   Visualizations are available in both **English** and **Spanish**.

### Requirements

-   Python 3.9+\
-   Main libraries: `pandas`, `matplotlib`, `geopandas`, `shapely`, `xarray`\
-   For final assembly: [Inkscape](https://inkscape.org) (manual integration step)

### Fonts

Visualizations rely on fonts from [Google Fonts](https://fonts.google.com).\
- Make sure the fonts are installed locally or linked in the notebook.\
- Examples: *Roboto*, *Literata*, *Inconsolata*.

### Repository structure

``` text
argentina-snowfall/
├── data/            # Datasets en Parquet
├── notebooks/       # Notebooks Jupyter (.ipynb) en ENG y ESP
├── figures/         # Paneles individuales (.png, .svg)
├── infographics/    # Infografía final (PNG, PDF)
├── README.md        # Documentación del proyecto
├── LICENSE          # Licencia MIT
└── .gitignore        
```

### License

-   **Code:** MIT License (see [LICENSE](LICENSE))\
-   **Figures and visualizations:** Please credit **Andrés Devegili** when reusing outputs.

------------------------------------------------------------------------

## Español

### Descripción

Este repositorio contiene datasets y cuadernos Jupyter en Python (`.ipynb`) para analizar y visualizar las tendencias de nevadas en Argentina (1985--2025).

El proyecto fue desarrollado para la producción de una **infografía** presentada al concurso **Contar con Datos 2025**.

Los notebooks generan **paneles individuales de visualización**, que luego fueron **integrados manualmente en una infografía final usando Inkscape**.

El código y las visualizaciones están disponibles en **español** e **inglés**. Las infografías finales se incluyen en formato PNG.

### Dataset

-   **Formato:** Archivos Parquet (`.parquet`)\
-   **Contenido:** Estimaciones diarias e interanuales de acumulación de nieve en Argentina\
-   **Fuente:** Derivados de datos de reanálisis climático (ERA5, ECMWF, Copernicus Climate Data Store)

Para ejecutar los notebooks, es necesario **cargar o vincular el dataset en formato Parquet** en el entorno de trabajo.

### Visualizaciones

-   El código produce **paneles individuales**:
    -   Series temporales\
    -   Mapas\
    -   Gráficos de waffle\
    -   Gráficos de lollipop\
-   Los paneles son luego combinados en **infografías finales** (integradas en Inkscape).\
-   Visualizaciones disponibles tanto en **español** como en **inglés**.

### Requerimientos

-   Python 3.9+\
-   Librerías principales: `pandas`, `matplotlib`, `geopandas`, `shapely`, `xarray`\
-   Para la integración final: [Inkscape](https://inkscape.org) (paso manual)

### Tipografías

Las visualizaciones utilizan tipografías de [Google Fonts](https://fonts.google.com).\
- Asegúrate de instalarlas localmente o enlazarlas en el notebook.\
- Ejemplos: *Roboto*, *Literata*, *Inconsolata*.

### Estructura del repositorio

``` text
argentina-snowfall/
├── data/            # Datasets en Parquet
├── notebooks/       # Notebooks Jupyter (.ipynb) en ENG y ESP
├── figures/         # Paneles individuales (.png, .svg)
├── infographics/    # Infografía final (PNG, PDF)
├── README.md        # Documentación del proyecto
├── LICENSE          # Licencia MIT
└── .gitignore        
```

### Licencia

-   **Código:** Licencia MIT (ver [LICENSE](LICENSE))\
-   **Figuras e infografías:** Por favor, acredita a **Andrés Devegili** si reutilizas los resultados.
