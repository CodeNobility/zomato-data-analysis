# Zomato Data Analysis Project

## Project Overview

This project aims to perform exploratory data analysis (EDA) on Zomato's restaurant data. Using Python libraries like Pandas, Matplotlib, and Seaborn, we explore various insights such as restaurant types, votes received, ratings, and order patterns. The project seeks to answer key questions through data visualization techniques.

## Dataset

The dataset contains various attributes related to restaurants, such as ratings, votes, approximate cost for two people, and whether online orders are accepted. Each row represents a restaurant's information.

### Key Columns:
- **rate**: Restaurant rating (converted to a numerical format in the project)
- **votes**: Number of votes a restaurant has received
- **approx_cost(for two people)**: Approximate cost for two people
- **listed_in(type)**: Type of restaurant (e.g., Dining, Cafes, etc.)
- **online_order**: Indicates whether the restaurant accepts online orders (Yes/No)

## Key Questions Addressed

1. **What type of restaurant do the majority of customers order from?**
   - Using a count plot, the analysis shows that most customers order from dining restaurants.

2. **How many votes did each type of restaurant receive?**
   - A bar plot reveals the total votes received by each type of restaurant. Dining restaurants received the highest number of votes.

3. **What are the ratings that the majority of restaurants have received?**
   - A histogram illustrates that the majority of restaurants have ratings between 3.6 and 4.1.

4. **What is the average spending for each order?**
   - A count plot shows that the majority of couples prefer restaurants with an approximate cost of 300 rupees.

5. **Which mode (online/offline) receives the highest ratings?**
   - A box plot comparison between online and offline orders shows that online orders tend to have higher ratings than offline orders.

6. **Which types of restaurants receive more offline orders?**
   - A heatmap is used to analyze the distribution of offline and online orders across restaurant types. Dining restaurants receive the most offline orders.

## Technologies Used

- **Python**: Main programming language used for data manipulation and analysis.
- **Pandas**: Used for data manipulation and cleaning.
- **Matplotlib**: Used for creating static visualizations.
- **Seaborn**: Used for advanced visualizations.

## Setup and Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/CodeNobility/zomato-data-analysis.git
   ```
2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```

## Running the Project

1. Load the dataset and run the Jupyter notebook or Python script.
2. Make sure you have the dataset file (`Zomato data .csv`) in the same directory as the script.
3. Execute the cells or script to view the analysis and visualizations.

## Visualizations

1. **Count Plots**: For analyzing types of restaurants and spending patterns.
2. **Bar Plots**: For visualizing the votes received by each type of restaurant.
3. **Histograms**: For understanding the rating distribution across restaurants.
4. **Box Plots**: For comparing ratings based on online/offline orders.
5. **Heatmaps**: For analyzing order distribution (online vs offline) for different restaurant types.

## Conclusion

- Dining restaurants dominate both in terms of customer orders and votes.
- Most restaurants receive ratings between 3.6 and 4.1.
- Couples tend to choose restaurants with an approximate cost of 300 rupees for two people.
- Online orders generally receive better ratings compared to offline orders.
- Dining restaurants also receive the highest number of offline orders.

## Future Work

- Expanding the analysis by considering other factors such as location and cuisine types.
- Implementing machine learning techniques to predict customer preferences.
