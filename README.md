Diamonds Sale Data

https://www.kaggle.com/code/kamilshaydullin/price-prediction-lr-ann-gbr-mape-0-79

#### We have a big dataset made up of 53490 diamond sales entries which we can use to train a predictive model.
#### An effective predictive model can be used to accurately price diamonds given we have all of the diamond features that the model has been trained on.
#### Strictly speaking we can quite accuratly estimate the price of diamonds even if we don't have certain featrures since some of them are strongly correlated, such as length, width and depth.

#### After data cleaning and feature engineering I trained 3 separate models.
#### The models all turned out to be sufficiently accurate, measured by mean absolute percentage error (MAPE), yet they vary in computational complexity:
#### Artificial Neural Network (ANN) - MAPE = 1.43%
#### Linear Regression (LR) - MAPE = 1.03%
#### Gradient Boosting Regressor (GBR) - MAPE = 0.79%

#### **GBR** turned out to be the most accurate model with **MAPE = 0.79%**

### Diamond characteristics / Features:

**Color** - In the data set: D (Absolutely Colorless), E (Colorless), F (Colorless), G (Near Colorless), H (Near Colorless), I (Near Colorless), J (Near Colorless). D = best, J = worst.

**Clarity** - In the data set: IF (100%), VVS1 (99%), VVS2 (99%), VS1 (95%), VS2 (85%), SI1 (50%), SI2 (15%), I1 (1%). IF = best, I1 = worst.

**Carat** - In the data set: min - 0.2 carat, max - 5.01 carat. Carat describes the weight of a diamond. 1 carat = 0.2 grams.

**Cut** - In the data set: Ideal, Premium, Very Good, Good, Fair. Diamond cut grade is based on a number of factors including symmetry, polish, brilliance and fire.

**Depth** - In the data set: min - 43, max - 79. The depth of a diamond refers to its measurement from top to bottom, from the table on the top of the diamond to the culet at its base. The depth of any diamond is expressed as a percentage. Depth percentage is calculated by dividing the diamond’s total height by its total width. The deeper the diamond’s depth, the higher the diamond’s depth percentage. Great diamonds are all about proportion. When a diamond has the right combination of depth and table percentages, it’s more capable of taking in and reflecting light. This results in a stronger, more beautiful sparkle and better visual balance.

**Table** - In the data set: min - 43, max - 95. A diamond’s table is the flat facet on its surface — the large, flat surface facet that you can see when you look at the diamond from above. As the largest facet on a diamond, the table plays a major role in determining how brilliant (sparkly) the diamond is. Ideal table size depends on the cut of a diamond.

**X** - In the data set: min - 0(errors), max - 10.74. Length in mm.

**Y** - In the data set: min - 0(errors), max - 58.9. Width in mm.

**Z** - In the data set: min - 0(errors), max - 31.8. Depth in mm.

**Price** - Price of a particular diamond. THis is the dependent variable we are trying to predict.

https://www.gia.edu/diamond-quality-factor

https://www.diamonds.pro/education/diamond-depth-and-table/#Is-Depth-important-in-a-diamond
