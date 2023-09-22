# sentence-reconstruction
The purpose of this project is to take in input a sequence of words corresponding to a random permutation of a given english sentence, and reconstruct the original sentence. 

The otuput can be either produced in a single shot, or through an iterative (autoregressive) loop generating a single token at a time.

CONSTRAINTS:
* No pretrained model can be used.
* The neural network models should have less the 20M parameters.

The project is been developed for the purpose of the exam of deep learning 2022/2023.

The whole experiment setup is analyzed and comment through the jupyter notebook provided. The final result are satisfacotry, even though the test set used isn't really that huge. 
