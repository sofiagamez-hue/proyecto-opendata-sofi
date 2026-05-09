# Proyecto Open Data — Educación Paraguay vs EE.UU.

**Estudiante:** Sofia Gamez  
**Módulo:** Big Data / Open Data  
**Docente:** Andres Ortiz  
**Institución:** Universidad Paraguayo Alemana  
**Fecha:** Mayo 2026  

## Descripción
Análisis comparativo de indicadores educativos entre Paraguay y Estados Unidos
utilizando datos abiertos oficiales. Se estudia la evolución de la matrícula escolar,
el gasto en educación y la distribución regional de estudiantes.

## Preguntas de investigación
1. ¿Cómo evolucionó la tasa de matrícula primaria en Paraguay vs EE.UU. entre 2000 y 2023?
2. ¿Qué departamentos de Paraguay concentran más estudiantes matriculados en 2023?
3. ¿Cuál es la diferencia en gasto en educación (% del PIB) entre ambos países?
4. ¿Qué diferencias existen entre zonas urbanas y rurales en Paraguay?
5. ¿Qué problemas de calidad de datos afectan el análisis del dataset MEC?

## Fuentes de datos
| Dataset | Fuente | Año | Licencia | Fecha descarga |
|---|---|---|---|---|
| Matrícula escolar MEC | datos.mec.gov.py | 2023 | Licencia Pública Paraguay | Mayo 2026 |
| Indicadores educativos | api.worldbank.org | 2000–2023 | CC BY 4.0 | Mayo 2026 |

## Estructura del proyecto
proyecto-opendata-sofi/
├── README.md
├── data/
│   ├── raw/                  # Datos originales descargados
│   └── processed/            # Datos limpios y transformados
├── notebooks/
│   └── AnalisisDatos.ipynb        # Análisis completo 
├── outputs/
│   └── figures/              # Gráficos exportados (Python + Power BI)
├── informe/                  # Informe final en PDF
└── presentacion/             # Presentación ejecutiva
## Herramientas utilizadas
- Python 3 (pandas, matplotlib, seaborn, urllib)
- Jupyter Notebook / VS Code
- Power BI Desktop
- Git / GitHub

## Cómo reproducir el análisis
1. Clonar el repositorio:
```bash
git clone https://github.com/sofiagamez-hue/proyecto-opendata-sofi
```
2. Instalar dependencias:
```bash
pip install pandas matplotlib seaborn wbdata
```
3. Abrir y ejecutar el notebook desde la primera celda:
notebooks/AnalisisDatos.ipynb
4. Los gráficos se guardan automáticamente en `outputs/figures/`

## Fecha de descarga de datos
- MEC: Mayo 2026  
- Banco Mundial API: Mayo 2026