# Spotting the Unseen: Identifying Sexism in Twitter Movements

Author: Jerin Easo Thomas  
Date: Spring 2023  
Affiliation: Luddy School of Informatics, Computing and Engineering, Indiana University Bloomington  
Contact: jerithom@iu.edu  

## Introduction

Sexism comments on social media propagate harmful stereotypes and gender-based prejudice, impacting users psychologically and fostering discrimination. This project aims to identify sexism in Twitter movements using machine learning and deep learning approaches. By analyzing sexist speech, we seek to create safer online environments, combat gender-based discrimination, and gain insights into societal prejudices.

## Research Question

This study focuses on two key questions:
1. How reliable and efficient are machine learning methods in spotting sexism in Twitter movements?
2. What are the source intentions behind tweeting sexist comments?

## Methods

Various methodologies were employed in this study:

1. **Valence Aware Dictionary and Sentiment Reasoner (VADER):** Used for sentiment analysis, especially on social media text.
2. **Neural Network:** Deep learning model structured to mimic the human brain's organization.
3. **Robustly Optimized BERT Pretraining Approach (RoBERTa):** Transformer-based neural network architecture pre-trained on a large text corpus.
4. **Pytesseract:** Python library for extracting text from image-based data.
5. **Google Translate API:** Utilized for language translations.

## Data

Data was collected from Twitter movements #MeToo, #8M, and #Time'sUp using the EXIST dataset. The dataset includes tweets in English and Spanish, annotated for sexism. Approximately 7900 rows of data were collected, comprising tweet comments, language, annotators, user details, and labels.

## Analysis

The analysis proceeded in three stages:

1. **Data Gathering and Preprocessing:** Included data analysis, preprocessing, and text normalization techniques.
2. **Model Building and Evaluation:** Utilized VADER for sentiment analysis, neural networks, and RoBERTa for tweet classification.
3. **Tweet Classification and Data Visualization:** Employed models to classify tweets as sexist or non-sexist, analyze source intentions, and visualize the results.

## Results

Key findings from the analysis include:
1. **Distribution of Classified Tweets:** Spanish tweets exhibited higher sexism rates compared to English tweets.
2. **Effectiveness of Image-based Data Classification:** Models effectively distinguished sexist and non-sexist tweets from image-based data.
3. **Source Intention Distribution:** Majority of English tweets showed 'Direct' source intention, while Spanish tweets displayed varied intentions.
4. **Most Often Used Words:** Word clouds revealed specific words more common in sexist tweets, providing insights into language usage.

## Conclusion

The RoBERTa-large model emerged as the most accurate for tweet classification, demonstrating its efficacy in identifying sexism and detecting source intentions. This study provides valuable insights into combating sexism on social media platforms and fostering inclusive online communities.

## References

1. Thomas Davidson, Dana Warmsey, Michael Macy, Ingmar Weber. "Automated Hate Speech Detection and the Problem of Offensive Language." [Link](https://arxiv.org/pdf/1703.04009)
2. Shimi Gersome and Jerin Mahibha. "Sexism Identification In Social Media Using Deep Learning Models." [Link](https://www.researchgate.net/publication/364947922_Sexism_Identification_In_Social_Media_Using_Deep_Learning_Models)
3. EXIST: sEXism Identification in Social Networks. [Link](http://nlp.uned.es/exist2023/)
4. Francisco Rodriguez-Sanchez, Jorge Carrillo-de-Albornoz, and Laura Plaza. "Automatic Classification of Sexism in Social Networks: An Empirical Study on Twitter Data." [Link](https://ieeexplore.ieee.org/document/9281090)
5. Regina Konig and Angela Heine. "Learning to detect sexism: An evaluation of the effects of a brief video-based intervention using ROC analysis." [Link](https://www.frontiersin.org/articles/10.3389/fpsyg.2022.1005633/full)
6. Google Translate API. [Link](https://pypi.org/project/googletrans/)
7. Training and evaluation with the built-in methods. [Link](https://www.tensorflow.org/guide/keras/train_and_evaluate)
8. Sentiment Analysis using VADER. [Link](https://towardsdatascience.com/sentimental-analysis-using-vader-a3415fef7664)
