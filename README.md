
```markdown
# 📊 E-Commerce Sales Performance & Customer Behavior EDA

## 📝 Project Overview
This project performs a comprehensive **Exploratory Data Analysis (EDA)** on an E-Commerce sales dataset. Since the dataset primarily focuses on revenue and customer metrics without profit/loss margins, the analysis is deeply geared towards understanding revenue drivers, seasonal trends, customer segmentation, geographic performance, and purchasing behaviors.

The goal is to provide actionable insights for marketing, logistics, and inventory management teams to optimize supply chains and target high-value customer groups effectively.

## 🗂️ Dataset Features
The analysis is conducted using a standard Superstore/E-Commerce dataset containing the following features:
* **Order Details:** `Order ID`, `Order Date`, `Ship Date`, `Ship Mode`
* **Customer Info:** `Customer ID`, `Customer Name`, `Segment`
* **Geography:** `Country`, `City`, `State`, `Region`, `Postal Code`
* **Product Details:** `Product ID`, `Category`, `Sub-Category`, `Product Name`
* **Core Metric:** `Sales`

## 🛠️ Tech Stack & Libraries Used
* **Language:** Python 3.x
* **Data Manipulation:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn
* **Environment:** Jupyter Notebook (`.ipynb`)

## 🔍 Key Analysis & Visualizations Included
The Jupyter Notebook is structured sequentially into the following analytical sections:

1. **Data Preprocessing & Feature Engineering:** Handling data types, checking for missing values, and extracting temporal features (`Year`, `Month`, `Day of Week`) from raw dates.
2. **Top Revenue Generators:** Identifying the Top 10 best-selling products.
3. **Time-Series Sales Trends:** Analyzing monthly sales to identify seasonal patterns and peak shopping months.
4. **Product Hierarchy Analysis:** Breaking down sales distribution by major `Category` and deep-diving into the Top 10 `Sub-Categories`.
5. **Geographical Performance:** Visualizing sales across different global `Regions` and pinpointing the Top 10 revenue-generating `States`.
6. **Logistics & Consumer Behavior:** Understanding customer `Segment` distribution (Consumer, Corporate, Home Office) and mapping their preferred `Ship Mode`.
7. **Advanced Behavioral Insights:** Isolating the Top 5 most valuable customers by cumulative expenditure and analyzing sales trends based on the `Day of the Week`.

## 💡 Key Business Insights Discovered
* **Seasonality:** Revenue spikes significantly during the Q4 holiday season (November and December), suggesting a need for increased inventory during these months.
* **Core Drivers:** Certain sub-categories (e.g., Technology items like Phones or Chairs in Furniture) dominate the overall sales share.
* **Geographic Focus:** A major portion of the sales is concentrated in specific high-performing states, highlighting ideal locations for targeted marketing campaigns.
* **Shipping Preference:** The majority of consumers prefer standard shipping, allowing logistics to plan baseline capacities accordingly, while express options remain niche.

## 🚀 How to Run the Project Locally

1. **Clone this repository:**
   ```bash
   git clone https://github.com/abrar-swapnil/ecommerce-sales-eda.git
2. Navigate the project directory:
   cd ecommerce-sales-eda
3. Install the required dependencies:
  pip install pandas numpy matplotlib seaborn
4. Launch jupyter notebook:
   jupyter notebook

🛠️ Author: Abrar Swapnil
📬 Feel free to connect with me for data analysis and visualization collaborations!
