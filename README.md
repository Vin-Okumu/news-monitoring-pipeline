<h1 align = "center">
News Monitoring Pipeline
</h1>

# Overview

This is a Python-based news monitoring system designed to collect news articles from selected online sources, identify mentions of configured keywords, companies and topics, remove duplicate records, and store the results in a structured database.

The project explores web data extraction, data cleaning, entity and keyword matching, relational database design, API development, automated scheduling, and pipeline reliability.

# Repository Structure

```
news-monitoring-pipeline
├── data/
├── docs/
│   ├── decisions/
│   ├── architecture.md
│   ├── data_dictionary.md
│   ├── database_design.md
│   ├── operations_guide.md
│   ├── project_understanding.md
│   ├── requirements.md
│   └── testing_strategy.md
├── notebooks/
├── scripts/
├── src/
│   ├── api/
│   ├── collectors/
│   ├── database/
│   ├── news_monitor/
│   ├── processing/
│   ├── scheduler/
│   ├── _init_.py
│   └── config.py
├── tests/
│   ├── api/
│   │   └── test_articles.py
│   ├── integration/
│   │   ├── test_database.py
│   │   └── test_pipeline.py
│   ├── unit/
│   │   ├── test_cleaner.py
│   │   ├── test_duplicator.py
│   │   └── test_matcher.py
│   └── conftest.py
├── .env
├── .env.example
├── .gitignore
├── pyproject.toml
└── README.md
```

# Project Status

**Status:** Initial setup and project discovery.

The requirements, data sources, architecture, and implementation approach will be documented and developed incrementally.

# Objectives

* Collect article metadata and relevant content from selected sources.
* Normalize and validate collected data.
* Identify monitored keywords, companies and topics.
* Prevent duplicate articles from accumulating.
* Store and retrieve articles through a structured database.
* Expose searchable results through an API.
* Automate collection and monitor pipeline failures.

# Planned Technology Stack

* Python
* HTTP clients and HTML/RSS parsers
* SQL and SQLite, with PostgreSQL considered for deployment
* FastAPI
* Automated testing with pytest
* Git and GitHub

The final technology choices will be confirmed during the design phase.



# Getting Started

Setup instructions, dependencies, configuration, execution commands and testing instructions will be added as the application develops.

# Responsible Data Collection

The system will prioritize official APIs and RSS feeds where suitable, respect applicable website terms and access restrictions, apply reasonable request limits, and avoid bypassing authentication, paywalls or other access controls.
