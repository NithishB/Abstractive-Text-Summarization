# Abstractive-Text-Summarization

### The repo has 3 important files
<ol>
  <li> Seq2seq python file</li>
  <li> Model Training Finale notebook </li>
  <li> Model Inference notebook </li>
</ol>

The description of each file are as follows:
<ol>
  <li> <b>Seq2seq python file</b><br>
    This file has the class defined to create the custom encoder-decoder architecture by providing parameters of interest
    These parameters are used to create the entire network and the class object construct a tensorflow computational graph and returns it. Also, training and inference graphs have been separated for ease of use. </li>
  <li> <b>Model Training Finale notebook</b><br>
     This file has the code for creating the model object using the above mentioned python class and training it on the gigaword dataset. </li>
  <li> <b>Model Inference notebook</b><br>
     This file has the code for creating the model object using the above mentioned python class for inference and loading the trained graph variables to evaluate the model using rouge scores. </li>
 </ol>
