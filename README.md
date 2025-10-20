# 🛡️ CMMC Dashboard
**Developer:** Eliza Ochoa (`@ochoa104cy`)  
**Domain:** Cybersecurity | Compliance | GRC | Data Science  

---

## 📋 Overview
The **CMMC Level 2 Compliance Dashboard** helps organizations visualize and track NIST 800-171 / CMMC controls, risk posture, and evidence readiness.  
It’s powered by **Streamlit (Python)** and integrates with Power BI for extended GRC analytics.

---

## 🚀 Features
- ✅ 110 CMMC Level 2 controls (pre-loaded)
- 📊 Streamlit dashboard with domain-based KPIs
- 🧩 Power BI companion dashboard
- 🔐 GRC alignment (NIST 800-171, DFARS 252.204-7012)
- 🧠 Evidence tracking and status updates
- ☁️ GitHub Actions CI/CD + Docker containerization

---

## 🧰 Tech Stack
| Category | Tools |
|-----------|-------|
| Language | Python 3.11 |
| Framework | Streamlit |
| Analytics | Power BI, Plotly |
| Data | CSV, PostgreSQL |
| DevOps | Docker, GitHub Actions |
| Compliance | NIST 800-171, CMMC L2, OSCAL |

---

## ⚙️ Installation
```bash
git clone https://github.com/ochoa104/CMMC-Dashboard.git
cd CMMC-Dashboard
python3 -m venv venv && source venv/bin/activate
pip install -r requirements.txt
streamlit run cmmc_dashboard.py
