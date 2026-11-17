# Sports Digest LLC Data Engineering Case Study

This repository contains the data, database artifacts, SQL analyses, and presentation materials for a Sports Digest LLC case study focused on English Premier League statistics.

## Repository contents

- `data/` — CSV datasets for match scores, player statistics, team statistics, seasons, teams, trophies, and countries. Match-score files cover the 2006/07 through 2019/20 seasons; player and team statistics are provided for seasons from 2007/08 through 2020/21.
- `Schema and Data Dump - Dump20201209.sql` — MySQL schema and data dump for `sports_digest_db`.
- `Queries 1 ,2,3 and 4.sql` — example queries for player minutes by age, leading goal scorers, player nationality, and home/away wins by season.
- `Tableau_Sports_Digest final.twbx` — Tableau workbook for exploring and presenting the analysis.
- `EER Model Final.pdf` and `Sports_Digets_ERR.mwb` — database relationship diagram and MySQL Workbench model.
- `Sports Digest LLC - DEPA Final Presentation.pptx` — case study presentation.

## Working with the data

The SQL dump targets MySQL 8 and creates the `sports_digest_db` database. It includes statements that drop and recreate tables and may require elevated MySQL privileges. Import it only into a local, disposable development database after reviewing the script; do not run it against a production or shared database.

Open `Queries 1 ,2,3 and 4.sql` in a MySQL client after loading the schema to review the sample analyses. Open the packaged `.twbx` workbook in Tableau to explore the visualization work.

The CSV files are organized by subject area under `data/`. The project has no application runtime or automated test suite.
