## Sentiment Prediction based on the text based user reviews using Neural Network and Pretrained word embeddings

### Input Dataset
* User text reviews with ratings 1 to 5

### Word Embedding
* Pre trained GloVe 100 word embeddings
* Vocab Size: 10000
* Sequence Length: 300 words

### Model 1:
* Basic Conv Net with the following architecture
![CNN](https://github.com/meavinash100/NNSentimentPred/blob/master/Conv%20Model%20Summary.PNG)

### Model 2:
* LSTM based RNN with the following architecture
![LSTM](https://github.com/meavinash100/NNSentimentPred/blob/master/LSTM%20RNN.PNG)

### Model 3:
* GRU based RNN with the following architecture
![GRU](https://github.com/meavinash100/NNSentimentPred/blob/master/GRU%20RNN.PNG)
### Possible Tuning Hyper-parameters 
* Different sizes of GloVe word embeddings (50, 100, 300)
* Different vocabulary sizes
* Different network architecture 
  * More neurons in the hidden layers
  * More hidden layers
  * Different dropout rate in different layers (0.1, 0.2, 0.3, 0.4, 0.5)
  * Different kernal sizes in the Convolution layers
  * Different mini batch sizes (16, 32, 64, 128, 256, ...)
  * More number of epochs 
  * Different optimizers (Adam, AdaOne, RMSProp)
  * Different activation function Tanh or Relu
  



