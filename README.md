# SpaceX Falcon 9 Success Landing Prediction

## 🚀 Project Overview
This project aims to predict whether the SpaceX Falcon 9 first stage will successfully land after a rocket launch. Successful landings enable cost savings through stage reuse, reducing launch costs significantly.

## 🛠 Objectives
- Predict the likelihood of Falcon 9’s first stage landing successfully.
- Analyze how variables like payload mass, launch site, orbit type, and number of flights affect landing success.
- Identify the best classification algorithm for binary prediction.
- Create visualizations and dashboards to share insights with stakeholders.

## 📄 Key Questions
1. How do variables such as payload mass, launch site, and orbit type influence landing success?
2. Have success rates improved over the years?
3. Which classification algorithm performs best for this case?

## 📋 Methodology

### 1. Data Collection
- **SpaceX RESTful API**: Gathered detailed launch data.
- **Web Scraping**: Extracted supplementary information from Wikipedia.

### 2. Data Wrangling
- Filtered and cleaned the data.
- Handled missing values.
- Applied One-Hot Encoding to prepare data for classification.

### 3. Exploratory Data Analysis (EDA)
- Used SQL for data querying and sorting.
- Created visualizations in Python to identify trends and patterns.

### 4. Interactive Visual Analytics
- Built dashboards using **Plotly Dash**.
- Created interactive maps with **Folium** for geographical analysis of launch sites.

### 5. Predictive Analysis
- Split data into training and testing sets.
- Trained classification models: Logistic Regression, SVM, Decision Tree, KNN.
- Performed hyperparameter tuning using **GridSearchCV**.
- Evaluated models using accuracy, F1-score, and confusion matrices.

## 📊 Tools and Technologies
- **Programming Languages**: Python
- **Libraries**: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Plotly, Folium
- **Database**: SQL
- **Machine Learning Models**: Logistic Regression, SVM, Decision Tree, KNN
- **Environment**: Jupyter Notebook

## 🔍 Findings and Insights
1. Launch sites near the equator benefit from Earth’s rotational speed, aiding rocket launches.
2. KSC LC-39A has the highest success rate among all sites.
3. Payload mass positively correlates with LEO (ISS) orbit success but negatively impacts GTO orbit success.
4. Success rates have improved significantly from 2013 to 2020.
5. The Decision Tree Model demonstrated the best performance.

## 💡 Conclusion
Using data science and machine learning, this project predicts Falcon 9 landing outcomes, providing insights that can help SpaceX optimize operations and reduce costs.

## 🔗 Resources
- SpaceX REST API: [Link](https://github.com/r-spacex/SpaceX-API)
- IBM Data Science Professional Certificate: [Link](https://www.coursera.org/professional-certificates/ibm-data-science)
