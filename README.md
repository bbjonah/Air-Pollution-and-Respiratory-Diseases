🌍 Air Pollution and Respiratory Diseases Analysis

📌 Project Overview
This project explores the relationship between air pollution and respiratory health outcomes, focusing on conditions such as asthma and chronic respiratory diseases. Using data science techniques, we analyze how pollutants like PM2.5, NO₂, and SO₂ influence the number of reported respiratory cases.

🎯 Objectives
Analyze trends in air pollution levels over time
Examine the relationship between pollution and respiratory diseases
Build a predictive model for respiratory cases based on pollution levels
Provide insights for public health decision-making
📊 Dataset Description
1. Air Pollution Data (air_pollution.csv)

Contains environmental measurements:

date – Observation date
location – City name (e.g., Lagos, Abuja, Port Harcourt)
pm25 – Fine particulate matter concentration
no2 – Nitrogen dioxide levels
so2 – Sulfur dioxide levels
2. Health Data (health_data.csv)

Contains health-related records:

date – Observation date
location – City name
respiratory_cases – Number of reported respiratory disease cases
⚙️ Technologies Used
Python
Pandas
NumPy
Matplotlib
Scikit-learn
🧠 Methodology
1. Data Preprocessing
Converted date columns to datetime format
Handled missing values
Merged datasets on date and location
2. Exploratory Data Analysis (EDA)
Visualized pollution trends
Checked correlations between pollutants and health outcomes
3. Modeling
Used Linear Regression to predict respiratory cases
Features:
PM2.5
NO₂
SO₂
4. Evaluation Metrics
Mean Squared Error (MSE)
R² Score
🚀 How to Run the Project
Clone the repository:
git clone https://github.com/your-username/air-pollution-health.git
cd air-pollution-health
Install dependencies:
pip install pandas numpy matplotlib scikit-learn
Run the script:
python main.py
📈 Sample Output
Scatter plot of actual vs predicted respiratory cases
Model performance metrics (MSE, R²)
Feature importance (pollutant impact)
📌 Key Insights
Higher pollution levels are associated with increased respiratory cases
PM2.5 often shows the strongest impact
Predictive models can help in early warning systems
⚠️ Limitations
Synthetic dataset (not real-world data)
Limited variables (no weather or demographic factors)
Linear model may not capture complex relationships
🔮 Future Improvements
Incorporate real-world datasets
Add weather and socioeconomic factors
Use advanced models (Random Forest, XGBoost, LSTM)
Build an interactive dashboard (Streamlit or Power BI)
🤝 Contributing

Contributions are welcome! Feel free to fork this repository and submit a pull request.

📄 License

This project is open-source and available under the MIT License.

👤 Author

Buka Bright Jonah
Data Science Enthusiast
