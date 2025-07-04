# Diabetes Dataset Exploratory Data Analysis (EDA)

This project performs exploratory data analysis (EDA) on the **Pima Indians Diabetes Dataset** using **Pandas**, **Matplotlib**, and **Seaborn**. The goal is to understand the relationships and distributions of various health-related features and their impact on diabetes outcomes.

## 📂 Dataset

- **File:** `diabetes.csv`
- **Features:**
  - `Pregnancies`
  - `Glucose`
  - `BloodPressure`
  - `SkinThickness`
  - `Insulin`
  - `BMI`
  - `DiabetesPedigreeFunction`
  - `Age`
  - `Outcome` (Target: 0 = No Diabetes, 1 = Diabetes)

## 🛠️ Libraries Used

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`

## 📊 Visualizations

The notebook/script includes:
- **Scatter plot:** BMI vs Age  
- **Line plot:** Age  
- **Histogram:** DiabetesPedigreeFunction  
- **Bar plot:** Age vs Insulin  
- **Pie chart:** Outcome distribution (⚠️ Note: pie chart on raw values may not be meaningful)
- **Seaborn lineplot:** Age vs Outcome  
- **Seaborn scatterplot:** Age vs Insulin  
- **Seaborn distplot:** Insulin distribution (⚠️ `distplot` is deprecated; consider `histplot` or `displot`)  
- **Seaborn barplot:** Age vs Outcome  
- **Seaborn boxplot:** Age vs Pregnancies  
- **Seaborn pairplot:** Pairwise plots colored by Insulin (⚠️ `hue="Insulin"` may not group well since Insulin is continuous)  
- **Seaborn heatmap:** Correlation matrix  

## 💡 Notes

- There are no missing values in the dataset.
- Some plots (e.g. pie chart and bar chart of Age vs Insulin) may not be suitable due to the nature of the data.  
- The code is designed for learning and visualization purposes — improvements can be made for clearer insights.



