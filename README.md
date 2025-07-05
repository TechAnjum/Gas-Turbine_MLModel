# 🔥 Gas Turbine Emission Prediction using Machine Learning
This project focuses on building a robust machine learning model to predict Carbon Monoxide (CO) emissions from a gas turbine based on input parameters such as ambient temperature, pressure, humidity, and energy readings. The goal is to develop a reliable regression model that can help in energy optimization and emission control.

# 📊 Overview
With increasing industrialization, it's crucial to monitor and reduce harmful emissions. This project leverages supervised regression techniques to forecast CO emission levels, using real-world sensor data from a gas turbine system.

# Key Features
Data Preprocessing: Cleaned and normalized raw turbine sensor data.

Exploratory Data Analysis (EDA): Visualized feature distributions, correlations, and trends.

Train-Test Split: Implemented an 80/20 split for robust model evaluation.

Model Training:

  1) Random Forest Regressor

  2) Linear Regression

  3) Decision Tree Regressor

  4) Support Vector Regressor (SVR)

 Hyperparameter Tuning: Used RandomizedSearchCV for optimized performance.

 Performance Metrics: R² Score and Error metrics for model evaluation.

 Graphs: Plots for actual vs predicted emissions, feature importance, and more.

🌐 Gradio UI (Optional): Interactive interface for real-time predictions.

📁 Dataset
The dataset contains multiple features collected from a gas turbine system. The target variable is:

CO (Carbon Monoxide) Emissions

# Key input features include:

Ambient Temperature (AT)

Ambient Pressure (AP)

Ambient Humidity (AH)

Gas Turbine Energy Yield (GT)

⚙️ Tech Stack
Python

Pandas & NumPy

Matplotlib & Seaborn

Scikit-learn

Gradio (for UI)

# 🚀 How to Run
1. Clone the Repository

git clone https://github.com/your-username/gas-turbine-ml.git
cd gas-turbine-ml

2. Install Dependencies

pip install -r requirements.txt

3. Run the Notebook
Open Gas_Turbine_MLModel.ipynb in Jupyter Notebook or VSCode to explore the model pipeline and visualizations.

4. Launch Gradio App (Optional)
# At the end of the notebook
gr.Interface(fn=predict_function, inputs=[...], outputs=[...]).launch()
