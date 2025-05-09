# 🏆 World Cup Match Predictor & Data Story

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange.svg)](https://scikit-learn.org/)
[![Plotly](https://img.shields.io/badge/Plotly-Data%20Visualization-brightgreen.svg)](https://plotly.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

> An end-to-end data analysis and machine learning project exploring historical FIFA World Cup data to uncover winning patterns and predict match outcomes.

🔗 **Live Demo / Interactive Data Story:** [View Website](https://zouge666.github.io/world-cup-ml-predictor/)

## 📖 Overview

This project analyzes over 7,600 player records and 900+ matches from historical World Cup datasets. By engineering unique features such as climate impact (Köppen climate classification), star-player presence, and historical team win rates, we aim to quantify the hidden factors that influence match outcomes.

The current release features an interactive data visualization dashboard and a baseline ensemble machine learning classifier predicting home-team victories.

## ✨ Key Features

- **Extensive Data Wrangling:** Cleaned and merged complex datasets containing match events, player statistics, and geographical data.
- **Advanced Feature Engineering:** - Extracted contextual features like `home_star` (presence of key players).
  - Mapped match locations to Köppen climate codes to analyze weather adaptability.
- **Interactive Visualization:** Built a dynamic data story using Plotly to visually explain the distribution of goals, player impacts, and team dominances.
- **Predictive Modeling:** Trained an ensemble Random Forest Classifier, currently achieving ~63% accuracy and 72% recall on predicting home-team wins.

## 🛠️ Tech Stack

- **Data Processing:** Python, Pandas, NumPy
- **Machine Learning:** Scikit-Learn (Random Forest)
- **Data Visualization:** Plotly
- **Deployment:** HTML/CSS, GitHub Pages

## 🚀 Future Roadmap (In Progress)

To further scale this project for AI Engineering and Full-Stack deployment, the following features are actively being developed:

- [ ] **Deep Learning Integration:** Transitioning from Random Forest to PyTorch-based sequential models (RNN/LSTM) utilizing historical match time-series data to improve prediction accuracy.
- [ ] **Model Interpretability:** Implementing **SHAP** (SHapley Additive exPlanations) values to build a feature importance dashboard, quantifying exactly how much specific players or climate conditions affect the final score.
- [ ] **Real-time API Deployment:** Wrapping the trained model into a FastAPI/Flask backend, dockerizing the application, and deploying it to the cloud to serve live predictions.

## 💻 How to Run Locally

1. **Clone the repository:**

   ```bash
   git clone [https://github.com/zouge666/world-cup-ml-predictor.git](https://github.com/zouge666/world-cup-ml-predictor.git)
   cd world-cup-ml-predictor
   ```

2. **Install dependencies:**

   ```bash
   pip install pandas numpy scikit-learn plotly jupyter
   ```

3. **Run the Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```
   Open `pro_vis.ipynb` to view the data analysis, visualization, and model training process.
