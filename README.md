# Next_Word_Prediction
<h2>Abstract</h2>
The model will consider the last word of a particular sentence and predict the next possible word. We will be using methods of natural language processing, language modeling, and deep learning. We will start by analyzing the data followed by the pre-processing of the data. We will then tokenize this data and finally build the deep learning model. The deep learning model will be built using LSTM’s.
<br>

<h2>Tools and Technologies</h2>
<ol>
  <li>Python3</li>
  <li>Keras</li>
  <li>Jupyter Notebook</li>
  <li>Html </li>
  <li>Css</li>
  <li>php</li>
</ol>


## Workflow
- Data collection
- Data preprocessing
- Removal of unwanted words
- Training Set <br>
   - Building Text Matrices
   - Encoding Sequences
   - Input and output sequences
- Building the model
   - RNN (Recurrent Neural Networks)
   - LSTM (Long Short Term Memory Cell)
- Fitting the model
- Testing the code
- Binding model to frontend

## LSTM Algorithm
Long Short Term Memory Network is an advanced RNN, a sequential network, that allows information to persist. It is capable of handling the vanishing gradient problem faced by RNN. A recurrent neural network is also known as RNN is used for persistent memory.
At a high-level LSTM works very much like an RNN cell. Here is the internal functioning of the LSTM network.The LSTM  consists of three parts:-

The first part chooses whether the information coming from the previous timestamp is to be remembered or is irrelevant and can be forgotten. In the second part, the cell tries to learn new information from the input to this cell. At last, in the third part, the cell passes the updated information from the current timestamp to the next timestamp.
These three parts of an LSTM cell are known as gates. The first part is called Forget gate, the second part is known as the Input gate and the last one is the Output gate.

## Output
![image](https://user-images.githubusercontent.com/66248163/164761806-76b3a8cc-ca52-46a4-91fe-52a84dd2e9b9.png)

