**Project 3: Regression and classification with housing data **

**Business Case**

You work for a real estate company interested in using data science to determine the best properties to buy and re-sell. Specifically, your company would like to identify the characteristics of residential houses that estimate the sale price and the cost-effectiveness of doing renovations.

There are three components to the project:

Estimate the sale price of properties based on their "fixed" characteristics, such as neighborhood, lot size, number of stories, etc.
Estimate the value of possible changes and renovations to properties from the variation in sale price not explained by the fixed characteristics. Your goal is to estimate the potential return on investment (and how much you should be willing to pay contractors) when making specific improvements to properties.
Determine the features in the housing data that best predict "abnormal" sales (forclosures, etc.).
This project uses the Ames housing data recently made available on kaggle.

** Directions **

Though the housing data for this project is very rich, it is not trivial to clean and prepare for modeling. Good EDA, cleaning, and feature engineering will be critical to the success of your models. Always remember to think critically about the data before modeling. The computer can't be the researcher for you!

The first two parts of the project are regression problems. There are potentially hundreds of features and plenty of multicollinearity, so regularization is definitely recommended.

The second question involves fitting a regression on the residuals of the first model. This is a practice that "covaries out" any effects of the predictors in the first model before investigating the effects of predictors in the second model.

The third section of the project is more challenging and involves dealing with significant class imbalance. This is a common and tricky problem in real-world classification tasks. We leave it up to you to decide how you want to tackle this problem and devise a solution, and highly recommend doing your own research into the topic.

** Concertated on the following things: **

Detailed EDA with justification for the steps. Visualize your data with pandas, matplotlib, or other plotting libraries. Explain the variables you choose for your models.
Detail your choice of regression and classification models for the task. Include Markdown explaining your justification, results, and interpretation of your models. Make sure your code is clean and clear.
Remember to frame your results according to your goals outlined in the project prompts.
