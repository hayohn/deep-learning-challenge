# Alphabet Soup Funding Prediction

## Overview:
Alphabet Soup is a charitable organization that provides funding to various causes. To optimize their funding decisions, they want to predict which funding applications are likely to be successful. This project utilizes deep learning techniques to create a predictive model that can help Alphabet Soup identify successful funding applications.

## Table of Contents:
- [Technologies Used](#technologies-used)
- [Data Preprocessing](#data-preprocessing)
- [Model Building](#model-building)
- [Model Evaluation](#model-evaluation)
- [Files in Repository](#files-in-repository)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Technologies Used:
- Python
- TensorFlow
- Scikit-learn
- Pandas
- MAtplotlib
- Google Colab

## Data Preprocessing:
- **Target Variable(s):** IS_SUCCESSFUL (Binary variable indicating funding success)
- **Feature Variable(s):** Various features such as APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, etc.
- **Data Cleaning:** Removed irrelevant columns like EIN and NAME. Handled categorical variables using one-hot encoding.
- **Data Splitting:** Split the data into training and testing sets.

## Model Building:
- Built a deep neural network using TensorFlow's Keras API.
- Defined the model architecture, including the number of layers, neurons, and activation functions.
- Compiled the model using appropriate loss function, optimizer, and evaluation metric.

## Model Evaluation:
- Trained the model on the training data.
- Evaluated the model's performance on the testing data using accuracy and loss metrics.
- Fine-tuned the model to improve performance.

## Files in Repository:
- `Alphabet_Soup_Funding.ipynb`: Jupyter Notebook containing the project code and analysis.
- `charity_data.csv`: Dataset containing Alphabet Soup's funding application data.
- `README.md`: This file, providing an overview of the project.
- Word File for the written analyis including graphs generated in the code.
Figure 1: APPLICATION_TYPE Value Counts After Binning
Figure 2: Distribution of the Target Variable "IS_SUCCESSFUL" in the Training Set
Figure 3: Top 10 Most Common Application Types
Figure 4: Correlation Heatmap of Feature Variables



## Getting Started:
To run the project locally, follow these steps:
1. Clone this repository to your local machine using `git clone`.
2. Install the required dependencies listed in the `requirements.txt` file using `pip install -r requirements.txt`.
3. Open and run the `Alphabet_Soup_Funding.ipynb` notebook in Jupyter Notebook or any compatible environment. this was created in googgle colab.

## Usage:
Feel free to use or modify the code provided here for your own projects. If you use this project as a reference or find it helpful, consider giving it a star on GitHub.

## Contributing:
Contributions to this project are welcome! If you have any suggestions, improvements, or new features to add, please open an issue or create a pull request.
