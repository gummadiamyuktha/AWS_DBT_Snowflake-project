Airbnb Data Engineering Project

AWS S3 • Snowflake • dbt

About

This project is a hands-on Data Engineering pipeline built using AWS S3, Snowflake, and dbt. The goal was to understand how raw data moves through a modern data stack and how it is transformed into analytics-ready datasets.

What I Built

Ingested raw data from AWS S3 into Snowflake

Used dbt to transform data using Bronze, Silver, and Gold layers

Built the pipeline in a metadata-driven way

Used Jinja templating to keep SQL reusable

Implemented incremental models for efficient data loading

Used dbt snapshots (SCD Type 2) to track historical changes

Created fact tables, star schema models, and One Big Table (OBT) outputs

Used ephemeral models for lightweight intermediate logic

Tools Used

AWS S3

Snowflake

dbt

SQL

GitHub

What I Learned

How Snowflake and dbt work together in a real pipeline

How Bronze/Silver/Gold layers are used in practice

How incremental loading and SCD Type 2 are implemented

How analytics models are designed for reporting
