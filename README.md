# Semi-Parametric-Survival-Analysis-Cox-Proportional-Hazards-Model-for-Unemployment-Duration-Analysis

This project focuses on the implementation of the Cox Proportional Hazards Model, a semi-parametric statistical technique used for survival analysis. The Cox model is employed to investigate the association between the duration of unemployment spells and various predictor variables, such as age, unemployment insurance benefits, and wage levels.

Project Description
The project involves loading a dataset containing information about unemployment spells, demographic characteristics, and economic indicators. It performs data preprocessing steps, including data type conversions, and then proceeds to fit the Cox Proportional Hazards Model using the lifelines library in Python. The model summary is printed, and the baseline survival function is plotted for visual analysis.

Getting Started
To run this project, you'll need Python 3 and the following libraries installed:

pandas
numpy
matplotlib
lifelines
You can install the required libraries using pip:


Copy code
pip install pandas numpy matplotlib lifelines
Usage
Clone the repository or download the project files.
Navigate to the project directory.
Run the Python script containing the code.
The script will load the dataset, preprocess the data, fit the Cox Proportional Hazards Model, and display the model summary and the baseline survival function plot.

Dataset
The dataset used in this project is assumed to be available locally in the project directory, named Survival~Unemployment~Duration.csv.

Contributing
Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

License
This project is licensed under the MIT License.

Acknowledgments
The lifelines library for survival analysis in Python.
The dataset used in this project
