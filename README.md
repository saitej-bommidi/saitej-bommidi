<h1 align="center">Hi, I'm Saitej 👋</h1>
<h3 align="center">Data Science @ Michigan State University · Data Intern @ Michigan Legal Help</h3>

<p align="center">
  <a href="https://linkedin.com/in/saitejb"><img src="https://img.shields.io/badge/LinkedIn-saitejb-0A66C2?logo=linkedin&logoColor=white" /></a>
  <a href="https://github.com/saitej-bommidi"><img src="https://img.shields.io/badge/GitHub-saitej--bommidi-181717?logo=github" /></a>
  <img src="https://img.shields.io/badge/Graduating-Dec%202026-18453B" />
  <img src="https://img.shields.io/badge/Open%20to-Data%20roles-success" />
</p>

---

## 🧭 About me

- 🎓 B.S. Data Science, **Michigan State University** — graduating **December 2026**
- ⚖️ First data intern at **Michigan Legal Help Program** — built the org's data strategy and workflow from scratch
- 🍇 Capstone: computer-vision yield estimation for **National Grape** (YOLO + SAM)
- ☀️ Former Solar Energy Consultant at **Sunrun** (Chicago · Maui · Palm Springs)
- 🏎️ Interested in sports & motorsports analytics
- 📫 Best way to reach me: [LinkedIn](https://linkedin.com/in/saitejb)

---

## 🚀 Featured projects

### 🍇 MSU FRUIT — Grape Cluster Detection & Yield Estimation
*CMSE 495 Capstone · Partner: National Grape · Fall 2026*

Turns Riesling vineyard video into a per-vine yield estimate.

```
video → frame extraction → cleaning (blur / dark / duplicate removal) → labeling
      → YOLO (detect clusters) + SAM (segment outlines) → frame-to-frame tracking
      → count each cluster once → yield estimate
```
- Fully scripted and documented so the partner or next year's team can rerun it on new footage
- **Stack:** Python · YOLO · Segment Anything (SAM) · OpenCV
- 🔗 [Repo](https://github.com/saitej-bommidi/Capstone-MSU_Fruit) <!-- update link if needed -->

### ⚖️ Legal Self-Help Center Survey Pipeline
*Michigan Legal Help Program · 2026*

End-to-end pipeline that standardizes survey data from 20+ Michigan legal self-help centers into one clean, analysis-ready master dataset (100k+ responses, 2013–present).
- Pre- and post-survey **standardizers** (Python) driven by a mapping workbook — new sources are onboarded by adding rows, not code
- Hourly **Google Apps Script** pipelines that keep live Google Sheets standardized from SurveyMonkey feeds
- Validation harness that pins expected counts and sweeps for data-quality issues (e.g., silent `N/A` erasure by pandas defaults)
- Loaded into a **BigQuery** warehouse (free tier) with a documented quarterly refresh + snapshot pattern
- Reconciled published 2025 report figures against raw sources and traced every discrepancy to its root cause
- **Stack:** Python · pandas · Google Apps Script · BigQuery · SQL · Excel
- 🔗 Code is internal to the organization — happy to walk through it

### 🗺️ Self-Help Center Finder Map
*Michigan Legal Help Program*

Maintain and audit the English & Spanish datasets behind the interactive ArcGIS self-help center map on michiganlegalhelp.org.
- **Stack:** ArcGIS Online · Excel · Python

### 📊 Self-Help Center Funding Research
EDA and research report (correlation, benchmarking, need/resource gap, PCA) on center-level visit, survey and county poverty data to inform funding decisions.
- **Stack:** Python · pandas · scikit-learn · matplotlib

<!-- Add more projects here: copy a block above -->

---

## 🛠️ Skills

**Languages:** ![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-4479A1?logo=postgresql&logoColor=white) ![JavaScript](https://img.shields.io/badge/Apps%20Script-F7DF1E?logo=javascript&logoColor=black)

**Data & ML:** ![pandas](https://img.shields.io/badge/pandas-150458?logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikitlearn&logoColor=white) ![YOLO](https://img.shields.io/badge/YOLO-00FFFF?logo=yolo&logoColor=black) ![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?logo=opencv&logoColor=white)

**Cloud & Tools:** ![BigQuery](https://img.shields.io/badge/BigQuery-669DF6?logo=googlebigquery&logoColor=white) ![Google Sheets](https://img.shields.io/badge/Google%20Sheets-34A853?logo=googlesheets&logoColor=white) ![ArcGIS](https://img.shields.io/badge/ArcGIS-2C7AC3?logo=arcgis&logoColor=white) ![Excel](https://img.shields.io/badge/Excel-217346?logo=microsoftexcel&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white) ![Looker Studio](https://img.shields.io/badge/Looker%20Studio-4285F4?logo=looker&logoColor=white)

**AI-assisted development:** Claude · ChatGPT Codex

**What I'm good at:** data cleaning & standardization · pipeline automation · data validation & reconciliation · computer vision · turning messy multi-source data into decisions non-technical teams can use

---

## 📈 GitHub stats

<p align="center">
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=saitej-bommidi&show_icons=true&hide_border=true" />
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=saitej-bommidi&layout=compact&hide_border=true" />
</p>
