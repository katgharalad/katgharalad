<h1 align="center">Aarav Singh</h1>
<p align="center">
  <b>Building systems that turn unstructured data into decision pipelines.</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-111827?style=for-the-badge&logo=python&logoColor=FFD43B" />
  <img src="https://img.shields.io/badge/C++-111827?style=for-the-badge&logo=c%2B%2B&logoColor=00599C" />
  <img src="https://img.shields.io/badge/SQL-111827?style=for-the-badge&logo=postgresql&logoColor=336791" />
  <img src="https://img.shields.io/badge/R-111827?style=for-the-badge&logo=r&logoColor=276DC3" />
  <img src="https://img.shields.io/badge/Scheme-111827?style=for-the-badge&logo=gnu&logoColor=A42E2B" />
  <img src="https://img.shields.io/badge/Linux-111827?style=for-the-badge&logo=linux&logoColor=FCC624" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/AWS-0F172A?style=for-the-badge&logo=amazonaws&logoColor=FF9900" />
  <img src="https://img.shields.io/badge/Azure-0F172A?style=for-the-badge&logo=microsoftazure&logoColor=0078D4" />
  <img src="https://img.shields.io/badge/FastAPI-0F172A?style=for-the-badge&logo=fastapi&logoColor=009688" />
  <img src="https://img.shields.io/badge/TensorFlow-0F172A?style=for-the-badge&logo=tensorflow&logoColor=FF6F00" />
  <img src="https://img.shields.io/badge/Scikit--Learn-0F172A?style=for-the-badge&logo=scikitlearn&logoColor=F7931E" />
  <img src="https://img.shields.io/badge/PostgreSQL-0F172A?style=for-the-badge&logo=postgresql&logoColor=4169E1" />
</p>

---

## Work

<table>
<tr>
<td width="100%">

### OPEF – Phase I ESA Automation

End-to-end system for automating environmental due diligence workflows for **Phase I Environmental Site Assessments**.

- Parses regulatory and environmental datasets from **EPA**, state records, and geospatial sources
- Builds an **evidence graph** to connect:
  `raw record → extracted fact → canonical entity → spatial relation → risk classification`
- Automates **REC (Recognized Environmental Condition)** identification
- Integrates document analysis, geospatial screening, and structured reasoning into one pipeline

**Impact**  
`$3000 / 2 weeks → ~$500 / <10 hours`

**Technical Stack**
- **Backend:** Python, FastAPI
- **Cloud / Infra:** AWS S3, AWS Lambda, PostgreSQL
- **Geospatial:** Google Earth Engine, Sentinel-2, GEDI, EPA APIs
- **Extraction / NLP:** embeddings, rule-based extraction, document parsing

</td>
</tr>
</table>

<details>
<summary><b>View technical flow</b></summary>

```mermaid
flowchart LR
    A[Raw Regulatory / Environmental Data] --> B[Parsing + Extraction]
    B --> C[Extracted Facts]
    C --> D[Canonical Entity Resolution]
    D --> E[Spatial Relationship Engine]
    E --> F[Risk Classification]
    F --> G[REC / ESA Finding]

Here is the **continuation after your Mermaid block**, clean and copy-paste ready:

```html
```

</details>

---

<table>
<tr>
<td width="100%">

### Mentor Connector

Matching system for founders ↔ mentors using hybrid retrieval.

* Combines dense embeddings (semantic similarity) + BM25 (lexical ranking)
* Ranking and filtering pipeline for high-precision matching
* Handles both structured and unstructured profile data
* Designed to avoid noisy keyword-only matches

**Technical Stack**

* Python
* Vector embeddings
* BM25 (information retrieval)
* REST APIs

</td>
</tr>
</table>

---

<table>
<tr>
<td width="100%">

### TSheets Processing System

Operational ETL pipeline for time and work logs.

* Ingests raw logs → cleans → normalizes → structures
* Handles inconsistent schemas and noisy inputs
* Outputs analytics-ready datasets for downstream workflows

**Technical Stack**

* Python
* SQL
* ETL pipelines

</td>
</tr>
</table>

---

<table>
<tr>
<td width="100%">

### LateGrub

Full-stack food ordering platform.

* Real-time order flow and backend handling
* Authentication, session management, database integration
* Built with focus on system design and execution

**Technical Stack**

* JavaScript
* Backend APIs
* Database systems

</td>
</tr>
</table>

---

<table>
<tr>
<td width="100%">

### OPEF Website

Product-facing system for technical and non-technical users.

* Communicates environmental analysis workflows clearly
* Built for demos, pilots, and stakeholder onboarding
* Structured for clarity and conversion

**Technical Stack**

* React
* Frontend systems
* Deployment pipelines

</td>
</tr>
</table>

---

## Technical Scope

<table>
<tr>
<td width="50%">

### Languages

Python
C++
SQL
R
Scheme
JavaScript

### Machine Learning

Scikit-learn
TensorFlow
Computer Vision
Geospatial ML

</td>
<td width="50%">

### Infra / Systems

AWS (S3, Lambda)
Azure
Linux
Scripting and automation
ETL pipelines
REST APIs

### Geospatial / APIs

Google Earth Engine
NASA Earthdata
Copernicus
Sentinel
GEDI
EPA datasets

</td>
</tr>
</table>

---

## Focus

* Systems over scripts
* Real data over toy datasets
* Speed and execution
* Traceable, production pipelines

---

## Contact

[aarav@opef.ai](mailto:aarav@opef.ai)

```
```

