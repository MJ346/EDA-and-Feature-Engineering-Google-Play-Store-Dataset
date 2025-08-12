# EDA-and-Feature-Engineering-Google-Play-Store-Dataset
# 📊 EDA and Feature Engineering – Google Play Store Dataset

## 📌 Project Overview
This project analyzes a dataset of 10,841 apps from the Google Play Store, containing 20 features such as Category, Rating, Installs, Size, and Last Updated. The objective is to identify the most popular app categories, top-installed apps, and trends in app size, ratings, and update history.

## 🛠 Tools & Libraries
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Jupyter Notebook

## 🔍 Key Steps
1. **Data Cleaning**  
   - Removed duplicates and irrelevant entries  
   - Converted `Installs` and `Size` columns to numeric formats  
   - Handled missing values and outliers  

2. **Feature Engineering**  
   - Extracted year, month, and day from `Last Updated`  
   - Created `Size_MB` and `Days_Since_Update` columns  

3. **Exploratory Data Analysis (EDA)**  
   - Identified most popular categories and top apps by installs  
   - Analyzed rating distributions and size vs. installs relationship  
   - Compared app categories based on installs and ratings  

## 📊 Insights
- **GAME** category had the highest total installs  
- Several utility apps also ranked high in installs despite fewer apps in the category  
- Larger app sizes did not always correlate with higher ratings  

