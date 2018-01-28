# ir-research-data
Research dataset for web content extraction and news-search clustering.

### Paper ###
- Utomo, V. & Leu, J.-S., Unpublished. Subject-Assisted Extraction: Looking at Web Content Extraction from Different Side. 
- Utomo, V. & Leu, J.-S., Unpublished. Automatic News-Roundup Generation using Clustering, Extraction, and Presentation. 

*Will be updated when published

### Explanation ###
Two dataset types are published here:
1. Web content extraction dataset:
- Big9 dataset: 10 different webpages from 9 different websites and from 4 different time cluster: 2005, 2009, 2013, 2017, totaling 360 webpages. The 9 websites used for the dataset are: Arstechnica, BBC, CNN, Forbes, FoxNews, LATimes, NYMag, NYPost, and Yahoo!News.
- Chaos dataset: 36 different queries used for this dataset totaling 360 different webpages. For this dataset, the required keyword for the experiment can be retrieved by using the keyword query used in Google search to collect the webpages. This dataset contains webpages from around 240 different websites. (Year 2017 only)
2. News-search result clustering dataset:
- The dataset was gathered using Google CSE API, no predefined websites listed beforehand and it’s configured to search the entire web. However, it’s type restricted using Schema.org types to look for ‘NewsArticle’ type of webpages. 20 different topic queries were used, which are afghanistan, apple, bitcoin, climate, coral reef, dinosaur, eclipse, elon musk, game of throne, google, hurricane Harvey, marvel movies, nasa, nationalist, north korea, star wars, terrorist, trump, typhoon, wearable. For each topic 50 first webpages were selected as the dataset, totaling 1000 webpages for the experiment.

### Term of use ###
Only for research purpose.

