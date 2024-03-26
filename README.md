Files
main.py: Main script for user interaction and crop prediction.

train_model.py: Script for training the machine learning model.

model.pkl: Pre-trained machine learning model.

predicted_values.csv: CSV file containing predicted values.

Contributing
If you'd like to contribute to the project, feel free to open an issue or submit a pull request

Methodology
Data Preparation:

The system uses historical weather data, city-specific information, and soil type characteristics. Outliers are removed from the dataset for better model training.

Machine Learning Model:

The machine learning model is trained using the train_model.py script. It employs a Gaussian Naive Bayes classifier and is saved as model.pkl.

Prediction Process:

The main.py script interacts with the user, takes input for city, soil type, and other parameters. It then loads the pre-trained model (model.pkl) and predicts the recommended crop based on the input.
