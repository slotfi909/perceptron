implementation of a single neuron(perceptron) classifier using numpy

## what is a perceptron?
In machine learning, the perceptron (or McCulloch-Pitts neuron) is an algorithm for supervised learning of binary classifiers.<br>
this perceptron uses a sigmoid function as it activation function.(although other activation function such as ReLU could be used in order to avoid [vanishing gradient](https://en.wikipedia.org/wiki/Vanishing_gradient_problem))
<!--
![image](https://github.com/slotfi909/perceptron/assets/82094903/ae8f8524-67a7-4c41-84b1-2af2c52dd8bc)# perceptron
-->
![image](https://github.com/slotfi909/perceptron/assets/82094903/08a25865-887e-4f68-b4ba-50b21f031dd8)
<br>
the perceptron takes its inputs, multiplies it by its weights, then adds biases to the result, and use an activation function(a non-linear function) on the result as its final output. then, by using [gradient descent](https://builtin.com/data-science/gradient-descent), changes its weights and biases to reach to an optimal state. <br>
in this model, cross entropy is used as its loss function.


## about dataset
The  provided [dataset](https://archive-beta.ics.uci.edu/dataset/75/musk+version+2), "Musk (Version 2)," is a collection of data related to the classification of molecules as either musks or non-musks. It contains 6,598 instances of molecules, with each instance described by 166 numerical attributes. The dataset was created by Dr. Ross Quinlan and is derived from the original Musk dataset. The main objective of this dataset is to predict whether a molecule is a musk or non-musk compound based on its various attributes. The dataset is labeled, with approximately 8% of the instances labeled as musks and the remaining 92% labeled as non-musks. It has been used in research papers related to machine learning and chemical informatics.
