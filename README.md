# Data Visualization: Analysis of Global Superstore Dataset

This project focuses on creating interactive data visualizations for the Global Superstore Dataset. The goal is to provide actionable insights for business decision-making by analyzing global sales, profitability, customer segmentation, and geographical performance. Visualizations were created using Tableau and Flourish to present insights related to sales trends, profitability, and customer behavior.

## Project Overview

- **Objective**: To analyze global sales, profitability, and customer behavior in the Global Superstore dataset through interactive data visualizations, highlighting key trends for business optimization.
- **Key Focus**:
  - Analyzing country-wise profitability and sales performance across different product categories.
  - Exploring sales trends over time (2011-2014) and identifying the top-performing countries.
  - Investigating profitability across U.S. states and product categories.
  - Identifying and rewarding top customers based on profit contributions and order frequency.
- **Tech Stack**: Tableau, Flourish, Python (Pandas)

## Dataset

The **Global Superstore Dataset** includes global sales data across multiple countries, covering the years 2011 to 2014. The dataset contains information related to sales, profit, product categories, and customer orders.

### Dataset Features:
- `Order Date`: The date on which the order was placed.
- `Region`: The region where the sale was made.
- `Country`: The country where the sale was made.
- `Sales`: The total sales value for each order.
- `Profit`: The profit generated by the sale.
- `Category` and `Sub-Category`: Product categories such as Furniture, Technology, and Office Supplies.
- `Customer Segment`: Consumer, Corporate, and Home Office.

### File Structure:
- **`Global Superstore.xls`**: The Excel file containing the Global Superstore data.
- **`Data Visualisation.twbx`**: Tableau workbook file containing the interactive visualizations.
- **`Code.ipynb`**: Jupyter notebook containing the code for initial data exploration and preprocessing.
- **`Report.pdf`**: Detailed report discussing the insights gained from the visualizations.
- **`requirements.txt`**: Python dependencies required to run the analysis.

## Analysis Workflow

### 1. Data Preprocessing
- **Data Cleaning**: Missing values were handled, and categorical data was cleaned to prepare for analysis.
- **Data Exploration**: Initial exploration of sales, profits, and customer segmentation across various regions and product categories.

### 2. Visualizations

- **Visualization 1**: **Global Sales and Profitability Performance** — A global map visualizing the profitability of countries, with an analysis of sales, costs, and profits across product categories. It highlights key markets like the U.S. and China.
  - **Insight**: The U.S. stands out as the most profitable market, while China has significant sales volume but lower profit margins.
  
- **Visualization 2**: **Comparative Sales Performance by Country (2011-2014)** — A line chart comparing the sales trends across different countries. The U.S. is the top performer with a steady sales increase, while countries like Tunisia and Paraguay show potential for expansion.
  - **Insight**: The U.S. is consistently the highest sales performer, and underperforming markets present opportunities for strategic expansion.

- **Visualization 3**: **Sales and Profitability by U.S. State** — A heatmap showing the profitability of different U.S. states and an analysis of product categories contributing to sales performance.
  - **Insight**: Minnesota stands out with a high profit ratio, while Ohio shows negative profitability, indicating potential operational inefficiencies.

- **Visualization 4**: **Top U.S. Cities' Financial Performance and Customer Segmentation** — A city-level analysis of sales, costs, and profitability, focusing on how different customer segments contribute to overall revenue.
  - **Insight**: New York City is the top profit generator, with the consumer segment being the primary driver of revenue.

- **Visualization 5**: **Top 20 Customers by Profit Contribution** — A bubble chart identifying the most profitable customers based on profit contribution and order frequency.
  - **Insight**: High-value customers with frequent orders are key contributors to profitability, and targeted loyalty programs can help retain and grow this customer base.

## Key Insights

1. **U.S. as the Most Profitable Market**: The U.S. has strong sales and profitability, suggesting that the Global Superstore should continue focusing on expanding operations there.
2. **Underperforming Markets**: Countries like Argentina show negative profitability, signaling a need for either exit strategies or a re-evaluation of market approaches.
3. **Technology as a High-Profit Category**: The technology category consistently shows strong profit margins across multiple regions, particularly in the U.S.
4. **Customer Segmentation**: Consumer segments play a significant role in driving sales, particularly in large cities like New York. A focus on customer engagement and loyalty could enhance profitability.

## Usage

The Tableau workbook and Flourish visualizations can be used interactively to explore the data and gain insights into the business performance of Global Superstore.

1. **Global Profitability and Sales Performance**: Explore sales and profitability across regions and product categories.
2. **U.S. Market Insights**: Drill down into U.S. state performance to understand where to focus resources.
3. **Customer Analysis**: Identify key customers and segments to target for revenue growth.

## Installation

To run the Jupyter notebook locally for data exploration:

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/Global-Superstore-Data-Visualization.git
    cd Global-Superstore-Data-Visualization
    ```

2. Install the required Python packages:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the Jupyter notebook:
    ```bash
    jupyter notebook
    ```

## Acknowledgements

This project was developed as part of the MSc in Business Analytics at Bayes Business School, under the module **Data Visualization**.

## License

MIT License
