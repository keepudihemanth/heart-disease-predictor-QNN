# heart-disease-predictor-QNN
Using Quantum Neural Network 
Heart Disease Predictor using Quantum Neural Networks (QNN)
📌 Overview

The Heart Disease Predictor is an AI-powered model that leverages Quantum Neural Networks (QNN) to predict the likelihood of a person having heart disease.
The model outputs 1 if the patient is predicted to have heart disease, and 0 if not.

This project combines classical machine learning preprocessing with quantum computing techniques to explore the potential of quantum algorithms in solving real-world classification problems in healthcare.
🎯 Objective

The main goal of this project is to:

    Analyze medical data related to cardiovascular health.

    Train a QNN model to classify patients into "Heart Disease" or "No Heart Disease".

    Compare quantum-based prediction performance with classical approaches.

    Demonstrate a hybrid classical-quantum workflow.

🔍 How It Works

    Dataset – The system uses medical attributes such as age, gender, blood pressure, cholesterol levels, maximum heart rate, etc., from a heart disease dataset (e.g., UCI Heart Disease Dataset).

    Preprocessing – Data is normalized and encoded for compatibility with quantum circuits.

    Quantum Model – A Quantum Neural Network (QNN) is built using frameworks like Qiskit Machine Learning or PennyLane.

    Training – A hybrid optimizer is used to train the QNN using classical optimizers and quantum circuits.

    Prediction – The trained QNN predicts:

        1 → Patient likely has heart disease.

        0 → Patient likely does not have heart disease.

    Evaluation – Accuracy, precision, recall, and other metrics are calculated to assess performance.

🛠 Features

    Binary classification: Predicts presence or absence of heart disease.

    Hybrid AI approach: Combines classical preprocessing with quantum machine learning.

    Scalable model: Can be adapted to other medical diagnostic tasks.

    Quantum ready: Runs on both real quantum hardware and simulators.

🚀 Technologies Used

    Python

    Qiskit Machine Learning / PennyLane

    NumPy, Pandas, Matplotlib for data handling and visualization

    scikit-learn for preprocessing and performance metrics

📊 Example Output
| Patient ID | Prediction |
|------------|------------|
| 001        | 0          |
| 002        | 1          |
| 003        | 0          |


Where:

    0 → No heart disease predicted.

    1 → Heart disease predicted.

📢 Disclaimer

This project is for educational and research purposes only and should not be used as a substitute for professional medical diagnosis.

If you want, I can also write you a shorter, one-paragraph README summary that’s concise enough for GitHub.
Do you want me to make that?
