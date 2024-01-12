# APM_project_group8
## Project Description
This is the course project of Advanced Process Mining at TU/e. The goal of this project is to predict the outcome of a loan application (whether successful or not) after the offer is sent. The prediction is based on event features up until offer sent and trace attributes including applicaiton type and loan goal. The project is based on the BPI Challenge 2017. The project is implemented in Python.

## Group Members
- Liliia Aliakberova
- You Xu
- Li, Yi-Chiau

## Logs
The event log of this project is based on the BPI Challenge 2017. The log is preprocessed and can be found in the following link.

Download the logs from the following link and put them in the folder `data`:
https://we.tl/t-9m35raQtKm

## Requirements
- Python 3.9 with the following packages:
    - pm4py
    - pandas
    - sklearn
    - matplotlib
    - numpy
    - Graphviz
    - seaborn
 
## Setup Instructions

### Verify Python Version:
Ensure that you have Python 3.9 installed on your system. You can check your Python version by running the following command in your terminal or command prompt:

`bash
python --version`

### Install Required Dependencies:
Make sure you have the necessary dependencies installed. Run the following commands to install them:

`pip install pm4py pandas scikit-learn matplotlib numpy graphviz seaborn`

### Verify Jupyter Notebook Installation:
Ensure that Jupyter Notebook is installed on your machine. You can check by running:

`jupyter notebook --version`

If not installed, you can install it using:

`pip install notebook`

### Download Data:
Obtain the necessary log files (OA_events.xes and end_A_event_log.xes) and place them in the appropriate directory. To download the log files, please refer to the [Logs](#logs) section.

### Run Jupyter Notebooks:
Open a terminal or command prompt, navigate to the directory containing the Jupyter notebooks (exploration_final.ipynb and encoding_prediction_final.ipynb), and run the following commands:

 `jupyter notebook exploration_final.ipynb`

 After completing the exploration, run:

 `jupyter notebook encoding_prediction_final.ipynb`

This will launch Jupyter Notebook in your web browser, allowing you to execute each cell in the notebook sequentially.

### Follow Notebook Instructions:
Inside the Jupyter notebooks, follow the instructions for data exploration, preprocessing, modeling, and evaluation. Execute each cell in order to progress through the analysis steps.
