# Novel Machine Learning and Neural Network Models for Human Activity Recognition
Human activity recognition (HAR) has been widely deployed in many real-life applications, such as virtual reality interaction, rehabilitation systems, and mobile health monitoring. HAR can be roughly divided into video-based HAR which utilizes a video camera to record activity and sensor-based HAR which uses inertial, magnetic or electrocardiogram sensor signals for activity classification and recognition. Two main challenges existing in sensor-based HAR include recognition of new activity with limited training data as well as fast and accurate models for robust recognition. With the goal of tackling the challenges, this study proposes a new attribute-based Machine Learning architecture for recognizing new human activity using limited data with good accuracy (83%~93%), and a fast and accurate hybrid Neural Network (CNN-LSTM) model (99.36% accuracy and 7s computation time) for HAR. Finally this report summarizes the advantages as well as limitations of the current design and discusses the future directions.

This project utilizes the MHEALTH dataset from UCI Machine Learning Repository. The dataset contains 23 types of inertial, magnetic and electrocardiogram sensor signals recorded from 10 subjects performing 12 different activities. The number of features available in the project are 21 types of inertial and magnetic sensor signals, since the electrocardiogram signals are disregarded in this project for HAR to reduce the complexity of modeling, as well as the labels (1 to 12) encoded for 12 various activities. 

1. Dataset preprocessing - reads all the separate dataset of log files of each subject and converts them into csv files. Then it concatenates all the csv files into one single csv file.

2. Feature engineering - this file creates new features for each activity, which would be used in “predicting new activities with limited training data” file.

3. EDA - this file performs basic exploratory data analysis (EDA) on the data including data class imbalance examination, acceleration signals distribution for various activities, etc.

4. Predicting new activities with limited training data - this file performs the attribute-based machine learning approach to recognize new human activities.

5. Machine Learning Models - this file performs various kinds of machine learning models for human activity recognition.

6. Basic deep learning model - this file developed a basic Neural Network model comprising a few dense layers and fit, evaluate the mode.

7. Multi-head CNN model - this file designed the multi-head CNN model comprising 4 heads of CNN layers and a few Dense layers. Model fitting and evaluation are also performed.

8. CNN-LSTM - this file contains the best performing CNN-LSTM model design, fitting, evaluation procedures.

9. Visualization for Machine Learning and Deep Learning models - this file performs the data visualization of the performance of all the machine learning and neural network models above.
