# Business Analytics Project

This repository contains a synthetic business dataset, an analysis notebook, and all necessary files to perform exploratory data analysis and build predictive models. The goal of this project is to showcase your skills as a business analyst, program manager, or data analyst.

## Project Structure

| File/Folders | Description |
| --- | --- |
| `synthetic_business_data.csv` | A synthetic dataset containing 1,000 rows of fictional sales and marketing data including region, product category, marketing spend, price, quantity sold, revenue, cost, profit, and customer satisfaction. |
| `analysis.ipynb` | Jupyter notebook for exploratory data analysis (EDA) and predictive modeling. It includes visualizations, summary statistics, and a sample regression model to predict profit based on various features. |
| `requirements.txt` | Python dependencies required to run the notebook. Install them via `pip install -r requirements.txt`. |

## Dataset Overview

The dataset is synthetic but mimics real-world business data. Each row represents monthly performance metrics for a specific region and product category.

**Columns include:**

- **Region**: The geographical region (North, South, East, West).
- **Product_Category**: Type of product (Technology, Furniture, Office Supplies).
- **Month**: Month number (1-12).
- **Marketing_Spend**: Amount spent on marketing (USD).
- **Price**: Unit price of the product (USD).
- **Quantity_Sold**: Number of units sold.
- **Revenue**: Total revenue (Price * Quantity_Sold).
- **Cost**: Cost associated with goods sold.
- **Profit**: Profit after subtracting cost and marketing spend.
- **Customer_Satisfaction**: Rating (1-10) indicating customer satisfaction.

## Instructions

1. Clone the repository or download the files.
2. Install the required dependencies using:

```bash
pip install -r requirements.txt
```

3. Launch Jupyter Notebook:

```bash
jupyter notebook analysis.ipynb
```

4. Follow the notebook to explore the data, create visualizations, and build predictive models.

## Potential Extensions

- **Feature Engineering**: Create additional features such as year-over-year growth or marketing ROI.
- **Classification Models**: Predict categories like high/low profit segments.
- **Dashboard**: Build an interactive dashboard using Plotly Dash or Streamlit.

Feel free to fork the repository and experiment with different modeling techniques or visualization tools.

## License

This project is released under the MIT License.
