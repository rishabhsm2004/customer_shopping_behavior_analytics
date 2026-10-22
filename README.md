# customer_shopping_behavior_analytics
Customer Shopping Behavior Analytics explores customer shopping patterns to uncover insights about purchasing behavior, product preferences, and sales trends. The analysis can help businesses better understand their customers and make informed decisions.

This project analyzes customer shopping data to identify patterns in spending, product preferences, discounts, shipping, and subscriptions. It includes a data preparation notebook, SQL analysis, and a Power BI dashboard.

## Project files

| File | Description |
|---|---|
| `Dataset.csv` | Customer shopping data used in the analysis |
| `Data_Prep_and_Modelling.ipynb` | Notebook for preparing and modeling the data |
| `Script.sql` | SQL queries used to answer business questions |
| `Dashboard.pbix` | Power BI dashboard file |
| `Dashboard.png` | Preview of the dashboard |
| `Business Problem Document.pdf` | Description of the business problem |
| `Project.pdf` | Project report |

## Questions explored

The analysis looks at:

- How revenue differs by customer gender and age group
- Which products have the highest average ratings
- Whether spending differs by shipping type
- How discounts are used across products
- How purchasing and subscription behavior relate
- Which products are most popular in each category
- How customers can be grouped by their previous purchases

## How to use this project

1. Download or clone this repository.
2. Open `Data_Prep_and_Modelling.ipynb` in Jupyter Notebook or JupyterLab to review the data preparation.
3. Load `Dataset.csv` into a SQL database as a table named `customer`.
4. Run the queries in `Script.sql`. They use common SQL features, including common table expressions and window functions.
5. Open `Dashboard.pbix` in Power BI Desktop to view the dashboard.

## Dataset

The dataset contains customer demographics, purchased items, product categories, purchase amounts, locations, ratings, shipping details, discount and promotion usage, subscription status, previous purchases, payment methods, and purchase frequency.

## Tools

- Python and Jupyter Notebook
- MySQL
- Microsoft Power BI
