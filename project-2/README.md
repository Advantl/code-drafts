# ETL-Project
Python-based ETL pipeline

## Архитектура

        student_activity_tracker/
        │
        ├── main.py
        ├── container.py
        │
        ├── config/
        │   ├── __init__.py
        │   ├── settings.py
        │   └── logging_config.py
        │
        ├── clients/
        │   ├── __init__.py
        │   ├── api_client.py
        │   └── google_sheets_client.py
        │
        ├── database/
        │   ├── __init__.py
        │   ├── database.py
        │   ├── repositories/
        │   │   ├── __init__.py
        │   │   └── activity_repository.py
        │   └── sql/
        │       ├── get_student_activity.sql
        │       └── insert_activity.sql
        │
        ├── parsers/
        │   ├── __init__.py
        │   └── activity_parser.py
        │
        ├── services/
        │   ├── __init__.py
        │   ├── metrics_calculator.py
        │   └── email_sender.py
        │
        ├── models/
        │   ├── __init__.py
        │   ├── activity.py
        │   └── report.py
        │
        ├── jobs/
        │   ├── __init__.py
        │   ├── historical_job.py
        │   └── daily_job.py
        │
        └── tests/
            ├── test_api_client.py
            ├── test_activity_parser.py
            ├── test_metrics_calculator.py
            └── test_activity_repository.py
