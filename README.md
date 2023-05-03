# Deep-Double-Descent
Repository to help track code related to the M.Bc. studies

## Content:
* [tensorflow MNIST 1 layer full](https://github.com/oridarshan/Deep-Double-Descent/blob/main/tensorflow%20MNIST%201%20layer_full.ipynb)
  * Reproducing Double-Descent phenomenon with simple FFNN with 1 hidden layer on MNIST dataset
  * Average results without added noise:  
  ![TensorFlow no noise](https://github.com/oridarshan/Deep-Double-Descent/blob/main/images/tf%20no%20noise.png)
  * Average results with 10% added noise:  
  ![TensorFlow with noise](https://github.com/oridarshan/Deep-Double-Descent/blob/main/images/tf%20with%20noise.png)
* [pytorch MNIST 1 layer](https://github.com/oridarshan/Deep-Double-Descent/blob/main/pytorch%20MNIST%201%20layer.ipynb)
  * Failed attempt to reproduce results from [tensorflow MNIST 1 layer full](https://github.com/oridarshan/Deep-Double-Descent/blob/main/tensorflow%20MNIST%201%20layer_full.ipynb) in pyTorch
  * Results:  
  ![pyTorch 1 layer](https://github.com/oridarshan/Deep-Double-Descent/blob/main/images/torch%201%20layer.png)
* [pytorch MNIST 3 layers](https://github.com/oridarshan/Deep-Double-Descent/blob/main/pytorch%20MNIST%203%20layers.ipynb)
  * Failed experiment with 3 hidden layers.
  * model fails to converge
  * model takes too long to run full experiment.
  * partial results:  
  ![pyTorch 3 layers](https://github.com/oridarshan/Deep-Double-Descent/blob/main/images/torch%203%20layer.png)
