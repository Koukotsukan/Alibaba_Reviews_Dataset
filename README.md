# Alibaba_Reviews_Dataset
The Alibaba Reviews Dataset contains Raw Data, Annotated Data, for Natural Language Processing Task or Aspect-based Sentiment Analysis.

## Introduction
1. The Alibaba Reviews Dataset contains reviews collected from Apple App Store, Google Play Store and Trustpilot.
2. In this project, in all context, _Alibaba_ refers to the _Alibaba Intertational B2B Online Platform_.
3. The Dataset was constructed and built for academic purpose only. The usage of the Dataset should be strcitly limited to academic purpose.

## Dataset Conponents
* **Alibaba-Reviews-Dataset.csv**: There are 2,693 reviews in total, with one column of reviews, and one columns of rating stars (maximum 5 stars, minimum 1 star).
* **ali-train.csv**: 2,153 reviews randomly chosen as the training dataset. 
* **ali-test.csv**: 540 reviews randomly chosen as the test dataset.
* **ali-train.atepc**: Auto-Annotated + Manually Annotated atepc file on Ali-train.csv
* **ali-test.atepc**: Auto-Annotated + Manually Annotated atepc file on Ali-test.csv

## Furtuer Exploration
* [Koukotsukan/Ali-Experience Website](https://aliexperience.online/)
* [Koukotsukan/Aspect_based_Sentiment_Analysis_to_Get_Insights_into_an_Online_Shopping_Experience_The_Case_of_Alibaba](https://github.com/Koukotsukan/Aspect_based_Sentiment_Analysis_to_Get_Insights_into_Online_Shopping_Experience_The_Case_of_Alibaba)

## Acknowledgements
This project makes use of several open-source packages, including:
* [yangheng95/PyABSA](https://github.com/yangheng95/PyABSA): A Python package for Aspect-Based Sentiment Analysis. It provides tools for processing and analyzing sentiment in text, focusing on aspects. This package is used for sentiment analysis tasks in our project. Licensed under the MIT License.

* [yangheng95/ABSADatasets](https://github.com/yangheng95/ABSADatasets): A collection of datasets for Aspect-Based Sentiment Analysis. These datasets are crucial for training our sentiment analysis models. Licensed under the MIT License.

* [cowboy-bebug/app-store-scraper](https://github.com/cowboy-bebug/app-store-scraper): This tool is used for scraping data from the Apple App Store. It's instrumental in our project for gathering app-related data for analysis. Licensed under the MIT License.

* [JoMingyu/google-play-scraper](https://github.com/JoMingyu/google-play-scraper): A package for scraping data from the Google Play Store. We use this to collect data from Android apps for our analytical purposes. Licensed under the MIT License.



## License
This project is under MIT licence, please cite this repo when you use it.


