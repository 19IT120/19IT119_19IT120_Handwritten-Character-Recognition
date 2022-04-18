**Handwritten Character Recognition**

Handwritten recognition is a typical task because there exists a variety of writing ways. Due to the same situation, the computer program does not find good accuracy for the handwritten character recognition task. Machine learning and deep learning algorithms have been widely used in past literature. Some necessary steps involved in handwritten character recognition are preprocessing, segmentation, representation, training, identification, and post- processing . machine learning and deep learning techniques for handwritten character recognition based on various factors like dataset and technique used.

**Introduction**

Our purpose is to identify the impact of machine learning in the domain of character identification. Character recognition has a lot of applications in the
fields of banking , healthcare and other fields for searchability , storability, readability, editability, accessibility, etc. to ease up various processes. Traditional machine learning techniques like a neural network, support vector machine, random forest, etc. have been used as classification techniques. Now with the advancement in the field of computer hardware and efficient research in artificial intelligence field have given emergence to deep learning algorithms. Recent articles are using deep learning for character identification. They also depict how various functions improve the performance in the filed of pattern recognition over time.

**What is character Recognition?**

There is a variety of challenges in the handwritten character recognition system. Process of the handwritten recognition system is shown in Figure1. There are two categories in character recognition: online and offline character recognition. Online character recognition involves a digital pen and tablet. Offline recognition includes handwritten and printed characters. Handwritten characters have a lot of varieties. Segmentation and without
segmentation is involved for written words. Further steps involve feature selection. Optimization can be used to speed up the process of classification. Subsequently, there is a requirement of a classification algorithm for reading features.

**What is CNN?**

A convolutional neural network (CNN) is a type of artificial neural network used in image recognition and processing that is specifically designed to process pixel data.
CNNs are powerful image processing, artificial intelligence (AI) that use deep learning to perform both generative and descriptive tasks, often using machine vison that includes image and video recognition, along with recommender systems and natural language processing (NLP).
Implementation
This system was made using deep learning concepts. Following is brief introductions about languages and services that is used for building this application.
The first task was to choose dataset. Here I have used A_Z Handwritten Alphabet dataset as this dataset contains 26 folders (A-Z) containing handwritten images in size 2828 pixels, each alphabet in the image is center fitted to 2020 pixel box. approximate 3.5 lacks images in this dataset. The dataset is suitable for testing several features or trainable classifiers. In order to simplify the comparison of algorithms, the images are divided into several categories, which also makes them suitable for training and testing classifiers.
Step 1 - Read a Data from given dataset.
Step 2 - Split data into images and their labels.
Step 3 - Shuffling the data.
Step 4 - Reshaping the training & test dataset so that it can be put in the model.
Step 5 - Doing Some Predictions on Test Data.
Step 6 - Doing Prediction on External Image

**prerequisites for this project:**

Python (3.7.4 used)
IDE (Jupyter used)
Required frameworks are

Numpy (version 1.16.5)

cv2 (openCV) (version 3.4.2)

Keras (version 2.3.1)

Tensorflow (Keras uses TensorFlow in backend and for some image preprocessing) (version 2.0.0)

Matplotlib (version 3.1.1)

Pandas (version 0.25.1)


Handwritten character recognition is a complex problem because of a variety of character in different languages. The complex architecture of characters is another major reason that makes the handwritten character recognition task stuff. Research in this direction focuses on segmentation procedures, feature extraction procedure, and classification algorithms. Various machine learning techniques have been used for solving the same problem. Initially, we presented a procedure of handwritten character recognition for English language.
