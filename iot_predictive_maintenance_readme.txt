# AI-Powered IoT Predictive Maintenance (AI4I 2020)

## Overview
This project develops a predictive maintenance system for IoT devices using the AI4I 2020 Predictive Maintenance Dataset. It predicts equipment failures based on sensor data (air temperature, process temperature, rotational speed, torque, and tool wear) using a neural network.

## Tools and Technologies
- **Python**: Core programming language
- **TensorFlow**: For building the neural network
- **Pandas/Scikit-learn**: For data preprocessing
- **Matplotlib/Seaborn**: For visualization

## Methodology
1. **Data Preprocessing**: Loaded the AI4I 2020 dataset and selected key features.
2. **Model Training**: Built a neural network with TensorFlow for binary classification (failure vs. no failure).
3. **Evaluation**: Achieved ~90% accuracy on test data.
4. **Visualization**: Plotted training and validation accuracy over epochs.

## Results
- **Test Accuracy**: ~90%
- The plot (`iot_predictive_maintenance_ai4i.png`) shows the model's learning progress.

## How to Run
1. Clone the repository.
2. Install dependencies: `pip install tensorflow pandas scikit-learn matplotlib seaborn`
3. Download the AI4I 2020 dataset from [Kaggle](https://www.kaggle.com/datasets/stephanmatzka/predictive-maintenance-dataset-ai4i-2020).
4. Update the dataset path in the script and run: `python iot_predictive_maintenance_ai4i.py`

## Mockup
![Predictive Maintenance](iot_predictive_maintenance_ai4i.png)