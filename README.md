# Carga de Enfermedades No Transmisibles en América Latina (1990–2021)

**Autora:** María Fernanda Ramírez Serrano  
**Curso:** Herramientas Básicas para el Análisis de Datos  
**Institución:** Centro de e-Learning UTN BA  
**Cohorte:** 2025  

---

## Descripción del proyecto

Este proyecto analiza la evolución de la carga de enfermedades no transmisibles (ENT) en América Latina entre 1990 y 2021, utilizando como métrica principal los años de vida ajustados por discapacidad (DALYs). Se busca identificar qué enfermedades concentran la mayor pérdida de años de vida saludable, cómo evolucionó la carga cardiovascular en la región y qué países presentan los valores más elevados en 2021.

El análisis integra Python para la exploración y visualización de datos, Power BI para la construcción de un dashboard interactivo, y GitHub como plataforma de documentación y publicación del proyecto.

---

## Dataset utilizado

- **Fuente:** Global Burden of Disease Study 2021 (GBD 2021)  
- **Organización:** Institute for Health Metrics and Evaluation (IHME), Universidad de Washington  
- **Enlace:** https://vizhub.healthdata.org/gbd-results/  
- **Contenido:** Estimaciones de DALYs, YLLs, YLDs y mortalidad para 204 países, 371 enfermedades, por sexo, grupo etario y año (1990–2021)  
- **Filtros aplicados:** países de América Latina, enfermedades no transmisibles, ambos sexos, todos los grupos etarios, años 1990–2021  
- **Volumen:** >500.000 filas  

---

## Tecnologías utilizadas

- Python 3 (pandas, matplotlib, seaborn)
- Power BI Desktop
- GitHub
- Google Colab / Jupyter Notebook

---

## Estructura del repositorio
├── data/
│   └── raw/          # Dataset original descargado del IHME
├── notebooks/        # Notebook con EDA completo (.ipynb)
├── dashboard/        # Archivo .pbix y capturas del dashboard
└── README.md
---

## Pasos realizados

1. Descarga y selección del dataset desde el GBD Results Tool (IHME)
2. Ingesta y auditoría de datos en Python: tipos, nulos, duplicados y outliers
3. Estandarización de columnas y filtrado por región (América Latina)
4. Análisis exploratorio con 5 visualizaciones interpretadas (matplotlib/seaborn)
5. Construcción de dashboard interactivo en Power BI con 3 KPIs y panel de filtros
6. Publicación del proyecto en GitHub con documentación completa

---

## KPIs principales

| KPI | Descripción |
|-----|-------------|
| KPI 1 | Top ENT por tasa de DALYs cada 100k hab. en Argentina (2021) |
| KPI 2 | Variación % de DALYs cardiovasculares en LATAM (1990–2021) |
| KPI 3 | Ranking de países por carga total de ENT (2021) |

---

## Referencias bibliográficas

- Global Burden of Disease Collaborative Network. (2022). *Global Burden of Disease Study 2021 (GBD 2021) Results*. Institute for Health Metrics and Evaluation (IHME). https://vizhub.healthdata.org/gbd-results/
- IHME. (2020). *GBD Compare*. University of Washington. https://vizhub.healthdata.org/gbd-compare/
- McKinney, W. (2017). *Python for Data Analysis* (2nd ed.). O'Reilly Media.
- Microsoft. (s/f). *Power BI Documentation*. https://learn.microsoft.com/power-bi/
