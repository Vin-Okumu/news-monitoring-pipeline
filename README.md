# News Monitoring Pipeline

## Overview

A Python-based news monitoring system designed to collect news articles from selected online sources, identify mentions of configured keywords, companies and topics, remove duplicate records, and store the results in a structured database.

The project explores web data extraction, data cleaning, entity and keyword matching, relational database design, API development, automated scheduling, and pipeline reliability.

## Project Status

**Status:** Initial setup and project discovery.

The requirements, data sources, architecture, and implementation approach will be documented and developed incrementally.

## Objectives

* Collect article metadata and relevant content from selected sources.
* Normalize and validate collected data.
* Identify monitored keywords, companies and topics.
* Prevent duplicate articles from accumulating.
* Store and retrieve articles through a structured database.
* Expose searchable results through an API.
* Automate collection and monitor pipeline failures.

## Planned Technology Stack

* Python
* HTTP clients and HTML/RSS parsers
* SQL and SQLite, with PostgreSQL considered for deployment
* FastAPI
* Automated testing with pytest
* Git and GitHub

The final technology choices will be confirmed during the design phase.

## Repository Structure

* `docs/` — Requirements, architecture, design decisions and operating documentation.
* `src/news_monitor/` — Application source code.
* `tests/` — Unit, integration and API tests.
* `scripts/` — Repeatable operational commands.
* `notebooks/` — Exploratory analysis and technical experiments.
* `data/` — Local development and sample data.

## Getting Started

Setup instructions, dependencies, configuration, execution commands and testing instructions will be added as the application develops.

## Responsible Data Collection

The system will prioritize official APIs and RSS feeds where suitable, respect applicable website terms and access restrictions, apply reasonable request limits, and avoid bypassing authentication, paywalls or other access controls.
