🌤️ Weather Prediction Dashboard
📌 Project Overview
The Weather Prediction Dashboard is a machine learning-based system that forecasts weather conditions—such as temperature and weather codes—for Delhi and Mumbai using historical data and real-time API integration. The predictions are visualized through an interactive dashboard built with NocoDB.

By combining real-time data with historical trends, users can track, analyze, and visualize weather patterns, enabling better planning and decision-making.

💡 Why It Matters
📅 Forecast Planning: Helps users plan activities based on weather conditions.

📊 Data Visualization: Tracks real-time forecasts and compares them with historical data.

⚡ Live Updates: Offers current conditions through API integration.

🔑 Key Features & Technologies
✨ Key Features:
Weather Prediction: Machine learning models trained on historical weather data to predict future conditions.

Real-Time Forecasting: Uses the Visual Crossing API to fetch live weather data.

Historical Analysis: Trained on past data from Open-Meteo for accurate trend analysis.

Interactive Dashboard: Built with NocoDB to explore data visually via tables and graphs.

🛠️ Technologies Used:
🔍 Machine Learning:
RandomForestClassifier – for weather condition (code) prediction.

RandomForestRegressor – for temperature prediction.

📊 Data Visualization:
NocoDB – No-code platform for displaying weather data in dashboards.

🌐 API Integration:
Visual Crossing API – Fetches current weather metrics like temperature, humidity, and wind speed.

🧮 Data Processing:
pandas – For data manipulation.

numpy – For numerical operations.

matplotlib – For plotting predictions vs. actual values.

🗄️ Database:
Supabase – Stores real-time and predicted weather data (PostgreSQL backend).

📁 Data Source:
Open-Meteo – Provides historical weather datasets.
🌐 Open-Meteo Weather Data

⚙️ Setup Instructions
✅ Pre-Requisites
Python 3.6 or higher

Required Python libraries:

pandas

scikit-learn

matplotlib

requests

supabase-py

🚀 Steps to Run the Project
Clone the Repository

bash
Copy code
git clone https://github.com/your-username/weather-prediction-dashboard.git
cd weather-prediction-dashboard
Install Dependencies

bash
Copy code
pip install -r requirements.txt
Download Historical Weather Data

Go to Open-Meteo and download data for:

Delhi → Save as delhi-jan-dec-2024.csv

Mumbai → Save as mumbai-jan-dec-2024.csv

Place both files in the project root directory.

Set Up Supabase

Create a Supabase project.

Replace placeholder credentials in the code with your Supabase keys.

Ensure the database has a table named weather_pred.

Run the Weather Prediction Script

bash
Copy code
python weather_prediction.py
View Dashboard in NocoDB

Open your NocoDB dashboard.

Connect it to the Supabase database.

Explore the weather data via interactive graphs and tables.

🤝 Contributing
We welcome contributions! To contribute:

Fork the repo

Create a new branch

Submit a pull request with proper documentation

Make sure existing features aren't broken

📄 License
This project is licensed under the MIT License. See the LICENSE file for more details.

👥 Coders
Hrithik Kumar
📧 goyalhrithik548@gmail.com

Shaik Anisah Firdaws
📧 anisahfirdaws1810@gmail.com
