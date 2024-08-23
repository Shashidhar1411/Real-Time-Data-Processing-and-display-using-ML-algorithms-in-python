# Real-Time Data Processing and Display using Python

This project implements a real-time data processing and display system using Python. It focuses on processing raw Ethernet data, applying machine learning algorithms, and visualizing results dynamically.

## Features

- Real-time processing of raw Ethernet data
- Feature extraction and preprocessing
- Application of various machine learning algorithms
- Dynamic visualization of processed data and accuracy metrics
- Interactive development using Jupyter Notebook

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Socket Programming
- IPython.display
- Plotly
- PySerial
- Seaborn

## Machine Learning Algorithms Implemented

1. SDGC Classifier (Stochastic Gradient Descent Classifier)
2. Random Forest Classifier
3. Passive Aggressive Classifier
4. Perceptron Classifier
5. Naïve Bayes Classifier
6. SVM Classifier (Support Vector Machine)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/real-time-data-processing.git
   cd real-time-data-processing

2.Create a virtual environment (optional but recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```
3.Install the required packages:
```bash
pip install -r requirements.txt
```


4.Usage

5.Start the server:
```bash
python server.py
```

6.Run the client in a Jupyter Notebook:
```bash
jupyter notebook client.ipynb
```

## Execute the cells in the notebook to process data and visualize results.

## Project Structure

server.py: TCP server for generating raw Ethernet data packets
client.ipynb: Jupyter Notebook for data processing and visualization
requirements.txt: List of Python dependencies
README.md: Project documentation 

## Results
The project outputs real-time graphs for different machine learning algorithms, showcasing their performance over time.
Contributing

## Fork the repository
Create your feature branch (git checkout -b feature/AmazingFeature)
Commit your changes (git commit -m 'Add some AmazingFeature')
Push to the branch (git push origin feature/AmazingFeature)
Open a Pull Request

## License
Distributed under the MIT License. See LICENSE for more information.
Acknowledgments

## Python community for their extensive libraries
## Scikit-learn developers for machine learning tools
## Matplotlib and Plotly teams for visualization capabilities
