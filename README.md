# 🏈 DTFFL Analytics

Fantasy football analytics platform for the **DTFFL (Toledo League)** — a 12-team half-PPR keeper league.

Powered by [nflverse](https://github.com/nflverse/nflverse-data) play-by-play data across 5 seasons (2021–2025).

## 🔗 Live Site

**[https://brandonsbombers.github.io/dtffl-analytics/](https://brandonsbombers.github.io/dtffl-analytics/)**

## What's Inside

| Section | Files | Description |
|---------|-------|-------------|
| Season reports | 260 | 52 metrics × 5 seasons (RB / WR-TE / QB) |
| Multi-season trends | 3 | Player trajectory cards with sparklines |
| Breakout / Regression | 3 | Age curve + WAR signals |
| 2026 Draft prep | 3 | Composite rankings + auto-scout notes |
| Index pages | 7 | Season browser + trends navigator |

## Scoring

**Half-PPR** — Rush/Rec yards 0.1 pts, TDs 6 pts, Receptions 0.5 pts, Fumbles lost −2 pts.  
QBs: Passing yards 0.04 pts, Passing TDs 4 pts, INTs −1 pt.

## Key Metrics

- **Fantasy WAR** — points above replacement level by position
- **Composite Score** — weighted blend of volume, efficiency, consistency, scoring, and explosive percentiles
- **EPA per attempt/target** — nflverse expected points added
- **Age curve tags** — Breakout / Peak / Declining / Veteran
- **Boom/Bust rate** — weekly scoring threshold analysis

## Data

- Source: [nflverse play-by-play](https://github.com/nflverse/nflverse-data) + roster CSVs
- Seasons: 2021, 2022, 2023, 2024, 2025
- Updated: pre-draft each season

## Built With

Google Colab · pandas · pyarrow · nflverse · vanilla HTML/CSS
