# supermarket-neural-network-classification-project
Creating neural networks to predict customer reaction to a marketing campaign for a supermarket

## Creating a marketing campaign for a supermarket using machine learning

This project was developed as part of a three hour hackathon with the focus of experimenting with neural networks  and optimisation methods. MLP Classifiers were created using both the sklearn and keras libraries, and GridSearchCV is utilised for hyperparameter optimisation. The time-pressure involved in the hackathon meant that understanding runtime drivers was particularly important. Although none of the models are perfect, it was an excellent experience and good exersize in thinking critically about what elements are crucial when developing machine learning models. <br>
<br>

<div class="alert alert-success">
<b>About Dataset</b>

<u>Context</u>

A supermarket is planning for the year-end sale. They want to launch a new offer - gold membership, that gives a 20% discount on all purchases for only 499, which is 999 on other days. It will be valid only for existing customers, and the campaign through phone calls is currently being planned for them. The management feels that the best way to reduce the cost of the campaign is to make a predictive model which will classify customers who might purchase the offer.

<u>Content</u>

The columns included in the dataset are:

<ol>
<li>id - Unique client identifier </li>  
<li>Response <b>(target)</b> - 1 if customer accepted the offer in the last campaign, 0 otherwise </li>
<li>Year_Birth - Age of the customer</li>
<li>Complain - 1 if the customer complained in the last 2 years</li>
<li>Dt_Customer - date of customer's enrollment with the company</li>
<li>Education - customer's level of education</li>
<li>Marital - customer's marital status</li>
<li>Kidhome - number of small children in customer's household</li>
<li>Teenhome - number of teenagers in customer's household</li>
<li>Income - customer's yearly household income</li>
<li>MntFishProducts - the amount spent on fish products in the last 2 years</li>
<li>MntMeatProducts - the amount spent on meat products in the last 2 years</li>
<li>MntFruits - the amount spent on fruits products in the last 2 years</li>
<li>MntSweetProducts - amount spent on sweet products in the last 2 years</li>
<li>MntWines - the amount spent on wine products in the last 2 years</li>
<li>MntGoldProds - the amount spent on gold products in the last 2 years</li>
<li>NumDealsPurchases - number of purchases made with discount</li>
<li>NumCatalogPurchases - number of purchases made using catalog (buying goods to be shipped through the mail)</li>
<li>NumStorePurchases - number of purchases made directly in stores</li>
<li>NumWebPurchases - number of purchases made through the company's website</li>
<li>NumWebVisitsMonth - number of visits to company's website in the last month</li>
<li>Recency - number of days since the last purchase</li>
</ol>


 <u>Inspiration</u>

The supermarket wants to predict the likelihood of the customer giving a positive response identifying the different factors which affect the customer's answer. You need to analyze the data provided to identify these factors and then build a prediction model to predict the probability of getting positive responses.
    
</div>

#### Approach Taken:

1) Import all libraries <br>
2) Load and investigate data <br>
3) Initial feature selection <br>
4) Investigate missing values <br>
5) Investigate multicollinearity <br>
6) Examine distribution <br>
7) Create training and test split <br>
8) Create preprocessing pipelines <br>
9) Create baseline model using SKLearn <br>
10) Evaluate baseline model performance <br>
11) Optimise baseline model using GridSearchCV <br>
12) Create additional model using Keras library <br>
13) Optimise Keras model using GridSearchCV <br>
14) Final evaluation
