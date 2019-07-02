# Web Mining Final Project
# Name: Bhagya Sree Chanda

## Final Project on WhatsApp Spyware Attack In Times Of India and The Hindu By Bhagya Sree Chanda

## Question

How different are two newspapers discussing a specific news, Which Newspaper is best to read? 

## Approach: 
The main objective of this project is to analyze how both Newspapers(Times Of India and The Hindu) reacted to major incident on WhatsApp. Also to analyze the content of these two Newspapers addressing the matter.I want to see which accounts are having good lexical diversity, word occurrences, sentiment analysis, generate word cloud.


## Data Collection

I have web scraped and collected the data from the online Newspapers of Times of India and The Hindu.
here are the links to those:
- https://timesofindia.indiatimes.com/business/india-business/whatsapp-fixes-bug-that-installed-spyware-via-voice-calling-urges-users-to-upgrade-app/articleshow/69325927.cms"

- https://www.thehindubusinessline.com/info-tech/social-media/whatsapp-urges-users-to-update-after-spyware-hacking/article27125342.ece

- importing bs4, requests API's, I have collected the data from these URL's.
### Libraries Required
 1. BeautifulSoup
 2. Pandas
 3. Requests
 4. Matplotlib
 5. nltk
 6. numpy
 7. wordcloud
 8. PIL
 9. urllib
 10. random

### Procedure
 - Web Scraping websites
 - Getting the data.
 - Performing analysis: Lexical Diversity, word occurrences, sentiment analysis, common words, generate word cloud
 - Visualizing the results using Matplotlib.
### Conculsion
- From the graph of Lexical Diverity Analysis, we can clearly state that "The Hindu" is a Newspaper with higher LD than "Times Of India" Newspaper.
- We can also see that the "The Hindu" has more unique words than the "Times Of India" Newspaper.
- From the above Sentimental Analysis, I can conclude that even if a Newspaper("The Hindu") is having more unique words, high lexical diversity too but it also has more Negative words, Aggressive terms in the Newspaper than the "Times of India". 
- It indicates "The Hindu" has more negative compound than the "Times of India"
- "The Hindu" has more uniqueness in words than "Times of India". Hence, reading "The Hindu" can help people in learning more new different words.
