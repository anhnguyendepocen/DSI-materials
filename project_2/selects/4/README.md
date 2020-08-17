# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 2 - Ames Housing Price Prediction

## Problem Statement

Stakeholders(Investors) are unable to decide on whether to invest in a property in Ames as there are many factors which would affect housing prices. Many of these factors (variables) are categorical in nature and it is difficult for an average investor to dicipher such complexity and translate the data into useful information for decision making.

Being unable to accurately identify factors affecting housing prices and predict prices of houses based on a given set of attributes would result in stakeholders(investors) getting confused and wasting a lot of time running through tons of information **(inefficiencies)** and may even result in making wrong investment decisions **(financial loss)**.

**A regression model can be constructed based on the Ames Housing Dataset.** This model would help to explain how dfferent variables affect housing prices and predict the price of a house in Ames.(model and scope)

Ultimately,using the predictive model, the stakeholders(investors) would be able to discover undervalued properties in Ames as they uncover the answers to the following problems:

**Which features of a property are important in predicting sale prices of houses in Ames?**

**What is the predicted sale price of a house in Ames based on its features?**

## Executive summary

**Are you an investor who is keen to invest in an Ames property but is spending alot of time not knowing what factors drive housing prices?**

**Are you worried about overpaying for an Ames property?**

**We can help you!!!**

We seek to examine the Ames housing dataset consisting of various attributes along with its sale prices during the period 2006 to 2010.

We would then explore which features of a property greatly affect it's prices by harnessing various regression models. The optimal model with best performance would be use to inform investors what are the **key** attributes affecting housing prices and to predict a property's price.

The model will be useful for many stakeholders besides investors. Secondary audience may include house owners, town council etc. It helps stakeholders  to make a more informed and efficient decision while reducing the financial risk.


## Findings

#### Top Predictors

Findings from our predictive model shows that the top 5 of the best predictors fall into 2 main categories

**A) Size**

1. Above grade (ground) living area in square feet

2. Total square feet of basement area
    
3. Size of garage in square feet
    
**B) Quality**

1. Overall material and finish quality of the house

2. Exterior material quality

Other key findings indicate that housing location matters with StoneBrook and Northridge as the prefered locations and the year of house remodlling also matters 

Interestingly, there are a few factors that has a negative impact on housing prices. Full baths and properties in Old town area are the biggest negative predictors.

#### Housing Price Prediction(Valuation)

Our model does relatively well in predicting houses that were priced below USD400,000. However, the variance between our predictions and true values start to increase after the 400,000 mark. 

## Recommendations and Conclusions

Based on our findings, we would be able to answer the questions that we have formulated as part of the problem statement.

* Which features of a property are important in predicting sale prices of houses in Ames?

We recommend the investor to consider the top 5 predictors, size of living area, size of basement, size of garage and overall quality and finish of house and exterior house material quality before investing in properties in Ames.

Research has shown that people travel around in Ames by car and the [[average car ownership is 2]](https://www.google.com/search?q=no+of+cars+per+family+in+ames&rlz=1C1CHBF_enSG888SG888&oq=no+of+cars+per+family+in+ames&aqs=chrome..69i57.7554j0j7&sourceid=chrome&ie=UTF-8). This could explain why the size of garage is an important consideration for a house.

In addition, Ames also has a [[higher risk of tornado]](https://www.google.com/search?q=tornado+risk+in+ames&rlz=1C1CHBF_enSG888SG888&oq=tornado+risk+in+ames&aqs=chrome..69i57j33.3742j1j9&sourceid=chrome&ie=UTF-8) compared to national average. This could also explain why factors such as size of basement matters, as people may use it for shelter and also explain why quality and exterior material quality matters so greatly.

Invstors should also focus on locations such as Stonebrook as it is close to Iowa State University, which employs around 25% of the population in Ames.

Investors should also take note that full baths and properties in Old Town area has a negative impact on housing prices.

* What is the predicted sale price of a house in Ames based on its features?

We would be able to answer this question based on attributes of a property the investor would like to purchase.
However, an important point to take note of is that the model works well for properties under USD 400K.

## Next Steps
while the predictive model and key features provide great insights for the investor, we noted on the limitations on the predictive prowess of the model for properties below USD400K. In addition, there could be other variables that have significant impact on housing prices.

To enhance the model and improve recommendations for our stakeholders, the following is proposed:

1. Increase data size collection to better train the model
2. Collate other variables info, such as distance to Iowa State University (Taking note that it hires 25% of the population in Ames)
3. Demographics of the residents in each housing area
4. Consider crime rates of each housing area
5. Using other more advance forms of regression models
6. Consider other economic factors

## Data Dictionary
https://www.kaggle.com/c/dsi-us-6-project-2-regression-challenge/data


## References
https://www.google.com/search?q=no+of+cars+per+family+in+ames&rlz=1C1CHBF_enSG888SG888&oq=no+of+cars+per+family+in+ames&aqs=chrome..69i57.7554j0j7&sourceid=chrome&ie=UTF-8

https://www.google.com/search?q=tornado+risk+in+ames&rlz=1C1CHBF_enSG888SG888&oq=tornado+risk+in+ames&aqs=chrome..69i57j33.3742j1j9&sourceid=chrome&ie=UTF-8

https://en.wikipedia.org/wiki/Old_Town_Historic_District_(Ames,_Iowa)

https://worldpopulationreview.com/us-cities/ames-population/
