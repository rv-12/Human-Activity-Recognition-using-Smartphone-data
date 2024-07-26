# 🕵️‍♂️ Human Activity Recognition Using Smartphone Data 📱

Welcome to the Human Activity Recognition project! This repository aims to classify daily activities using data collected from smartphones equipped with inertial sensors. 🌟

📜 Description
The Human Activity Recognition dataset is based on recordings from 30 volunteers performing various activities while carrying a waist-mounted smartphone. The goal is to classify the activities into one of the six categories:

🚶‍♂️ Walking

🏃‍♂️ Walking Upstairs

🏃‍♂️ Walking Downstairs

🪑 Sitting

🚶‍♂️ Standing

🛌 Laying

The experiments involved participants aged 19-48 years, each wearing a Samsung Galaxy S II smartphone. The device recorded 3-axial linear acceleration and 3-axial angular velocity at 50Hz. Data was video-recorded for manual labeling and then divided into training (70%) and test (30%) sets.

🧪 Experiment Details

Device Used: Samsung Galaxy S II

Sampling Rate: 50Hz

Activities Performed: 6 (Walking, Walking Upstairs, Walking Downstairs, Sitting, Standing, Laying)

Data Partition: 70% training, 30% testing

Preprocessing:
Noise filtering

Fixed-width sliding windows (2.56s, 50% overlap)

Separation of body acceleration and gravity using a Butterworth low-pass filter (0.3 Hz cutoff)

📚 Notebook - Table of Contents

📦 Importing Necessary Libraries

📂 Loading Data

🔧 Data Preprocessing

3.1 🔍 Checking for Duplicates

3.2 ❓ Checking for Missing Values

3.3 ⚖️ Checking for Class Imbalance

📊 Exploratory Data Analysis

4.1 📈 Analyzing tBodyAccMag-mean Feature

4.2 🔭 Analyzing Angle between X-axis and Gravity Mean Feature

4.3 🔭 Analyzing Angle between Y-axis and Gravity Mean Feature

4.4 🌌 Visualizing Data Using t-SNE

🤖 Model Prediction and Evaluation
5.1 🔍 Logistic Regression with Hyperparameter Tuning and Cross Validation
5.2 🔍 Linear SVM with Hyperparameter Tuning and Cross Validation
5.3 🔍 Kernel SVM with Hyperparameter Tuning and Cross Validation
5.4 🔍 Decision Tree with Hyperparameter Tuning and Cross Validation
5.5 🔍 Random Forest with Hyperparameter Tuning and Cross Validation
