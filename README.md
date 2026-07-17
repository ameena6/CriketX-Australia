# CriketX-Australia 🏏

Exploratory data analysis of Australia's **Big Bash League (BBL)**, covering matches from **2011–2019**. The project cleans and combines match, ball-by-ball, and delivery-level data to surface trends across teams, players, and seasons.

## Overview

This repo takes raw BBL data and turns it into something you can actually explore — cleaning messy fields, joining match/ball/delivery records together, and generating summary stats and visualizations (top run-scorers, wicket-takers, team performance by season, venue trends, etc.).

## Dataset

| File | Description |
|---|---|
| `data/BBL Matches 2011-2019.csv` | Match-level summary: teams, venue, date, result |
| `data/match.csv` | Additional match metadata |
| `data/deliveries.csv` | Ball-by-ball delivery records |
| `data/ball.csv` | Supplementary ball-level data |

> Data covers Big Bash League seasons from 2011 to 2019.

## Getting Started

### Prerequisites

- Python 3.8+
- Jupyter Notebook

### Installation

```bash
git clone https://github.com/ameena6/CriketX-Australia.git
cd CriketX-Australia
pip install -r requirements.txt
```

### Usage

Launch the notebook and run the cells in order:

```bash
jupyter notebook bbl_analysis.ipynb
```

## What's Inside

- Data cleaning and preprocessing of raw match/ball/delivery CSVs
- Merging datasets into a unified view for analysis
- Summary statistics: top scorers, leading wicket-takers, team win rates
- Visualizations of trends across teams, players, and seasons

## Key Findings

_Add 2–3 bullet points here summarizing your most interesting results, e.g.:_
- Which team had the best win rate across the sampled seasons
- Standout individual performances (top run-scorer / wicket-taker)
- Any notable trend over time (e.g. scoring rates increasing season to season)

## Tech Stack

- Python
- pandas / numpy
- matplotlib / seaborn
- Jupyter Notebook

## License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.
