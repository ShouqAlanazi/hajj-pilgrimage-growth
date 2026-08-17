# Hajj Pilgrimage Growth Over Time

An analysis of how the number of Hajj pilgrims has changed from 1970 to 2025, and what drove the major shifts — infrastructure investment, transportation changes, and the COVID-19 pandemic.

**[View the interactive chart](./hajj_chart.html)** (download and open in your browser)

## The Question

How has the scale of the Hajj changed over the past five decades, and what explains the major turning points in that growth?

## Data Source

Yearly pilgrim counts (1970–2025) are sourced from [Saudipedia](https://saudipedia.com/en/timeline-of-the-number-of-pilgrims-from-1970-to-2025), citing Saudi Arabia's General Authority for Statistics and the Saudi Press Agency.

## What the Data Shows

**1970s–1990s: Steady growth.** Pilgrim numbers climbed from around 1 million to over 2 million, with some year-to-year fluctuation tied to regional and logistical factors.

**2000s–2012: Accelerating growth.** Numbers rose more sharply through the 2000s, peaking at over 3.1 million pilgrims in 2012 — the highest on record.

**2013: A sharp but temporary drop.** Pilgrim numbers fell noticeably due to construction-related capacity restrictions around the Grand Mosque in Mecca, as major expansion work limited how many pilgrims could be accommodated.

**2010s: Infrastructure expansion.** The Haramain High-Speed Railway and Jeddah airport expansion improved capacity and transportation, supporting numbers recovering back toward 2.4–2.5 million by 2019.

**2020–2021: COVID-19 collapse.** The pandemic caused a near-total halt — just 1,000 pilgrims in 2020 and under 59,000 in 2021, both restricted to residents of Saudi Arabia only.

**2022–2025: Recovery.** As restrictions eased, numbers climbed back up — reaching 1.84 million by 2023 and settling around 1.6–1.8 million through 2025.

## Tech Stack

- **Python** + **pandas** for data loading and cleaning
- **Plotly** for the interactive visualization
- **Jupyter Notebook** for the analysis workflow

## Project Structure

```
hajj-pilgrimage-growth/
├── data/
│   └── hajj_pilgrims_raw.csv    # Year-by-year pilgrim counts
├── notebooks/
│   └── hajj_analysis.ipynb      # Full analysis and chart code
├── hajj_chart.html               # Standalone interactive chart
└── README.md
```

## Running It Yourself

```bash
python -m venv venv
venv\Scripts\activate      # Windows
pip install -r requirements.txt
jupyter notebook
```

Then open `notebooks/hajj_analysis.ipynb` and run all cells.
