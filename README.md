# IPL 2025 Data Analysis Project

This project is an exploratory data analysis (EDA) workflow for the Indian Premier League 2025 season using Jupyter Notebook and Python libraries.

The analysis reads two IPL 2025 performance datasets:

- Batters dataset: player batting statistics such as runs, matches, innings, strike rate, average, boundaries, and sixes
- Bowlers dataset: bowling statistics such as wickets, overs, runs, strike rate, economy, and averages

## Project Files

- Notebook: `ipl2025.ipynb`
- Dataset files are expected to be available locally from the external archive path used in the notebook

## Objectives

The notebook answers questions such as:

- Top run scorers in IPL 2025
- Top wicket takers
- Teams with the highest cumulative runs and wickets
- Players with batting averages above a threshold
- Bowlers with economy rates below a target
- Batters scoring more than 500 runs
- Correlation between key batting metrics

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Setup

Install the required Python packages:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

Open the notebook:

```bash
jupyter notebook ipl2025.ipynb
```

## Notes

The notebook currently uses absolute CSV file paths on the local machine. If you want to reuse this project, update the CSV paths in the notebook to match your dataset location.
