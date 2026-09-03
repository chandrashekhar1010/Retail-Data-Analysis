# 🛒 Retail Data Analysis

A data analysis project focused on exploring retail order data using **Python, Pandas, Matplotlib, and Seaborn**.

The project performs data cleaning, preprocessing, feature engineering, and exploratory data analysis (EDA) on online retail order information.

## 📌 Project Overview

This project analyzes retail order data to understand patterns across:

* Product categories
* Regions
* Customer demographics
* Order dates
* Age groups
* Gender distribution

The dataset contains **4,310 records and 10 original columns**, including order information, customer details, location, product category, and product name.

## 🗂️ Dataset Features

The original dataset contains the following columns:

| Column             | Description             |
| ------------------ | ----------------------- |
| `order_id`         | Unique order identifier |
| `order_date`       | Date of the order       |
| `customer_id`      | Customer identifier     |
| `customer_name`    | Customer name           |
| `age`              | Customer age            |
| `gender`           | Customer gender         |
| `region`           | Customer region         |
| `city`             | Customer city           |
| `product_category` | Product category        |
| `product_name`     | Product name            |

## 🧹 Data Cleaning

The following preprocessing steps were performed:

1. Removed rows with missing `order_id` or `customer_id`.
2. Filled missing age values using the median age.
3. Converted `order_date` into a proper datetime format.
4. Converted age into integer format.
5. Standardized gender values.
6. Created an `Other` category for unmapped gender values.

## ⚙️ Feature Engineering

Additional features were created from the existing data:

* `order_year`
* `order_month`
* `order_day_name`
* `age_group`

Age groups were categorized as:

* `<18`
* `18-25`
* `26-35`
* `36-45`
* `46-60`
* `60+`

## 📊 Exploratory Data Analysis

The project includes visual analysis of:

### Orders by Product Category

![Orders by Category](images/orders_by_category.png)

### Orders by Region

![Orders by Region](images/orders_by_region.png)

## 🛠️ Technologies Used

* Python
* Pandas
* Matplotlib
* Seaborn
* Jupyter Notebook

## 📁 Project Structure

```text
Retail-Data-Analysis/
│
├── Retail_Data_Analysis.ipynb
├── online_retail.csv
├── README.md
├── requirements.txt
├── .gitignore
│
└── images/
    ├── orders_by_category.png
    └── orders_by_region.png
```

## 🚀 How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/Retail-Data-Analysis.git
```

### 2. Navigate to the project directory

```bash
cd Retail-Data-Analysis
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```text
Retail_Data_Analysis.ipynb
```

Make sure `online_retail.csv` is present in the same project directory.

## 📈 Key Skills Demonstrated

* Data cleaning
* Missing value handling
* Data type conversion
* Date/time feature extraction
* Feature engineering
* Categorical data preprocessing
* Exploratory Data Analysis
* Data visualization
* Python programming
* Pandas data manipulation

## 👨‍💻 Author

**Chandrashekhar Prakash Rana**

This project was created as a practical data analytics project using Python and exploratory data analysis techniques.
