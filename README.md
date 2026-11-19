# Data Analyst & Data Engineer Resource Guide

A curated list of sites for **mock data, datasets, practice platforms, courses, and portfolio building**.

**Legend:** 🟢 Beginner · 🟡 Intermediate · 🔴 Advanced · 🆓 Free · 💲 Paid / freemium

---

## Table of Contents

1. [Mock & Synthetic Data](#1-mock--synthetic-data)
2. [Public Datasets](#2-public-datasets)
3. [SQL Practice](#3-sql-practice)
4. [Python & Pandas Practice](#4-python--pandas-practice)
5. [Data Engineering Learning](#5-data-engineering-learning)
6. [BI & Visualization](#6-bi--visualization)
7. [Projects, Portfolio & Competitions](#7-projects-portfolio--competitions)
8. [Interview Preparation](#8-interview-preparation)
9. [Communities & Newsletters](#9-communities--newsletters)
10. [Learning Roadmaps](#10-learning-roadmaps)
11. [Project Ideas](#11-project-ideas)
12. [Quick Picks](#12-quick-picks)

---

## 1. Mock & Synthetic Data

### Web-based generators

| Site | Output formats | Best for | Cost |
|---|---|---|---|
| [Mockaroo](https://www.mockaroo.com) | CSV, JSON, SQL, Excel | Custom schemas with 100+ field types | 🆓 / 💲 |
| [Generatedata](https://generatedata.com) | SQL, CSV, XML, JSON | Quick tables for testing | 🆓 |

### Fake REST APIs (practice API ingestion)

| Site | Provides | Cost |
|---|---|---|
| [JSONPlaceholder](https://jsonplaceholder.typicode.com) | Posts, comments, todos, users | 🆓 |
| [DummyJSON](https://dummyjson.com) | Users, products, carts, recipes | 🆓 |
| [Random User API](https://randomuser.me) | Realistic user profiles | 🆓 |
| [Fake Store API](https://fakestoreapi.com) | E-commerce products and carts | 🆓 |

### Libraries (generate data in code)

| Library | Language | Best for |
|---|---|---|
| [Faker](https://faker.readthedocs.io) | Python | Names, addresses, transactions, text |
| [SDV (Synthetic Data Vault)](https://sdv.dev) | Python | ML-based synthetic data from real tables |
| [faker-js](https://fakerjs.dev) | JavaScript | Fake data in JS/Node projects |
| [dbt-faker / dbgen](https://github.com/dbgen-project) | SQL / CLI | Large synthetic databases |

---

## 2. Public Datasets

### General-purpose

| Site | Highlights |
|---|---|
| [Kaggle Datasets](https://www.kaggle.com/datasets) | Huge variety, community notebooks |
| [Google Dataset Search](https://datasetsearch.research.google.com) | Search engine for datasets |
| [Awesome Public Datasets](https://github.com/awesomedata/awesome-public-datasets) | GitHub list organized by topic |
| [Hugging Face Datasets](https://huggingface.co/datasets) | ML and NLP datasets |
| [UCI ML Repository](https://archive.ics.uci.edu) | Classic benchmark datasets |

### Government & economic

| Site | Region / focus |
|---|---|
| [data.gov](https://data.gov) | United States |
| [data.gov.in](https://data.gov.in) | India |
| [World Bank Open Data](https://data.worldbank.org) | Global economic indicators |
| [Our World in Data](https://ourworldindata.org/data) | Clean global statistics |

### Large-scale / big data

| Site | Use it for |
|---|---|
| [NYC Taxi & Limousine Data](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page) | Millions of rows, Spark/warehouse practice |
| [AWS Open Data Registry](https://registry.opendata.aws) | Cloud-hosted large datasets |

---

## 3. SQL Practice

### Learn from scratch 🟢

| Site | Style |
|---|---|
| [SQLBolt](https://sqlbolt.com) | Interactive lessons |
| [SQLZoo](https://sqlzoo.net) | Exercises with instant feedback |
| [W3Schools SQL](https://www.w3schools.com/sql/) | Quick reference |
| [Mode SQL Tutorial](https://mode.com/sql-tutorial) | Analytics-focused |

### Practice problems 🟡

| Site | Style |
|---|---|
| [Select Star SQL](https://selectstarsql.com) | Learn through a real dataset |
| [pgexercises](https://pgexercises.com) | PostgreSQL drills |
| [HackerRank SQL](https://www.hackerrank.com/domains/sql) | Graded challenges |
| [SQL Murder Mystery](https://mystery.knightlab.com) | Gamified detective story |

### Interview-level 🔴

| Site | Style |
|---|---|
| [LeetCode Database](https://leetcode.com/problemset/database/) | Interview-style problems |
| [DataLemur](https://datalemur.com) | FAANG-style SQL |
| [StrataScratch](https://www.stratascratch.com) | Real company questions |

---

## 4. Python & Pandas Practice

| Site | Level | Notes |
|---|---|---|
| [Kaggle Learn](https://www.kaggle.com/learn) | 🟢 | Short free courses (Python, Pandas, ML, SQL) |
| [Exercism (Python)](https://exercism.org/tracks/python) | 🟢🟡 | Mentored exercises |
| [pandas-exercises](https://github.com/guipsamora/pandas_exercises) | 🟡 | Pandas drills on GitHub |
| [Real Python](https://realpython.com) | 🟡 | In-depth tutorials |
| [Advent of Code](https://adventofcode.com) | 🟡🔴 | Annual puzzle challenges |
| [DataCamp](https://www.datacamp.com) | 🟢🟡 | Guided courses (💲, some free) |

---

## 5. Data Engineering Learning

### Courses & guides

| Resource | Focus |
|---|---|
| [Data Engineering Zoomcamp](https://github.com/DataTalksClub/data-engineering-zoomcamp) | Free, project-based, end to end |
| [Start Data Engineering](https://www.startdataengineering.com) | Blog and tutorials |
| [Awesome Data Engineering](https://github.com/igorbarinov/awesome-data-engineering) | Curated tools list |

### Tools & platforms

| Tool | Learn it at | Category |
|---|---|---|
| Apache Airflow | [airflow.apache.org/docs](https://airflow.apache.org/docs/) | Orchestration |
| dbt | [learn.getdbt.com](https://learn.getdbt.com) | Transformation |
| Spark / Databricks | [databricks.com/learn](https://www.databricks.com/learn) | Big data processing |
| Kafka | [developer.confluent.io](https://developer.confluent.io) | Streaming |
| Docker | [Play with Docker](https://labs.play-with-docker.com) | Containers |

### Free-tier cloud for building pipelines

- [AWS Free Tier](https://aws.amazon.com/free)
- [Google Cloud Free](https://cloud.google.com/free)
- [Azure Free](https://azure.microsoft.com/free)

---

## 6. BI & Visualization

| Resource | Type |
|---|---|
| [Tableau Public](https://public.tableau.com) | Free tool and gallery for inspiration |
| [Power BI Learning](https://learn.microsoft.com/en-us/power-bi/) | Official docs and training |
| [Looker Studio](https://lookerstudio.google.com) | Free dashboards |
| [Maven Analytics](https://mavenanalytics.io) | Free datasets and challenges |
| [Makeover Monday](https://www.makeovermonday.co.uk) | Weekly viz challenges |

---

## 7. Projects, Portfolio & Competitions

| Site | Purpose |
|---|---|
| [Kaggle Competitions](https://www.kaggle.com/competitions) | Compete and learn from public notebooks |
| [DrivenData](https://www.drivendata.org) | Data for social good |
| [DataCamp Projects](https://www.datacamp.com/projects) | Guided projects |
| [GitHub](https://github.com) | Host your portfolio and code |
| [Dataquest Blog](https://www.dataquest.io/blog/) | Project ideas and tutorials |

---

## 8. Interview Preparation

| Site | Covers |
|---|---|
| [Interview Query](https://www.interviewquery.com) | SQL, Python, case studies |
| [DataLemur](https://datalemur.com) | SQL |
| [StrataScratch](https://www.stratascratch.com) | SQL and Python from real interviews |
| [LeetCode](https://leetcode.com) | SQL and Python |

---

## 9. Communities & Newsletters

| Name | Type |
|---|---|
| [r/dataengineering](https://reddit.com/r/dataengineering) | Reddit |
| [r/datascience](https://reddit.com/r/datascience) | Reddit |
| [DataTalks.Club](https://datatalks.club) | Slack community |
| [Locally Optimistic](https://locallyoptimistic.com) | Analytics community |
| [Data Engineering Weekly](https://www.dataengineeringweekly.com) | Newsletter |

---

## 10. Learning Roadmaps

### Data Analyst track

| Stage | Focus | Resources |
|---|---|---|
| 1. Foundations | SQL basics, Excel, stats | SQLBolt, Mode SQL, Kaggle Learn |
| 2. Core skills | Python/Pandas, cleaning, EDA | Kaggle Learn, pandas-exercises |
| 3. Visualization | Dashboards, storytelling | Tableau Public, Power BI, Makeover Monday |
| 4. Practice | Real problems | DataLemur, StrataScratch, Kaggle datasets |
| 5. Showcase | Portfolio, interviews | GitHub, Tableau Public, Interview Query |

### Data Engineer track

| Stage | Focus | Resources |
|---|---|---|
| 1. Foundations | SQL, Python, Git, Linux | SQLBolt, Exercism, Real Python |
| 2. Storage & modeling | Databases, warehousing | pgexercises, Mode SQL |
| 3. Pipelines | ETL/ELT, orchestration | Airflow docs, dbt Learn |
| 4. Scale | Spark, streaming, cloud | Databricks Academy, Confluent, free-tier cloud |
| 5. Capstone | End-to-end project | Data Engineering Zoomcamp, GitHub |

---

## 11. Project Ideas

| Level | Idea | Data source |
|---|---|---|
| 🟢 | Sales dashboard | Mockaroo, Maven Analytics |
| 🟢 | Exploratory analysis of a public dataset | Kaggle, data.gov.in |
| 🟡 | API to database pipeline | JSONPlaceholder or DummyJSON, PostgreSQL |
| 🟡 | Scheduled ETL with Airflow | Random User API, Faker |
| 🔴 | Taxi trip analytics warehouse | NYC Taxi data, dbt, BigQuery or Snowflake |
| 🔴 | Real-time streaming pipeline | Kafka, Faker-generated events, Spark |

---

## 12. Quick Picks

| I want to... | Go to |
|---|---|
| Generate a custom CSV fast | [Mockaroo](https://www.mockaroo.com) |
| Practice API calls | [DummyJSON](https://dummyjson.com) |
| Learn SQL from zero | [SQLBolt](https://sqlbolt.com) |
| Prepare for SQL interviews | [DataLemur](https://datalemur.com) |
| Learn data engineering free | [DE Zoomcamp](https://github.com/DataTalksClub/data-engineering-zoomcamp) |
| Find big datasets | [NYC Taxi Data](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page) |
| Build a public dashboard | [Tableau Public](https://public.tableau.com) |

---

*Tip: bookmark this file in a GitHub repo and tick off resources as you complete them.*
