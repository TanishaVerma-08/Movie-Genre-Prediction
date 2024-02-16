# Movie-Genre-Prediction
Import libraries: This code imports necessary libraries for data analysis, feature extraction, model training, and evaluation.
<br>
Load the dataset: Load the movie genre dataset into a Pandas DataFrame.
<br>
Preprocess the data: Fill missing values in the overview column with empty strings.
<br>
Create feature vectors: Use the CountVectorizer to convert the textual overviews into numerical feature vectors. This process removes stop words and counts the occurrences of each word in each overview.
<br>
Separate features and target labels: Separate the feature vectors (X) from the target labels (y), which in this case are the movie genres.
<br>
Split the data: Divide the data into training and test sets using train_test_split. This allows you to train the model on one set and evaluate its performance on unseen data.
<br>
Train the model: Train a Multinomial Naive Bayes classifier using the training features and labels. This model is suitable for text classification tasks.
<br>
