## Real-Time Data Processing and Display using Python
This project implements a real-time data processing and display system using Python. It focuses on processing raw Ethernet data, applying machine learning algorithms, and visualizing results dynamically.
Project Overview

## Features

Real-time processing of raw Ethernet data
Feature extraction and preprocessing
Application of various machine learning algorithms
Dynamic visualization of processed data and accuracy metrics
Interactive development using Jupyter Notebook

## Technologies Used

Python
Pandas
NumPy
Matplotlib
Scikit-learn
Socket
IPython.display
Plotly
PySerial
Seaborn

## Machine Learning Algorithms Implemented

SDGC Classifier (Stochastic Gradient Descent Classifier)
Random Forest Classifier
Passive Aggressive Classifier
Perceptron Classifier
Naïve Bayes Classifier
SVM Classifier (Support Vector Machine)

## Installation
1. Clone the repository
```bash
git clone https://github.com/yourusername/real-time-data-processing.git
cd real-time-data-processing
pip install -r requirements.txt
Usage
```

## Start the server:
python server.py

## Run the client in a Jupyter Notebook:
jupyter notebook client.ipynb

## Execute the cells in the notebook to process data and visualize results.

Project Structure

server.py: TCP server for generating raw Ethernet data packets
client.ipynb: Jupyter Notebook for data processing and visualization
requirements.txt: List of Python dependencies
README.md: Project documentation (this file)

## Results
The project outputs real-time graphs for different machine learning algorithms, showcasing their performance over time.
Contributing
Contributions to improve the project are welcome. Please feel free to fork the repository and submit pull requests.
License
MIT License
Acknowledgments
Special thanks to the Python community and the developers of the libraries used in this project.
