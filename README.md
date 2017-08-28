### BKHardenstein_Portfolio
Data Science projects for Brian Hardenstein

All projects used models from SciKit-Learn unless otherwise noted. Data manipulation was performed using Numpy/Pandas unless otherwise indicated. Cross validation was utilized in all cases.

### Case Studies During Bootcamp:

Ride Sharing App Churn Prediction
* Tools used: logistic regression, confusion matrices, profit curves (LTV vs CAC), ROC
* Summary: Prioritized optimizing recall instead of accuracy as downsides of incorrect predictions had the biggest impact

Event Planning Fraud Detection
* Tools used: gradient boosting classifier, recall optmized, serialized model, confusion matrices, ROC, flask website, AWS EC2
* Summary: In two days built a web dashboard that showed events that had the highest predicted fraud as well as cost (downside) to the company to help client staff use their anti-fraud time more effectively

Classify Phone Apps Based on Text Descriptions (1hr assessment)
* tfidf vectorizer, NLP, Multinomial Naive Bayes Classifier
* For a 1hr test used sklearn's tfidfvectorizer with basic stop words to get a sparse matrix which was then fed into a MultinomialNB classifier. 92% mean accuracy (of 5 runs)

### Individual Case Studies:

[Indie Game Recommender (Capstone Project)](https://github.com/Brionnic/Indie-Game-Recommender/blob/master/README.md)
* Tools used: BeautifulSoup, Selenium, AWS EC2/S3, MongoDB, EDA, Spark/PySpark, Spark MLLib NMF ALS explicit/implicit, rating weighting system, model serialization, capstone presentation
* Summary: Scraped 3M web pages in 5+ rounds of iteration, wrangled data with MongoDB workflow, ultimately predicted using ~10M rows of data, switched from explicit ratings to implicit ratings (log10 playtime) which ended up improving predictions quite a bit, presented capstone project to audience > 50. Serialized model for flask website but have not yet implemented front end. 

[Home Price Prediction: Ames, IA (work in progress)](https://github.com/Brionnic/sturdy-umbrella/blob/master/README.md)
* Tools used: Selenium scraping/munging, EDA, stacked ensemble, feature engineering, model experimentation, kaggle-like project, PostGreSQL
* Summary: Inspired by a meetup presentation implemented home price regressor using Ames, Iowa dataset. Scraped additional data from Story County Assessor website (Ames’ county) to create new features and SQL to manipulate/store data.

DeepTraffic Neural Network (work in progress)

