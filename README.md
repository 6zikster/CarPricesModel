# Model predicting car prices.

This is a Jupyter Notebook where I developed a model to predict car prices. Below is an overview of the steps and processes involved in the project.

1) Data Collection:

    The notebook begins with parsing data from a local website.

    The parsed data is then saved for further processing.

2) Data Preparation:

    The collected data is loaded into a Pandas DataFrame.

    Missing values in the dataset are handled.

    Categorical data is transformed into numerical format using get_dummies (one-hot encoding).

3) Model Training:

    A Random Forest Regressor is trained on the processed dataset.

    Model performance is evaluated using Mean Absolute Error (MAE).

4) Model Saving:

    The trained model is saved for future use or deployment.