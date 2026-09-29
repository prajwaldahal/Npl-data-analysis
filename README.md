# NPL Data Analysis

Analysis of the Nepal Premier League: 64 matches across the 2024/25 and 2025/26 seasons.

## Contents

- `data-json/`: ball-by-ball match files from [Cricsheet](https://cricsheet.org)
- `data-csv/npl_matches.csv`: one row per match
- `data-csv/npl_deliveries.csv`: one row per ball
- `data-csv/npl_players.csv`: batting and bowling styles (from ESPNcricinfo, Wikipedia and Wikidata)
- `npl-matches-EDA.ipynb`, `npl-deliveries-EDA.ipynb`: EDA, each with a data dictionary
- `analysis.ipynb`: practice workbook with 100 questions

## Setup

```bash
python -m venv venv && source venv/bin/activate
pip install -r requirements.txt
jupyter lab
```
