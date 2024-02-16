# Movie-Genre-Prediction
1. Import libraries: This code imports necessary libraries for data analysis, feature extraction, model training, and evaluation.
<br>

2. Load the dataset: Load the movie genre dataset into a Pandas DataFrame.
<br>

3. Preprocess the data: Fill missing values in the overview column with empty strings.
<br>

4. Create feature vectors: Use the CountVectorizer to convert the textual overviews into numerical feature vectors. This process removes stop words and counts the occurrences of each word in each overview.
<br>

5. Separate features and target labels: Separate the feature vectors (X) from the target labels (y), which in this case are the movie genres.
<br>

6. Split the data: Divide the data into training and test sets using train_test_split. This allows you to train the model on one set and evaluate its performance on unseen data.
<br>

7. Train the model: Train a Multinomial Naive Bayes classifier using the training features and labels. This model is suitable for text classification tasks.
<br>
