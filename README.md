# Movie-Review-Sentiment-Analysis
This repository contains the code and resources for a text sentiment classification project. The goal is to predict whether movie reviews are positive or negative in sentiment based on their textual content. The project involves data preprocessing, feature extraction using CountVectorizer, and training various Naive Bayes classifiers.

🚀 **Project Breakdown**:

1. **Data Cleaning and Preparation**: Leveraging Python's pandas library, I meticulously preprocessed the data. I removed HTML tags, special characters, and converted text to lowercase. Eliminating stopwords using nltk and applying stemming ensured clean and standardized text.

2. **Feature Extraction**: Employing scikit-learn's CountVectorizer, I converted cleaned text into a numerical format suitable for machine learning. This facilitated building a bag-of-words model with a vocabulary of the most frequent 1000 words.

3. **Model Training**: I experimented with three Naive Bayes classifiers – Gaussian, Multinomial, and Bernoulli. These classifiers were trained on a meticulously prepared training dataset and evaluated on a separate test dataset.

4. **Results and Insights**: The Multinomial Naive Bayes model emerged as the frontrunner with an impressive accuracy score of 81.2% on the test data. 

5. **Application to New Data**: I further assessed the Multinomial Naive Bayes model's performance on a new dataset, generating insightful sentiment predictions.


The experience of working on this project has solidified my belief in the transformative potential of data-driven insights and algorithms. I look forward to continuing my journey as a data enthusiast, leveraging these skills in real-world applications.


Feel free to tailor this post to your internship experience and personal style. Good luck!
