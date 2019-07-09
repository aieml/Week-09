# Week-09

In Week-09 we discussed about Convolutional Neural Networks(CNN) and also neighborhood operations in image processing. Note that in this repository I have not included the training images, testing video or pickle files.
I have included the ```python CNN_for_Cats_Dogs.h5 ``` inside the codes folder which contains the learned weights and biases of the CNN used for identifying cat and dogs after training it for 10 epochs. 
Please run the ```python 4.2 Testing the CNN.ipynb ``` code to see the predictions done by the CNN for the video ```python 4.2 Funny Cat and Dog Videos Compilation   15 Minutes.mp4 ```(Please save the video inside the codes folder)

## Code Explanation

```python model.load_weights('CNN_for_Cats_Dogs.h5') ```
Saves the learned weights and biases after training to the given directory

```python model.load_weights('CNN_for_Cats_Dogs.h5') ```
loads the learned weights and biases to a exsisting Neural Network. Note that this existing NN should be in the same architecture as the trained NN.
