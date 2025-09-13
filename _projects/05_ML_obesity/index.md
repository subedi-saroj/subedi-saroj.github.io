---
layout: post
title: Obesity Risk Classification Using Machine Learning
description:  Built predictive models to classify obesity risk into eight categories using lifestyle and genetic factors. Compared Random Forest, KNN, and CNN models on Kaggle health datasets from Mexico, Peru, and Colombia, achieving up to 95% accuracy. Developed a Streamlit app to enable interactive user predictions.
skills:
  - Machine Learning (Random Forest, KNN, CNN)
  - Python (Scikit-learn, TensorFlow, PyTorch, Pandas, Seaborn)
  - Data Preprocessing & Feature Engineering
  - Exploratory Data Analysis & Visualization
  - Hyperparameter Optimization
main-image: /main.jpg 
---

---
## Background
With obesity rising as a global health crisis, early risk detection is crucial for prevention. This project aimed to leverage machine learning to predict obesity risk levels based on lifestyle and genetic factors, providing a proactive healthcare tool.
<br>

## Methods
- Collected and cleaned Kaggle dataset (populations from Mexico, Peru, Colombia).
- Performed exploratory data analysis (EDA) with correlation heatmaps, histograms, and feature importance analysis.
- Preprocessed data (encoding categorical features, scaling, handling missing values).
- Trained three models: Random Forest, KNN, and CNN, including hyperparameter tuning via Grid Search and Randomized Search.
- Built a **Streamlit web app** for user interaction with the trained model.
{% include image-gallery.html images="method.jpg" height="400" %}
{% include image-gallery.html images="output.png" height="500" %}
<br>

## Key Results
- **Random Forest** achieved the highest accuracy (~95%), outperforming CNN (~86%) and KNN (~80%).
- Identified top predictive features: frequency of vegetable consumption, number of main meals, height, weight, and screen time.
- The Streamlit app allowed users to input lifestyle parameters and receive obesity risk classification in real-time.
{% include image-gallery.html images="perf_comp.jpg" height="500" %}
{% include image-gallery.html images="gui.jpg" height="500" %}
