# Kaggle-Titanic
I began working on this to re-fresh basic machine learning/data science concepts in preparation for joining the workforce. I plan on training multiple models of different types, comparing the models and then ultimately
choosing the best-performant one to submit with. I want to try a simple regression model, a decision tree, some form of ensemble learning and a shallow neural network. This is for two reasons - I want to refresh my 
memory on how these models are implemented and refresh my understanding of how they work. 

I also want to use some form of regression to predict missing values for the Age category for the positive and negative classes. There are 177 missing or NA values in total: 52 for the positive class and 125 for the negative class.
I could take the simple route and use some measure of central tendency (mean, median, mode) but this might not be very accurate. I want the predictions of my models to be as close as possible. I will first examine the 
correlation between the numeric variables and determine which ones are highly correlated. Following this I will use the most highly correlated variables to predict what the unknown age of the passenger was. 
