# Machine_Learning
<p>Deliverable 1 & 2: https://github.com/JoePizz/Machine_Learning/blob/main/AlphabetSoupCharity.ipynb<p>
<p>Deliverable 3: Attempt 1 https://github.com/JoePizz/Machine_Learning/blob/main/AlphabetSoupCharity_Optimzation.ipynb
  Attempt 2: https://github.com/JoePizz/Machine_Learning/blob/main/AlphabetSoupCharity_Optimzation2.ipynb
  Attempt 3: https://github.com/JoePizz/Machine_Learning/blob/main/AlphabetSoupCharity_Optimzation3.ipynb
  https://github.com/JoePizz/Machine_Learning/blob/main/trained_application.h5
  https://github.com/JoePizz/Machine_Learning/blob/main/trained_application_adjust.h5
  
<p> Deliverable 4 <p>
<p>The purpose of this analysis is to create a binary classifier that can predict whether or not an application will be successfully funded by Alphabet Soup. The binary classifier will use information with historic data of successful and unsuccessful applicants to Alphabet Soup.<p>
<p>**Results**<p>
  <p>Data Preprocessing<p>
    <p>The target variable for this model is the IS_SUCCESSFUL variable. I chose this as the target variable as we are looking to predict in the future if certain applicants will     be successful or not and building the model off of this variable will help us do so.<p>
    <p>I decided to remove the "EIN", "NAME", "CLASSIFICATION", "APPLICATION_TYPE" columns from the data as this data did not help to indicate whether or not an application will be successful. So they were removed to help consolidate the data.<p>
  <p>Compiling, Training and Evaluating the Model<p>
  <p>I ran three optimization attempts to improve the loss and accuracy score of the model.<p>
    <p>In attempt 1 I used 1 hidden layer, 1 feature input, 300 neurons, and a linear actication for the hidden layer. For the output layer I used a linear activation and 1 unit. This resulted in an accuracy score of 52.75% and a Loss of 0.889.<p>
      <p>https://github.com/JoePizz/Machine_Learning/blob/main/Screen%20Shot%202022-01-16%20at%2011.37.33%20AM.png<p>
    <p>In attempt 2 I used 2 hidden layers and 1 feature input. The first layer had 300 neurons and a relu activation, the second layer had 250 neurons and a relu activation and the output layer had 1 unit and a sigmoid activation. This setup resulted in an accuracy score of 53.06% and a Loss of 0.92.<p>
      <p>https://github.com/JoePizz/Machine_Learning/blob/main/Screen%20Shot%202022-01-16%20at%2011.58.53%20AM.png<p>
      <p>In attempt 3 I used 0 input features, and 1 hidden layer. The Hidden layer had 300 neurons, a linear activation and the output layer had 1 units and a linear activation.        This resulted in an accuracy score of 0.4896 and a Loss of 3.68.<p>
      <p>https://github.com/JoePizz/Machine_Learning/blob/main/Screen%20Shot%202022-01-16%20at%2011.37.04%20AM.p![Screen Shot 2022-01-16 at 11 47 32 AM](https://user-images.githubusercontent.com/89032468/149669374-bb4f56c0-2ce7-45b1-b822-9eb71408bee3.png)
ng<p>        
  <p>To increase the models performance I removed a hidden layer, increased and decreased the neurons, changed the activation and changed the number of features.<p>
<p>Summary<p>
<p>In summation after making many adjustments to the model and spending time in Tensor Flow Playground to help improve the loss and accuracy of the model. Overall I was unable to make the necessary adjustments to get the model to a 75% accuracy. As seen in my 3 attempts, changing the neurons, adding a hidden layer, removing columns, changing the output units and changing the activation type, I was still unable to get the model to 75% accuracy.<p>
<p>The Random Classifier is another model that could work here for solving this classification problem. The Random Forest Classifier fits decision tree classifiers. It could have better results here as it uses averaging to improve the predictive accuracy and controls over-fitting.<p>
