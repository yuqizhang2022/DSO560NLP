# DSO560NLP
This is Group Violet's final NLP project

**Step1: Data Selection & Data Preprocessing (Part1).ipynb**
- Select reviews for UK hotel and within a year from hotel dataset
- Change positive and negative reviews to lowercase
- Regularize all urls, hashtags, numbers, emails, emojis, and currency symbols
- Remove all punctuations

**Step2: Data Pre-processing (Part2) & TF-IDF and Topic Modeling.ipynb**
- Lemmatize tokens in positive and negative reviews 
- Remove stopwords
- Regex grouping, including further handling by comparing common words with 20k most commonly used English words
- TF-IDF
- Topic Modeling 


**Step3: Modeling - Random Forest**
- Combine positive and negative reviews into a new column
- Data Encoding
- Train/Test Dataset Split
- Vectorization
- RandomForestClassifier
- Important Features
