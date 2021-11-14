# Deep Learning
<hr>

## Purpose
<p align = 'justify'>The purpose of this project is to use a deep-learning neural network with TensorFlow library to analyze and classify the success of charitable donations from Alphabet Soup.</p>
<hr>

## Data Processing
<ul>
  <li>The columns 'EIN' and 'NAME' were dropped.</li>
  <li><p align = 'justify'>The target variable is found in the 'IS_SUCCESSFUL' column. This is going to be predicted to determine the success rate of the charities.</p></li>
  <li><p align = 'justify'>The columns 'APPLICATION_TYPE', 'AFFILIATION', 'CLASSIFICATION', 'USE_CASE', 'ORGANIZATION', 'STATUS', 'INCOME_AMT', 'SPECIAL_CONSIDERATIONS', 'ASK_AMT' are feature values.</p></li>
</ul>

## Model Evaluation 1
<ul>
  <li><strong>Compiling, Training, and Evaluating the Model</strong></li>
  <p align = 'justify'>The attempt at compiling a neural network consisted of layers of 80 neurons and the second one of 30; both layers had relu activation functions. In addition, the output layer had a sigmoid activation function. The assembled model had the Adam optimization algorithm, and the fitting model had a validation split of 0.15 and 100 epochs.</p>
The results for this model were:
<ul>
<li>Loss: 0.5653</li>
<li>Accuracy: 0.7291</li>
<li>Recall: 0.7826</li>
</ul> </ul>

## Model Evaluation 2
<ul>
  <li><strong>Compiling, Training, and Evaluating the Model</strong></li>
  <p align = 'justify'>The attempt at compiling a neural network consisted of layers of 3 neurons: the second one of 50 and the third one of 20 all layers had relu activation functions. In addition, the output layer had a sigmoid activation function. The assembled model had the Adam optimization algorithm, and the fitting  model had a validation split of 0.15 and 100 epochs.</p>
      
  The results for this model were:
<ul>
<li>Loss: 0.5734</li>
<li>Accuracy: 0.7294</li>
<li>Recall: 0.7822</li>
</ul></ul>

## Model Evaluation 3
<ul>
  <li><strong>Compiling, Training, and Evaluating the Model</strong></li>
  <p align = 'justify'>The attempt at compiling a neural network consisted of layers of 80 neurons and the second one of 30; both layers had relu activation functions. In addition, the output layer had a sigmoid activation function. The assembled model had the Adam optimization algorithm, and the fitting model had a validation split of 0.15 and I reduced the epochs to 50.</p>
  The results for this model were:
<ul>
<li>Loss: 0.5578</li>
<li>Accuracy: 0.7270</li>
<li>Recall: 0.7794</li>
</ul></ul>
  

  
