<h1 align="center"> Data analytics - Bootcamp Henry:rocket: </h1>

> Repositorio del tercer proyecto individual del bootcamp [Henry](https://www.soyhenry.com).  

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

# **Tabla de Contenidos:**
- [**Tabla de Contenidos:**](#tabla-de-contenidos)
- [El proyecto <a name="proyecto"></a>](#el-proyecto-)
  - [Datos](#datos)
- [Sobre el repositorio <a name="about_repo"></a>](#sobre-el-repositorio-)
  - [EDA <a name="eda"></a>](#eda-)
  - [Base de datos <a name="db"></a>](#base-de-datos-)
  - [Reporte de calidad <a name="reporte"></a>](#reporte-de-calidad-)
- [Enviroment](#enviroment)
- [Licencia<a name="license"></a>](#licencia)

# El proyecto <a name="proyecto"></a>
Este proyecto está enfocado en el perfil de analista de datos. El objetivo fue desarrollar un análisis sobre los accidentes de aviones producidos desde 1908. Algunos de los requisitos fueron:
- Realizar un EDA.
- Armar una base de datos.
- Hacer un dashboard a partir de los datos en la base de datos.
- Un informe de calidad.
## Datos
Los datos proporcionados para este proyecto se pueden descargar de la carpeta de datasets.
# Sobre el repositorio <a name="about_repo"></a>
En este repositorio se encuentran la mayoría de los requisitos listados anteriormente
## EDA <a name="eda"></a>
El EDA, con la transformación exacta, extracción de datos y obtención de datos para el dashboard se encuentra en `EDA.ipynb`.
##  Base de datos <a name="db"></a>
La base de datos se encuentra en el archivo .db en la carpeta `database`.

## Reporte de calidad <a name="reporte"></a>
El reporte de calidad, donde se encuentra un resumen del EDA y la descripción de los campos en el dataset se encuentra en `reporte_calidad.ipynb`
# Enviroment
Los notebooks requieren Python <= 3.8.13. Primero hay que clonar el repositorio:

```
    git clone https://github.com/marianaiv/analytics_Pi03
```

Entre al repositorio:
```
    cd datathon-henry
```

Cree un entorno virtual desde el archivo `enviroment.yml` usando conda y luego activelo:
```
    conda env create -f environment.yml
    conda activate analytics-env
```
# Licencia<a name="license"></a>

El uso de este trabajo está licenciado bajo [GNU General Public License v3.0 (GNU GPLv3)](https://choosealicense.com/licenses/gpl-3.0/).