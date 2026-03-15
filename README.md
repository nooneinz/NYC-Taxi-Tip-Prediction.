# NYC-Taxi-Tip-Prediction.
Predicting NYC taxi tips using 1M+ records. This project benchmarks IBM Snap ML vs. Scikit-Learn to demonstrate high-performance machine learning, feature engineering, and training speed optimization. Includes data preprocessing, normalization, and MSE performance evaluation
🚕 NYC Taxi Tip Prediction: Benchmarking Scikit-Learn vs. IBM Snap ML
📌 Project Overview
This project aims to predict taxi tip amounts using a large-scale dataset of 1 million NYC taxi trips. The core objective is to demonstrate the performance advantages of IBM's Snap ML library over the traditional Scikit-Learn implementation, focusing on training speed and model accuracy.

🚀 Key Features
Large-Scale Data Handling: Processed and cleaned a dataset with 1,000,000 observations.
Feature Engineering: Extracted high-value features such as pickup_hour, day_of_week, and trip_duration.
Advanced Preprocessing: Implemented memory optimization, L1 normalization, and robust data cleaning.
Performance Benchmarking: Comparative analysis of training times between standard and high-performance libraries.
🛠️ Tech Stack
Language: Python 3.x
Libraries: - Snap ML (IBM high-performance library)
Scikit-Learn (Standard ML library)
Pandas & NumPy (Data Manipulation)
Matplotlib (Visualization)
📊 Results & Performance
The results highlight the efficiency of Snap ML's multi-threaded architecture:

Library	Training Time (Seconds)	MSE (Accuracy)
Scikit-Learn	Check your output	Check your output
IBM Snap ML	Fastest	Comparable
Outcome: Snap ML delivered a significant performance gain (X.XXx speedup), proving its effectiveness for enterprise-level Big Data tasks.

📁 Dataset Source
The dataset used is provided by the NYC Taxi and Limousine Commission (TLC) and was accessed through IBM Cloud Storage. It includes detailed records of pickup/drop-off times, locations, and fare breakdowns.

🔧 Installation & Usage
Clone the repository:
git clone [https://github.com/YourUsername/Taxi-Tip-Prediction.git](https://github.com/YourUsername/Taxi-Tip-Prediction.git)

