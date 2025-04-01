# Credit-Card-fraud-detection
This script builds a fraud detection model using machine learning. It loads fraudTest.csv, preprocesses data (handles missing values, encodes categorical features, scales numerical data), splits it into training/testing sets, and trains a RandomForestClassifier. It then evaluates performance using accuracy and a classification report.

Load the Dataset

Reads the fraudTest.csv file into a Pandas DataFrame.

Data Preprocessing

Handles missing values by filling them with the median.

Encodes categorical variables using LabelEncoder.

Feature & Target Separation

Splits the dataset into features (X) and target (y), assuming is_fraud is the target column.

Train-Test Split

Splits the dataset into training (80%) and testing (20%) subsets.

Feature Scaling

Uses StandardScaler to normalize the features.

Model Training

Uses RandomForestClassifier with 100 trees.

Trains the model on the training dataset.

Model Evaluation

Predicts fraud labels on the test set.

Evaluates performance using accuracy score and a classification report.
