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
Mapped the most frequently mentioned words to seven key attributes - Seating, Flight Punctuality, Dining, Luggage Handling, Entertainment, and Service.

*Analysis Framework:*

Sentiment Analysis: Leveraged VADER to determine positive and negative sentiments across reviews.
Time Series Analysis: Assessed trends in sentiments and ratings using a 3-year moving average.
Attribute Contribution: Evaluated attribute-wise contributions to customer reviews pre and post-takeover.

## Data Analysis

*Time Series Analysis*
Sentiment Trends: Decline in customer sentiment from 2013 to 2022 reflects worsening perceptions, but there was a noticeable improvement post-TATA takeover, indicating positive restructuring impacts.
Rating Trends: Declining ratings pre-2022 highlight customer dissatisfaction, followed by positive rating shifts post-takeover, suggesting operational improvements.

*Attribute Analysis*
In-flight service consistently dominated mentions pre- and post-takeover, highlighting its role as a key driver of customer experience.
Entertainment-related mentions rose by 15% post-takeover, reflecting increased importance in customer satisfaction.
Dining-related mentions dropped by 20%, possibly indicating a shift in focus or priorities.

## Insights & Recommendations

The positive shifts in customer sentiment and ratings seem to validate early restructuring efforts by TATA. A heightened focus on enhancing dining, service, and entertainment can further elevate customer experience. Social media and review aggregation platforms like Facebook and TripAdvisor can be leveraged to strengthen brand-building efforts. Furthermore, the analysis can be expanded to focus on attribute-specific sentiment tracking to see how the changes in each area affect customer experience.

## Files Included

*Airline Scraping.ipynb*: Generates a cleaned dataset of ~1500 reviews and ratings for Air India, scraped from SkyTrax, spanning 2011–2024.
*Time-Series.ipynb*: Time series analysis of customer sentiments and ratings.
*sentiment_data_v2.csv*: Contains user ratings and reviews with corresponding sentiment scores.
*attribute_word_frequencies.csv*: Contains the 5 most frequently mentioned customer experience attributes in reviews, both before and after the TATA takeover.

## Conclusion

This analysis highlights a noticeable improvement in Air India's customer sentiment post-TATA Group's acquisition. It underscores the importance of targeted service improvements and leveraging positive sentiment for future brand development.
