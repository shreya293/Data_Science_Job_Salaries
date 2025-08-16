# 📊 Data Science Job Salaries Dashboard

Tableau Dashboard: https://public.tableau.com/app/profile/shreya.singh.chauhan/viz/GlobalDataScienceJobSalariesDashboard/GlobalDataScienceJobSalaries?publish=yes

This project is an interactive dashboard built using **Streamlit** that visualizes data science job salary trends across various roles, locations, and company types.

## 🚀 Features

- Visualize salary distribution by:
  - **Employment type**
  - **Company size**
  - **Job titles**
  - **Company location**
  - **Employee residence**
- Interactive dropdown for selecting job titles
- Clean UI built using Seaborn and Matplotlib
- Full form mappings for abbreviations like:
  - `FT → Full_time`
  - `EN → Entry`
  - `US → United States`, etc.

## 🗂️ Project Structure

Data_Science_Job_Salaries/

│

├── app/

│ 
└── streamlit_app.py # Main Streamlit app

├── data/

│
└── Data Science Job Salaries.csv

├
── src/

│
└── model.py # (Optional) ML/analysis logic
├

── notebooks/

│ 
└── analysis.ipynb # Exploratory analysis

├── requirements.txt # All dependencies

└── README.md # This file


## 🛠️ Technologies Used

- Python 🐍
- Streamlit 📈
- Pandas
- Seaborn
- Matplotlib

## ▶️ Run the App Locally

1. Clone this repository  
   ```bash
   git clone https://github.com/shreya293/Data_Science_Job_Salaries
   cd data-science-job-salaries
2.  Create and activate a virtual environment(Optional)
   ```bash
   python -m venv job
   job\Scripts\activate
3. Install Dependencies
   pip install -r requirements.txt
4. Run the App
   streamlit run app/streamlit_app.py


