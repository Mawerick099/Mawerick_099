<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=26&duration=3000&pause=1000&color=569CD6&center=true&vCenter=true&width=800&lines=Data+Analysis+Project;SQL+%2B+Python+%2B+Databricks+%2B+Power+BI;Built+by+Mawerick+Garces+Fontalvo" alt="Typing SVG" />

<br/>

<img src="https://img.shields.io/badge/STATUS-IN%20DEVELOPMENT-1e1e1e?style=for-the-badge&labelColor=007ACC&color=1e1e1e" />
<img src="https://img.shields.io/badge/LICENSE-MIT-1e1e1e?style=for-the-badge&labelColor=007ACC&color=1e1e1e" />
<img src="https://img.shields.io/badge/MAINTAINED-YES-1e1e1e?style=for-the-badge&labelColor=007ACC&color=1e1e1e" />

</div>

<br/>

```
┌──────────────────────────────────────────────────────────┐
│  data-analysis-portfolio                                 │
│  ── SQL · Python · Databricks · Power BI · Excel ──      │
│  > run pipeline --env=production                         │
│  [OK] ETL completed · [OK] KPIs generated · [OK] Deployed │
└──────────────────────────────────────────────────────────┘
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

## `// 01` Overview

```python
project = {
    "name": "Data Analysis Portfolio",
    "author": "Mawerick Garces Fontalvo",
    "role": "Data Analyst | Logistics Analyst",
    "stack": ["SQL", "Python", "Databricks", "Power BI", "Excel"],
    "status": "in_development"
}
```

> Replace this block with the real summary: what problem this project solves, what data it uses, and what decisions it supports. Example: *"End-to-end pipeline that ingests raw sales/inventory data, cleans and models it in Databricks, and exposes KPIs through an interactive Power BI dashboard."*

***

## `// 02` Architecture

```
 ┌─────────────┐     ┌──────────────┐     ┌───────────────┐     ┌─────────────┐
 │   RAW DATA  │ ──▶ │  SQL / ETL   │ ──▶ │  DATABRICKS   │ ──▶ │  POWER BI   │
 │ CSV / DB /  │     │  extraction  │     │  transform +  │     │  dashboard  │
 │ Sheets      │     │  & cleaning  │     │  aggregation  │     │  & KPIs     │
 └─────────────┘     └──────────────┘     └───────────────┘     └─────────────┘
                                │
                                ▼
                        ┌───────────────┐
                        │ Python/Jupyter │
                        │ EDA + modeling │
                        └───────────────┘
```

***

## `// 03` Tech Stack

| Layer | Tool | Purpose |
|---|---|---|
| `01` | **SQL** | Data extraction, joins, and cleaning queries |
| `02` | **Databricks** | Distributed processing, transformation pipelines |
| `03` | **Python (Jupyter)** | Exploratory data analysis, pandas, statistical modeling |
| `04` | **Power BI** | Dashboarding, KPI visualization, business reporting |
| `05` | **Excel / Google Sheets** | Cross-validation, quick checks, lightweight sharing |
| `06` | **VS Code** | Development environment for scripts & notebooks |

***

## `// 04` Repository Structure

```bash
data-analysis-portfolio/
├── .vscode/
│   └── settings.json          # Editor config (formatter, linting)
├── data/
│   ├── raw/                   # Original, untouched data
│   └── processed/             # Cleaned, transformed data
├── sql/
│   └── queries.sql            # Extraction & transformation queries
├── notebooks/
│   └── analysis.ipynb         # EDA and modeling in Python
├── databricks/
│   └── etl_pipeline.py        # Databricks transformation job
├── powerbi/
│   └── dashboard.pbix         # Final interactive dashboard
├── docs/
│   └── assets/                # Screenshots, diagrams, GIFs
├── requirements.txt
├── .gitignore
└── README.md
```

***

## `// 05` Getting Started

```bash
# 1. Clone the repository
git clone https://github.com/Mawerick099/data-analysis-portfolio.git
cd data-analysis-portfolio

# 2. Create a virtual environment
python -m venv venv
source venv/bin/activate      # macOS/Linux
venv\Scripts\activate         # Windows

# 3. Install dependencies
pip install -r requirements.txt

# 4. Launch the analysis notebook
jupyter notebook notebooks/analysis.ipynb

# 5. Open the dashboard
#    powerbi/dashboard.pbix -> Power BI Desktop
```

***

## `// 06` Dashboard Preview

```
[ SCREENSHOT PLACEHOLDER ]
docs/assets/dashboard_dark.png
```

```markdown
![Power BI Dashboard](docs/assets/dashboard_dark.png)
```

***

## `// 07` Key Insights

```diff
+ Insight 1: [metric] improved by [X%] after [action taken]
+ Insight 2: [finding] identified across [dataset/segment]
- Risk found: [bottleneck / data quality issue] detected in [process]
```

***

## `// 08` Roadmap

* \[x] Define data sources and schema
* \[x] Build ETL pipeline (SQL → Databricks)
* \[ ] Automate Power BI refresh
* \[ ] Add data quality tests
* \[ ] Deploy scheduled pipeline

***

## `// 09` Author

<div align="left">

```json
{
  "name": "Mawerick Garces Fontalvo",
  "title": "Data Analyst | Logistics Analyst",
  "location": "Riohacha, La Guajira, Colombia",
  "email": "mawerick.g.fontalvo@gmail.com",
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
    <img src="https://img.shields.io/badge/Email-1e1e1e?style=for-the-badge&logo=gmail&logoColor=EA4335" />
  </a>
  <a href="https://github.com/Mawerick099">
    <img src="https://img.shields.io/badge/GitHub-1e1e1e?style=for-the-badge&logo=github&logoColor=white" />
  </a>
</p>

***

## `// 10` License

```
MIT License — see LICENSE file for details.
```

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=1e1e1e&height=100&section=footer&text=Thanks%20for%20visiting&fontColor=569CD6&fontSize=22" />
</div>
