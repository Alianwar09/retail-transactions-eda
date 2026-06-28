# Retail Transactions EDA

Exploratory Data Analysis mini-project on a retail transactions dataset using Python, Pandas, Matplotlib, and Seaborn.

This project analyzes customer behavior, payment preferences, store performance, seasonal revenue trends, promotions, discounts, and product-level patterns from retail transaction data.

## Project Contents

- `retail_transactions_eda.ipynb` - main Jupyter Notebook with the full EDA workflow
- `requirements.txt` - Python libraries needed to run the notebook
- `IITG_DSBA_Week 17_Graded Mini Project.pdf` - assignment reference
- `Task to be performed-Week 17.docx` - task document
- `Week 17 Graded Mini Project (Kanak_Baghel).pdf` - submitted project report

## Dataset

The dataset is not included in this repository.

Download it from Kaggle:

[Retail Transactions Dataset](https://www.kaggle.com/datasets/kanakbaghel/retail-transactions-dateset/data)

After downloading, place the CSV file in the project folder with this exact name:

```text
Retail_Transactions_Dataset.csv
```

The notebook expects the file to be available in the same folder as `retail_transactions_eda.ipynb`.

## Analysis Covered

- Data loading and preparation
- Date parsing and feature extraction
- Transaction and customer exploration
- Top-selling product analysis
- City-wise transaction analysis
- Customer category spending behavior
- Payment method preferences
- Store type analysis
- Promotion and discount impact
- Seasonal revenue trends
- Visual dashboard charts

## Tools Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

## How to Run

1. Clone this repository.

```bash
git clone <your-repository-url>
cd retail-transactions-eda
```

2. Install the required libraries.

```bash
pip install -r requirements.txt
```

3. Download the dataset from Kaggle and place `Retail_Transactions_Dataset.csv` in the project folder.

4. Open the notebook.

```bash
jupyter notebook retail_transactions_eda.ipynb
```

5. Run the cells from top to bottom.

## Output

The notebook generates exploratory summaries and visualizations, including:

- Transactions per city
- Payment method distribution
- Monthly revenue trends
- Average spending per season
- Revenue by season and customer category

## Project Type

This is an academic EDA mini-project, not a production application.
