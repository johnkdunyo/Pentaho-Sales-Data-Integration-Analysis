# Pentaho: Sales Data Integration & Analysis

The goal of this project is to develop a comprehensive data integration and analysis platform that will empower the sales team to effectively track, analyze, and optimize their performance. By leveraging powerful tools and a structured approach, the platform will provide a unified view of sales-related data in a dimensional model star schema, enabling data-driven decision-making and improved business outcomes.

## Tools and Stacks

- MySQL
- Pentaho Data Integration (PDI)
- PostgreSQL
- Tableau

## Project Repo Structure

1. **docker-compose.yaml**: This file contains the configuration for Docker Compose, which is used to orchestrate multiple Docker containers. It defines three services:

   - `source_system`: The source system's MySQL database.

2. **source_system_init/AdventureWorks2019.sql**: This SQL script initializes the source and sink system's databases with sample data and appropriate schema.

## How It Works

## Running the Project

1. Clone this repository.
1. Ensure you have Docker and Docker Compose installed on your machine.
1. Navigate to the root repository directory and run `docker-compose up`.
1. you can access the source (MySQL) and sink (PostgreSQL) databases on ports 3306 and 5434 respectively. Check **docker-compose.yml** for connection credentials
