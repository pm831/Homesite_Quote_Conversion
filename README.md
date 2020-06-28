# Homesite Quote Conversion
### Pujan Malavia

![homesite](https://user-images.githubusercontent.com/19572673/62336567-d6051300-b49e-11e9-9746-e7c3b2c4bedd.png)

### Link to Dataset:
https://www.kaggle.com/c/homesite-quote-conversion/data

### Abstract:
Before asking someone on a date or skydiving, it's important to know your likelihood of success. The same goes for quoting home insurance prices to a potential customer. Homesite, a leading provider of homeowners insurance, does not currently have a dynamic conversion rate model that can give them confidence a quoted price will lead to a purchase. 

Using an anonymized database of information on customer and sales activity, including property and coverage information, Homesite is challenging you to predict which customers will purchase a given quote. Accurately predicting conversion would help Homesite better understand the impact of proposed pricing changes and maintain an ideal portfolio of customer segments. 

https://www.kaggle.com/c/homesite-quote-conversion

### Industry:
Insurance

### Company Information:
Homesite. We've got you covered. 

Founded in 1997, Homesite insurance was the first company to enable customers to purchase insurance directly online, during a single visit.

Since then, we’ve continued to innovate at the pace of our customers and their changing expectations. One thing that’s stayed the same since our founding: our commitment to our customers and partners. 

We now offer Home, Renter, Life, Small Business, Condo and Flood Insurance. 

A.M. Best has assigned an initial financial strength rating of A (Excellent) and an insurer credit rating of "A"​ to all Homesite Group insurance companies. 

https://www.linkedin.com/company/homesite-insurance/about/

https://go.homesite.com/

### Use Case:
Predict which customers will purchase a given quote

### Tool:
Python (Jupyter Notebook)

### Techniques:

xgboost 

### Initial Dataset(s):

train.csv

test.csv

### Data

This dataset represents the activity of a large number of customers who are interested in buying policies from Homesite. Each QuoteNumber corresponds to a potential customer and the QuoteConversion_Flag indicates whether the customer purchased a policy.

The provided features are anonymized and provide a rich representation of the prospective customer and policy. They include specific coverage information, sales information, personal information, property information, and geographic information. Your task is to predict QuoteConversion_Flag for each QuoteNumber in the test set.

### Data Fields:

QuoteNumber

Original_Quote_Date

QuoteConversion_Flag

Field6

Field7 ............

Field11

Field12

CoverageField1A

CoverageField1B ............

CoverageField11A

CoverageField11B

SalesField1A

SalesField1B ............

SalesField14

SalesField15

PersonalField1

PersonalField2 ............

PersonalField83

PersonalField84

PropertyField1A

PropertyField1B ............

PropertyField39A

PropertyField39B

GeographicField1A

GeographicField1B ............

GeographicField63

GeographicField64

### Communication of Results to Business Partner:
To a business partner, I would explain that the xgBoost (all else equal) is an efficient and easy to use algorithm which delivers high performance and accuracy as compared to other algorithms.

### Future Work:
Continue to do hyperparameter tuning of the model and creating new features/removing old features to help increase the prediction accuracy of the model

Try other types of models to see if the accuracy rate improves

More data visualization/patterns within the dataset (external sources) that can lead to more insights and decision-making from a business perspective
