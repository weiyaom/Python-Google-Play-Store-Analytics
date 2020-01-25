# Python-project
Nowadays, apps affect all aspects of our life, such as Uber, Twitter, Yelp, etc. These apps make people's life more convenient, improve production efficiency, and provide more choices and possibilities. More importantly, they contain a lot of valuable information worth studying. By mining the information of app store, we would have a deeper understanding of this field to help app developers find business opportunities, make decisions and adjust the app in time. We can also gain some insights about people or society. After researching for this topic, we found that there have been many comprehensive analyses for iOS Apps, but conversely, analysis for Apps in Android, actually the most popular mobile operating system, is not that much, so we choose a dataset focusing on Android Apps market to study.

Our dataset is from Kaggle dataset provided by Lavanya Gupta who scraped it from Google Play Store (https://play.google.com/store/apps) and updated last month. The data includes two csv files:

googleplaystore.csv: details about apps consist of 13 columns and 10841 rows:

App: Application name
Category: Category the app belongs to
Rating: Overall user rating of the app (as when scraped)
Reviews: Number of user reviews for the app (as when scraped)
Size: Size of the app (as when scraped)
Installs: Number of user downloads/installs for the app (as when scraped)
Type: Paid or Free
Price: Price of the app (as when scraped)
Genres: An app can belong to multiple genres (apart from its main category). e.g., a musical family game will belong to Music, Game, Family genres.
Content Rating: Age group the app is targeted at - Children / Mature 21+ / Adult
Last Updated: Date when the app was last updated on Play Store (as when scraped)
Current Ver: Current version of the app available on Play Store (as when scraped)
Android Ver: Min required Android version (as when scraped)
googleplaystore_user_reviews.csv (5 columns and 64294 rows): first ‘most relevant’ 100 reviews for each app with 3 new features: Sentiment, Sentiment Polarity and Sentiment Subjectivity:

App: Name of app
Translated_Review: User review (Preprocessed and translated to English)
Sentiment: Positive/Negative/Neutral (Preprocessed)
Sentiment_Polarity: Sentiment polarity score
Sentiment_Subjectivity: Sentiment subjectivity score
