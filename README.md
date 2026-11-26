<div align="center">

![Visualización](https://img.shields.io/badge/VISUALIZACI%C3%93N-00838F?style=for-the-badge)

# Técnicas de visualización de datos financieros

Tres técnicas de visualización aplicadas a cotizaciones de Apple, Microsoft y Google, publicadas como página web interactiva.

[![Web en vivo: Ver visualizaciones](https://img.shields.io/badge/WEB_EN_VIVO-Ver_visualizaciones-2EA043?style=for-the-badge&logo=googlechrome&logoColor=white)](https://juliouq.github.io/Tecnicas_de_Visualizacion_de_Datos/)

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white) ![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white) ![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)

<img src="docs/captura-web.png" alt="Página publicada con el gráfico de sectores del volumen medio negociado por empresa" width="100%" />

</div>

---

## Descripción general

Ilustra tres enfoques distintos sobre los mismos datos bursátiles (AAPL, MSFT y GOOG): proporciones, evolución temporal y dispersión geométrica.

## Funcionalidades

- **Gráfico de sectores:** volumen medio negociado por empresa.
- **Velas japonesas:** evolución de los precios de apertura, máximo, mínimo y cierre, con tendencias y volatilidad.
- **Envolvente convexa:** polígono mínimo que contiene los puntos de cada empresa, para comparar dispersión y estabilidad.

## Tecnologías y herramientas

| Ámbito | Herramientas |
| --- | --- |
| Gráficos | Plotly, Plotly Graph Objects |
| Geometría | SciPy (`ConvexHull`) |
| Datos | pandas |

## Estructura del proyecto

```text
.
├── index.html            # Página publicada en GitHub Pages
├── Visualizaciones.py    # Genera los tres gráficos
├── Visualizaciones/      # Gráficos exportados en HTML
├── notebooks/            # Desarrollo en Jupyter
├── Data/                 # acciones_limpio.csv
└── Presentacion/         # Diapositivas y vídeo
```

## Instalación y uso

```bash
pip install pandas plotly scipy
python Visualizaciones.py
```

## Autor

**Julio Úbeda Quesada** · Data Scientist

[![Portfolio](https://img.shields.io/badge/Portfolio-0B2545?style=flat-square&logo=astro&logoColor=white)](https://juliouq.github.io/Portfolio-Web---JulioUQ/es/) [![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square)](https://www.linkedin.com/in/juliouq/) [![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/JulioUQ)

<sub>Proyecto realizado en el Máster Universitario en Ciencia de Datos.</sub>
