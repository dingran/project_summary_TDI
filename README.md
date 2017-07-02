# Summary of side projects

## Project1: Manufacturing data set assembly and analysis

At my work, I analyzed our manufacturing data in various formats and from various sources (CSV, SQL database, raw measurement traces). Through this exercise, I gained experience in assembling, cleaning and normalizing data. In addition, I build a regression based model to relate results observed at later stages of the manufacturing pipeline to earlier stage test criteria to generate insights regarding how test criteria should be adjusted to prevent failures in later stages (which is much more expensive than early stage tests). I present the results through a web app built with Django and Python for streamlined access for multiple teams at our company.

## Project2: Web scraping and startup idea exploration

A side project I did was to explore the latest trend in startup ideas. I scraped AngelList, Crunchbase, and Kickstarter using Python and its packages Selenium and BeautifulSoup. The web scraper I implemented is "polite" in the sense that it avoid visiting the same website too frequently and will keep track of pages that it already saw to avoid duplicated download. This is for personal use only, so it didn't violate the relevant policies of these websites. The AngelList web scraper is at https://github.com/dingran1019/angellist-webscrape/blob/master/code/AngelScraper.py

Using the collected data, I used simple Natural Language Processing (NLP) techniques (such as TFIDF) to encode the company/product descriptions, non-negative matrix factorization (NMF) for dimension reduction and unsupervised learning methods (Agglomerative Clustering, and KNN) to cluster companies into a few themes. And used t-SNE for visualization. An example notebook can be found here https://github.com/dingran1019/startup-explore/blob/master/data_preprocess.ipynb

## Project3: Deep learning with tensorflow for traffic sign classification

As presented here https://github.com/dingran1019/traffic-sign-classifier/blob/master/Traffic_Sign_Classifier.ipynb (I also plan to have a write up soon). In this project, I implemented various deep neural networks in TensorFlow to classify traffic signs in the Germany traffic sign benchmark dataset. Using LeNet-5 as a baseline I implemented multi-scale feature extraction architecture and achieved 99.02% on the test set, which is slightly better than the published results by Yann Lecun's group. A related project is lane detection: https://github.com/dingran1019/lane-detection

This project is not directly on data analysis but is more on using deep neural networks to train models and make predictions. I think DNN is a powerful toolkit for using data to make predictions, and hope to combine it with other data science/machine learning techniques in future work.

## Kaggle projects (profile https://www.kaggle.com/dingran)

Top 11% in Prudential Life Insurance competition: https://www.kaggle.com/c/prudential-life-insurance-assessment

Top 13% in Bosch Production Line Performance competition https://www.kaggle.com/c/bosch-production-line-performance

Both projects are good exercises in cleaning and imputing data, engineering features, handling large dataset and building an organized pipeline for data injection, model training, and hyper-parameter tuning.
