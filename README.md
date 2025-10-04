 Airways Customer Booking Prediction

This Jupyter notebook analyzes customer booking data for an airline and builds a machine learning model to predict whether a booking will be completed based on various features.

Description

The notebook performs the following tasks:
- Loads and explores the customer booking dataset (`customer_booking.csv`)
- Visualizes booking patterns based on sales channel, trip type, and flight day
- Preprocesses the data by encoding categorical variables and scaling numerical features
- Handles class imbalance using random oversampling
- Trains a Random Forest Classifier to predict booking completion
- Evaluates the model performance with accuracy and classification report
- Performs cross-validation
- Saves the trained model as `airline_booking_model.pkl`

Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- imbalanced-learn
- joblib

Installation

Install the required packages using pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn joblib
```

Usage

1. Ensure the `customer_booking.csv` file is in the same directory as the notebook.
2. Open the `airways.ipynb` notebook in Jupyter Lab or Jupyter Notebook.
3. Run the cells in order to execute the analysis and model training.
4. The trained model will be saved as `airline_booking_model.pkl` for future use.

Dataset

The analysis uses the `customer_booking.csv` dataset, which contains customer booking information including features like purchase lead time, length of stay, flight details, and booking origin.

Model

The notebook trains a Random Forest Classifier to predict booking completion (binary classification). The model achieves an accuracy score and provides a detailed classification report.

License

This project is for educational purposes. Please refer to the dataset source for any licensing information.
