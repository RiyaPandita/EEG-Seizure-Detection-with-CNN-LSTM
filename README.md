# EEG Seizure Detection with CNN-LSTM

This project implements a deep learning pipeline for epileptic seizure detection using EEG data. It covers data preprocessing, feature engineering, exploratory analysis, and a hybrid CNN-LSTM model for classification.

---

## About the Project

This project aims to build a robust model for detecting epileptic seizures from EEG signals. The key features of this project are:

-   **Data Preprocessing:** Cleaning and preparing EEG data for feature extraction.
-   **Feature Engineering:** Extracting meaningful features from the EEG signals.
-   **Hybrid Model:** Utilizing a combination of Convolutional Neural Networks (CNNs) and Long Short-Term Memory (LSTM) networks to capture both spatial and temporal patterns in the EEG data.
-   **Evaluation:** Assessing the model's performance using various metrics like classification reports and confusion matrices.

---

## Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

Make sure you have Python and the following libraries installed:

-   `tensorflow`
-   `keras`
-   `keras-cv`
-   `scikit-learn`
-   `scipy`
-   `mne`
-   `pandas`
-   `numpy`
-   `matplotlib`
-   `seaborn`
-   `ipywidgets`
-   `pymupdf`
-   `python-docx`

### Installation

1.  Clone the repo:
    ```sh
    git clone [https://github.com/your_username/your_project_name.git](https://github.com/your_username/your_project_name.git)
    ```
2.  Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

---

## Usage

1.  Open the `EEG Seizure Detection.ipynb` notebook in a Jupyter environment.
2.  Make sure the dataset is available in the specified path.
3.  Run the cells sequentially to see the data preprocessing, model training, and evaluation steps.

The notebook will guide you through:
1.  **Environment Setup:** Installing necessary packages.
2.  **Data Loading and Preprocessing:** Loading the dataset and preparing it for the model.
3.  **Model Training:** Training the CNN-LSTM model on the preprocessed data.
4.  **Evaluation:** Evaluating the model's performance on the test set.

---

## Model Architecture

The model used in this project is a hybrid CNN-LSTM network.

-   **CNN Layers:** The convolutional layers are used to extract spatial features from the EEG signals.
-   **LSTM Layers:** The recurrent layers (LSTM) are used to learn the temporal dependencies in the EEG data.

This combination allows the model to effectively learn the complex patterns associated with epileptic seizures.

---

## Results

The model's performance is evaluated using the following metrics:

-   **Classification Report:** Provides precision, recall, and F1-score for each class (Seizure and Non-Seizure).
-   **Confusion Matrix:** Visualizes the number of correct and incorrect predictions for each class.

The notebook includes visualizations of the results to help in understanding the model's performance.

---

## Dependencies

-   **TensorFlow:** 2.18.0
-   **Keras:** 3.5.0
-   **KerasCV:** 0.9.0

---


