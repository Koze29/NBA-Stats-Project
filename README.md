# NBA Statistics Project

An exploratory data analysis project using **R** to examine NBA player statistics, with a focus on **LeBron James**. The project uses statistical methods and visualizations to explore scoring, playing time, field-goal attempts, and relationships between offensive statistics.

## Project Goals

- Explore and summarize NBA player statistics.
- Examine LeBron James's scoring and playing-time averages.
- Investigate the relationship between field-goal attempts and points scored.
- Use correlation and linear regression to interpret statistical relationships.
- Present the findings through data analysis and visualizations.

## Tools

- **R** – data cleaning, statistical analysis, and visualization
- **RStudio** – development environment
- **CSV dataset** – NBA statistics stored in `NBA STATsR.csv`

## Analysis

The project examines variables including:

- Player
- Year
- Minutes played (MP)
- Points scored (PTS)
- Field-goal attempts (FGA)
- Field-goal percentage (FG%)

The analysis includes descriptive statistics, correlation, and a linear regression model.

## Selected Results

### LeBron James

| Statistic | Average |
|---|---:|
| Minutes played (MP) | 36.71 |
| Points scored (PTS) | 26.49 |
| Field-goal attempts (FGA) | 18.78 |

### Relationships Across the Dataset

| Comparison | Correlation |
|---|---:|
| Field-goal attempts and points (FGA vs. PTS) | 0.9807 |
| Field-goal percentage and points (FG% vs. PTS) | 0.2462 |

A linear regression model was also fit to estimate points scored from field-goal attempts:

```
PTS = -0.530043 + 1.279042(FGA)
R-squared = 0.9618
```

In this dataset, field-goal attempts have a very strong positive relationship with points scored. Field-goal percentage has a weaker positive correlation with points.

## How to Run

1. Clone or download this repository.
2. Open the R project or R script in RStudio.
3. Make sure the dataset file `NBA STATsR.csv` is in the location expected by the code.
4. Run the script to reproduce the analysis.

## Project Focus

This project demonstrates the use of R for working with real-world sports statistics, applying statistical techniques, and communicating findings through data analysis.

---

*Created as an academic statistics project focused on NBA performance data.*
