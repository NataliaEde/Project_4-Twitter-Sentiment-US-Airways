# Project 4, Twitter Sentiment Analysis on US Airlines

<img width="451" alt="Screen Shot 2023-04-07 at 10 27 26 AM" src="https://user-images.githubusercontent.com/44559346/230625618-13316618-fcf1-4b9b-b59d-83103c447bd0.png">


Welcome to my project on airline sentiment analysis. In this project, I aim to analyze tweets about various airlines to gain valuable insights into customer sentiment, with the goal of helping airlines improve their services and enhance customer satisfaction. Along with machine learning algorithms such as Random Forest, XGBoost, and GaussianNB, I also used Hugging Face's  NLP tools and an LSTM model for sentiment analysis. 

### Data

The Twitter Airline Sentiment dataset consisting of approximately 14,640 tweets about six major U.S. airlines, collected during February 2015. The tweets have been classified into three sentiment categories: positive, negative, and neutral. https://www.kaggle.com/datasets/crowdflower/twitter-airline-sentiment

### Here's a brief overview of this project's key components:

A WordCloud visualization to identify the most common words in positive and negative tweets, giving a snapshot of customers' sentiment towards various airlines.


<img width="562" alt="Screen Shot 2023-04-17 at 5 17 19 PM" src="https://user-images.githubusercontent.com/44559346/232613039-6b32f2a7-fb77-42e4-9f8a-a07ef01ae973.png">


Model evaluation using various machine learning algorithms with a focus on accuracy, including BERT-based models and XGBoost models with TF-IDF and CountVectorization. The use of Hugging Face's powerful NLP tools and an LSTM model for sentiment analysis.


<img width="1054" alt="Screen Shot 2023-04-17 at 3 31 10 PM" src="https://user-images.githubusercontent.com/44559346/232613132-d93daec7-875c-4269-b55f-45e9926edaa2.png">


SHAP (SHapley Additive exPlanations) was used to explain the predictions of the best-performing models, providing insights into the most important features driving sentiment classification. This tool was particularly useful in understanding the decision-making processes of the BERT-based and XGBoost models.

![image](https://user-images.githubusercontent.com/44559346/232613784-be638bdf-8e47-466c-8540-9dbc69de9982.png)

Conclusion:

We explored a dataset of tweets about major airlines to perform sentiment analysis. By analyzing the top words and evaluating different models, we gained valuable insights into customer sentiment, which airlines can use to improve their services and enhance customer satisfaction. By continuing to monitor and analyze social media sentiment, airlines can stay ahead of the competition and provide an even better travel experience for their customers.

**************

US Airline Sentiment Analysis: Repo includes notebook in PDF, code, and presentation
