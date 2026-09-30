# Chitransh Sharma — Data Analyst & Power BI Developer Portfolio

[![Live Site](https://img.shields.io/badge/Live_Portfolio-chitransh24god.github.io-teal?style=for-the-badge&logo=googlechrome)](https://chitransh24god.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Chitransh_Sharma-0A66C2?style=for-the-badge&logo=linkedin)](https://linkedin.com/in/chitransh-sharma-252145390)
[![GitHub](https://img.shields.io/badge/GitHub-chitransh24god-181717?style=for-the-badge&logo=github)](https://github.com/chitransh24god)
[![Email](https://img.shields.io/badge/Email-chitransh.pgdmds25%40nbs.edu.in-D14836?style=for-the-badge&logo=gmail)](mailto:chitransh.pgdmds25@nbs.edu.in)

> **"Transforming messy operational and financial data into boardroom-ready decisions."**

---

## 🎯 About Me

I am a **Data Analyst & Power BI Developer** with a Commerce background (**B.Com, University of Rajasthan**) and currently pursuing a **PGDM in Data Science & Analytics** at **Narayana Business School** (AICTE approved, CGPA 7.35). 

Having a commerce core paired with technical data science capabilities allows me to bridge the gap between complex analytical logic and bottom-line commercial impact.

### 📊 Portfolio Highlights & Key Numbers
- **10,000+** raw customer records cleaned, validated, and processed using Python & MongoDB.
- **₹321.7 Cr** commercial revenue and margin risk modeled across 7,535 transactions.
- **1,470** workforce attrition records segmented with 10+ custom DAX measures.
- **40+** data formats automated in-memory via my custom *DataForge* engine.
- **90%+** resume parsing & ATS keyword match accuracy with *Know Your Resume* (Llama 3.3 70B via Groq).

---

## 🛠️ Technical Competency Stack

| Domain | Tools & Frameworks | Key Specializations |
| :--- | :--- | :--- |
| **Business Intelligence** | Power BI, Advanced Excel | DAX Measures, Power Query (M), Star Schema, Drill-through, Slicers, KPI Engineering |
| **Database & Querying** | SQL / MySQL, MongoDB | Complex Joins, Window Functions, CTEs, Aggregation Pipelines, Schema Normalization |
| **Programming & Data Science** | Python (Pandas, NumPy, Scikit-learn) | In-Memory ETL, PDF Parsing (PyMuPDF), Linear Regression, Automated Dispatch |
| **Web Applications** | Streamlit, Plotly Express | Rapid Decision Platforms, AI Workflow Integration (Groq Cloud API, Llama 3.3) |
| **Statistical Modeling** | RapidMiner, Excel Stats | K-Means Clustering, Outlier Detection, CAGR, Sharpe Ratio, Volatility Benchmark |

---

## 🚀 Featured Projects

### 1. [HR Analytics & Employee Retention Dashboard](./index.html#projects)
* **Stack**: Power BI, DAX, Power Query (M), Star Schema
* **Dataset**: IBM HR Analytics benchmark (1,470 employee records, 35 attributes)
* **Core Impact**: Uncovered that Sales Reps and Laboratory Technicians working mandatory overtime suffered a 31.2% voluntary attrition rate (vs 10.4% in non-overtime peers); identified high flight-risk inflection at month 18.
* **DAX Engineered**: Dynamic Attrition Rate `%`, Average Tenure, High-Risk Overtime Segment.

### 2. [Know Your Resume — AI ATS & Resume Intelligence Web App](https://chitransh24god-know-your-resume.streamlit.app)
* **Stack**: Python, Streamlit, Groq API (Llama 3.3 70B), PyMuPDF, Tesseract OCR
* **Live App**: [chitransh24god-know-your-resume.streamlit.app](https://chitransh24god-know-your-resume.streamlit.app)
* **Code Repository**: [github.com/chitransh24god/know-your-resume](https://github.com/chitransh24god/know-your-resume)
* **Core Impact**: Sub-second text extraction from PDFs and DOCX files, automated ATS scoring out of 100, 8–15 missing keyword identification, and bullet rewriting into quantifiable STAR accomplishments.

### 3. [ABC Ltd Commercial Performance & Margin Risk (Executive Case)](./index.html#projects)
* **Stack**: Power BI, Advanced Excel, Financial Modeling
* **Scale**: Modeled ₹321.7 Cr revenue across 7,535 transactions with an overall 51.8% operating profit margin.
* **Critical Finding**: Discovered that the Operations category drove ₹129.8 Cr (40.3% of revenue) but generated only a 21.2% margin (vs 57.4% company average) due to 33.8% fulfillment delays in Tier 3 cities.

### 4. [DataForge — Universal Ingestion & Excel Converter Engine](https://github.com/chitransh24god)
* **Stack**: Python, Streamlit, Pandas, OpenPyXL
* **Capability**: Automatically detects schemas, normalizes headers, and converts 40+ raw formats (Parquet, SQL dumps, JSONL, YAML, CSV) into client-ready Excel workbooks with zero configuration.

### 5. [AIWise Consulting — SME AI Adoption & Financial ROI Decision Platform](./index.html#projects)
* **Stack**: Streamlit, Plotly Express, Rule-based Decision Engine
* **Capability**: Calculates payback periods (months) and unit economics comparing current manual labor expenses against API token and infrastructure overhead.

### 6. [Major Indian Banks Benchmark & Risk Analytics](./index.html#projects)
* **Stack**: Excel Advanced, Power BI, Financial Statistics
* **Scope**: Comparative performance and volatility analysis of SBI, HDFC, ICICI, and Axis Bank benchmarked against the BSE Sensex.

---

## 📐 Star Schema Architecture Principle

In all my Power BI implementations, I adhere strictly to Kimball dimensional modeling:
- **Fact Table**: Contains quantitative measures and numeric foreign keys (e.g. `Fact_Employee_Monthly`, `Fact_Sales`).
- **Dimension Tables**: Filter facts via `1-to-Many (*)` single-direction relationships (`Dim_Calendar`, `Dim_Department`, `Dim_JobRole`).
- **Performance**: Prevents bi-directional cross-filter ambiguities and keeps DAX memory consumption optimized in VertiPaq.

---

## 💻 Local Setup & Deployment

### Run Locally
Simply clone and open `index.html` in any modern web browser:
```bash
git clone https://github.com/chitransh24god/chitransh24god.github.io.git
cd chitransh24god.github.io
# Open index.html directly or with VS Code Live Server
start index.html
```

---

## 📬 Contact Me

- **Email**: [chitransh.pgdmds25@nbs.edu.in](mailto:chitransh.pgdmds25@nbs.edu.in)
- **Phone**: [+91 91161 27014](tel:+919116127014)
- **LinkedIn**: [linkedin.com/in/chitransh-sharma-252145390](https://linkedin.com/in/chitransh-sharma-252145390)
- **GitHub**: [github.com/chitransh24god](https://github.com/chitransh24god)
