How to Run the Code
Preprocessing and Model Training

The statistical_model.py script performs the following steps:

Loads the training and development datasets.
Extracts features using TF-IDF vectorization.
Trains a Linear Regression model on the training data.
Evaluates the model on the development data.
Saves the trained model to the models/ directory.
To run the script, use the following command:

bash
Copy code
python models/statistical_model.py
Model Evaluation

After training, the script evaluates the model's performance on the development set and prints the Mean Squared Error (MSE).

Saving the Model

The trained model is saved as statistical_model.pkl in the models/ directory using joblib.

Additional Information
Ensure that the datasets (train.csv, dev.csv, test.csv) are correctly formatted and placed in the data/ directory before running the script.
The script assumes that the text data is in a column named text and the corresponding emotion intensity is in a column named intensity.
You can modify the statistical_model.py script to try different machine learning algorithms or feature extraction methods.
