# Atmanirbhar Bharat: Local Vocalist

## THEME
**Atmanirbhar Bharat: Local Vocalist**

## REASON TO PICK THIS THEME
The COVID-19 pandemic significantly impacted businesses and sales across the country. In response, the Government of India has introduced new regulations aimed at revitalizing the economy. We are interested in analyzing public opinion on the Atmanirbhar Bharat Scheme to understand whether people support this initiative. In this repository, we collect tweets regarding the Atmanirbhar Bharat Scheme.

## INTRODUCTION
The term **Atmanirbhar Bharat** translates to "Self-Reliant India." Launched by the Central Government, the **Atmanirbhar Bharat Abhiyan** (Self-Reliant India Mission) includes a stimulus package of ₹20 lakh crores. In his address, the Prime Minister emphasized that to fulfill the vision of making the 21st century India’s century, it is essential for the country to become self-reliant. The slogan **"Local for Global"** conveys that local products should have a global appeal and reach.

## STEPS INVOLVED
1. **Data Collection**
   - We extract tweets using the **snscrape** library.
   
2. **Data Cleaning**
   - Prepare raw text for Natural Language Processing (NLP) through various cleaning techniques, including:
     - Removing emojis
     - Removing URLs and hashtags
     - Removing stopwords and punctuation
     - Performing word tokenization
   
3. **Sentiment Analysis**
   - Analyze the sentiment of the cleaned tweets to determine if the sentiments are positive, negative, or neutral using the **TextBlob** library.

4. **Topic Modeling**
   - Utilize unsupervised machine learning techniques to identify patterns and clusters within the documents.

### Tools and Libraries
- **Data Extraction:** [snscrape](https://github.com/JustAnotherArchivist/snscrape)
- **Sentiment Analysis:** [TextBlob](https://textblob.readthedocs.io/en/dev/)
- **NLP Libraries:** [NLTK](https://www.nltk.org/), [spaCy](https://spacy.io/)

## DATA EXTRACTION
We use the **snscrape** library to extract tweets related to:
- Atmanirbhar Bharat
- Vocal For Local
- Atmanirbhar Bharat Abhiyan

### Installation
```bash
pip3 install snscrape

