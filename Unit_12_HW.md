* Using News API to analyze sentiment, and content of BTC and ETH media. 

** Sentimental Analysis

Which coin had the highest mean positive score?
I combined the 'title sent' mean and 'text sent' mean scores for both coints. 

ETH was the highest at 0.5. BTC was negative Perhaps since BTC is very well known, the negatives titles draw in the users? 

Which coin had the highest negative score?

I combined the 'title neg' Max and 'text neg' Min scores for both coins. 

BTC did, at 0.425. Since BTC is such a larger and more well known coin, negative articles about speculation are more common. ETH is much less well known, so articles could be more forgiving. Although, the text and title nuetral numbers for BTC are higher, the volume of articles that mention BTC are likely much higher than those that mention ETH. 


Which coin had the highest positive score?

I combined the 'title pos' Max and 'text pos' Max scores for both coins.

ETH by far had a higher score, mostly due to a title_pos max score of 0.53. Many very positive headlines for ETH recently. This could come from the blockchain enterprise community, while BTC is very popular (And at times lucrative) there is typically a steady stream of positive media around smart contracts and the usability in enterprise. 


** Word Count/Word Cloud

The BTC wordcount and word clouds were disproportianately effected from a random blog "Bitcoin Today". However, I was happy to see some mention of Satoshi high in the count. ETH's word clouds were corrupted in a similiar fashion. If I had more time I would inhibit the blog post from populating the API request. 


** SPACY 

While a good concept, the SPACY function didn't work super well. An example being misidentifying "robot colleague" as an organization, when really its a reference fictional person. 

** Overall, Word Clouds/Sent Analysis/ and Word Counts are very helpful and unique for news especially. But as usual, good input data and a good developer are needed to train these programs. 