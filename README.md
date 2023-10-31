# Handwritten Digit Recognition Using Deep Learning with MNIST Dataset

I've created a multi-layer neural network using Keras for handwritten digit recognition. Through 5-fold cross-validation, the model achieved an average accuracy of 98.960%, with a standard deviation of 0.097. Additionally, when evaluating the model using built-in metrics, it achieved an accuracy of 99.13%.


## Steps:

1. Library and Dataset Import: Begin by importing essential libraries, packages, and the MNIST dataset.
2. Data Preprocessing: Prepare the data for modeling through preprocessing.
3. Model Construction: Create the neural network model.
4. Model Training and Evaluation: Train and assess the model's performance.
5. Model Saving: Save the trained model for future use.
6. Prediction Generation: Employ the model to make predictions.

# Run
```
python3 predict.py
```
## About MNIST dataset:
The MNIST dataset[(Modified National Institute of Standards and Technology database)](https://medium.com/r/?url=http%3A%2F%2Fyann.lecun.com%2Fexdb%2Fmnist%2F), which stands for the Modified National Institute of Standards and Technology database, is widely recognized as one of the most popular datasets in the fields of machine learning and deep learning. This dataset consists of 60,000 training images, each measuring 28x28 pixels in grayscale, showcasing handwritten digits ranging from 0 to 9. An additional 10,000 images are reserved for testing purposes. In total, the MNIST dataset encompasses 10 distinct classes of handwritten digits.
<br/><br/>

# Resources:
[Deep Learning Introduction](https://medium.com/r/?url=https%3A%2F%2Fwww.forbes.com%2Fsites%2Fbernardmarr%2F2018%2F10%2F01%2Fwhat-is-deep-learning-ai-a-simple-guide-with-8-practical-examples%2F%235a233f778d4b)<br/>
[Install Tensorflow](https://medium.com/@cran2367/install-and-setup-tensorflow-2-0-2c4914b9a265)<br/>
[Why Data Normalizing](https://medium.com/@urvashilluniya/why-data-normalization-is-necessary-for-machine-learning-models-681b65a05029)<br/>
[One-Hot Code](https://medium.com/r/?url=https%3A%2F%2Fmachinelearningmastery.com%2Fwhy-one-hot-encode-data-in-machine-learning%2F)<br/>
[Understanding of Convolutional Neural Network (CNN)](https://medium.com/@RaghavPrabhu/understanding-of-convolutional-neural-network-cnn-deep-learning-99760835f148%20https://www.youtube.com/watch?v=YRhxdVk_sIs)<br/>
[CNN layers](https://medium.com/r/?url=https%3A%2F%2Fwww.tensorflow.org%2Fapi_docs%2Fpython%2Ftf%2Fkeras%2Flayers%2FLayer)<br/>
[K-cross Validation](https://medium.com/r/?url=https%3A%2F%2Fwww.youtube.com%2Fwatch%3Fv%3DTIgfjmp-4BA)<br/>
[Plotting Graphs](https://medium.com/r/?url=https%3A%2F%2Fmatplotlib.org%2Fapi%2Fpyplot_api.html)<br/>
