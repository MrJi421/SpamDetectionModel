# SpamDetectionModel

# Spam Classification Model

This project involves building a machine learning model to classify spam and non-spam (ham) messages. The dataset consists of text messages labeled as either spam (1) or non-spam (0). The goal is to train a model that can accurately predict whether a given message is spam or not.

## Libraries Used

- **os**: Operating system interface for file handling.
- **re**: Regular expression operations for string manipulation.
- **numpy**: Library for numerical computations.
- **pandas**: Data manipulation and analysis library.
- **matplotlib**: Data visualization library.
- **seaborn**: Data visualization library built on top of Matplotlib.
- **scikit-learn**: Machine learning library for building predictive models.
- **joblib**: Library for saving and loading models.
- **PIL**: Python Imaging Library for image processing.
- **pytesseract**: Optical Character Recognition (OCR) tool for reading text from images.

## Data Loading and Exploration

- The data is loaded from a CSV file named `combined_data.csv`.
- The dataset contains two columns: `label` (spam or not spam) and `text` (message content).
- Basic exploratory data analysis is performed to understand the data distribution.

## Data Preprocessing

- Null values and duplicate records are checked and handled accordingly.
- The text data is converted into numerical features using Count Vectorization.
- The dataset is split into training and testing sets.

## Model Building and Training

- Several classification algorithms are considered, including Naive Bayes, Logistic Regression, Support Vector Machines, Decision Trees, and Random Forest.
- Cross-validation is performed to select the best-performing model based on accuracy.
- The selected model is then trained on the training data.

## Model Evaluation

- The trained model is evaluated on both the training and testing datasets.
- Performance metrics such as accuracy, confusion matrix, and classification report are computed.
- The model is saved for future use.

## Usage

1. Ensure all necessary libraries are installed (can be installed via pip).
2. Load the dataset using pandas and preprocess the data as shown in the code.
3. Build and train the model using the provided algorithms.
4. Evaluate the model's performance and fine-tune as necessary.
5. Save the trained model for later use.
6. Use the saved model to make predictions on new data.

## Example Usage

- An example of loading the saved model and making predictions on new messages is provided in the code.
- Input text messages are transformed using Count Vectorization before being fed into the model.
- Predictions are made on whether the messages are spam or not.

## Contributors

- [Your Name]

## License

This project is licensed under the [MIT License](LICENSE).



THE DATA IS TAKEN FROM THE KAGGLE.COM TO TRAIN THE MODEL AND IT HAS BEEN STORED IN THE DRIVE.
THE DRIVE LINK: [https://drive.google.com/file/d/1D_tl-v8jySxvdnkP7GS0Phr6ulpImJ5k/view?usp=drive_link](url)
