<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=24&duration=3000&pause=1000&color=569CD6&center=true&vCenter=true&width=800&lines=Portafolio+de+An%C3%A1lisis+de+Datos;SQL+%2B+Python+%2B+Databricks+%2B+Power+BI;Mawerick+Garces+Fontalvo" alt="Typing SVG" />

<br/>

<img src="https://img.shields.io/badge/ESTADO-EN%20DESARROLLO-1e1e1e?style=for-the-badge&labelColor=007ACC&color=1e1e1e" />
<img src="https://img.shields.io/badge/LICENCIA-MIT-1e1e1e?style=for-the-badge&labelColor=007ACC&color=1e1e1e" />
<img src="https://img.shields.io/badge/VERSI%C3%93N-1.0.0-1e1e1e?style=for-the-badge&labelColor=007ACC&color=1e1e1e" />
<img src="https://img.shields.io/badge/MANTENIDO-S%C3%8D-1e1e1e?style=for-the-badge&labelColor=007ACC&color=1e1e1e" />

</div>

<br/>

```
┌────────────────────────────────────────────────────────────────┐
│  data-analysis-portfolio                                       │
│  ── SQL · Python · Databricks · Power BI · Excel ──            │
│                                                                  │
│  > ejecutar pipeline --entorno=produccion                      │
│  [OK] Extracción completa   [OK] Transformación completa       │
│  [OK] KPIs generados        [OK] Dashboard desplegado          │
└────────────────────────────────────────────────────────────────┘
```

<div align="center">

<img src="https://skillicons.dev/icons?i=python,vscode,git,github,azure&theme=dark" />

<br/><br/>

<img src="https://img.shields.io/badge/SQL-1e1e1e?style=for-the-badge&logo=postgresql&logoColor=4479A1" />
<img src="https://img.shields.io/badge/Databricks-1e1e1e?style=for-the-badge&logo=databricks&logoColor=FF3621" />
<img src="https://img.shields.io/badge/Power_BI-1e1e1e?style=for-the-badge&logo=powerbi&logoColor=F2C811" />
<img src="https://img.shields.io/badge/Jupyter-1e1e1e?style=for-the-badge&logo=jupyter&logoColor=F37626" />
<img src="https://img.shields.io/badge/Excel-1e1e1e?style=for-the-badge&logo=microsoftexcel&logoColor=217346" />
<img src="https://img.shields.io/badge/Google_Sheets-1e1e1e?style=for-the-badge&logo=googlesheets&logoColor=34A853" />
<img src="https://img.shields.io/badge/VS_Code-1e1e1e?style=for-the-badge&logo=visualstudiocode&logoColor=007ACC" />

</div>

***

## 📑 Tabla de contenido

* [`01` Resumen ejecutivo](#-01-resumen-ejecutivo)
* [`02` Arquitectura del proyecto](#-02-arquitectura-del-proyecto)
* [`03` Stack tecnológico](#-03-stack-tecnológico)
* [`04` Estructura del repositorio](#-04-estructura-del-repositorio)
* [`05` Instalación y ejecución](#-05-instalación-y-ejecución)
* [`06` Dashboard y resultados](#-06-dashboard-y-resultados)
* [`07` Hallazgos clave](#-07-hallazgos-clave)
* [`08` Calidad de datos y buenas prácticas](#-08-calidad-de-datos-y-buenas-prácticas)
* [`09` Hoja de ruta](#-09-hoja-de-ruta)
* [`10` Autor](#-10-autor)
* [`11` Licencia](#-11-licencia)

***

## `01` Resumen ejecutivo

```python
proyecto = {
    "nombre": "Data Analysis Portfolio",
    "autor": "Mawerick Garces Fontalvo",
    "rol": "Analista de Datos | Analista Logístico",
    "stack": ["SQL", "Python", "Databricks", "Power BI", "Excel"],
    "objetivo": "Transformar datos operativos en indicadores accionables",
    "estado": "en_desarrollo"
}
```

> Reemplaza este bloque con el resumen real del proyecto: qué problema de negocio resuelve, qué fuente de datos utiliza y qué decisiones soporta.
>
> **Ejemplo:** *"Pipeline de extremo a extremo que ingiere datos crudos de ventas/inventario, los limpia y modela en Databricks, y expone KPIs a través de un dashboard interactivo en Power BI, reduciendo el tiempo de generación de reportes de X horas a Y minutos."*

**Problema de negocio** → **Fuente de datos** → **Proceso analítico** → **Resultado / impacto**

***

## `02` Arquitectura del proyecto

```
 ┌──────────────┐     ┌───────────────┐     ┌────────────────┐     ┌──────────────┐
 │  DATOS CRUDOS │ ──▶ │  SQL / ETL    │ ──▶ │  DATABRICKS    │ ──▶ │  POWER BI    │
 │  CSV/BD/Sheets│     │  extracción y │     │  transformación│     │  dashboard   │
 │               │     │  limpieza     │     │  y agregación  │     │  e indicadores│
 └──────────────┘     └───────────────┘     └────────────────┘     └──────────────┘
                                │
                                ▼
                        ┌────────────────┐
                        │ Python / Jupyter│
                        │ EDA + modelado  │
                        └────────────────┘
```

**Flujo de trabajo:**

1. **Ingesta** — captura de datos desde bases SQL, Excel o Google Sheets.
2. **Transformación** — limpieza, normalización y reglas de negocio aplicadas en SQL/Databricks.
3. **Análisis** — exploración estadística y modelado en Python (Jupyter Notebook).
4. **Visualización** — construcción de indicadores y dashboard interactivo en Power BI.
5. **Entrega** — reporte final documentado y disponible para toma de decisiones.

***

## `03` Stack tecnológico

| # | Herramienta | Función en el proyecto |
|---|---|---|
| 01 | **SQL** | Extracción, joins, limpieza y consultas sobre la base de datos |
| 02 | **Databricks** | Procesamiento distribuido y pipelines de transformación |
| 03 | **Python (Jupyter)** | Análisis exploratorio de datos (EDA), pandas, modelado estadístico |
| 04 | **Power BI** | Construcción de dashboards, KPIs y reportes ejecutivos |
| 05 | **Excel / Google Sheets** | Validación cruzada, revisiones rápidas y compartición ligera |
| 06 | **Visual Studio Code** | Entorno de desarrollo para scripts SQL y notebooks Python |
| 07 | **Git / GitHub** | Control de versiones y documentación del proyecto |

***

## `04` Estructura del repositorio

```bash
data-analysis-portfolio/
├── .vscode/
│   └── settings.json          # Configuración del editor (formato, linting)
├── data/
│   ├── raw/                   # Datos originales, sin procesar
│   └── processed/             # Datos limpios y transformados
├── sql/
│   └── queries.sql            # Consultas de extracción y transformación
├── notebooks/
│   └── analisis.ipynb         # Exploración y modelado en Python
├── databricks/
│   └── etl_pipeline.py        # Job de transformación en Databricks
├── powerbi/
│   └── dashboard.pbix         # Dashboard final interactivo
├── docs/
│   └── assets/                # Capturas, diagramas y material visual
├── requirements.txt           # Dependencias del proyecto
├── .gitignore                 # Archivos y carpetas excluidos del control de versiones
└── README.md                  # Este documento
```

***

## `05` Instalación y ejecución

```bash
# 1. Clonar el repositorio
git clone https://github.com/Mawerick099/data-analysis-portfolio.git
cd data-analysis-portfolio

# 2. Crear entorno virtual
python -m venv venv
source venv/bin/activate      # macOS/Linux
venv\Scripts\activate         # Windows

# 3. Instalar dependencias
pip install -r requirements.txt

# 4. Ejecutar consultas SQL
#    Ubicadas en sql/queries.sql sobre tu motor de base de datos

# 5. Abrir el notebook de análisis
jupyter notebook notebooks/analisis.ipynb

# 6. Abrir el dashboard
#    powerbi/dashboard.pbix -> Power BI Desktop
```

**Requisitos previos:** Python 3.10+, acceso a la base de datos/fuente SQL, Power BI Desktop, cuenta de Databricks (según el alcance del proyecto).

***

## `06` Dashboard y resultados

```
[ CAPTURA PENDIENTE ]
docs/assets/dashboard_principal.png
```

```markdown
![Dashboard Power BI](docs/assets/dashboard_principal.png)
```

> Sustituye este bloque por capturas reales del dashboard: vista general, KPIs principales y filtros interactivos.

***

## `07` Hallazgos clave

```diff
+ Hallazgo 1: [métrica] mejoró un [X%] tras [acción implementada]
+ Hallazgo 2: [tendencia identificada] en [segmento/periodo]
+ Hallazgo 3: [oportunidad detectada] con impacto estimado de [valor]
- Riesgo identificado: [cuello de botella / inconsistencia de datos] en [proceso]
```

***

## `08` Calidad de datos y buenas prácticas

* ✅ Validación de nulos, duplicados y formatos antes de cada carga.
* ✅ Documentación de cada transformación en `sql/queries.sql` y `databricks/etl_pipeline.py`.
* ✅ Control de versiones de datos crudos vs. procesados (`data/raw/` nunca se sobrescribe).
* ✅ Nomenclatura consistente de columnas e indicadores en todo el pipeline.
* ✅ Revisión cruzada de resultados entre Power BI y Excel antes de publicar reportes.

***

## `09` Hoja de ruta

* \[x] Definir fuentes de datos y esquema
* \[x] Construir pipeline ETL (SQL → Databricks)
* \[ ] Automatizar la actualización del dashboard en Power BI
* \[ ] Incorporar pruebas de calidad de datos (data quality tests)
* \[ ] Documentar diccionario de datos completo
* \[ ] Desplegar pipeline programado (scheduled run)

***

## `10` Autor

<div align="left">

```json
{
  "nombre": "Mawerick Garces Fontalvo",
  "cargo": "Analista de Datos | Analista Logístico",
  "ubicacion": "Riohacha, La Guajira, Colombia",
  "correo": "mawerick.g.fontalvo@gmail.com",
  "linkedin": "linkedin.com/in/mawerick-garces-fontalvo-9a6232121",
  "github": "github.com/Mawerick099"
}
```

</div>

<p align="left">
  <a href="https://www.linkedin.com/in/mawerick-garces-fontalvo-9a6232121/">
    <img src="https://img.shields.io/badge/LinkedIn-1e1e1e?style=for-the-badge&logo=linkedin&logoColor=0A66C2" />
  </a>
  <a href="mailto:mawerick.g.fontalvo@gmail.com">
    <img src="https://img.shields.io/badge/Correo-1e1e1e?style=for-the-badge&logo=gmail&logoColor=EA4335" />
  </a>
  <a href="https://github.com/Mawerick099">
    <img src="https://img.shields.io/badge/GitHub-1e1e1e?style=for-the-badge&logo=github&logoColor=white" />
  </a>
</p>

***

## `11` Licencia

```
Licencia MIT — consulta el archivo LICENSE para más detalles.
```

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=1e1e1e&height=100&section=footer&text=Gracias%20por%20visitar&fontColor=569CD6&fontSize=22" />
</div>
