# Convolutional-AutoEncoder-Classifier
 A modification of the Convolutional AutoEncoder that has a Classifier attached to it.
 Based on work by:

 [https://github.com/axkoenig/autoencoder](https://github.com/axkoenig/autoencoder)
 
 
Although MNIST classification can even be done through MLP networks, By using the output of the encoder portion of an AutoEncoder, we’d be able to classify more complex images after transfer learning.

The AutoEncoder section of this project achieved a 96% reduction in size when the output of the encoder is compared against the original MNIST file.

The classifier portion of this project achieved a 88% accuracy off the outputs of the encoder.