# EEG Signal Classification Project

This repository contains the final project for my degree, which focuses on classifying EEG signals. The project includes two Jupyter notebooks, each dedicated to a different classification task using EEG data.

## Files

### 1. Mental State Classification
This notebook focuses on classifying EEG signals to determine the mental state of individuals, such as whether they are relaxed, focused, or distracted. It uses EEG data from healthy volunteers with various mental conditions (e.g., eyes open vs. eyes closed) and applies machine learning models to classify the mental state based on the EEG patterns. Key steps include:

- Data preprocessing (artifact removal, normalization)
- Feature extraction
- Training and evaluation of classification models
- Performance metrics for model evaluation

### 2. Epilepsy Classification
This notebook is designed to classify EEG signals for epilepsy diagnosis. It involves EEG data from patients with epilepsy and healthy individuals, distinguishing between seizure activity, non-seizure periods, and healthy brain activity. The key steps in this notebook include:

- EEG signal preprocessing (removal of artifacts, filtering)
- Segmentation of EEG data (seizure vs. non-seizure)
- Applying machine learning models to classify seizure activity
- Evaluation and comparison of model performance

## Usage

Each notebook provides step-by-step instructions for running the classification models. Simply open the notebook and follow the workflow for data preprocessing, feature extraction, and model training.

## Requirements

The project requires Python 3.x and the following libraries:
- NumPy
- Pandas
- Scikit-learn
- MNE (for EEG data handling)
- Matplotlib
- TensorFlow (if using deep learning models)


## License

This project is licensed under the MIT License.
