# CNN_TELOMERES
A convolutional neural network to detect the length of human telomeres in white blood cells.

CNN for discovery of telomere length Neural Network Architecture The model is built using Keras, utilizing TensorFlow as the backend. TensorFlow was chosen as the backend due to better performance over Theano, and the ability to visualize the neural network using TensorBoard.

For predicting two categories, OLD or YOUNG

After pooling, the data is fed through a single dense layer of size 128, and finally to the output layer, consisting of 2 softmax nodes.

TensorBoard CNN


![cnn_two_classes_tensorboard](https://user-images.githubusercontent.com/30676606/50735726-5d94d880-1181-11e9-963d-8fd1d4b54dd1.png)
