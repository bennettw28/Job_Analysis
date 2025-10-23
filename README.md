# Job Percentage (Job%)

**Author:** Bennett Weinstein  
UC Berkeley — Economics & Data Science  
[LinkedIn](https://www.linkedin.com/in/bennettweinsteinberkeley) • [GitHub](https://github.com/bennettw28)

## Overview
**Job Percentage (Job%)** measures how efficiently teams convert high-leverage run-scoring situations into results. This repo contains the presentation, HTML, and reproducible code.

All CSV files required to reproduce this analysis are hosted on Google Drive due to size limits on GitHub. To reproduce the results, download the CSVs from the data folder above and read them into the notebook using your preferred file paths.

## Deliverables
- 🎥 **Presentation (mp4):** [Watch Here](https://drive.google.com/file/d/1g7o_aDMyM6DJfJcZPawoYazWo_lZoHig/view?usp=sharing)
- 🌐 **HTML Report:** [View Here](https://bennettw28.github.io/Job_Analysis/)
- 💻 **Notebook (code):** [View Here](https://github.com/bennettw28/Job_Analysis/blob/main/Job_pct.ipynb)
- 📂 **Download Folder:** [Job_Analysis_Data](https://drive.google.com/drive/folders/1cu1kaxKReTosaMzJ2BSD8KAtcYKelEln?usp=sharing)

## Methods (1-paragraph)
This analysis uses Statcast data from the 2025 MLB regular season to quantify how often teams convert high-leverage run-scoring opportunities into results. Job Percentage (Job%) is computed from all plate appearances with a runner on second and no outs, or a runner on third with 0–1 outs. A separate playoff analysis uses postseason data from the 2022–2024 seasons to examine how situational efficiency differs under higher-pressure environments. I calculate each team’s Job% and use ordinary least squares (OLS) regressions to test its relationship with total wins. Visualizations and regression outputs were produced in Python using pandas, NumPy, Matplotlib, and statsmodels.


## Contact
bennett_weinstein@berkeley.edu
