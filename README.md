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
