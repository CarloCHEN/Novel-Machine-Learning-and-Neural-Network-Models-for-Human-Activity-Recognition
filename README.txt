This README.txt file is a description of various python code files in the project.


1. Dataset preprocessing - reads all the separate dataset of log files of each subject and converts them into csv files. Then it concatenates all the csv files into one single csv file.
2. Feature engineering - this file creates new features for each activity, which would be used in “predicting new activities with limited training data” file.
3. EDA - this file performs basic exploratory data analysis (EDA) on the data including data class imbalance examination, acceleration signals distribution for various activities, etc.
4. Predicting new activities with limited training data - this file performs the attribute-based machine learning approach to recognize new human activities.
5. Machine Learning Models - this file performs various kinds of machine learning models for human activity recognition.
6. Basic deep learning model - this file developed a basic Neural Network model comprising a few dense layers and fit, evaluate the model;
7. Multi-head CNN model - this file designed the multi-head CNN model comprising 4 heads of CNN layers and a few Dense layers. Model fitting and evaluation are also performed.
8. CNN-LSTM - this file contains the best performing CNN-LSTM model design, fitting, evaluation procedures.
9. Visualization for Machine Learning and Deep Learning models - this file performs the data visualization of the performance of all the machine learning and neural network models above.