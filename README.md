# Sentiment-Analysis-using-Naive-Bayes-Classifier-of-BEST-BUY-Google-Mini-Reviews
Performed Text Analytics determining the sentiment of reviews using Naive Bayes Classifier for Google Mini Reviews from BestBuy
<br />
<img width="500" height="500" src="https://cnet2.cbsistatic.com/img/IMKLzOuIl4vMHFlRBMx9Uwgoeak=/970x0/2017/10/06/e3f31773-a89c-4f4e-9bd1-9df6955cc7e8/google-home-mini-14.jpg">
<img width="200" height="200" src="https://botw-pd.s3.amazonaws.com/styles/logo-thumbnail/s3/0023/5388/brand.gif?itok=6YcMRAjS"><br />
<br />
<br />
## Scraped the data from Best Buy reviews of Google Mini using Python Library Beautiful Soup
 Using Beautiful Soup, web scraped around 5000 customer reviews of Google Mini <br />
 Based on the HTML tags, for customer reviews scraped the data 
 
## Extracted the data into a dataframe using Pandas
<div align="center">
    <img src="/Pictures/dataframe.PNG" width="400px"</img> 
</div>
## Bing Lexicon- lexicon containing a set of positive and negative words was extracted from a text file

## Tokenized the reviews into words using NLTK
 
## Categorized the reviews into positive and negative sentiment comapring it with the Bing Lexicon
 
## Applied Naive Bayes Classifier for sentiment analysis on the extracted features
