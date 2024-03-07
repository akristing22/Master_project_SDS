# Master Project Social Data Science WS 2023/2024
## RWTH Aachen | Prof. Dr. Jana Lasser
### Lawrence Fulton, Kristin Gnadt, Jona Rekate

### Research Question

*Do the debated topics on Twitter by German politicians differ from the topics debated in the German parliament?*


Welcome to our master project!
In this repo, you can find the code we used for analysing the topics German MPs discuss on Twitter and in parliament during the 19th legislation period (2017-2021).

### Data
The data we used can be accessed/ requested at:

Bundestag Open Data:
https://www.bundestag.de/services/opendata

Twitter Data Study:
https://doi.org/10.1093/pnasnexus/pgac186

### Methods

**BERTopic**
https://maartengr.github.io/BERTopic/index.html

**Bundestag Parser**
https://github.com/pournaki/bundestag-parser

The code we used can be find in the respective folder. A documentation of the notebooks can be found in the README in that folder.



| File                                 | Content                                                                       |
|--------------------------------------|-------------------------------------------------------------------------------|
| 1_get_MPs_WP19.ipynb                 | Get the MPs of the 19th Election Period.                                      |
| 2_match_mps_with_twitter_users.ipynb | Match those MPs with the Twitter Users.                                       |
| 3_select_tweets_from_mps_wp19.ipynb  | Only select tweets from the users which  are MP in the 19th Election Period.  |
| interrater_reliability.ipynb         | Calculated Fleiss' Kappa                                                      |
| parser.py & run_parser.py            | Code to run the parser to parse speeches                                      |
| speech_cleaning.ipynb                | Cleaning speeches.                                                            |
| speech_modelling.ipynb               | BERTopic of speeches                                                          |
| topic_mapping_recommendations.ipynb  | Recommendations for tweet <-> speech mapping.                                 |
| topics_analysis.ipynb                | Final statistical data analysis.                                              |
| tweet_cleaning.ipynb                 | Cleaning of Tweets.                                                           |
| tweet_modelling.ipynb                | BERTopic of tweets.                                                           |



