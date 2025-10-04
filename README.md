##  SENTIMENT-ANALYSIS

## Objective
To build a machine learning model that can classify tweets as *positive* or *negative* using NLP techniques.

##  Project Workflow
1. *Data Loading* – Used a public tweet sentiment dataset
2. *Data Preprocessing* – Cleaned the text, removed stopwords, stemming
3. *Feature Extraction* – TF-IDF Vectorization
4. *Modeling* – Trained a Logistic Regression classifier
5. *Evaluation* – Accuracy score, classification report, and confusion matrix
6. *Insights* – Most impactful words for each sentiment class

##  Files in this Repository
| File                             | Description                            |
|----------------------------------|--------------------------------------- | 
| Sentiment_Analysis.ipynb         | Main notebook with all code and output |
| Sentiment_Analysis.pdf           | Exported notebook for viewing          |
| README.md                        | Project summary                        |


##  Results
- *Model Used*: Logistic Regression
- *Accuracy Achieved*: ~90% (varies with train/test split)
- *Top Positive Words*: love, happi, best, etc.
- *Top Negative Words*: hate, worst, sad, etc.
