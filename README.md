# Automatic Vowel Detection using Decision Trees

This repository contains the source code, dataset, and final academic paper for the project **"Vowels detection using Decision Trees"**. The system evaluates acoustic resilience in adverse environments, simulating Search and Rescue (SAR) scenarios using Mel-Frequency Cepstral Coefficients (MFCCs), dynamic data augmentation, and Decision Tree classifiers.

## Repository Structure

* `Notebook 1.ipynb`: Contains the Jupyter Notebook used for dynamic feature extraction (MFCCs, Deltas, Delta-Deltas), data augmentation, and model training.
* `Audios/ & Example_Environmental_Noise/`: Contains the original audio recordings (clean Spanish vowels) and some of the environmental noise samples used for dynamic SNR injection.
* `Vowels detection using Decision Trees.pdf`: Contains the final PDF report with the complete methodology, theoretical background, and Out-of-Distribution (OOD) validation.
* `README.md`: Project documentation.

## Technologies & Libraries

This project was built using **Python 3**. The data pipeline and machine learning models rely on the following libraries:

**Audio & Data Processing:**
* `librosa`: Core audio processing, time stretching, pitch shifting, and mathematical MFCC extraction.
* `soundfile`: Reading and writing audio arrays.
* `numpy` & `pandas`: Data structuring, arrays, and mathematical operations.
* `matplotlib.pyplot`: Data visualization and plotting acoustic signatures.

**Machine Learning (`scikit-learn`):**
* `DecisionTreeClassifier`: Main classification algorithm utilizing Gini Impurity.
* `GridSearchCV`: Hyperparameter tuning and structural limits.
* `StandardScaler`: Feature scaling and normalization.
* `train_test_split` & `accuracy_score`: Dataset partitioning and empirical evaluation.

*(Note: Standard built-in Python libraries such as `os`, `re`, and `random` were also utilized for directory management and stochastic processes).*

## Requirements
To install the necessary libraries, run:
`pip install librosa soundfile numpy pandas matplotlib scikit-learn`

## Author
* **Miguel Roca** - Universidad CEU San Pablo, Montepríncipe
