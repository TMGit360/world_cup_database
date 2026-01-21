# World Cup Database

PostgreSQL-based database project modeling FIFA World Cup match results, focusing on relational schema design, data ingestion, and SQL querying using Bash and PostgreSQL.

Completed as part of the FreeCodeCamp Relational Database certification.

## Competencies

- SQL queries and reporting
- Relational schema with primary and foreign keys
- Bash scripting for CSV parsing and database interaction
- Loading CSV data into PostgreSQL via Bash using `psql`

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
```
