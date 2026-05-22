# EPL Database Design

## Project Overview
A paragraph describing what the system models and why

## Tech Stack
- PostgreSQL
- dbdiagram.io
- SQL

## Business Requirements
- [Business Requirements](docs/business_requirements.md)

## Entity List
**1. Player**
Stores personal details about each player — name, date of birth, nationality, and position
2. Stadium
Stores details about each ground — name, city, and capacity
3. Referee
Stores details about each match official — name and nationality
4. Manager
Stores details about each club manager — name, nationality, and date of birth
5. Team
Stores details about each club — club name, year founded, and their home stadium
6. Competition
Stores the different tournaments — Premier League, UCL, UEL, and Conference League
7. Season
Stores each season as a separate record — 2023/24, 2024/25 and so on — so all stats and standings are tied to a specific year
8. Match
Stores details about each game — date, gameweek number, home team, away team, venue, and final score
9. MatchEvent
Stores every notable moment during a match — goals, assists, yellow cards, red cards, and substitutions, each with a minute stamp and which half it occurred in
10. Transfer
Stores player movement between clubs — which player moved, from which club, to which club, the transfer fee, and the date
11. PlayerStats
Stores a player's accumulated statistics for an entire season — appearances, goals, assists, and clean sheets — tied to a specific player, team, and season

## ERD
coming soon

## How to Run Locally
coming soon
