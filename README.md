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
│   └── Cleaned Dataset for Reference.csv           # Dataset of Yelp reviews for LA restaurants (cleaned; used a reference/guide)
│   └── Guiding Code for Case Study.ipynb          # Juypter Notebook containing reference code for EDA, sentiment analysis and NB model
├── Hook/
│   └──  CS3Hook_SentimentAnalysis.pdf             # PDF giving you a bried overview of the instructions and premise for the case study
│
├── Rubric/
│   └──  CS3Rubric_SentimentAnalysis.pdf           # PDF rubric that gives detailed information about required content and formatting
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

3. **Compute EDA**:
   - Open `sentiment_analysis.ipynb` in Google Colab or Jupyter. (for reference)
   - Run all cells to preprocess the data, compute VADER sentiment scores, and build the Naive Bayes model.
   
### Section 4: References
