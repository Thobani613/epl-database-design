# Business Requirements — EPL Database Management System

## Project Overview
This system models the English Premier League ecosystem. It tracks clubs,
players, matches, events, transfers, referees, and seasonal statistics.
The goal is to provide a robust relational database that supports both
operational data management and analytical reporting.

## What the System Tracks
- Seasons (e.g. 2023/24, 2024/25)
- Clubs and their home stadiums
- Players and which club they currently belong to
- Managers per club
- Matches — gameweek, date, home club, away club, venue
- Match events — goals, assists, yellow cards, red cards,
  substitutions with minute and half stamps
- Referee assignments per match
- Player transfers — fee, date, from club, to club
- League standings — points, wins, draws, losses,
  goal difference per club per season
- Player statistics per season — appearances, goals,
  assists, clean sheets

## Business Questions the System Must Answer
1. Who is the golden boot leader in the current season?
2. Which club has conceded the fewest goals at home?
3. What is a player's full transfer history including fees?
4. How many red cards has a specific referee issued this season?
5. What are the full standings after a specific gameweek?
6. Which player has the most assists in a single season
   in the last 5 years?
7. Which club scores the most goals in the second half of matches?

## Entities
1. Player — name, DOB, nationality, position
2. Stadium — name, city, capacity
3. Referee — name, nationality
4. Manager — name, nationality, DOB
5. Team — club name, founded year, home stadium
6. Competition — Premier League, UCL, UEL, Conference League
7. Season — 2023/24, 2024/25 etc.
8. Match — date, gameweek, home team, away team, venue
9. MatchEvent — goal, yellow card, red card,
   substitution, minute, half
10. Transfer — player, from club, to club, fee, date
11. PlayerStats — appearances, goals, assists,
    clean sheets per player per season
