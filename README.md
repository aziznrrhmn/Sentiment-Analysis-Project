# Sentiment Analysis of GoPay Application Review from Google Play Store

## Preface
This is my first end-to-end data science project. It is about Sentiment Analysis which implements Natural Language Processing (NLP) Technique in Text Processing and Vectorization. In this case, I used GoPay application review data which was scraped from Google Play Store. 

## Aim of The Project:
Objective:
- Obtain Insight of general rating and sentimen for the application.
- Understand pattern of sentiment each month from launching to present.
- Investigate why reviewers give either positive or negative sentiment in the last three months.
- Create Machine Learning Model to classify sentiment.

Data was scraped from google play store with google-play-scraper from launching (April) until November, 22 2023. It is only in Indonesian text. The data is obtained as 24,909 rows.

## Content
Flow of the step is involved:
- Data cleaning (handling missing value and duplicated data)
- Data Labelling ( Labelling score into two classification: Positive and Negative Sentiment)
- Data Transformation (Transform column into month)
- Text Processing (Case Folding, Tokenization, Replace Slang and Word Elongation, Stemmization, Remove Irrelevant Words Manually) with applying NLP technique
- Recheck Data Condition

There are some model to compare: K-NN, Logistic Regression, Decision Tree, Random Forest, and Naive Bayes with various treatment (Cross validation, Hyperparameter Tuning, and Oversampling)

## Result
Conclusion:

Overall, sentiment for GoPay is superb (positive sentiment is much greater than negative one in general and based on each month). Several GoPay users love the application because of easiness in transaction and providing free transfer to any bank. Some users dislike the application due to failure in upgrading Gopay Plus, Rejection of requesting Gopay Pinjam, and the problem of deducted balance. The best machine learning model according this project is Logistic Regression with Precison : 95.67% and ROC-AUC : 86.77%. Other metric: Recall : 88.06%, F1 Score : 91.71%, Accuracy : 87.51. 

Recommendation for action: 

- Enhance monitoring system to detect potential bug or technical issue related to failure of upgrading Gopay plus and the problem of deducted balance when transaction is not delivered to recipient well.
- Give specific message clearly why ti is failed to upgrade gopay plus to users.
- Create shortcut information about the cause of gopay pinjam activation is rejected on the menu 'activate pinjam
- Create live chat in working hour on the application to respond user complaint swiftly.
- Build Chatbot to answer frequently ask of users than only list question and answer on the application.
- Provide informatian and tips about finance on the application.
- Create feature such as e-wallet management or e-wallet planning. This can help users divide their money expenditure based on their needs. Thus, this feature can enhance user retention because of versality of the application.

## Note
This is feedback from my mentor : To define or find out what the topic in both the sentiment positive or negative, you can explore about 'Topic Modelling' method to extract topic of sentiment if using N-grams did not answer your objective.

## Closing
For further insight, you are allowed to read mine on the link.

There is no perfection in the world. Therfore, It is pleasure to receive positive feedback from the expert.

Thank You :)
