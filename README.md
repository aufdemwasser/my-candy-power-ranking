The goal of [the ultimate halloween candy power ranking problem](https://fivethirtyeight.com/videos/the-ultimate-halloween-candy-power-ranking/) 
is to figure out what candy people most perfer based on [the online ranking results](https://github.com/fivethirtyeight/data/tree/master/candy-power-ranking).

1. data_analyse.ipynb analysed the correlationship between the attributes. We had the conclusion:
    a. the candies with chocolade are generally higher ranked than without.
    b. the chocolate candies with extra ingredient e.g. caramel, peanutalmondy, nougat or crispedricewafer are more beloved than without.
    c. the chocolate candies are hard, and almost all of them are in bar.
    d. the corelationship between sugarpercent and winpercent is not linear as the one between pricepercent and winpercent. 
    
2. based on the analysis above, we use ML to find out a most prefered hard chocolade candy. After testing with different models, we decided for the random forest based on R2 score. The most prefered candy is hard chocolade with peanutalmondy, 0.732 sugarpercent, 0.651 pricepercent. 
    
