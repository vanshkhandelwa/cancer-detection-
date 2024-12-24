# Cancer_Classification_Deep-Learning
Classification of Cancer Tumours into Benign And Malignant Using Artificial Neural Network(ANN)


Introduction:
1.This project focuses on the use of Artificial Neural Networks to classify a tumour as Benign or Malignant
2.The project also focuses on getting maximum accuracy by using the concept of dropping layers and earlystoping.
3.Used modern day optimisers(adam) and activation functions(relu and sigmoid).

Contents:
1.Using a csv file which contents the data regarding the dimensions and type of the tumour, I have designed a neural networks model to predict whether the a random tumour is malignant or benign.
2. The csv file contains the target variable which contains the predefined results.
3. We will split our training data in to train test split using sklearn library and calculate our models accuracy using the confusion matrix and classification report
4. The accuracy comes out to be above 90% so we can test our model on a random dataset.
5. I have used the inbuilt model of Artificial neural networks that comes with the tensorflow library.
6. As tensorflow has adopted keras as its API, we can import different functions using tensorflow that will help us prepare our neural networks model.
7. Now we will use some improvements in our model to get the best accuracy out of our model.
8. These improvements include Dropout layers and Earlystopping.
9. Dropout layers basically decreases the number of active neurons at each stage.


Observation:
1. Using sklearn library we will import confusion matrix and classification report and run them on our predicted data in comparison to our test data.
2. We will observe that our f1scorce and accuracy both are above 90%.


Conclusion:
1. We arrive at the conclusion that our model has successfully predicted approximately 90% of the cancer cases,but it can be further improved for higher accuracy.





