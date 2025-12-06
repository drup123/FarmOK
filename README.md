Farmok - Intelligent Agriculture System 🌾
📋 Overview
Farmok is a Machine Learning-based web application designed to assist farmers and agricultural enthusiasts in making data-driven decisions. By leveraging Deep Learning (CNN) and Predictive Modeling (Random Forest), Farmok provides precise recommendations to maximize crop yield and ensure plant health.

The system is built with Flask and features three core modules:

Crop Disease Detection (Image Processing)

Crop Recommendation (Predictive Analysis)

Fertilizer Suggestion (Nutrient Analysis)

🚀 Key Features
1. Plant Disease Prediction 🍃
Input: Image of a plant leaf.

Algorithm: Convolutional Neural Networks (CNN).

Functionality: The system analyzes leaf textures and patterns to detect specific plant diseases or confirm if the plant is healthy. It provides immediate feedback to help prevent disease spread.

2. Crop Recommendation 🌽
Input: Soil and Environmental parameters (Nitrogen, Phosphorous, Potassium, pH, Rainfall, Humidity, Temperature).

Algorithm: Random Forest Classifier / Decision Trees.

Functionality: Based on the soil composition and weather conditions, the model predicts the most suitable crop to cultivate for maximum profitability and yield.

3. Fertilizer Suggestion 🧪
Input: Soil nutrient data (N, P, K), Soil Type, and Crop Type.

Algorithm: Classification Models.

Functionality: Analyzes nutrient gaps in the soil for a specific crop and recommends the exact fertilizer required to restore soil health.

🛠️ Tech Stack
Frontend: HTML5, CSS3, JavaScript, Bootstrap.

Backend: Flask (Python).

Machine Learning Libraries:

TensorFlow/Keras: For the CNN disease detection model.

Scikit-learn: For Random Forest and crop/fertilizer prediction models.

NumPy & Pandas: For data preprocessing and manipulation.

Pickle: For model serialization.
