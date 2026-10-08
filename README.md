# Farmers Insurance — SQL Analysis

SQL analysis of Indian farmers' insurance data: 29 business questions across
filtering, aggregation, joins, subqueries, and window functions.

## Dataset

- `FarmersInsuranceData` table: state-wise crop insurance records with fields
  such as state name, year, farmers covered, sum insured, and premium amounts.
- The table itself is not in this repo; the `.sql` file holds the queries.

## What it covers

10 sections, 29 questions (28 answered):

1. SELECT queries
2. Filtering with WHERE
3. Aggregation with GROUP BY
4. Sorting with ORDER BY
5. String functions
6. Joins
7. Subqueries
8. Window functions
9. Data integrity (constraints, foreign keys)
10. UPDATE and DELETE

## How to run

```sql
use ndap;
```

then run the sections in order in any MySQL-compatible client with the
`FarmersInsuranceData` table loaded.

## Known limitations

- Requires the source table to be loaded separately; no schema or seed data is
  included.
