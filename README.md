# 🛒 Retail Transactions EDA

Exploratory Data Analysis (EDA) of a retail transactions dataset using Python, Pandas, Matplotlib, and Seaborn — submitted as a graded mini-project for **IITG DSBA Week 17**.

This project uncovers patterns in customer behavior, payment preferences, store performance, seasonal revenue trends, promotions, discounts, and product-level insights from real-world retail transaction data.

---

## 📁 Project Structure

```
retail-transactions-eda/
│
├── retail_transactions_eda.ipynb        # Main Jupyter Notebook (full EDA workflow)
├── requirements.txt                     # Python dependencies
├── IITG_DSBA_Week 17_Graded Mini Project.pdf   # Assignment reference
├── Task to be performed-Week 17.docx    # Task description
└── README.md                            # Project documentation
```

---

## 📊 Dataset

The dataset is **not included** in this repository due to size.

👉 Download it from Kaggle: [Retail Transactions Dataset](https://www.kaggle.com/datasets/kanakbaghel/retail-transactions-dateset/data)

After downloading, place the CSV file in the root project folder with this exact name:

```
Retail_Transactions_Dataset.csv
```

The notebook expects this file in the same directory as `retail_transactions_eda.ipynb`.

---

## 🔍 Analysis Covered

| Area | Description |
|------|-------------|
| **Data Preparation** | Loading, cleaning, date parsing, feature extraction |
| **Customer Exploration** | Transaction counts, unique customers, spending behavior |
| **Product Analysis** | Top-selling products by revenue and quantity |
| **City-wise Analysis** | Transaction volume and revenue across cities |
| **Payment Methods** | Distribution and preference across customer segments |
| **Store Type Analysis** | Performance comparison across store types |
| **Promotions & Discounts** | Impact of promotions on revenue and transaction volume |
| **Seasonal Trends** | Monthly and seasonal revenue patterns |
| **Visual Dashboard** | Summary charts combining key insights |

---

## 💡 Key Findings

- Seasonal peaks are clearly visible in revenue trends, with certain months consistently outperforming others
- Promotional transactions show a measurable uplift in average order value
- Payment method preferences vary significantly across customer categories
- A small subset of products drives a disproportionately large share of total revenue

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| Python 3.x | Core programming language |
| Jupyter Notebook | Interactive analysis environment |
| Pandas | Data manipulation and aggregation |
| NumPy | Numerical computations |
| Matplotlib | Base plotting library |
| Seaborn | Statistical data visualization |

---

## ▶️ How to Run

**1. Clone the repository**
```bash
git clone https://github.com/Alianwar09/retail-transactions-eda.git
cd retail-transactions-eda
```

**2. Install dependencies**
```bash
pip install -r requirements.txt
```

**3. Download the dataset**

Download `Retail_Transactions_Dataset.csv` from [Kaggle](https://www.kaggle.com/datasets/kanakbaghel/retail-transactions-dateset/data) and place it in the project root folder.

**4. Launch the notebook**
```bash
jupyter notebook retail_transactions_eda.ipynb
```

**5. Run all cells** from top to bottom (Kernel → Restart & Run All).

---

## 📈 Sample Outputs

The notebook generates the following visualizations:

- 📍 Transactions per city (bar chart)
- 💳 Payment method distribution (pie/bar chart)
- 📅 Monthly revenue trends (line chart)
- 🌦️ Average spending per season (grouped bar)
- 🏷️ Revenue impact of promotions and discounts
- 👥 Revenue by customer category and season

---

## 📋 Requirements

```
pandas
numpy
matplotlib
seaborn
jupyter
```

Install all at once:
```bash
pip install -r requirements.txt
```

---

## 👤 Author

**Ali Anwar**
BCA Student — School of Management Sciences, Lucknow
IITG DSBA Program | Roll No: 2310924050009

---

## 📄 License

This project is open for academic reference. Feel free to fork and build upon it.
