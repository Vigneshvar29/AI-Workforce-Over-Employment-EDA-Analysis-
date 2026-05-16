# Impact of Automation on Employment: Exploratory Data Analysis

This project explores how automation, artificial intelligence, robotics adoption, and reskilling investments influence employment trends across countries and industries.

Using R and R Markdown, I performed Exploratory Data Analysis (EDA) on two datasets to uncover patterns in automation growth, salary trends, job creation, and job displacement.

---

## Project Objectives

- Analyze automation trends from 2015 to 2025 across multiple countries.
- Study the relationship between automation and employment rates.
- Examine the impact of automation on average salaries.
- Compare job creation trends in major economies.
- Evaluate the relationship between reskilling investment and employment.
- Analyze robotics adoption and job displacement by industry.

---

## Datasets Used

### 1. AI Workforce Dataset

Contains country-level metrics such as:
- Country
- Year
- Automation Rate (%)
- Employment Rate (%)
- AI Investment (Billion USD)
- Reskilling Investment (Million USD)
- Job Creation (Million)
- Job Displacement (Million)
- Average Salary (USD)
- Productivity Index
- AI Readiness Score

### 2. Robotics Dataset

Contains industry-level data including:
- Industry
- Year
- Robots Adopted
- Jobs Displaced
- Productivity Gain
- Cost Savings
- Training Hours

---

## Project Structure
impact-of-automation-on-employment/
│── datasets/
│   ├── ai_workforce.csv
│   ├── ai_workforce_cleaned.csv
│   └── robotics.csv
│
│── visualisation/
│   ├── graph1.png
│   ├── graph2.png
│   ├── ...
│   └── graph10.png
│
│── code.nb.html
│── README.md
│── .gitignore

## Technologies Used
- R
- RStudio
- R Markdown
- zoo package
- Base R plotting

## Data Preprocessing
Handled missing values using mean and median imputation.
Filled missing country values using forward and backward fill.
Reconstructed the Year column for consistency.
Removed variables with poor data quality.

## Visualizations Included
Robotics Adoption Over Time
Robots Adoption by Industry
Jobs Displaced by Industry
Jobs Displacement Over Time
Automation Growth Over Time
Employment Trend Over Time
Impact of Automation on Salaries
Job Creation in Selected Countries
Automation Rate by Country (Boxplot)
Reskilling Investment vs Employment Rate

## Key Insights
Automation rates increased steadily from 2015 to 2025.
Employment rates showed moderate fluctuations rather than a uniform decline.
Higher automation rates were associated with higher average salaries.
Reskilling investment showed a modest relationship with employment outcomes.
Manufacturing accounted for the highest robotics adoption and job displacement.

## Future Improvements
Build machine learning models to predict employment trends.
Develop an interactive dashboard using Shiny.
Integrate real-world data from OECD, World Bank, and IFR.

## Author

Vigneshvar Srinivasan
B.Tech Artificial Intelligence and Data Science Student
Aspiring Data Scientist and Machine Learning Engineer

GitHub: https://github.com/Vigneshvar29
LinkedIn: linkedin.com/in/vigneshvar-srinivasan-0a81853ba
