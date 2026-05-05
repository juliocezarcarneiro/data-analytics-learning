# Automated Sales Performance Reporting System 🚀
<img src="https://geps.dev/progress/40" alt="40% Complete" width="100"/>

**A Python-based ETL pipeline for daily sales performance monitoring with automated alerts.**

---

## 📌 Overview
This system automates daily sales performance tracking with:
- **Daily performance briefings** (HTML/PDF/Email)
- **Real-time alerts** for underperforming regions/products
- **Data validation** to ensure reporting accuracy

---

## 🛠️ Technologies Used
| Category       | Technologies                          |
|----------------|---------------------------------------|
| **Core**       | Python (Pandas, SQLAlchemy)           |
| **Database**   | SQLite (PostgreSQL-ready)             |
| **Orchestration** | Apache Airflow                      |
| **Reporting**  | HTML, CSS, Jinja2                     |
| **Alerting**   | Slack/Email (SMTP) integration        |

---

## ✨ Key Features
| Feature                      | Description                                  |
|------------------------------|---------------------------------------------|
| **Automated ETL**            | Daily data pulls from multiple sources      |
| **Smart Alerts**             | Threshold-based notifications (Slack/Email) |
| **Data Quality Checks**      | Null detection, outlier flagging            |
| **Parameterized Reports**    | Region/team/department-level filtering      |
| **Self-healing Pipeline**    | Auto-retry for failed tasks                 |

---

## 🚀 Installation & Setup

### Prerequisites
- Python
- Airflow
- SQLite/PostgreSQL

