# Hotel_cancellation_predict_randomforest_classification

## Project Description:

In this particular project, we are using the Hotel_Booking dataset that contains information like hotel, meal, country, meal, adult, children deposit type etc and using that to predict the chances of cancellation.
However, before you go ahead and make predictions, it is advised that you first pre-process and study the data, since it may contain some irregularities and noise.

# Part 1: data Exploration and Pre-processing

1) load the given dataset 
2) Print the unique values in all columns
3) Fill nan value with ‘other’
4) Fill nan in agent with mean of agent columns
5) Drop all the remaining null values
6) Plot the count of adult and children with help of a bar plot
7) Perform Label encoding on categorical columns

# Part 2:  Model Building

1. Create features and target data
2. Split into training & testing
3. Apply Random forest classifier on data
4. Create function which show Precision score, recall score, accuracy, classification report and confusion matrix
