<p align="center">
      <img src="https://i.ibb.co/0tnp8Wy/uber-eats-logo-CA3-BA2098-B-seeklogo-com.png">
</p>

<p align="center">
   <img src="https://img.shields.io/badge/Pandas-lavender" alt="Pandas">
   <img src="https://img.shields.io/badge/NumPy-thistle" alt="NumPy">
   <img src="https://img.shields.io/badge/Matplotlib-lightcyan" alt="Matplotlib">
   <img src="https://img.shields.io/badge/ydata_profiling-lavender" alt="ydata_profiling">
   <img src="https://img.shields.io/badge/TensorBoard-thistle" alt="TensorBoard">
   <img src="https://img.shields.io/badge/MultitaskModel-lightcyan" alt="MultitaskModel">
   <img src="https://img.shields.io/badge/Neural_networks-lavender" alt="Neural networks">
</p>

## Introduction

The project aims to optimize the delivery process and enhance customer experience by predicting the delivery time of orders accurately. The main task involves forecasting whether an order will be delivered early, on time, or with a delay, considering various factors such as delivery distance, type of transport used, and other relevant characteristics.

The context and motivation for the project lie in improving logistics efficiency and providing more precise forecasts to enhance delivery time management.

## Overview

The project deals with data containing information about orders, including delivery distance, order preparation time, transport type, and other parameters. The problem addressed by the project is to predict whether an order will be delivered early, on time, or with a delay.

The data structure includes various variables such as delivery distance, order preparation time, responsible party identifier, geographical coordinates of delivery and order points, and other relevant parameters.

## Goals and Objectives

**Project Goal:**
Optimize the delivery process and improve customer satisfaction by accurately predicting the delivery time of orders.

**Objectives:**
1. Develop a multi-task model for classification and regression tasks.
2. Utilize machine learning techniques to analyze and predict delivery times.
3. Enhance the efficiency of the logistics process.

## Technologies and Tools

The project utilizes the following technologies, libraries, and tools:

- Python
- PyTorch
- pandas
- scikit-learn
- NumPy
- Matplotlib
- TensorBoard

## Dataset
[Click](https://disk.yandex.ru/d/2QUHsV2ce1TiOQ)

## Dataset features description
* direct_delivery `string`: indication if the courier had only one order to deliver or not,
* batched_pickup `string` : indication if the courier had only one order to pickup from vendor or multiple (batch of orders),
* transport_type `string` : courier transport type (i.e automobile, Bicycle, etc ), 
* order_time `Timestamp`: time when the order is placed,
* delivery_distance `int` : the distance between the vendor and the client in meters,
* order_preparation_time `int` : order preparation time in minutes,
* responsible_id `int`: the ID for vendor preparing the order,
* store_latitude `float` : vendor/store location latitude,
* store_longitude `float` :vendor/store location longitude,
* client_latitude `float` :client location latitude,
* client_longitude `float` :client location longitude,
* status `string` (target variable): label for an order if it is delivered late, early or ontime,
* status_time `float` (target variable): label for an order indicating the difference between the expected delivery time and factual delivery time in minutes (note if the absolute difference is between less than 3 min, and order is counted as `ontime` )

## Data Processing

The dataset undergoes initial loading, profiling, and preprocessing steps. This includes handling missing values, sorting by date, dropping unnecessary columns, and addressing outliers.

## Target Variable Transformation

The 'status' column, representing delivery status, is transformed using label encoding for numerical representation, facilitating model training.

## Methodology and Approach

The methodology involves the following steps:

1. Data preprocessing and cleaning.
2. Feature engineering for relevant variables.
3. Model selection and development.
4. Training the multi-task model for classification and regression.
5. Evaluation and fine-tuning.

The chosen approach combines machine learning techniques with deep learning for improved prediction accuracy.

## Model Training

The core model is trained using appropriate loss functions, optimizing parameters to minimize losses for both classification and regression.

## Performance Evaluation

Evaluation metrics, tailored to classification and regression tasks, measure the model's effectiveness, guiding adjustments for improved performance.

## Results Visualization

Visualizations, such as graphs and charts, illustrate key findings and enhance understanding of the model's predictions.

## Conclusion

The project successfully predicts delivery times through a systematic process, combining data analysis, methodology selection, and model development.

## Recommendations

Future improvements may involve exploring additional features, experimenting with diverse model architectures, and collecting more varied data for training.



## Developers

- Kamyshnikov Dmitrii :
      - [GitHub](https://github.com/kama34)
      - [Email](mailto:kamyshnikovdmitri@yandex.ru)
      - [Telegram](https://t.me/+79101663108)

## License
Project kama34.DeliveryTimePrediction is distributed under the MIT license.

## Contact Information

For inquiries or collaboration, contact the project authors:

- [Author 1](mailto:author1@example.com)
- [Author 2](mailto:author2@example.com)
