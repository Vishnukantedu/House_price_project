# 🏡 King County House Price Analysis

This project explores real estate data from King County, Washington (USA), using Python and visualization tools to understand what factors influence housing prices.

> 📊 Dataset Source: [Kaggle – House Sales in King County, USA](https://www.kaggle.com/datasets/harlfoxem/housesalesprediction)

---

## 📌 Project Objectives

- Understand the distribution of house prices
- Identify key features that influence pricing
- Explore geographic and temporal patterns
- Clean and prepare data for analysis
- Apply basic feature engineering for deeper insight

---

## 🛠️ Tools & Technologies

- **Python** (Pandas, NumPy)
- **Seaborn** & **Matplotlib** for plotting
- **Jupyter Notebook** for analysis
- **Kaggle dataset** for real-world data

---

## 🧹 Data Cleaning Steps

- Converted `date` column to datetime format
- Removed duplicate rows
- Verified no missing values
- Filtered out extreme outliers in `bedrooms` and `sqft_living`

---

## 📊 Exploratory Data Analysis (EDA)

### 🏠 Price Distribution
Most homes are priced under $1 million, but a few luxury homes reach up to $7.7M.

### 🛏 Bedrooms vs Price
Price increases with bedroom count up to a point, but plateaus after 5 bedrooms.

### 📐 Living Area vs Price
Strong positive correlation — larger homes generally cost more.

### 🏷 Grade vs Price
Homes with higher construction and design grades tend to be more expensive.

### 📍 Geographic Insights
Higher prices cluster in specific zip codes (e.g., Seattle, waterfront areas).

### ⏳ Price Trends Over Time
Slight increase in average prices observed from 2014 to 2015.

### 🧪 Correlation Analysis
Top features influencing price:
- `sqft_living`
- `grade`
- `bathrooms`
- `price_per_sqft` (engineered feature)

---

## 🧠 Feature Engineering

| Feature | Description |
|--------|-------------|
| `price_per_sqft` | Helps normalize pricing across homes of different sizes |
| `house_age` | Provides insights into how the age of a property affects price |

---

## 📈 Key Visualizations

- Distribution plot of house prices
- Boxplots: Bedrooms vs Price, Grade vs Price
- Scatterplots: Sqft vs Price, Latitude/Longitude vs Price
- Bar plot: Price trends by year
- Correlation heatmap for top predictors

---

## 🔍 Insights Summary

- 💡 Larger, newer, and better-graded homes command higher prices.
- 🏙 Central and coastal locations are significantly more expensive.
- 🔍 Engineered features like price per square foot provide deeper insights.
- 🕒 A slight upward trend in prices occurred from 2014 to 2015.

---

## 📂 File Structure

