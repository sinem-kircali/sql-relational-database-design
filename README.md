# European Football SQL Database

A relational database project modeling European football data — built for the Information Systems course at Koç University.

## Schema
7 tables with proper primary/foreign key relationships:

| Table | Description |
|---|---|
| `Countries` | 10 European countries |
| `Leagues` | Top-flight and second-division leagues per country |
| `Seasons` | Season years |
| `Teams` | Club teams with current league reference |
| `Players` | Player records with nationality |
| `Team_Leagues` | Team participation per season (with champion flag) |
| `Player_Teams` | Player–team contracts with salary data |

## Queries
Analytical SQL queries covering:
- Players and their current teams (multi-table JOIN)
- All-time league champions per country
- Total career earnings per player
- Foreign player counts per team
- Teams that have never won a specific league
- Player and team history across seasons

## Tech Stack
- MySQL
- Standard SQL (DDL + DML + analytical queries)

## How to Run
1. Import `european_football_database.sql` into any MySQL instance
2. Run queries section by section — each is labeled and self-contained
