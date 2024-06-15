
![handwritten_images](https://github.com/gbulbul/simple-ANN-application-on-MNIST/assets/79763247/441a4c18-372a-4705-8b49-989ddd614378)

MNIST dataset is a benchmark dataset which was originally used to recognize handwritten numbers. MNIST has 10 classes, including grey scale (in this case) images of handwritten integers from 0 to 9. So, the task can be seen as a computer vision application when the aim is to detect images correctly as what the integer is on the given image. 


![simple_NN_on_MNIST](https://github.com/gbulbul/simple-ANN-application-on-MNIST/assets/79763247/614d0fbc-05ae-46b7-8450-d0cffc0fc7e6)

The model is depicted above, as we see it is simple as it could be with one dense layer.


![mnist_simple_nn](https://github.com/gbulbul/simple-ANN-application-on-MNIST/assets/79763247/e8190dda-fa0b-40f4-9acd-8082bff9998b)

From the figure showing the confusion matrix, we can make a conclusion that how the model did on classification task where there are 10 categories of numbers when the images of handwritten numbers were used to train the model.


![simple_nn_accuracy_loss](https://github.com/gbulbul/simple-ANN-application-on-MNIST/assets/79763247/4acbab1e-abe8-4b96-8ae0-10621082746d)

The loss and accuracy plots suggest that the model on MNIST dataset is suitable in a way that good accuracy score is achieved by the model.


Since CNNs are known for being successful at image detection, classification, a CNN model which is shown below was applied on MNIST to achieve the task of classifying the images of handwritten numbers.

![CNN](https://github.com/gbulbul/Recognizing-handwritten-numbers-by-a-simple-neural-net-and-CNN/assets/79763247/3ab8054e-02e4-4705-8857-e22ade713666)

This CNN model didn't outperform the simple NN model and its diagnostics (loss-accuracy plots & CM) are given as well.
![loss_on_MNIST_CNN](https://github.com/gbulbul/Recognizing-handwritten-numbers-by-a-simple-neural-net-and-CNN/assets/79763247/f0cc8edc-6fdb-4081-b674-71850f6195ba)

![cm_CNN_on_mnist](https://github.com/gbulbul/Recognizing-handwritten-numbers-by-a-simple-neural-net-and-CNN/assets/79763247/7b2bc33c-1614-49e4-85ce-437ad0aac05a)





