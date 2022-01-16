# Machine_Learning
<p> Deliverable 4 <p>
<p>The purpose of this analysis is to create a binary classifier that can predict whether or not an application will be successfully funded by Alphabet Soup. The binary classifier will use information with historic data of successful and unsuccessful applicants to Alphabet Soup.<p>
<p>**Results**<p>
  <p>Data Preprocessing<p>
    <p>The target variable for this model is the IS_SUCCESSFUL variable. I chose this as the target variable as we are looking to predict in the future if certain applicants will     be successful or not and building the model off of this variable will help us do so.<p>
    <p>I decided to remove the "EIN", "NAME", "CLASSIFICATION", "APPLICATION_TYPE" columns from the data as this data did not help to indicate whether or not an application will be successful. So they were removed to help consolidate the data.<p>
  <p>Compiling, Training and Evaluating the Model<p>
  <p>I used 2 Hidden layers, 8 neurons in the first and 5 in the second, and 2 features. I did this as this gave me the best results in the Tensor Flow playground.<p>
  <p>To increase the models performance I: removed a hidden layer, increased and decreased the neurons, changed the activation and changed the number of features.<p>
<p>Summary<p>
<p>In summation...
