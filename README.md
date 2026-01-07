# HR Analytics – Employee Attrition Project

## 📌 Project Overview
This project focuses on analyzing employee attrition using HR data and building a predictive analytics dashboard. The goal is to identify key factors that influence employee turnover and calculate attrition risk probability for each employee.

## 🛠 Tools and Technologies Used
- Python
- Pandas and NumPy
- Machine Learning (scikit-learn)
- Power BI
- Tableau Public

## 📂 Dataset
The dataset used in this project is the Employee Attrition Dataset containing 1470 employee records with multiple HR-related features such as Age, Department, Job Role, Income, Overtime, etc.

### Data Files Available
All processed data files are stored in the `/data` folder:
- cleaned_attrition_data.csv
- attrition_predictions.csv

## 🧹 Data Cleaning
A separate Python notebook was created to clean and preprocess the dataset.

### Notebook Location
Data cleaning notebook:
`/python_code/data_cleaning.ipynb`

Steps performed:
- Removed unnecessary columns
- Handled missing values
- Converted categorical fields into numeric format
- Created new calculated fields such as:
  - Age Group
  - Income Group
  - Attrition Numeric

## 🤖 Machine Learning Model

### Notebook Location
Attrition prediction model:
`/python_code/attrition_model.ipynb`

### Libraries Used
The following Python libraries are required to run the project:

See `requirements.txt` in root directory.

### Model Building Steps
- Split dataset into training and testing sets
- Applied Label Encoding to categorical columns
- Scaled features using StandardScaler
- Built predictive models:
  - Logistic Regression
  - Random Forest Classifier
- Evaluated model using:
  - Accuracy Score
  - Confusion Matrix
  - Classification Report
- Calculated Attrition Risk Probability for each employee

## 📊 Dashboards Created

### Power BI Dashboard
Screenshot available in:
`/screenshots/`

The Power BI dashboard includes:
- Total Employees
- Attrition Count
- Department-wise Attrition
- Income-wise Attrition
- Age-wise Attrition
- Overtime Impact Chart
- Salary Hike Impact

### Tableau Public Dashboard
A live interactive dashboard was also created using Tableau Public.

#### Key Features
- Multiple dashboard filters
- Attrition risk probability slider
- Reset filters control
- Fully interactive visuals

#### Live Link
Tableau Dashboard Published on Tableau Public Profile.

*https://public.tableau.com/views/HRAnalyticsEmployeeAttritionDataset/Dashboard12?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link*

## 🔁 How to Run This Project

### Step 1 – Clone Repository
Download or clone this repository to your local system.

### Step 2 – Install Dependencies
Open terminal and run:

pip install -r requirements.txt

### Step 3 – Run Notebooks
- Open Jupyter Notebook
- Execute:
  - data_cleaning.ipynb
  - attrition_model.ipynb

### Step 4 – View Dashboards
- Open Power BI file or screenshots
- Use Tableau Public live dashboard link

## 🎯 Business Outcome
This project helps HR teams and organizations:
- Understand why employees leave
- Identify high-risk employees
- Improve retention strategies
- Make data-driven HR decisions

## 📎 Portfolio Use
This project can be used as a complete Data Analytics portfolio demonstrating:
- End-to-end data preprocessing
- Machine learning modeling
- Dashboarding and visualization
- User interactivity with filters and actions
