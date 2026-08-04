# daily-data-ingestion-automation
Python automation for daily JSON data ingestion, transformation and SQL Server loading.


# Daily Data Ingestion Automation

## Overview

A Python-based ETL automation project that demonstrates how to automate a daily JSON data ingestion workflow.

The project simulates a production scenario where JSON data is:

- Extracted
- Validated
- Transformed
- Loaded into SQL Server
- Logged for monitoring

---

## Business Problem

Many organizations perform repetitive daily data ingestion tasks manually.

This project demonstrates how Python can automate those tasks, reducing manual effort, improving consistency, and minimizing processing time.

---

## Solution Architecture

```text
JSON Input
     │
     ▼
Extract
     │
     ▼
Validate
     │
     ▼
Transform
     │
     ▼
Load into SQL Server
     │
     ▼
Execution Logs
```

---

## Tech Stack

- Python
- SQL Server
- pyodbc
- JSON
- pandas

---

## Features

- Modular ETL architecture
- Configuration-driven execution
- Logging
- Error handling
- SQL Server integration
- Sample data included

---

## Project Structure

```text
daily-data-ingestion-automation/
│
├── config/
├── docs/
├── logs/
├── sample_data/
├── sql/
├── src/
└── tests/
```

---

## Future Improvements

- Scheduler integration
- Email notifications
- Unit tests
- Docker support
