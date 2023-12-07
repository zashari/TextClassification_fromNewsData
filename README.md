# Web Scrapping and Text Classification

### Introduction

As part of the Mid Exam Project of college, I embarked on an ambitious endeavor involving web scraping and text classification. The objective was to harness the power of Python programming and its libraries to extract and analyze textual data from various online news sources.

### Background

#### Web Scraping
The web scraping phase of the project was executed using Python, primarily utilizing libraries such as `requests` for fetching web pages, `BeautifulSoup` for parsing HTML content, and `pandas` for data manipulation. This phase involved:

- **Extracting News Articles**: Scraping news articles from various Indonesian news websites such as CNN Indonesia, CNBC Indonesia, Kompas Indonesia, Suara Edukasi, Folkative, and BINUS News.
- **Data Extraction**: Retrieving key information from each article, including the title, text, media source, and category.
- **Data Storage**: Compiling the extracted data into a coherent dataset and saving it as a CSV file for further analysis.

#### Text Classification
The text classification phase focused on processing and classifying the scraped textual data, involving:

- **Data Cleaning**: Implementing text cleaning techniques to remove unnecessary characters and stop words from the text, ensuring data quality for analysis.
- **Feature Engineering**: Employing `TfidfVectorizer` and `Word2Vec` for transforming textual data into numerical formats suitable for machine learning models.
- **Model Training and Evaluation**: Utilizing machine learning algorithms such as Support Vector Machine (SVM) and Random Forest Classifier to classify text data. The models were trained and tested on features extracted from the text, and their performance was evaluated based on accuracy, precision, and recall metrics.

### Project Results

The project yielded significant results in both web scraping and text classification:

1. **Successful Data Extraction**: Successfully scraped and stored a rich dataset comprising various news articles, which formed the backbone for the classification models.

2. **Effective Text Classification**:
    - The SVM model trained on Word2Vec features achieved an accuracy of 75%, with precision and recall at approximately 88.9% and 66.7% respectively.
    - The SVM model using TF-IDF features showed a lower accuracy of 50%, but with a higher precision and recall at 75%.
    - The Random Forest model trained on Word2Vec features displayed a balanced performance with 50% accuracy, precision, and recall.
    - The Random Forest model with TF-IDF features remarkably achieved 100% accuracy, precision, and recall, indicating a potentially overfitted model.

### Conclusion

The project demonstrated the effective application of web scraping techniques to gather relevant data from the internet and the power of machine learning in classifying text data. While the models showed varying levels of performance, they provided valuable insights into the potential of using automated methods for data extraction and analysis. This project not only contributed to my academic growth but also served as a practical application of my programming skills in Python.
