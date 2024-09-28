# Fish Species Exploratory Data Analysis and Predictive Model

## Description
This project explores a dataset of fish species, their heights, weights, and the weight-to-height ratio. Through data analysis and machine learning techniques, a predictive model was developed to identify fish species based on their physical attributes.

## Dataset
The dataset used for this analysis can be found at the following link: [Fish Species Sampling Weight and Height Data](https://www.kaggle.com/datasets/taweilo/fish-species-sampling-weight-and-height-data/data).

## Objective
The primary objective of this project is to uncover patterns and trends within the dataset and to build a machine learning model that can predict the species of fish based on their physical characteristics, including weight, height, and weight-to-height ratio.

## Technologies Used
- **NumPy**: For numerical computations.
- **Pandas**: For data manipulation and analysis.
- **Scikit-learn**: For implementing machine learning algorithms.
- **Decision Trees**: As the predictive modeling technique.
- **Grid Search CV**: For tuning hyperparameters to optimize model performance.

## Results
Here are some notable findings from the analysis:

### Predictive Equations for Fish Species:
- **Species: Anabas testudineus**: Weight = 0.03 * Length + 2.99
- **Species: Coilia dussumieri**: Weight = 0.02 * Length + 2.30
- **Species: Otolithoides biauritus**: Weight = 0.04 * Length + 2.55
- **Species: Otolithoides pama**: Weight = 0.02 * Length + 3.43
- **Species: Pethia conchonius**: Weight = 0.02 * Length + 4.43
- **Species: Polynemus paradiseus**: Weight = 0.00 * Length + 3.93
- **Species: Puntius lateristriga**: Weight = 0.02 * Length + 2.43
- **Species: Setipinna taty**: Weight = 0.04 * Length + 2.46
- **Species: Sillaginopsis panijus**: Weight = 0.03 * Length + 5.13

### Notable Species:
- **Lengthiest Species**: Sillaginopsis panijus - 31.06 m
- **Heaviest Species**: Sillaginopsis panijus - 6.180 kg

### Model Performance:
- **Test Accuracy with Best Parameters**: 0.94
- **Highest Weight-to-Length Ratio**: Pethia conchonius - 0.4857

## Conclusion
This exploratory data analysis and predictive modeling project demonstrates the ability to analyze biological data and make predictions based on physical characteristics. The insights gained could be beneficial for further research and understanding of fish species.

