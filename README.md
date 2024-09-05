# Air Quality Index Prediction

## Introduction

Air quality significantly impacts public health and the environment, making it crucial to monitor and predict air quality indices accurately. This project leverages machine learning models to classify and predict air quality indices based on various environmental parameters, aiming to provide timely insights into pollution levels.

## Project Description

This project focuses on predicting air quality indices using a variety of machine learning algorithms. The models are trained on a dataset containing air quality measurements and pollutant data, allowing the system to classify air quality into different categories or predict numerical values of air quality indices.

## Problem Statement

Air pollution is a growing concern worldwide, with severe implications for health and climate. Traditional methods of measuring and predicting air quality indices are often costly and time-consuming. Therefore, there is a need for automated, data-driven solutions that can accurately predict air quality indices based on available environmental data.

## Objectives

- Develop a machine learning-based system to classify and predict air quality indices.
- Utilize a diverse dataset with various air quality measurements to train and evaluate the models.
- Extract meaningful features from the dataset to facilitate effective classification and prediction.
- Evaluate the performance of different machine learning models to identify the best approach for air quality index prediction.
- Provide an easy-to-use solution that can be deployed to monitor air quality indices in real-time.

## Dataset Description

The dataset used in this project comprises various environmental parameters and pollutant measurements. It includes data points such as the concentration of harmful gases, meteorological factors, and other relevant features. The data is collected from multiple sensors and monitoring stations, providing a comprehensive view of the air quality in different locations.

### Key Features

- **PM2.5 and PM10**: Particulate matter levels that directly impact the air quality index.
- **NO2, SO2, CO, O3**: Concentrations of nitrogen dioxide, sulfur dioxide, carbon monoxide, and ozone.
- **Temperature**: Ambient temperature, which can influence pollutant dispersion.
- **Humidity**: Relative humidity, affecting the formation of certain pollutants.
- **Wind Speed**: Wind conditions that affect the movement of pollutants.
- **Pressure**: Atmospheric pressure, which can influence air quality levels.
- **Season**: Seasonal variations impacting pollution levels.

## Data Preprocessing and Feature Extraction

The dataset undergoes preprocessing, including cleaning, handling missing values, and feature extraction, to ensure the models receive the most relevant data. The features extracted are crucial for distinguishing between different air quality levels and predicting numerical indices.

## Model Training and Evaluation

Various machine learning models are employed to classify air quality into categories and predict numerical air quality indices. The models are evaluated based on accuracy, precision, recall, and other relevant metrics.

| Model              | Type            | Accuracy |
|--------------------|-----------------|----------|
| Decision Tree      | Classification  | 94.50%   |
| Random Forest      | Classification  | 96.17%   |
| Linear Regression  | Regression      | 73.25%   |
| Random Forest      | Regression      | 94.19%   |

## Further Scope

- **Real-Time Monitoring**: Integrate the models with real-time data streams to provide up-to-date air quality index assessments.
- **Geographical Expansion**: Expand the dataset to include data from different regions, improving the model's generalization.
- **Advanced Feature Engineering**: Incorporate more advanced features like traffic density, industrial activity, and vegetation indices for enhanced accuracy.
- **Integration with IoT**: Utilize IoT devices for live data collection and predictions, enhancing real-time decision-making.
- **Mobile Application**: Develop a mobile app that provides air quality index alerts and insights to users based on their location.

## Getting Started

To get started with the project, clone the repository and install the required dependencies. Run the Jupyter notebooks provided to preprocess data, train the models, and evaluate their performance.

1. Clone the repository:

   ```bash
   git clone https://github.com/PriyanshuLathi/Air-Quality-Index-Prediction
   ```

2. Navigate to the project directory:

   ```bash
   cd air-quality-index-prediction
   ```

3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Run the Jupyter Notebooks:

   ```bash
   jupyter notebook air_quality_regression_main.ipynb
   ```

## License
This project is licensed under the MIT License - see the [LICENSE](https://github.com/PriyanshuLathi/Air-Quality-Index-Prediction/blob/main/LICENSE) file for details.

## Contact

For questions or feedback, feel free to reach out:

- LinkedIn: [Priyanshu Lathi](https://www.linkedin.com/in/priyanshu-lathi)
- GitHub: [Priyanshu Lathi](https://github.com/PriyanshuLathi)

## Authors
- Priyanshu Lathi
