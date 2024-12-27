# customer-perception-analysis
A data-driven approach to evaluating consumer sentiment pre and post Air India's takeover by the TATA Group

## Objective
This project was completed as part of the Unstructured Data Analysis coursework, for the MS in Business Analytics program at the McCombs School of Business.
It aims to analyze consumer sentiment surrounding Air India before and after the TATA Group's acquisition using reviews and ratings from Skytrax. The goal is to determine alignment between restructuring efforts and consumer perceptions and identify key drivers for improving the customer experience.

## Key Tasks

*Data Collection:*
Scraped ~1500 reviews and user ratings from Skytrax using Selenium, spanning the timeline 2011–2024.
Preprocessed the dataset to remove stopwords and clean raw text using NLP techniques like regular expressions and NLTK.

*Attribute Mapping:*
Mapped the most frequently mentioned words to seven key attributes: Seating, Flight Punctuality, Dining, Luggage Handling, Entertainment, and Service.

*Analysis Framework:*

  Sentiment Analysis: Leveraged VADER to determine positive and negative sentiments across reviews.
  Time Series Analysis: Assessed trends in sentiments and ratings using a 3-year moving average.
  Attribute Contribution: Evaluated attribute-wise contributions to customer reviews pre and post-takeover.
