# Automatic Vowel Detection using Decision Trees 

This repository contains the source code, dataset, and final academic paper for the project **"Vowels detection using Decision Trees"**. The system evaluates acoustic resilience in adverse environments, simulating Search and Rescue (SAR) scenarios using Mel-Frequency Cepstral Coefficients (MFCCs), dynamic data augmentation, and Decision Tree classifiers.

## Repository Structure

* `src/`: Contains the Python scripts / Jupyter Notebooks used for dynamic feature extraction (MFCCs, Deltas, Delta-Deltas) and model training.
* `dataset/`: Contains the original audio recordings (clean Spanish vowels) and the environmental noise samples used for dynamic SNR injection.
* `paper/`: Contains the final PDF report with the complete methodology, theoretical background, and Out-of-Distribution (OOD) validation.
* `README.md`: Project documentation.

## Technologies Used

* **Python 3.x**
* **scikit-learn:** Implementation of the Decision Tree classifier and hyperparameter tuning (Gini Impurity, pre-pruning).
* **librosa:** Core audio processing, time stretching, pitch shifting, and mathematical MFCC extraction.
* **numpy / pandas:** Data structuring and mathematical operations.

## How to Run

1. Clone this repository to your local machine:
```bash
   git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
