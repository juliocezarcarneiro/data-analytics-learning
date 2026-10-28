![Analytics Training Archive](assets/banner.svg)

# Analytics Training Archive

**Every exercise and project from the University of Toronto Data Analytics Bootcamp (edX), plus ongoing case studies, organized by skill: SQL, Python, ETL, NoSQL, dashboards, machine learning, web scraping and Excel.**

![SQL](https://img.shields.io/badge/SQL-1F4E79?style=flat-square&logo=postgresql&logoColor=white) ![Python](https://img.shields.io/badge/Python-1F4E79?style=flat-square&logo=python&logoColor=white) ![pandas](https://img.shields.io/badge/pandas-1F4E79?style=flat-square&logo=pandas&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-1F4E79?style=flat-square&logo=mongodb&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-1F4E79?style=flat-square&logo=scikitlearn&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-1F4E79?style=flat-square&logo=javascript&logoColor=white) ![Excel](https://img.shields.io/badge/Excel-1F4E79?style=flat-square&logo=microsoftexcel&logoColor=white)

> Looking for finished, business-focused case studies? Start with my **[portfolio](https://github.com/juliocezarcarneiro)**. This repo shows the foundations behind them.

---

## Case studies

| Project | What it does | Tools |
|---|---|---|
| [E-Commerce Conversion Analytics](projects-in-progress/e-commerce-conversion-analytics) | End-to-end analysis of the UCI Online Retail dataset: customer behaviour, conversion and revenue | Python, pandas |
| [Automated Sales Reporting](projects-in-progress/automated-sales-reporting-system) | Automates daily sales performance briefings (HTML, PDF, email) | Python, Airflow, SQLite |
| [HR Attrition Analysis](projects-in-progress/employee-attrition-analysis) | Explores what drives employee attrition (in progress) | Python, SQL |
| [Home Sales Analysis](projects-in-progress/home-sales-analysis) | Home price metrics by features and build year, with caching and partitioning benchmarks | PySpark, SparkSQL |

## By skill

### SQL
| Project | What it does |
|---|---|
| [Employee Database Analysis](sql/bootcamp/employee-database-analysis) | Data modelling (ERD), schema design and SQL analysis of a fictional company's employee records |
| [Hawaii Climate API](sql/bootcamp/sqlalchemy-challenge) | Climate analysis with SQLAlchemy on SQLite, served through a Flask API |

### Python
| Project | What it does |
|---|---|
| [School District Performance](python/bootcamp/pandas-challenge) | District and school-level KPIs with pandas |
| [Clinical Trial Drug Analysis](python/bootcamp/matplotlib-challenge) | Statistical summaries and charts comparing drug regimens |
| [Weather vs Latitude](python/bootcamp/python-api-challenge) | Collects live weather data from APIs and tests how climate changes with latitude |

### ETL
| Project | What it does |
|---|---|
| [Crowdfunding ETL Pipeline](etl/bootcamp/crowdfunding-etl-pipeline) | Extracts Excel data, transforms it with pandas and loads it into PostgreSQL |

### NoSQL
| Project | What it does |
|---|---|
| [UK Food Hygiene Analysis](nosql/bootcamp/nosql-challenge) | MongoDB setup, cleaning and analysis of Food Standards Agency ratings |

### Dashboards and maps
| Project | What it does |
|---|---|
| [Biodiversity Dashboard](dashboards/bootcamp/belly-button-challenge) | Interactive D3/Plotly dashboard ([live](https://juliocezarcarneiro.github.io/belly-button-challenge/)) |
| [Earthquake Map](dashboards/bootcamp/leaflet-challenge) | Leaflet map of USGS earthquake data |

### Machine learning
| Project | What it does |
|---|---|
| [Loan Credit Risk Classification](machine-learning/bootcamp/credit-risk-classification) | Predicts healthy vs high-risk loans for a peer-to-peer lender |
| [Nonprofit Funding Success Predictor](machine-learning/bootcamp/deep-learning-challenge) | Neural network vs XGBoost to predict which funding applications succeed |
| [Crypto Market Clustering](machine-learning/bootcamp/CryptoClustering) | K-Means and PCA to group cryptocurrencies by price behaviour |

### Web scraping
| Project | What it does |
|---|---|
| [Mars Data Collection](web-scraping/bootcamp/mars-data-collection) | Scrapes news articles and weather tables, then analyzes the data |

### Excel
| Project | What it does |
|---|---|
| [Stock Performance Analysis](spreadsheets/bootcamp/stock-analysis) | Multi-year stock analysis automated with VBA |

## How to run a project

Each folder is self-contained. Open its README, install the libraries it lists (pandas, matplotlib, scikit-learn and so on), then:

```bash
jupyter notebook
```

Projects that call external APIs read keys from a local `api_keys.py`, which is never committed. Copy `api_keys.example.py` and add your own keys.

## Contact

**Julio Carneiro** · Data Analyst · Toronto, ON
[LinkedIn](https://www.linkedin.com/in/juliocezarcarneiro/) · [Portfolio](https://github.com/juliocezarcarneiro) · [Email](mailto:juliocezarcarneiro@outlook.com)
