📊 IBM HR Analytics – Employee Attrition & Performance
This project analyzes employee attrition data from IBM to identify key factors that influence employee turnover. Using exploratory data analysis, machine learning, and Power BI visualizations, the project helps HR departments make informed decisions to reduce attrition and improve employee satisfaction.

📁 Project Structure
├── IBM-HR-Employee-Attrition.csv       # Dataset used for analysis
├── IBM_HR.ipynb                        # Jupyter Notebook with analysis and modeling
├── IBM_HR.pbit                         # Power BI report template
└── README.md                           # Project documentation

🔍 Objectives
  -->Analyze IBM employee data to understand patterns of attrition.
  -->Identify important factors contributing to employee attrition.
  -->Build machine learning models to predict attrition.
  -->Visualize insights using Power BI.

🧪 Technologies Used
  -->Programming: Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)
  -->Visualization: Power BI
  -->Tools: Jupyter Notebook

📌 Key Components
📊 Data Analysis (IBM_HR.ipynb)
 -->Data cleaning and preprocessing
 -->Exploratory Data Analysis (EDA)
 -->Feature engineering
 -->Machine learning models (e.g., Logistic Regression, Decision Tree, Random Forest)
 -->Model evaluation (accuracy, confusion matrix, ROC-AUC)

📈 Power BI Dashboard (IBM_HR.pbit)
 -->Interactive visuals showing:
 -->Attrition by age, department, job role, environment satisfaction, etc.
 -->Trends and patterns for HR decision making
 -->KPI metrics like attrition rate, average satisfaction, etc.

📂 Dataset Overview
File: IBM-HR-Employee-Attrition.csv
Records: 1,470
Features: 35+
Target Variable: Attrition (Yes/No)

Key features include:
   Age, Gender, Education, EnvironmentSatisfaction, JobRole
   MonthlyIncome, YearsAtCompany, OverTime, etc.

🚀 How to Run
🧪 Jupyter Notebook
-->Install requirements:
       pip install pandas numpy matplotlib seaborn scikit-learn
-->Open and run IBM_HR.ipynb in Jupyter Notebook or VSCode.

📈 Power BI
 -->Open IBM_HR.pbit in Power BI Desktop.
 -->Connect it to the dataset (IBM-HR-Employee-Attrition.csv) when prompted.

📚 Insights
 -->Employees working overtime or with low environment satisfaction tend to leave.
 -->Job role, income, and work-life balance are critical in predicting attrition.
 -->ML models can help predict who is at risk of leaving with high accuracy.

📌 Conclusion
This project demonstrates the power of data science and BI tools in solving real-world HR problems. By identifying key attrition drivers and visualizing them interactively, HR teams can take proactive steps to retain talent.
