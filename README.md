# CNN_TELOMERES
A convolutional neural network to detect the length of human telomeres in white blood cells.

CNN for discovery of telomere length Neural Network Architecture The model is built using Keras, utilizing TensorFlow as the backend. TensorFlow was chosen as the backend due to better performance over Theano, and the ability to visualize the neural network using TensorBoard.

This model predicts using TWO specific labels: OLD or YOUNG. This denotes the length and health of the telomere and thus the health of the patient.

After pooling, the data is fed through a single dense layer of size 128, and finally to the output layer, consisting of 2 softmax nodes.

TensorBoard CNN

![image](https://user-images.githubusercontent.com/30676606/137251077-6bdf853e-30bc-4876-abc0-9b1a4e44364b.png)




