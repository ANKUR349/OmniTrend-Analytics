# OmniTrend Analytics
![Python](https://img.shields.io/badge/Python-3.9%2B-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/MYSQL-Data_Warehousing-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)
![Maintained](https://img.shields.io/badge/Maintained%3F-yes-brightgreen?style=for-the-badge)

OmniTrend Analytics is an enterprise-grade customer behavior and revenue analytics platform designed to transform raw transactional data into actionable business intelligence. The framework unifies automated Python ETL workflows, structured SQL data warehousing, and interactive Power BI dashboards for end-to-end retail reporting.

---

## 🏛 Platform Architecture

```text
Raw Transaction Data (CSV/JSON)
           │
           ▼
┌───────────────────────────────────────────┐
│ 1. Data Cleaning & Preparation (Python)   │ ──> Missing value handling & schema validation
└───────────────────────────────────────────┘
           │
           ▼
┌───────────────────────────────────────────┐
│ 2. Relational Warehousing & EDA (SQL)    │ ──> RFM Analysis, Segment Querying & Metrics
└───────────────────────────────────────────┘
           │
           ▼
┌───────────────────────────────────────────┐
│ 3. Interactive BI Reporting (Power BI)    │ ──> Executive Dashboards & Key KPIs
└───────────────────────────────────────────┘

```
🛠 Technology Stack
Language: Python 3.9+ (Pandas, NumPy, Matplotlib, Seaborn, sqlalchemy)

Database: SQL (MySQL)

## 🛠 Setup & Installation

### 1. Prerequisites
* Python 3.9+
* SQL Database Instance (PostgreSQL/MySQL)

### 2. Environment Setup
```bash
# Clone the repository
git clone [https://github.com/YOUR_USERNAME/PulseRetail-360.git](https://github.com/YOUR_USERNAME/PulseRetail-360.git)
cd PulseRetail-360
```

# Create virtual environment
python3 -m venv venv
```
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

# Install dependencies
```
pip install -r requirements.txt
```
## 👥 Author & Contributor

* **Ankur Sarkar** - *Data Analytics & Engineering*

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
