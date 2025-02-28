# 📦 Amazon Business Analyst Project: Delivery Time Analysis & Delay Prediction

## 📌 Overview

This project aims to analyze and predict delivery times for Amazon's logistics network using the Amazon Business Research Analyst Dataset. The goal is to identify key factors affecting delivery delays and build a predictive model to estimate delivery times more accurately.

By using Python, SQL, and Tableau, this project focuses on data-driven decision-making and process optimization.

## 🎯 Objectives

- Analyze the impact of factors such as traffic, weather, and vehicle type on delivery times.

- Predict expected delivery times based on historical data.

- Visualize delivery trends to help optimize logistics operations.

- Provide business insights for reducing delivery inefficiencies.

## 🗂 Dataset

The dataset contains order details, delivery personnel information, location coordinates, timestamps, weather conditions, and traffic density.

### Key Columns

```bash
- Order_Date
- Time_Orderd
- Time_Order_picked
- Restaurant_latitude
- Restaurant_longitude
- Delivery_location_latitude
- Delivery_location_longitude
- Weather
- Road_traffic_density
- Delivery_person_Age
- Delivery_person_Ratings
- Type_of_vehicle
- multiple_deliveries
```

## 🛠 Tech Stack

- Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)
- SQL (for querying and data manipulation)
- Power BI / Tableau (for visualization)
- Jupyter Notebook (for analysis and modeling)

## 📊 Exploratory Data Analysis (EDA)

- Handle missing values and correct data types.
- Calculate Order Processing Time and Delivery Duration.
- Identify patterns in delivery delays across different factors (weather, traffic, vehicle type, etc.).

## 🔮 Predictive Modeling

- Feature Engineering: Extract meaningful insights from timestamps and geospatial data.
- Model Selection: Compare Linear Regression, Decision Trees, and XGBoost.
- Evaluate performance using RMSE and R-squared metrics.

## 📈 Insights & Recommendations

- Traffic Impact: Orders in 'Jam' conditions take X% longer than normal.
- Weather Impact: 'Stormy' and 'Foggy' conditions cause an average delay of Y minutes.
- Vehicle Type: Motorcycles deliver faster than electric scooters.
- Business Suggestion: Adjust delivery time estimates dynamically based on traffic and weather predictions.

## 🚀 How to Use This Project

```bash
# Clone the repo:

git clone https://github.com/yourusername/amazon-business-analyst-project.git

# Install dependencies:
pip install -r requirements.txt

# Run the Jupyter notebook:
jupyter notebook
```

## 📌 Future Improvements

- Enhance the predictive model using deep learning techniques.
- Optimize delivery routes using geospatial clustering.
- Develop a real-time dashboard with interactive insights.

## 👨‍💻 Author

Cassie GU

## 📜 License

This project is licensed under the MIT License.
