nba_records
- Purpose: Analyze player and team-level NBA performance data to surface trends, relationships and notable player statistics. Typical analysis components:
	- Aggregation of per-player and per-game statistics (points, field goals, free throws, minutes played, etc.).
	- Time/trend analysis to show how metrics evolve across seasons or game counts.
	- Salary vs performance comparisons to explore compensation patterns relative to outputs (e.g., points per minute, efficiency indicators).
	- Visualization of distributions, leaderboards (top scorers, most minutes, highest efficiency) and simple regressions/correlations where informative.

Files to note:
- `Basketball Trends and More.Rmd` — main R Markdown analysis that strings together the different analyses and visualizations.
- `Basketball-Trends-and-More.pdf` — rendered PDF report summarizing the analyses and key charts.
- CSVs: `Points.csv`, `FieldGoals.csv`, `FieldGoalAttempts.csv`, `FreeThrows.csv`, `FreeThrowAttempts.csv`, `MinutesPlayed.csv`, `Games.csv`, `Salary.csv` — raw data sources used across the notebook.
