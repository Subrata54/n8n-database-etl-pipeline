# n8n-database-etl-pipeline
# Database-to-Warehouse ETL Pipeline (n8n)

## Overview

This project automates data movement from PostgreSQL to Snowflake using n8n.

### Features

* Incremental data loading
* Data transformation
* Schema validation
* Duplicate detection
* Snowflake warehouse loading
* Slack notifications
* Error handling

## Workflow

Schedule Trigger → PostgreSQL → Data Validation → Data Transformation → Snowflake → Slack

## Tech Stack

* n8n
* PostgreSQL
* JavaScript
* Snowflake
* Slack

## Use Case

Automatically sync operational database records into a data warehouse for analytics and reporting.

