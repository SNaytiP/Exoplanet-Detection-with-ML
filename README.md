# Exoplanet-Detection-with-ML
Exoplanet Detection with Machine Learning

Project Overview:
This project uses real astronomical data from space telescopes (like Kepler or TESS) and applies machine learning to detect exoplanets—planets outside our solar system.

Astronomers often detect exoplanets by monitoring the brightness of stars over time (called a light curve). A dip in brightness could mean a planet passed in front of the star—a transit. Your machine learning model will learn to spot those dips and identify potential planets automatically.

⚙️ How It Works:
Data Collection
Get real light curve data from NASA’s Kepler/TESS datasets.
Format it for training (brightness vs. time).
Preprocessing
Clean noisy data, normalize brightness.
Extract features (e.g., transit depth, duration, periodicity).
Model Building
Train a classification model using scikit-learn or TensorFlow/Keras.
Label examples: transit = planet, no transit = no planet.
Algorithms: Logistic Regression, Random Forest, or a Neural Network.
Evaluation
Test model on unseen data.
Metrics: accuracy, precision, recall, confusion matrix.
Prediction + Visualization
Predict on new data and show light curves where potential planets were found.
Plot and annotate dips for human verification.
