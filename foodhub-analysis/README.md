# 🍔 FoodHub Data Analysis Project

## 📋 Project Overview

This project analyzes order data from **FoodHub**, a food aggregator company operating in New York City. FoodHub provides access to multiple restaurants through a single smartphone app, connecting customers with their favorite restaurants and managing the entire delivery process.

## 🎯 Problem Statement

The number of restaurants in New York is increasing rapidly, and busy students and professionals rely heavily on online food delivery services. FoodHub has collected data on various orders placed by registered customers and wants to analyze this data to:

- Understand the demand for different restaurants
- Enhance customer experience
- Improve business operations
- Identify opportunities for growth

## 📊 Dataset Description

The dataset contains **1,898 orders** with the following features:

| Column                  | Description                                                                |
| ----------------------- | -------------------------------------------------------------------------- |
| `order_id`              | Unique ID of the order                                                     |
| `customer_id`           | ID of the customer who ordered the food                                    |
| `restaurant_name`       | Name of the restaurant                                                     |
| `cuisine_type`          | Cuisine ordered by the customer                                            |
| `cost_of_the_order`     | Cost of the order (in dollars)                                             |
| `day_of_the_week`       | Whether the order was placed on a weekday or weekend                       |
| `rating`                | Rating given by the customer (out of 5)                                    |
| `food_preparation_time` | Time taken by the restaurant to prepare food (in minutes)                  |
| `delivery_time`         | Time taken by the delivery person to deliver the food package (in minutes) |

## 🛠️ Technologies Used

- **Python 3.x**
- **Google Colab** - Cloud-based interactive development environment
- **pandas** - Data manipulation and analysis
- **numpy** - Numerical computations
- **matplotlib** - Data visualization
- **seaborn** - Statistical data visualization

## 📁 Project Structure

```
foodhub/
├── README.md                          # Project documentation
├── data/
│   └── foodhub_orders.csv            # Raw order data
├── notebooks/
│   └── foodhub_analysis.ipynb        # Analysis notebook
└── outputs/
    └── foodhub_analysis_output.html  # HTML export of analysis
```

## 🚀 How to Run the Analysis

### Option 1: Using Google Colab (Recommended)

1. **Upload the notebook to Google Colab**
   - Go to [Google Colab](https://colab.research.google.com/)
   - Click on `File` → `Upload notebook`
   - Upload `notebooks/foodhub_analysis.ipynb`

2. **Upload the data file**
   - Upload `data/foodhub_orders.csv` to your Google Drive
   - Update the file path in the notebook to match your Google Drive location
   - The notebook will mount your Google Drive automatically

3. **Run the analysis**
   - Execute all cells in sequence (`Runtime` → `Run all`)
   - All required libraries (pandas, numpy, matplotlib, seaborn) are pre-installed in Colab

### Option 2: Using Local Jupyter Notebook

1. **Install required libraries**

   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```

2. **Launch Jupyter Notebook**

   ```bash
   jupyter notebook
   ```

3. **Update data path**
   - Open `notebooks/foodhub_analysis.ipynb`
   - Comment out the Google Drive mount code
   - Update the CSV file path to your local path: `../data/foodhub_orders.csv`
   - Run all cells to reproduce the analysis

## ❓ Analysis Questions Addressed

The analysis answers 17 key business questions, including:

1. Dataset structure and composition
2. Data quality and missing value treatment
3. Statistical summary of order metrics
4. Restaurant and cuisine popularity analysis
5. Customer behavior patterns
6. Rating distribution analysis
7. Cost and revenue analysis
8. Preparation and delivery time analysis
9. Weekend vs. weekday performance comparison
10. Business recommendations based on insights

## 📝 Conclusion

This analysis provides actionable insights into FoodHub's operations, revealing opportunities to improve customer retention, optimize delivery operations, and leverage popular restaurants and cuisines. By implementing the recommended strategies, FoodHub can enhance customer experience and drive business growth.

---

⭐ If you found this project useful, consider giving it a star!
