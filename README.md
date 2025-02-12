# Stock Price Prediction Using LSTM

## Project Description
This project aims to predict stock prices using a **Long Short-Term Memory (LSTM)** neural network. Given historical stock price data, the model learns patterns and trends to provide future price predictions. LSTMs, a type of recurrent neural network (RNN), are particularly well-suited for time-series forecasting due to their ability to capture long-term dependencies in sequential data.

## Model Architecture
The model is designed as follows:
- **Input Layer**: A sequence of past stock prices as input features.
- **LSTM Layers**: Two stacked LSTM layers to extract temporal dependencies.
- **Dropout Layers**: To prevent overfitting and improve generalization.
- **Dense Layer**: A fully connected layer to output the final predicted stock price.

### Why LSTM?
- LSTM can remember past patterns and dependencies over long sequences.
- Unlike traditional RNNs, LSTMs overcome the vanishing gradient problem, making them more effective for time-series data.
- Works well for financial data, where past trends significantly impact future stock movements.

## Achievements
- Successfully trained an LSTM-based model for stock price prediction.
- Achieved a **low Mean Squared Error (MSE)** on test data, indicating good prediction accuracy.
- Visualized both **training and validation MSE** (also the 'loss' metric, which is the same as mse in this case) to monitor performance.
- Plotted **actual vs. predicted prices**, showing a close approximation of stock trends.

## Visualization
- **Model Architecture:** Displays the LSTM model structure.

![model_architecture](https://github.com/user-attachments/assets/6ed72325-118e-4267-9dcb-537b1027773a)
  
- **Loss Curve:** Plots training and validation loss across epochs.

  ![loss_function](https://github.com/user-attachments/assets/fc96e68c-9f97-42a9-8359-9c5e137c75d5)

- **Prediction Graph:** Compares actual vs. predicted stock prices.

  ![predicted_price_vs_actual_price](https://github.com/user-attachments/assets/ea072ee7-4597-432e-bce5-70e58c8eb12d)
