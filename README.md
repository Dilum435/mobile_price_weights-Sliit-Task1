Mobile Price Classification using ANN 📱
This project was developed to help a new mobile company in Sri Lanka, founded by Nimal, to estimate the price range of mobile phones based on their technical specifications. By analyzing historical sales data, this Artificial Neural Network (ANN) model identifies relationships between features like RAM, battery power, and internal memory to classify phones into two categories: High Price (1) and Low Price (0).

📋 Project Requirements
Data Processing: Split the dataset into 75% training and 25% testing data.

Architecture:

Input Layer: Based on feature count (20 attributes).

Hidden Layer 1: 8 neurons (ReLU activation).

Hidden Layer 2: 4 neurons (ReLU activation).

Output Layer: 1 neuron (Sigmoid activation for binary classification).

Training: 100 Epochs with a batch size of 32.

Saving: Export model weights as an .h5 file for future deployment.

🚀 Technologies Used
Python

TensorFlow / Keras (Deep Learning)

Pandas (Data Manipulation)

Scikit-learn (Data Splitting & Scaling)

🛠️ Installation & Usage
Clone this repository:

Bash

git clone https://github.com/your-username/mobile-price-classification.git
Install dependencies:

Bash

pip install tensorflow pandas scikit-learn
Run the notebook or script to train the model and generate the mobile_price_weights.h5 file.

📊 Results
The model was trained for 100 epochs. By implementing Feature Scaling (StandardScaler), the model overcomes the disparity between large values (Battery) and small values (Clock Speed), leading to a significant increase in classification accurac
