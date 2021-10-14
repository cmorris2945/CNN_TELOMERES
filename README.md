# CNN_TELOMERES
A convolutional neural network to detect the length of human telomeres in white blood cells.

CNN for discovery of telomere length Neural Network Architecture The model is built using Keras, utilizing TensorFlow as the backend. TensorFlow was chosen as the backend due to better performance over Theano, and the ability to visualize the neural network using TensorBoard.

This model predicts using TWO specific labels: OLD or YOUNG. This denotes the length and health of the telomere and thus the health of the patient.

After pooling, the data is fed through a single dense layer of size 128, and finally to the output layer, consisting of 2 softmax nodes.

TensorBoard CNN

![image](https://user-images.githubusercontent.com/30676606/137251194-55f15a41-39be-4678-8e30-6fd38ea10437.png)





![image](https://user-images.githubusercontent.com/30676606/137251251-7ebca418-0d2b-4005-be4d-75b61a9fbc7e.png)




