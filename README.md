# 🚗 Car Price Prediction

## About the Project

Why are some cars much more expensive than others? Is it because of their brand, engine performance, luxury features, or a combination of different factors?

That's what I want to explore in this project.

I'll analyze car data to understand how different characteristics, such as horsepower, engine size, manufacturing year, brand, and luxury classification, relate to car prices. After exploring the data, I'll also try to build a Multiple Linear Regression model to predict car prices based on these characteristics.

My goal is not just to predict prices, but also to understand what makes certain cars more expensive than others and discover interesting patterns in the data.

Since this is an introductory data analysis project, I'll focus on learning by doing, from cleaning the data and creating visualizations to building and evaluating a prediction model.

## 🎯 What I Want to Find Out

* Do cars with higher horsepower tend to be more expensive?
* Are luxury and performance cars more expensive than standard cars?
* How much does a car's brand relate to its price?
* How does a car's manufacturing year affect its price?
* Which characteristics have the strongest relationship with car prices?
* Can I use these characteristics to predict a car's price?

These are the main questions I want to explore, and I'll use the data to find the answers rather than making assumptions beforehand.

## 📊 Dataset Options

I found three datasets that could work for this project. Each has different features, so I'll choose the one that best fits my research questions.

### 1. Car Features and MSRP

🔗 [View dataset on Kaggle](https://www.kaggle.com/CooperUnion/cardataset)

This dataset contains information about different car models, including their manufacturer, year, horsepower, engine specifications, fuel efficiency, vehicle type, and market category.

It also includes categories such as luxury and performance, making it a good option for exploring how these characteristics relate to car prices.

**Best for:** Analyzing luxury cars, performance, brands, and MSRP.

### 2. CarDekho Car Price Prediction

🔗 [View dataset on Kaggle](https://www.kaggle.com/competitions/task-02-car-price-prediction/data)

This dataset contains information about more than 5,000 cars, including manufacturing year, kilometers driven, fuel type, transmission, engine size, maximum power, torque, and selling price.

I find this dataset interesting because it includes engine performance information and focuses on used-car prices.

**Best for:** Exploring how engine specifications, mileage, and other characteristics relate to used-car prices.

*Note: This Kaggle competition may require an invitation to access its data.*

### 3. Used Car Price Prediction Challenge

🔗 [View dataset on Kaggle](https://www.kaggle.com/competitions/used-car-price-prediction-challenge/data)

This dataset contains real-world used-car listings with information such as brand, model, manufacturing year, mileage, fuel type, transmission, vehicle condition, and price.

It could be useful for studying the used-car market and understanding how different vehicle characteristics relate to listing prices.

**Best for:** Analyzing real-world used-car listings and predicting their prices.

### My Plan for the Dataset

I'll explore these options and choose one based on the available features and how suitable the data is for my research questions.

I won't necessarily use every feature mentioned in this README. The final analysis will depend on what is actually available in the selected dataset.

## 🛠️ Tools I'll Use

* **Python** — for working with the data.
* **Pandas** — for cleaning and analyzing the dataset.
* **NumPy** — for numerical operations.
* **Matplotlib** — for creating charts.
* **Seaborn** — for visualizing relationships between variables.
* **Scikit-learn** — for building and evaluating the prediction model.
* **Jupyter Notebook** — for writing and running the analysis.

## 📈 My Plan

1. **Find the dataset:** Choose a suitable dataset for the project.
2. **Clean the data:** Check for missing values, duplicates, and inconsistent information.
3. **Explore the data:** Understand the dataset using summary statistics and visualizations.
4. **Analyze the features:** Investigate how horsepower, brand, vehicle age, and other available characteristics relate to price.
5. **Build the model:** Use Multiple Linear Regression to predict car prices.
6. **Evaluate the model:** Compare predicted prices with actual prices using metrics such as MAE, RMSE, and R².
7. **Share the findings:** Summarize what I learned and discuss the limitations of the analysis.

## 💡 What I Hope to Learn

Through this project, I want to improve my Python and data analysis skills while gaining some hands-on experience with machine learning.

I'm particularly interested in understanding the relationship between engine performance, luxury classification, and car prices. I also want to learn how to interpret the results instead of just building a model and looking at its accuracy.

I know that car prices can depend on many factors, and a prediction model won't always be accurate. That's part of what I want to learn from this project.

## 📂 Project Structure

```text
car-price-prediction/
│
├── data/
├── notebooks/
│   └── car_price_analysis.ipynb
├── images/
├── requirements.txt
└── README.md
```

I'll update the structure as the project develops. The dataset itself may be kept outside the repository if it is large or subject to redistribution restrictions.

## 🚀 Project Status

**Currently:** Planning and selecting a dataset.

   Choose the project topic
   Define the research questions
   Select a dataset
   Clean and explore the data
   Create visualizations
   Build the prediction model
   Evaluate the results
   Document the findings

---

This is one of my early projects as a Data Science and AI student. I'm using it as an opportunity to practice what I've learned and explore a real-world problem that I'm genuinely interested in.
