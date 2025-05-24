# 🚗 Vehicle Price Prediction using TensorFlow

## 📄 Description
This project focuses on predicting vehicle prices using a regression model built with TensorFlow and Keras. The model uses features such as vehicle age, mileage, ratings, condition, fuel economy, top speed, horsepower, torque, and more to estimate the current price of a vehicle.

## 📊 Dataset
The dataset used (`train.csv`) contains the following columns:

- `v.id`
- `on road old`
- `on road now`
- `years`
- `km`
- `rating`
- `condition`
- `economy`
- `top speed`
- `hp`
- `torque`
- `current price`

## 🧠 Model
The regression model is implemented using TensorFlow/Keras with the following components:

- **Normalization Layer**: For feature scaling
- **Dense Layers**: For learning the regression mapping
- **Loss Functions**:
  - Mean Squared Error (MSE)
  - Huber Loss
  - Mean Absolute Error (MAE)
- **Optimizer**: Adam
- **Evaluation Metric**: Root Mean Squared Error (RMSE)

## 📈 Visualizations
- **Seaborn Pairplot**: To explore feature correlations
- **Matplotlib Graphs**: To visualize training performance

## 🛠️ Installation


