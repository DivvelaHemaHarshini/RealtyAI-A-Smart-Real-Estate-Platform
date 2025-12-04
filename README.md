<h1>🏠 REALTY AI</h1>
<h3>A Smart Real Estate Insight Platform</h3>
<h4>Realty AI is an end-to-end AI-powered real estate analytics platform that automates property evaluation, price prediction, and market trend forecasting. It integrates satellite image segmentation, house price modeling, and time-series forecasting into a unified system designed for buyers, sellers, investors, and developers.</h4>
<h3>
  🧩 Problem Statement</h3>
  <h2>
The real estate industry struggles with:
Inefficient and subjective property evaluation
Manual, time-consuming analysis
Inaccurate price predictions
Difficulty forecasting long-term market trends
  </h2>
<h3>Realty AI aims to solve these challenges by delivering actionable insights using an automated and data-driven AI platform.
</h3>
<h3>
  🚀 Project Overview</h3>
<h2>Objectives
1.Build a scalable platform that:
-Performs satellite image segmentation using U-Net
-Classifies buildings from segmented images
-Predicts house prices using XGBoost
-Forecasts market trends using an LSTM model
-Provides secure access using Streamlit + SQLite
-Generates automated analytical PDF reports

  2.Outcomes
-Accurate property insights
-Automated multi-model evaluation
-Interactive user interface for analysis
-Scalable and secure architecture
</h2>
<h3>🛠️ Methodology
End-to-End Workflow:</h3>
<h2>
User Authentication (Signup/Login/Logout)
Data Preprocessing (images + tabular data)
Satellite Image Segmentation with U-Net
Building Classification using CNN
House Price Prediction (XGBoost Regression)
Market Trend Forecasting (LSTM)
PDF Report Generation
Visualization Dashboards (Streamlit)</h2>
<h3>Model Arhcitectures </h3>
<h2>
🔹U-Net
High-precision building footprint extraction
Captures spatial context with skip connections

🔹 CNN Classifier
Categorizes building structures from segmented outputs

🔹 XGBoost Regression
Predicts property prices using optimized tree boosting

🔹 LSTM
Learns historical patterns to forecast future real estate trends </h2>
<h3>Techstack</h3>
<h2>
Python, NumPy, Pandas
TensorFlow, Keras, PyTorch (optional)
XGBoost
Streamlit
SQLite
Matplotlib / Seaborn / Plotly
OpenCV</h2>

# Clone the repository #
git clone https://github.com/DivvelaHemaHarshini/RealtyAI.git
cd RealtyAI

# Create a virtual environment #
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows

# Install dependencies #
pip install -r requirements.txt

# Run the Streamlit app #
streamlit run app.py



