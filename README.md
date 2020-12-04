# Welcome to the encoder-decoder sorting project.

### Goal: Given a sequence of integers, create a encoder-decoder network for sorting.
### Structure Used: Vanilla RNN
### Libraries Used: Numpy,Scikit,Seaborn,Matplotlib
### Evaluation Method:Cross Entropy Check, Gradient Check.
### Constraints:Positive Integers
### DL Frameworks:None

#### Project Overview:
 The goal of this project is used to create an encoder-decoder architecture which uses only numpy and manual differentiation(no dl frameworks). It was a pretty engaging and challenging task
 given that most of the time we use dl frameworks which makes our work a lot easier by taking away the complexities. The project uses Recurrent Neural Network created from scratch using
 numpy.and uses it to create a seq2seq model in which the encoder is an RNN and takes an input sequence and ecodes it into an intermediate vector which is then fed as the input to the
 decoder which then outputs the desired sequence. The main loss function for evaluating the performance of the model used by me is Cross Entropy which calculates the difference between two probablistic
 models involving random variables. As required by the project an additional gradient check is used for further evaluation of the model.Since I have only worked with positive integers, I assumed
 that it can be added as a constraint, negative number testing can also be done.
