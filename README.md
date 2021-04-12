# Digit Recognizer

#### Competition Description
MNIST ("Modified National Institute of Standards and Technology") is the de facto “hello world” dataset of computer vision. Since its release in 1999, this classic dataset of handwritten images has served as the basis for benchmarking classification algorithms. As new machine learning techniques emerge, MNIST remains a reliable resource for researchers and learners alike.

In this competition, your goal is to correctly identify digits from a dataset of tens of thousands of handwritten images. We’ve curated a set of tutorial-style kernels which cover everything from regression to neural networks. 
##### Data
train.csv : 785 columns, including the 'Label', is the digit that was drawn by the user.The rest of the columns contain the pixel-values of the associated image.<br>
test.csv : 784 columns. The columns contain the pixel-values of the associated image.<br>
sampleSubmission.csv : default form of files to submit<br>
submission.csv : submission file I created<br> 

##### Used libraries
- numpy
- pandas
- matplotlib
- seaborn
- train_test_split
- Sequential
- Dense, Dropout, Flatten, Conv2D, MaxPool2D, BatchNormalization
- Adam
- ImageDataGenerator
- confusion_matrix