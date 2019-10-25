# Predict-the-price-of-a-bottle-of-wine-kaggle-competition
This repo shows our proposed solution for the kaggle competition "Predict the price of a bottle of wine from it's reviews and other wine features".

This solution was crafted as part of the african master of machine intelligence.

The data summarize 258210 wine reviews:<br>
• 175000 are the training set, the data on which to train your models.<br>
• the remaining 83210 observations constitute the test set.

# File description:
train.csv - the training set. <br>
test.csv - the test set.<br>
 
# Data fields:
country (String) The country that the wine is from
province (String) The province or state that the wine is from
region_1 (String) The wine growing area in a province or state (ie Napa)
region_2 (String) Sometimes there are more specific regions within the wine growing area (ie Rutherford inside the Napa Valley), but this value can sometimes be blank
winery (String) The winery that made the wine
variety (String) The type of grapes used to make the wine (ie Pinot Noir)
designation (String) The vineyard within the winery where the grapes that made the wine are from
taster_name (String) taster name
taster_twitter_handle (String) taster twitter account name
review (String) A few sentences from a sommelier describing the wine's taste, smell, look, feel, etc.
review_score (Numeric) Number of points WineEnthusiast rated the wine on a scale of 1-100

TARGET: price (Numeric) The cost for a bottle of wine.
