# deep-learning-challenge

#Overview of the analysis 

The purpose of this analysis is to predict whether applicants for funding from Alphabet Soup, a nonprofit foundation, will be successful.

#Results 

Data Preprocessing: 
The target variables for the model are accuracy,
The featured variables for the model are classifification.
The variables 'EIN' and 'Name' were removed from the input data because they are neither targets or features.


#Compiling, Training, and Evaluating the Model

There are 80 neurons in the first layer, 30 neurons in the second layer and 1 neuron in the third layer. I chose these parameters to help maintain a neuron count that was enough to account for the features.

Target model performance of 75% or greater was not achieved. The target model performance I achieved was approx 73%. 
In attempt to increase the model performance, I increased the number of neurons and increased the epoch number and after 3 attempts still recieved a performance of 72-73%.


#Summary 

Even though I failed to achieve 75% performance level, my second optimization attempt achieved 72.9% accuracy. 
The logistic regression model perhaps would've been better to solve this occurrence. The logistic regression model would be beneficial as we try to predict the growth/successfulness of applicants. It would have produced long term results that would help the nonprofit foundation would be useful in providing funding to applicants presently and in the years to come. 
