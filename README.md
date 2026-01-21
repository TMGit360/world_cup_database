# World Cup Database

PostgreSQL database project that stores FIFA World Cup match results and demonstrates basic relational design, data loading, and querying using SQL and Bash.

Completed as part of the FreeCodeCamp Relational Database certification.

## What It Shows

- Relational schema with primary and foreign keys
- Loading CSV data into PostgreSQL via Bash
- Basic SQL queries and reporting

## Files

- `worldcup.sql` – database schema
- `games.csv` – source data
- `insert_data.sh` – load data
- `queries.sh` – run queries

## Run

```bash
psql -U postgres -f worldcup.sql
bash insert_data.sh
bash queries.sh
