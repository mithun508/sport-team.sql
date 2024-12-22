# SPORT TEAM MANAGEMENT.sql
Overview
This project implements a structured relational database for managing data related to the Indian Premier League (IPL). It models entities such as coaches, teams, players, matches, and match scoreboards. The database schema leverages SQL features like foreign keys, joins, stored procedures, and aggregate functions to facilitate comprehensive data management and analysis.
Database Structure
1. Database Name: IPL
The IPL database serves as the central repository for IPL-related data.
2. Tables:
a).coaches-id,name,age
b).teams-id,name,city
c).players-id,name,age
d).matches-schedules,venue,date,timing
e).scoreboard-team_name,runs,wickets
Toolused -MySQL
 Analysis:
The database structure and queries support in-depth analysis of IPL data, including:
Team Performance: Analyzing the performance of teams based on match scores (runs and wickets).
Player Information: Detailed statistics about players, their ages, and the teams they play for.
Venue Analysis: Fetching match summaries based on specific venues.
Coach Information: Linking coaches to their respective teams and analyzing their age.
The system is flexible for retrieving comprehensive IPL data and can be expanded to include more detailed statistics, such as player strike rates, economy rates, and rankings.













