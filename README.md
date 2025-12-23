# 📌 NLP-Detection-of-Fake-News
The aim of the project is to develop a machine learning model that can accurately detect fake news. The model will be integrated into the Chrome plug-in and will provide users with real-time feedback on the veracity of the news they are reading.
##### *NOTE: These analyses are for educational purposes only. It is clear that the proposed analyses are too limited on a specific data set that only contains news on certain topics*
---

## 📂 Repository Structure
```
E-commerce-sales-analysis/
│── data/
      ├── Fake
      ├── True
│── images/
      ├── Insights on fake news
      ├── Training model
│── python/
      │──NLP_Detection of Fake News.ipynb
      |──NLP_Detection of Fake News.py
│── README.md
```

## 🎯 Project objectives


##### 1. The main objective of the project is to develop a machine learning model capable of accurately identifying fake news.
##### The secondary objectives will be:
##### 2. Data analysis
      a) Is fake news more common in certain categories?
      b) Are there topics more commonly associated with fake news?
      c) Do fake news headlines follow recurring patterns?
##### 3. Training model
    a) Which combination of NLP and machine learning techniques leads to the best model?
##### 4. Model evaluation
    a) What types of performance metrics should be used to evaluate the model's efficiency?

##### 5. Exporting the model to pickle
---

## 🗂️ Dataset
**Source:** Profession AI - Master in Data Analytics
**Period examined:** from 2015 to 2018  
**Dimension of dataset:** Fake Dataset: 23481 news and True Dataset: 21417 news

### 📌 Key variables
| Variables | Description |
|----------|-------------|
| Title | News title |
| Text  | News text |
| Subject| News category |
| Date | Date of news|
---

## 🧹 Data Cleaning
Key operations performed:
- Handling missing values
- Format correction (dates format)
- Data preprocessing (e.g. Remove punctuation, remove stopwords, tokenizzation, vectorizzation)
---

## 📊 Methodology:
- Used techniques (N-gram, NER, Logistic Regression, Multilayer Perceptron)
- Main libraries (Pandas,Sklearn,Spacy,Matplotlib,Seaborn,Gensim)

---

## 🔍 Key results
- **Insight 1**: The categories of news with the most fake news concern ‘News’, “Politics” and ‘Left-news’ [Box chart](https://github.com/VincenzoPaternoster/NLP-Detection-of-Fake-News/blob/main/images/Insights%20on%20fake%20news/MostFakeCategories.png)
- **Insight 2**: The topics with the highest number of fake news stories are ‘Donald Trump’, ‘Hilary Clinton’, ‘White House’ and ‘United States’, in line with the period (from 2015 to 2018) in which the news was collected, i.e. pre, during and post US elections [Box chart](https://github.com/VincenzoPaternoster/NLP-Detection-of-Fake-News/blob/main/images/Insights%20on%20fake%20news/MostUsedTopics.png) and [Word cloud](https://github.com/VincenzoPaternoster/NLP-Detection-of-Fake-News/blob/main/images/Insights%20on%20fake%20news/WordCloud.png)
- **Insight 3**: News headlines have recognisable and repetitive patterns that include the use of names of people (PERSON), organisations (ORG) and nationalities/political groups (NORP). In fact, the main elements contained in fake news headlines are “Donald Trump”, “President Trump”, “Hilary Clinton”, “White House” and “Fox News” [Box chart](https://github.com/VincenzoPaternoster/NLP-Detection-of-Fake-News/blob/main/images/Insights%20on%20fake%20news/MostFrequentBi.png) and [Box chart with NER entities](https://github.com/VincenzoPaternoster/NLP-Detection-of-Fake-News/blob/main/images/Insights%20on%20fake%20news/NER_MostHead.png)
- **Insight 4**: Finally, two models (Logistic regression and Multi Perceptron, MLP) were trained and tested with the aim of creating a browser plug-in capable of filtering fake news. The analyses and results showed that the MLP model was better able to predict fake news than the Logistic regression model [Comparison between models](https://github.com/VincenzoPaternoster/NLP-Detection-of-Fake-News/blob/main/images/Training%20model/CombinedConfusion.png)


---

## 🧠 Conclusions
##### In this project I learned how to use spacy, gensim and sklearn in order to execute operations of natural language processing
##### mixed with machine learning tecniques such as logistic regression and multilayer perceptron (MLP).
---

## 🛠️ Tools
- Python (pandas,matplotlib,seaborn,sklearn,gensim)
- Google Colab
- Obsidian

---

## 📬 Contacts

- **Vincenzo Paternoster**
- Email: vincenzopaternoster99@gmail.com
- LinkedIn: www.linkedin.com/in/vincenzo-paternoster
