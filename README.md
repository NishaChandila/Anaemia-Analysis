# Anemia Analysis Dashboard

**"Taking care of your body is the most important investment you can make in your future."**

## Introduction
Welcome to the **Anemia Analysis Dashboard**! This project was created to explore the relationship between **hemoglobin levels**, **pixel composition** (red, green, and blue), and **anemia status**. The dataset categorizes data by **sex** and provides insights into the prevalence of anemia among different groups.

Through this interactive **Power BI dashboard**, users can visualize key health metrics, including **pixel composition** and **hemoglobin levels**, and examine how they correlate with **anemia status**. The goal of this project is to raise awareness about anemia, highlight potential gender differences, and encourage further research for better detection and treatment strategies.

- Anemia [Dataset](https://github.com/NishaChandila/Anemia-Analysis/blob/main/file_.csv)
- Python [EDA](https://github.com/NishaChandila/Anemia-Analysis/blob/main/anaemia-prediction.ipynb)
- Power Bi [Dashboard](https://github.com/NishaChandila/Anemia-Analysis/blob/main/Anemia-Dashboard.pdf)

## Data Structure
The dataset used in this analysis includes key health metrics that help us understand **anemia** and its correlation with various factors. Below are the columns analyzed in the dashboard:

![Dataset](https://github.com/NishaChandila/project-assets/blob/main/Anemia-Dashboard-Dataset.PNG)

- **Sex**: The gender of the individual (**Male/Female**).
- **% Red Pixel**: The percentage of **red** pixels in the data sample.
- **% Green Pixel**: The percentage of **green** pixels in the data sample.
- **% Blue Pixel**: The percentage of **blue** pixels in the data sample.
- **Hemoglobin (HB)**: The hemoglobin level in the blood, which is crucial for anemia detection.
- **Anemic**: Indicates whether the individual is **anemic** (**Yes/No**) based on their hemoglobin levels and other health factors.

- Anemia [Dataset](https://github.com/NishaChandila/Anemia-Analysis/blob/main/file_.csv)

## Executive Summary

![Home](https://github.com/NishaChandila/project-assets/blob/main/Anemia-Dashboard1.PNG)

### Power BI Executive Summary:

![Anemia](https://github.com/NishaChandila/project-assets/blob/main/Anemia-Dashboard2.PNG)

- The **Power BI Dashboard** visualizes **anemia prevalence** by **gender** and **hemoglobin levels**, with insights into health metrics.
- Interactive charts, including **bar charts** and **pie charts**, show the distribution of **anemia status** across **sex**, highlighting the differences.
- **KPI cards** display key metrics, such as average **hemoglobin levels**, with slicers for easy filtering of data by **sex** and **anemia status**.
- The dashboard integrates **RGB pixel data** to analyze correlations between **pixel composition** and **anemia**, supporting data-driven health interventions.

- Power Bi [Dashboard](https://github.com/NishaChandila/Anemia-Analysis/blob/main/Anemia-Dashboard.pdf)

### Python Executive Summary:
- **Data Encoding**: Categorical variables (**Sex** and **Anaemic**) were encoded into numerical values for further analysis.
- **Exploratory Data Analysis (EDA)**: The distribution of **hemoglobin levels** and **anemia status** by **sex** was analyzed with **count plots**.
- **Hemoglobin Classification**: A custom function classified **hemoglobin levels** as **Normal** or **Abnormal** based on gender-specific thresholds.
- **Data Scaling**: The **Red, Green, and Blue pixel** values, along with **Anaemic** status, were scaled using **StandardScaler** for consistency.
- **Model Evaluation**: The performance of the **KNN classifier** was assessed using a **confusion matrix**, highlighting prediction accuracy.
- **Statistical Summary**: **Descriptive statistics** provided insights into the dataset's distribution, including **min/max values** and **unique counts**.

- Python [EDA](https://github.com/NishaChandila/Anemia-Analysis/blob/main/anaemia-prediction.ipynb)

## Recommendation
- **Data Expansion**: Collect a larger dataset to capture more diverse health metrics, enabling more accurate insights and trend analysis.
- **Gender-Specific Interventions**: Focus on tailored health interventions for **females**, as they show a higher prevalence of anemia compared to males.
- **Pixel Data Analysis**: Further explore the correlation between **RGB pixel composition** and **anemia**, which could potentially inform new diagnostic methods.
- **Regular Monitoring**: Encourage regular **hemoglobin level** checks, particularly for populations with high anemia risk, to support early detection and timely treatment.

- Anemia [Dataset](https://github.com/NishaChandila/Anemia-Analysis/blob/main/file_.csv)
- Python [EDA](https://github.com/NishaChandila/Anemia-Analysis/blob/main/anaemia-prediction.ipynb)
- Power Bi [Dashboard](https://github.com/NishaChandila/Anemia-Analysis/blob/main/Anemia-Dashboard.pdf)

