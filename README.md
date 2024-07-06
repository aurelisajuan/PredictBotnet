# PredictBotnet

PredictBotnet is a project aimed at analyzing network traffic patterns to predict potential cyber-attacks, specifically botnets. This project leverages existing datasets containing historical network traffic and attack logs to identify patterns and anomalies associated with cyber threats, helping in early detection and prevention. We use data science techniques to model and train the datasets, ensuring accurate and efficient prediction of botnet attacks.

## Table of Contents

- [Project Overview](#project-overview)
- [Datasets](#datasets)
- [Installation](#installation)
- [Data Preparation](#data-preparation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Model Development](#model-development)
- [Evaluation](#evaluation)
- [Visualization](#visualization)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Project Overview

The main goal of this project is to build a robust and efficient model that can predict botnet attacks based on network traffic data. The project includes data cleaning, exploratory data analysis (EDA), feature engineering, model training, and evaluation.

## Datasets

We use publicly available datasets from Kaggle for network malware detection and connection analysis. The primary dataset used is:

- [Network Malware Detection & Connection Analysis](https://www.kaggle.com/datasets/agungpambudi/network-malware-detection-connection-analysis/versions/1?select=CTU-IoT-Malware-Capture-1-1conn.log.labeled.csv)

## Installation

To get started with the project, clone the repository and install the necessary dependencies.

### Prerequisites

- Python 3.7 or higher
- Jupyter Notebook
- Git

### Clone the Repository

```bash
git clone https://github.com/aurelisajuan/PredictBotnet.git
cd PredictBotnet
```

### Installed Required Libraries

```bash
pip install -r requirements.txt
```

### Data Preparation & Exploratory Data Analysis

Data preparation involves loading, cleaning, and transforming data to be suitable for analysis:

- 1. **Data Loading and Cleaning**: Load the data from the CSV file, handle missing values, and correct any inconsistencies in the data format.
- 2. **Feature Engineering**: Implement one-hot encoding for categorical data and normalize continuous features to enhance model performance.

Perform exploratory data analysis to understand the underlying patterns and distributions in the data, including:

- Statistical summaries
- Correlation analysis
- Visualizations of data distributions and relationships

### Model Development

Develop the model using the following steps:

- Model Selection: Choose suitable models based on the nature of the data and the problem. For this project, we use Random Forest and K-means clustering.
- Training: Train the model on the prepared dataset.
- Hyperparameter Tuning: Optimize model parameters to improve performance.

### Evaluation 

Evaluate the model's performance using various metrics:

- Accuracy
- Confusion Matrix
- ROC Curves

### Visualization

Visualize the results and insights from the model:

- Feature importance charts
- Cluster visualizations
- Performance metrics visualizations

### Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your proposed changes.

### License

This project is licensed under the MIT License - see the LICENSE file for details.

### Acknowledgements & Soruces

Credits to the authors of the datasets used in this project and the community contributors on Kaggle and GitHub who provided valuable insights and code examples.

### Presentation

For a detailed walkthrough of our project, refer to our presentation:
- [View PredictBotnet Presentation PDF](https://www.canva.com/design/DAGJYnUY8kI/qYSKUti5MHV20biZoQgkng/edit?utm_content=DAGJYnUY8kI&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)

Watch our detailed presentation video here:
- [View PredictBotnet Presentation Video](https://www.canva.com/design/DAGJYnUY8kI/qYSKUti5MHV20biZoQgkng/edit?utm_content=DAGJYnUY8kI&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)

Feel free to contact us with any questions or feedback:

- Hong Le: hongle622@gmail.com
- Aurelisa Sindhunirmala: aurelisa.sindhu@gmail.com
