# Zomato Data Analysis

This project performs an exploratory data analysis (EDA) on a Zomato restaurant dataset to uncover insights about customer behavior, restaurant performance, and ordering trends.

## Project Overview

- Analyze customer and restaurant data from Zomato.
- Visualize trends in ratings, votes, cost, and order modes (online/offline).
- Answer business questions to support strategic decisions for customer engagement and restaurant optimization.

## Dataset

The dataset (`Zomato data .csv`) contains information about restaurants, including:
- Name
- Online order availability
- Table booking availability
- Rating
- Number of votes
- Approximate cost for two people
- Type of restaurant

## Analysis Performed

- Data cleaning: checked for duplicates and null values.
- Converted rating column to numeric type.
- Visualized distribution of restaurant types and ratings.
- Analyzed votes received by each restaurant type.
- Explored spending patterns of couples.
- Compared ratings for online vs offline orders.
- Identified which restaurant types receive more offline/online orders.

## Key Insights

- Majority of restaurants fall under the "Dining" category.
- Dining restaurants receive the most votes.
- Most restaurant ratings are between 3.5 and 4.
- Couples prefer restaurants with an approximate cost of 300 rupees.
- Online orders generally receive higher ratings than offline orders.
- Dining restaurants primarily accept offline orders, while cafes receive more online orders.

## How to Run

1. Clone this repository.
2. Ensure you have Python 3.x and the following libraries installed:
   - pandas
   - numpy
   - seaborn
   - matplotlib
3. Place the `Zomato data .csv` file in the project directory.
4. Open and run the Jupyter notebook: `Zomato_Data_Analaysis.ipynb`.

## Visualizations

The notebook includes various plots such as count plots, histograms, box plots, line graphs, and heatmaps to illustrate the findings.

