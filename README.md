# Data Science Research Project
# Research Title: Prediction of Sentiments of Online Product Reviews
In this research work Amazon unlocked mobile phone product reviews dataset has been used, which consists of 4,13,840 reviews and is publicly available online. Reviews play an important part in understanding customers demand. In order to analyze these reviews, supervised machine learning algorithms are suitable.
This research work proposed a comparison between four of the most well-accepted supervised learning classification algorithms like Naïve Bayes, Logistic Regression, Support Vector Machines, and Random Forest. Model evaluation was performed using accuracy, precision, recall, and F1-Score. Experiment findings show that the Random Forest was the most suitable algorithm for this sentiment analysis and achieved the highest accuracy of 97.33%.

Firstly, experiment was performed on the imbalance dataset (P = 284496, N = 96954 reviews) and second, experiment was performed on balanced dataset (P = 96954, N = 96954 reviews). The Balanced dataset was obtained by undersampling. For labeling the sentiments into positive and negative reviews, a rating feature was used. Ratings with 4 & 5 were considered as positive reviews and 1 & 2 ratings were considered as negative reviews.

Overall, the accuracy, precision, recall, and F1-score were calculated for the best fit model. As for the CountVectorizer technique was concerned, the model with the highest accuracy was the RF model in both imbalance and the balanced dataset and achieved accuracy between 95.51% and 97.33%. It can be also seen that the accuracy for the RF model with CountVectorizer technique on the imbalanced dataset with train/test split and cross validation was 97.33% and 97.27% respectively. The difference between the two accuracies was very less. Similar results can be observed on the balanced dataset as well. RF model with CountVectorizer technique on the balanced dataset with train/test split and cross validation was 95.59% and 95.51% respectively. The RF model outperformed all models when used with the CountVectorizer technique.

# About Data:
This dataset consist of 400 thousand reviews of unlocked mobile phones sold on Amazon.com. The dataset has 4,13,840 reviews (rows) and 6 attributes (columns). The
proposed technique for sentiment analysis was based on English reviews. Pandas python library was used to read review CSV file of size 125mb.

# Data Source:
https://www.kaggle.com/datasets/PromptCloudHQ/amazon-reviews-unlocked-mobile-phones
