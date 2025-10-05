🥗 Healthy Eating Behavior Analysis
Overview
This project analyzes healthy eating patterns using a dataset of 2,000 meal records.
It focuses on nutrition composition, diet types, cooking methods, and health ratings to understand what factors contribute to healthier meals.
The goal is to identify trends in eating habits and provide actionable recommendations for healthier meal planning.

Dataset
File: healthy_eating_dataset.csv
Records: 2,000
Columns include:

Meal ID, Meal Name, Cuisine, Meal Type

Diet Type (Keto, Vegan, Paleo, etc.)

Calories, Protein, Carbs, Fat, Fiber, Sugar

Sodium, Cholesterol, Serving Size

Cooking Method, Preparation & Cooking Time

Rating, Health Label (Is_Healthy)

Analysis Performed
Data Cleaning – handled missing values, removed duplicates, and checked for outliers in calorie and nutrient levels.

Descriptive Statistics – computed mean, median, and distribution for nutrients and meal ratings.

Visualizations –

Histograms for calorie and protein distributions

Pie charts for diet types and cooking methods

Bar charts comparing cuisines and average ratings

Boxplots for calorie variations by meal type

Relationship Analysis –

Calories vs Rating

Diet Type vs Healthiness

Cuisine vs Average Fat and Sugar

Cooking Method vs Nutrition Density

Key Findings
Most meals have calories between 300–700 kcal, indicating balanced nutrition.

Vegan and Paleo diets show higher average health ratings.

Grilled and Boiled dishes tend to be healthier than Fried ones.

Indian and Mediterranean cuisines feature more nutrient-rich meals.

Average preparation time is ~45 minutes, with a cook time of ~50 minutes.

Recommendations
Promote low-sodium and high-fiber meal options.

Encourage grilling and boiling methods over frying to improve health scores.

Develop personalized meal plans based on calorie needs and diet preferences.

Highlight quick-to-prepare healthy meals for busy users.

Review outliers with extremely high calorie (>1000 kcal) or fat (>60g) content.

Tools Used
Python (Pandas, NumPy, Matplotlib, Seaborn)

Jupyter Notebook

Data Cleaning and Visualization Techniques
