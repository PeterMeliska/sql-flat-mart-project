# SQL Project: Data Warehouse / Datamart

## About
This repository contains my SQL practice project focused on building a simple data warehouse and datamart structure for job postings analysis.

## Project Scope
The project includes dimension tables, a fact table, and a bridge table to model relationships between companies, job postings, and required skills. Data is loaded from CSV files and structured into an analytical model suitable for further querying and reporting.

## Data Model
The warehouse structure includes:
- `company_dim` for company information
- `skills_dim` for skill definitions
- `job_postings_fact` as the central fact table for job postings
- `skills_job_dim` as the bridge table between jobs and skills

## Purpose
This project was created to strengthen my practical skills in SQL, data modeling, table relationships, and building structured analytical datasets.

## Key Skills Demonstrated
- SQL table creation
- Primary and foreign keys
- Fact and dimension modeling
- Bridge table design
- Loading external CSV data
- Preparing data for analytics

## Tools
- SQL
- DuckDB
- CSV data sources

## Outcome
This project demonstrates how raw source data can be transformed into a structured warehouse model that supports analytics and reporting.
