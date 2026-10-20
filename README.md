# Smart-Agriculture-AI
Machine learning-based crop recommendation system with an interactive Streamlit dashboard.

# Smart Agriculture AI: Crop Recommendation System

## About the Project
Smart Agriculture AI is a machine learning project that recommends a suitable crop based on soil nutrients and environmental conditions.

## Objectives
- Analyze soil and weather-related data.
- Train a machine learning model for crop recommendation.
- Build an interactive dashboard using Streamlit.
- Present model performance and feature importance.

## Features
- Crop recommendation from input parameters.
- Soil and environmental data analysis.
- Model performance visualization.
- Feature importance analysis.
- Interactive dashboard.

## Dataset
The project uses a crop recommendation dataset containing:
- Nitrogen (N)
- Phosphorus (P)
- Potassium (K)
- Temperature
- Humidity
- Soil pH
- Rainfall
- Crop label

**Dataset source:** Add the original Kaggle dataset URL here.

## Technologies Used
Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Plotly, Joblib, Streamlit, Jupyter Notebook.

## Installation
```bash
git clone YOUR_GITHUB_REPOSITORY_URL
cd Smart-Agriculture-AI
python -m venv .venv
```

Activate the environment:
Windows:
```bash
.venv\Scripts\activate
```
Install dependencies:
```bash
pip install -r requirements.txt
```
## Run the Dashboard
```bash
streamlit run app.py
```

## Project Structure
- `MLproject.ipynb` — model development and analysis
- `app.py` — interactive Streamlit dashboard
- `Crop_recommendation.csv` — dataset, if redistribution is permitted
- `crop_model.pkl` — saved trained model, if included
- `requirements.txt` — project dependencies

## Results
Add the actual model accuracy, precision, recall, and F1-score after running the notebook from start to finish.

## Author
Add your name and academic details here.

## Disclaimer
This project is for educational purposes. Crop recommendations should be validated against local agricultural conditions and expert guidance.
