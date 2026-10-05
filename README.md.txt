# DSA 4060 Week 1: Popularity Based Movie Recommender

## Student Information
- **Name:** Evelyne Kimani
- **Student ID:** 666813

## Project Overview
This project processes MovieLens user-item ratings and builds two non-personalized movie recommendation baselines: a threshold-based popularity baseline and an IMDb-style weighted rating baseline[cite: 1].

## Dataset
- **Dataset Name:** MovieLens Latest-Small Dataset (GroupLens)[cite: 1, 3]
- **Source:** https://grouplens.org/datasets/movielens/[cite: 3]
- **Files Used:** `movies.csv`, `ratings.csv`[cite: 1, 3]

## Methods
1. Rating-count and average-rating exploration
2. Minimum-rating popularity baseline
3. Weighted-rating baseline

## How to Run
1. Clone the repository
2. Install packages: `pip install -r requirements.txt`
3. Place `movies.csv` and `ratings.csv` into `data/`[cite: 3]
4. Open `notebooks/week1_popularity_recommender.ipynb` and run all cells[cite: 3]

## Key Findings
- Weighted rating scoring provides a stable baseline for cold-start homepages[cite: 2].
- Raw average ratings suffer from extreme low-volume distortion[cite: 2].

## Limitations
- Non-personalized (every user gets the exact same output)[cite: 1].
- High popularity bias against obscure movies.

## Screenshot
![Top 10 Recommendations](images/top10_recommendations.png)[cite: 3]