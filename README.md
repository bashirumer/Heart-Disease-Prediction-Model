# Heart Disease Prediction Model

This repository contains the code and dataset used for building a machine learning model to predict heart disease status based on various quantifiable variables.

## Project Overview

Cardiovascular diseases (CVDs) are the leading cause of death globally, accounting for an estimated 17.9 million lives each year. Early detection and management are crucial for individuals at high risk of cardiovascular diseases. This project aims to leverage data science techniques to predict heart disease using a dataset containing several cardiovascular metrics.

## Dataset

The dataset used in this project is a structured collection of data points concerning individual cardiovascular health metrics. It includes the following attributes:

- **Age**: Age of the individual in years.
- **Sex**: Sex of the individual (0 = Male, 1 = Female).
- **Chest Pain Type**: Type of chest pain experienced (1 = ATA, 2 = NAP, 3 = ASY, 4 = TA).
- **Resting Blood Pressure**: Resting blood pressure (mm Hg).
- **Cholesterol**: Serum cholesterol (mm/dl).
- **Fasting Blood Sugar**: Fasting blood sugar level (1 if fasting blood sugar > 120 mg/dl, 0 otherwise).
- **Resting ECG**: Resting electrocardiogram results.
- **Maximum Heart Rate Achieved**: Max heart rate during the test.
- **Exercise-Induced Angina**: Exercise-induced chest pain (Y = yes, N = no).
- **Oldpeak**: ST depression induced by exercise relative to rest.
- **ST Slope**: Slope of the peak exercise ST segment.
- **Heart Disease**: Heart disease status (1 = disease, 0 = normal).

The data is split into training and test sets, with 75% of the data used for training the models.

## Tools and Libraries

The project utilizes R for data analysis, with the following libraries:
- `tidyverse` for data manipulation and visualization.
- `tidymodels` for building and evaluating the machine learning models.

## Model Building

The prediction model uses the k-nearest neighbors (KNN) algorithm. The model training includes preprocessing steps such as scaling and centering of predictor variables.

## Usage

1. Clone the repository:
git clone [repository-url]

2. Open the R project and run the script `model_training.R`.

## Results

The model's accuracy and other metrics are evaluated using the test data. Further details are documented in the analysis script.

## Contribution

Contributions to this project are welcome. You can suggest improvements or additional features by opening an issue or submitting a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
