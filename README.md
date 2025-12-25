# PGA Tour Performance Analysis  
**Rocket Mortgage Classic (2022 PGA Tour Data)**

## Overview
This project analyzes PGA Tour performance data from the Rocket Mortgage Classic using 2022 event data. 
The goal of the analysis is to evaluate scoring consistency, identify key performance drivers, and examine 
how round-to-round variance relates to tournament outcomes, earnings, and FedEx Cup points.

---

## Tools Utilized
- Python
- Pandas
- NumPy
- Matplotlib
- SciPy

---

## Data Sources
- **PGA Tour leaderboard data** scraped from ESPN using a custom Python script  
- **Tournament weather data** sourced from a public Kaggle dataset:  
  https://www.kaggle.com/datasets/montiebrown/pga-tournament-data-with-weather-data-2009-2022

All scripts required to reproduce the dataset are included.

---

## Project Structure
- README.md
- Tournaments_Weather.csv
- scrape_pga_leaderboard.ipynb
- clean_merge_leaderboard_weather.ipynb
- pga_performance_analsis.ipynb

---

## Methods
- Web scraping and data cleaning of PGA Tour leaderboard data
- Merging leaderboard and tournament-level weather data
- Feature engineering and calculation of round-level score variance
- Hypothesis testing to evaluate relationships between scoring consistency and performance outcomes
- Exploratory data analysis and visualization

---

## Key Findings
- Golfers with lower round-to-round scoring variance achieved significantly better tournament scores
- Increased scoring consistency was associated with higher earnings and FedEx Cup performance
- Performance trend analysis demonstrates how Python-based analytics can inform practice and training adjustments

---

## How to Run
1. Run `scrape_pga_leaderboard.ipynb` to collect PGA Tour leaderboard data  
2. Run `clean_merge_leaderboard_weather.ipynb` to clean and merge datasets  
3. Run `pga_performance_analysis.ipynb` to generate analysis, statistics, and visualizations  

---

## Author
Adeline Maki  
B.B.A. Business Analytics and Information Systems  
University of Iowa
