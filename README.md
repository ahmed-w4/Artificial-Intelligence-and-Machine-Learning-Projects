# Artificial-Intelligence-and-Machine-Learning-Projects
Artificial Intelligence & Machine Learning Portfolio
Student: Ahmed Wael
This repository contains a comprehensive collection of assignments demonstrating a wide range of data science, machine learning, and deep learning skills. The projects are grouped by topic, showcasing a progression from basic data handling to advanced model deployment.

1. Core Data Handling & Analysis
Assignment: Pandas Fundamentals
Dataset: Iris.csv / company_data.csv

Skills Demonstrated:

Loading data using pandas.

Initial data exploration with head(), shape, info(), and describe().

Data filtering and selection based on conditions.

Grouping and aggregation to compute summary statistics.

Sorting data.

Creating new derived columns.

Handling missing values.

Data cleaning (splitting columns, dropping irrelevant ones).

2. Data Visualization & Preprocessing (Healthcare)
Assignment: Stroke Risk Prediction Pipeline
Dataset: healthcare-dataset-stroke-data.csv

Objective: To prepare a healthcare dataset for machine learning.

Skills Demonstrated:

Exploratory Data Analysis (EDA): Using seaborn and matplotlib to create countplots for class distribution, subplot visualizations for categorical features, histograms/KDEs for numerical features, and a correlation heatmap.

Data Cleaning:

Handling missing values using mean/median imputation.

Removing duplicates and irrelevant columns.

Outlier detection using boxplots and the IQR method.

Feature Engineering: Encoding categorical variables using Label Encoding and One-Hot Encoding.

Machine Learning Pipeline:

Splitting data into training and test sets with train_test_split.

Feature scaling using StandardScaler.

Handling class imbalance using SMOTE.

3. Classical Machine Learning Models
Assignment: Linear Regression
Dataset: Expanded_data_with_more_features.csv

Objective: To predict a student's math score.

Skills Demonstrated:

Extensive data cleaning (handling missing values, outlier removal using IQR).

Feature encoding and scaling.

Building a Linear Regression model using scikit-learn.

Evaluating model performance with MSE, RMSE, MAE, and R².

Visualizing results with a "Predicted vs Actual" scatter plot.

Assignment: K-Nearest Neighbors (KNN)
Dataset: Dry_Bean_Dataset.xlsx

Objective: To classify different types of dry beans.

Skills Demonstrated:

Outlier detection and removal.

Comparing model performance with and without feature scaling.

Tuning the k hyperparameter by testing values from 1-25 and plotting accuracy vs. k.

Comparing distance metrics (Euclidean vs. Manhattan).

Confusion matrix analysis to identify misclassified classes.

Assignment: Support Vector Machines (SVM)
Dataset: diabetes.csv

Objective: To predict diabetes onset.

Skills Demonstrated:

Data cleaning (identifying and handling invalid values like 0 for BMI/Glucose with median imputation).

Training and comparing SVM models with Linear, RBF, and Polynomial kernels.

Hyperparameter tuning using GridSearchCV for parameters like C and gamma.

Analyzing support vectors.

Testing model robustness by introducing noise to the data.

Assignment: Tree-Based Models
Dataset: Dry_Bean_Dataset.xlsx

Objective: To classify different types of dry beans.

Skills Demonstrated:

Building and comparing Decision Trees, Random Forests, and XGBoost models.

Using feature importance to interpret model predictions.

Assignment: Clustering
Dataset: Mall_Customers.csv

Objective: To segment customers using clustering techniques.

Skills Demonstrated:

Feature scaling for distance-based algorithms.

Using the Elbow Method (WCSS) and Silhouette Score to find the optimal number of clusters (K) for K-Means.

Visualizing results to interpret clusters.

Comparing K-Means vs. DBSCAN on synthetic, non-spherical (make_moons) data to highlight the limitations of K-Means and the strengths of DBSCAN for such data shapes.

4. Advanced Deep Learning & NLP
Assignment: Deep Learning (Artificial Neural Networks)
Dataset: Breast Cancer Wisconsin Dataset.

Objective: To build an ANN for binary tumor classification.

Skills Demonstrated:

Building a complete machine learning pipeline (loading, cleaning, EDA, splitting, scaling).

Constructing a baseline ANN model in TensorFlow/Keras.

Training the model with validation split and Early Stopping.

Evaluating the model with various metrics (Accuracy, Precision, Recall, F1-Score, Confusion Matrix).

Improving the model through experiments with different activations, optimizers, learning rates, and architectures.

Assignment: CNN Image Classification
Dataset: Vegetable Image Dataset (15 classes).

Objective: To classify vegetable images using a Convolutional Neural Network.

Skills Demonstrated:

Data exploration and visualization.

Using ImageDataGenerator for image preprocessing and augmentation (rotation, zoom, shift, flip).

Building a CNN from scratch in Keras.

Training the model with Early Stopping and monitoring for overfitting.

Plotting accuracy and loss curves to analyze training progress.

Assignment: Natural Language Processing (Sentiment Analysis)
Dataset: COVID-19 Twitter data.

Objective: To perform sentiment analysis on tweets.

Skills Demonstrated:

Text Preprocessing: Lowercasing, removing URLs/hashtags/mentions, expanding contractions, tokenization, stopword removal, lemmatization.

Classical Deep Learning: Training an LSTM/BiLSTM model for sequence classification.

Transformers: Fine-tuning a BERT/DistilBERT model using the transformers library.

Deployment: Saving models and building a Streamlit web application for real-time predictions.

5. Advanced Computer Vision (YOLO)
Assignment: YOLO for Practical Applications
Objective: To apply YOLO (You Only Look Once) to four practical tasks.

Skills Demonstrated:

Object Detection: Training a custom YOLO model for fire and smoke detection using a Roboflow dataset.

Object Counting: Using Ultralytics YOLO with tracking to count objects crossing a defined line in a video.

Vision Mapping: Implementing VisionEye to visualize object mapping from a specific viewpoint.

Custom Training: Training a YOLO model on a custom Neural Ocean dataset and testing it on new images.

Key Tools & Technologies Used
Languages: Python

Core Libraries: Pandas, NumPy

Data Visualization: Matplotlib, Seaborn

Machine Learning: Scikit-learn (Linear Regression, KNN, SVM, Trees, Clustering)

Deep Learning: TensorFlow, Keras

NLP & Transformers: NLTK, Transformers (Hugging Face)

Computer Vision: Ultralytics YOLO, OpenCV

Model Deployment: Streamlit

Platforms: Kaggle, Google Colab, Jupyter Notebooks
