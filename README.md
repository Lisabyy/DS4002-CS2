# README

## Yelp Text Review Sentiment Analysis Case Study



### Section 1: Hook and Rubric Documents
The hook document outlining the case study is the file labeled [CS3Hook_SentimentAnalysis.pdf](/CS3Hook_SentimentAnalysis.pdf). 
The rubric [CS3Rubric_SentimentAnalysis.pdf](/CS3Rubric_SentimentAnalysis.pdf) outlines the formatting and required content in your final submission. Utilize the rubric as guide for your final submission to be successful.

### Section 2: Map of the Documentation
```
Project_Folder/
│
├── Materials/
│   └── CS2_SentimentAnalysis_GuidingCode.ipynb                            # Juypter Notebook containing reference code for EDA, sentiment analysis and NB model
|   └── Cleaned Dataset for Reference.csv                                  # Dataset of Yelp reviews for LA restaurants (cleaned; used a reference/guide)
|   └── Naive Bayes classifier tutorial: With Python Scikit-Learn          # Website to assist with Predictive Model
|   └── Performing Sentiment Analysis With Naive Bayes Classifier          # Website to assist with Performing Sentiment Analysis
|
│CS3Hook_SentimentAnalysis.pdf             # PDF giving you a bried overview of the instructions and premise for the case study
│

│CS3Rubric_SentimentAnalysis.pdf           # PDF rubric that gives detailed information about required content and formatting
│
└── README.md                # This file
```

### Section 3: Instructions for Producing the Results
1. **Set up environment**:
   - Install Python 3.12.6.
   - Install necessary packages using pip:
     ```
     pip install pandas numpy matplotlib seaborn scikit-learn nltk wordcloud
     ```
   
2. **Download dataset**:
   - The dataset that you will be using for this case study can be found at the following link. The Materials folder contains references to help throughout the project process.

3. **Compute EDA and Run the Model**:
   - Open `sentiment_analysis.ipynb` in Google Colab or Jupyter (for your own reference). 
   - Run all cells to preprocess the data, compute VADER sentiment scores, and build the Naive Bayes model.
   
### Section 4: References
[1]Yelp, “Yelp - Company - Fast Facts,” www.yelp-press.com. https://www.yelp-press.com/company/fast-facts/default.aspx

[2]H. Dhaduk, “Performing Sentiment Analysis With Naive Bayes Classifier!,” Analytics
Vidhya, Jul. 13, 2021.
https://www.analyticsvidhya.com/blog/2021/07/performing-sentiment-analysis-with-naive-bayes
-classifier/

[3]]A. A. Awan and A. Navlani, “Naive Bayes classifier tutorial: With Python Scikit-Learn,”
DataCamp, https://www.datacamp.com/tutorial/naive-bayes-scikit-learn (accessed Sep. 16,
2024)

[4]] H. Dhaduk, “Performing Sentiment Analysis With Naive Bayes Classifier!,” Analytics
Vidhya, Jul. 13, 2021.
https://www.analyticsvidhya.com/blog/2021/07/performing-sentiment-analysis-with-naive-bayes
-classifier/
