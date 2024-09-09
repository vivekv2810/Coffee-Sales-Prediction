# Coffee Sales Prediction

This project aims to predict coffee sales using different machine learning models: Support Vector Machine (SVM) Regression, Long Short-Term Memory (LSTM) neural network, Support Vector Machine (SVM) Classification, and K-Means Clustering.

## Dataset

The dataset used for this project includes various features such as:
- `cash_type`: Type of payment (card, cash, etc.)
- `coffee_name`: The name of the coffee purchased.
- `money`: The amount of money spent.
- Date and time features extracted from the transaction date and time.

## Project Structure

- **EDA (Exploratory Data Analysis):** Understand the dataset, visualize key patterns, and identify potential features for modeling.
- **Data Preprocessing:** Convert date-time data, encode categorical variables, and normalize numerical data.
- **Modeling:** Apply the following models:
  - **Support Vector Machine (SVM) Regression:** Predict the `money` spent based on input features.
  - **Long Short-Term Memory (LSTM):** Time series forecasting model to predict `money` spent.
  - **Support Vector Machine (SVM) Classification:** Classify types of coffee or other categorical targets.
  - **K-Means Clustering:** Cluster data into groups based on similarity.

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/your-repo/coffee-sales-prediction.git
    ```

2. Install dependencies:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

1. **Data Preprocessing:**
   - Load the dataset and preprocess it by encoding categorical features and normalizing the data.

2. **Model Training:**
   - Train each model with the preprocessed data.
   - Evaluate models using appropriate metrics (MSE for regression, accuracy for classification).

3. **Prediction:**
   - Use the trained models to predict on new or test data.

4. **Visualization:**
   - Visualize the clustering results or the model's prediction performance.

## Results

- **SVM Regression:** Predicts the amount spent (`money`) with a certain Mean Squared Error.
- **LSTM:** Forecasts future sales with a time series approach.
- **SVM Classification:** Classifies different types of coffee sales.
- **K-Means Clustering:** Groups data points into clusters based on similarity.

## Conclusion

This project demonstrates how different machine learning techniques can be applied to sales prediction tasks, providing insights and improving decision-making processes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
"""
