# IBM Data Science Capstone Project - SpaceX

## Introduction
Welcome to the IBM Data Science Capstone Project. In this project, we aim to predict whether the Falcon 9 first stage will successfully land. SpaceX offers Falcon 9 rocket launches at a cost of $62 million, significantly lower than the $165 million charged by other providers. This cost-saving is largely due to SpaceX's ability to reuse the first stage. Accurately predicting the first stage's landing success will help determine the launch cost more precisely. This information is valuable for companies that wish to compete with SpaceX in the rocket launch market.

This capstone project provides a realistic experience of what data scientists encounter in the field, working with real datasets. You will assume the role of a Data Scientist at a startup aiming to compete with SpaceX, following the Data Science methodology involving [data collection](https://github.com/chuksoo/IBM-Data-Science-Capstone-SpaceX/blob/main/Data%20Collection%20API.ipynb), [data wrangling](https://github.com/chuksoo/IBM-Data-Science-Capstone-SpaceX/blob/main/Data%20Wrangling.ipynb), [exploratory data analysis](https://github.com/chuksoo/IBM-Data-Science-Capstone-SpaceX/blob/main/EDA%20with%20SQL.ipynb), [data visualization](https://github.com/chuksoo/IBM-Data-Science-Capstone-SpaceX/blob/main/EDA%20with%20Data%20Visualization.ipynb), [model development](https://github.com/chuksoo/IBM-Data-Science-Capstone-SpaceX/blob/main/Machine%20Learning%20Prediction.ipynb), [model evaluation](https://github.com/chuksoo/IBM-Data-Science-Capstone-SpaceX/blob/main/Machine%20Learning%20Prediction.ipynb), and [reporting](https://github.com/chuksoo/IBM-Data-Science-Capstone-SpaceX/blob/main/Winning%20Space%20Race%20with%20Data%20Science.pdf) your results to stakeholders.

## Business Problem
SpaceX advertises Falcon 9 rocket launches on its website at a cost of $62 million, while other providers charge upwards of $165 million per launch. Much of this savings comes from SpaceX's ability to reuse the first stage of the rocket. If we can accurately predict the likelihood of the first stage landing successfully, we can better estimate the launch cost. Your Data Science models and findings will enable the startup to make more informed bids against SpaceX for rocket launches.

## Objective
- To apply data science tools and machine learning techniques to accurately predict the likelihood of the first stage rocket landing successfully.
- To explore the data and gain deeper insights.

## Business Metric
**Classification Accuracy** - The ratio of correct predictions to the total number of predictions, defined as:
$$Accuracy = \frac{TP+TN}{TP+FP+TN+FN}$$

![Confusion Matrix](https://github.com/chuksoo/IBM-Data-Science-Capstone-SpaceX/blob/main/Plots/Confusion%20matrix.PNG)

## Deliverables
- Accurate predictive algorithms.
- A comprehensive business case report for stakeholders.

## Project Structure
- **Data Collection:** [Data Collection API Notebook](https://github.com/Fridoom14/Space-X-Falcon-9-First-Stage-Landing-Success/blob/main/1.%20Data%20Collection%20and%20Data%20Wrangling/jupyter-labs-spacex-data-collection-api.ipynb)
- **Data Wrangling:** [Data Wrangling Notebook](https://https://github.com/Fridoom14/Space-X-Falcon-9-First-Stage-Landing-Success/blob/main/1.%20Data%20Collection%20and%20Data%20Wrangling/labs-jupyter-spacex-Data%20wrangling.ipynb)
- **Exploratory Data Analysis:** [EDA with SQL Notebook](https://github.com/Fridoom14/Space-X-Falcon-9-First-Stage-Landing-Success/blob/main/2.%20Exploratory%20Data%20Analysis/jupyter-labs-eda-sql-coursera_sqllite.ipynb) | [EDA with Data Visualization Notebook](https://github.com/Fridoom14/Space-X-Falcon-9-First-Stage-Landing-Success/blob/main/2.%20Exploratory%20Data%20Analysis/edadataviz.ipynb)
- **Model Development and Evaluation:** [Machine Learning Prediction Notebook](https://github.com/Fridoom14/Space-X-Falcon-9-First-Stage-Landing-Success/blob/main/4.%20Machine%20Learnng/SpaceX_Machine%20Learning%20Prediction_Part_5.ipynb)
- **Reporting:** [Winning Space Race with Data Science](https://github.com/Fridoom14/Space-X-Falcon-9-First-Stage-Landing-Success/blob/main/5.%20Final%20Presentation/DS-Capstone-Presentation%20by%20Fridoom.pdf)

## How to Use This Repository
1. **Clone the repository:**
   ```bash
   git clone https://github.com/chuksoo/IBM-Data-Science-Capstone-SpaceX.git
   cd IBM-Data-Science-Capstone-SpaceX

2. **Install necessary packages::**
   Ensure you have Python and Jupyter Notebook installed. Then, install the required libraries:
   ````bash
   pip install -r requirements.txt
  
3. **Run Jupyter Notebooks:**
   Open Jupyter Notebook and run through each notebook in the specified order to reproduce the analysis.

4. **Follow the Documentation:**
   Each notebook contains detailed documentation and comments to guide you through the steps of the analysis.

## Conclusion
By following this capstone project, you will gain hands-on experience in data science, working with real-world data to solve a meaningful problem. The predictive models developed in this project will help a startup company compete with SpaceX by providing accurate predictions of the Falcon 9 rocket's first stage landing success. This will enable better-informed bidding and cost estimations for rocket launches.

Feel free to contribute to this project by submitting issues or pull requests. Happy coding!

