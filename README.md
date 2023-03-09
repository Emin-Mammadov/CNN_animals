# CNN_animals
# <font color=black>**Animal Classification using Convolutional Neural Networks**</font>
This project is an implementation of a Convolutional Neural Network (CNN) for image classification using TensorFlow and Keras. The goal of the project is to classify images of animals into three different classes: cats, dogs, and elephants.

The project is divided into several stages:

1. <font>**Data Acquisition**</font>: The dataset of images was obtained from the Flickr API using the FlickrAPI library. The dataset contains images of cats, dogs, and elephants.
2. Data Preprocessing: The preprocessing stage involved resizing the images, normalizing the pixel intensities, and splitting the dataset into training, validation, and test sets. This stage used OpenCV and TensorFlow libraries to preprocess the data. Images with incompatible extensions were removed.
3. Model Building: The model was built using Conv2D, MaxPooling2D, Flatten, Dense, and Dropout layers. The model used the softmax activation function for the output layer to output probabilities for the three classes.
4. Model Training: The model was trained using the training set, and its performance was evaluated on the validation set after each epoch. The best model was saved to disk.
5. Model Evaluation: The performance of the model was evaluated on the test set using various metrics such as accuracy, precision, and recall.
6. Testing on Out-of-Sample Data: The model was tested on out-of-sample data by manually downloading and selecting images of cats, dogs, and elephants from the web.

Additionally, a Telegram bot was implemented using the python-telegram-bot library to provide updates on the training process via Telegram.

The final model achieved an accuracy of 100% on the test set.
Overall, this project demonstrates the use of CNNs for image classification tasks and provides a working example of how to build, train, and evaluate a model.
