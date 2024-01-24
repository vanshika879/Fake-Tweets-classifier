# Fake-Tweets-classifier
# Objective 
The objective of a Fake Tweets Classifier project is to develop a system that can automatically distinguish between genuine and fake tweets on social media platforms. 
 
 # Data Preparation and Cleaning:
 
Imported necessary libraries like NumPy, Pandas, and NLTK. Loaded the fake tweets dataset using Pandas and dropped unnecessary columns. Renamed columns for clarity. Encoded the target labels using LabelEncoder. Checked for missing values and duplicates, and handled them appropriately.

# Exploratory Data Analysis (EDA):

Visualized the class distribution of fake and real tweets using a pie chart. Calculated and analyzed statistics about the number of characters, words, and sentences in messages. Plotted histograms and pair plots to compare features between fake and real tweets. Created a heatmap to visualize correlations between different numerical features.

# Text Preprocessing:

Performed various text preprocessing steps, including lowercasing, tokenization, removing special characters, stopwords, and punctuation. Applied stemming using the Porter Stemmer algorithm to reduce words to their root form. Visualized word clouds for both spam and ham messages to highlight the most frequent words in each category. Created bar plots to display the most common words in both Fake and real tweets.

# Model Building - CountVectorizer:

Utilized the CountVectorizer to convert text data into a numerical format suitable for modeling. Split the dataset into training and testing sets. Built and evaluated three Naive Bayes classifiers (GaussianNB, MultinomialNB, BernoulliNB) using accuracy, confusion matrix, and precision score.

# Model Building - TfidfVectorizer:

Used the TfidfVectorizer to create a feature matrix with TF-IDF weighted values. Split the dataset into training and testing sets again. Repeated the process of building and evaluating the three Naive Bayes classifiers using accuracy, confusion matrix, and precision score.

# Multiple Model Experimentation:

Experimented with a variety of classifiers including K-Nearest Neighbors, Multinomial Naive Bayes, Decision Tree, Logistic Regression, Random Forest. Trained and evaluated each classifier on the TfidfVectorizer-transformed data. Plotted a bar chart to visualize the accuracy and precision scores of each classifier.

# Results:

Naive Bayes and KNN performed well in terms of both accuracy and precision.
