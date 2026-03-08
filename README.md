# Fantasy Golf League 2026

A web-based application for managing the Fantasy Golf League.

## About

This app provides league members with:
- Live leaderboard and standings
- Team rosters and statistics
- Player search functionality
- Drop/Add transaction history
- Complete league by-laws

## Live App

Visit the app at: `https://THE-FGFOUNDER.github.io/Fantasy-Golf/`

## Features

- **Leaderboard**: Current standings and team rankings
- **Team Scores**: View individual team rosters and points
- **Player Search**: Search any golfer to see which team they're on
- **Drop/Adds**: Complete transaction history for the season
- **By-Laws**: Full league rules and scoring system

## Scoring System

- 1st place: 10 points
- 2nd place: 5 points
- 3rd place: 4 points
- 4th place: 3 points
- 5th place: 2 points

### Multipliers

- **Majors (3x)**: Masters, PGA Championship, U.S. Open, The Open Championship
- **Players & Tour Championship (2x)**
- **Elevated Events (1.5x)**: AT&T Pebble Beach, Genesis Invitational, Arnold Palmer, RBC Heritage, Memorial, Travelers

### Special Rules

- Scottie Scheffler's points are halved (×0.5)

## How to Update Scores

1. Update the `FG_2026_AI_Scores.xlsx` file with new tournament results
2. Run `update_league_data.py` to generate updated JSON data
3. Upload the new `league-data.json` file to this repository
4. GitHub Pages will automatically rebuild the site (1-2 minutes)

## Files

- `index.html` - Main application file
- `league-data.json` - Current league data (updated weekly)
- `update_league_data.py` - Script to extract data from Excel
- `FG_Logo_Updated.png` - League logo
- `DEPLOYMENT_GUIDE.txt` - Instructions for deployment and maintenance
- `INSTRUCTIONS.txt` - Technical documentation

## Technology

- Pure HTML, CSS, and JavaScript (no frameworks required)
- Data-driven from JSON file
- Mobile-responsive design
- Hosted on GitHub Pages

## Commissioner

League managed by THE-FGFOUNDER

---

*Since 1993*
