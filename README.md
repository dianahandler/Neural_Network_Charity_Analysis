# Neural_Network_Charity_Analysis

## Overview
The purpose of this analysis was to incorporate both aspects of neural networks and machine learning to classify whether applicants will succeed if offered funding by Alphabet Soup. A deep learning neural network model was trained in order to assess the success rate from past companies that received funding from Alphabet Soup.


### Data Preprocessing

- The target variable from the dataset was labeled IS_SUCCESSFUL
- Features of our model: all other columns(sans target variable)
- Variables that were not considered as either target or features were those that do not contribute data that could affect our outputs. Such variables include identifiers such as EIN and NAME

### Compiling, training, and evaluating the model

- Two layers were used. One had 80 neurons and the second 30 neurons. 3 activation functions were utilized, one in each hidden layers and one in each output
- I was unable to reach an accuracy of 75%. The accuracy scores were as follows: .725%, .724%, .725%

<img width="1033" alt="Screen Shot 2021-09-16 at 7 52 11 AM" src="https://user-images.githubusercontent.com/82029390/133607487-be505d4f-2b91-4d9f-8a2b-4d9c3868b386.png">

<img width="1023" alt="Screen Shot 2021-09-16 at 7 52 30 AM" src="https://user-images.githubusercontent.com/82029390/133607534-91d68853-4ab8-47c2-b3d2-31be3f0d026f.png">

<img width="1040" alt="Screen Shot 2021-09-16 at 7 52 53 AM" src="https://user-images.githubusercontent.com/82029390/133607557-6cd5bb84-fd45-4121-af16-abedfd576b9e.png">





### Summary
While the goal accuracy score of 75% was not achieved, I was able to generate a score of 73% for a model to predict the success rate of future companies funded by ALphabet Soup. I would recommend a supervised machine learning model that could classify and create regression models that would not be so subject to overfitting.

