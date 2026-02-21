# Movie Data Trends Pipeline 🎬

## Project Overview
This is a solo Big Data project developed to analyze and visualize trends within the TMDB Top 10,000 Movies dataset. The goal was to build a clean, reproducible data pipeline that transforms raw movie metadata into actionable insights.

## The "Why"
As a Computer Science student specializing in Big Data, I created this project to demonstrate:
* **Professional Workflow:** Implementing a structured repository (Raw vs. Processed data).
* **Data Integrity:** Handling missing values and correcting schema types.
* **Exploratory Data Analysis (EDA):** Identifying production trends and popularity outliers.

## Project Structure
* `dataset/raw/`: Original Kaggle dataset (Top Rated Movies).
* `dataset/processed/`: Cleaned and transformed CSV ready for analysis.
* `notebooks/`: Jupyter/Colab notebooks for data profiling and visualization.
* `src/`: Production-ready Python scripts.

## Key Insights
* **Data Density:** Identified an exponential rise in movie production/documentation starting around the year 2000.
* **Outlier Analysis:** Discovered significant popularity variance, with top outliers exceeding 300 points compared to the 0-50 average.

## How to Run
1. Clone the repository.
2. Install dependencies: `pip install -r requirements.txt`
3. Run the notebooks in the `/notebooks` directory.