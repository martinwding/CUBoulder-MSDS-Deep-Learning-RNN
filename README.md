# CUBoulder-MSDS-Deep-Learning-RNN

## 1. The Project
### 1.1 Project Description
The aim of this project is to build an RNN model that classifies Tweets into real disasters and non-disasters. 

### 1.2 Project Background
With the growing adoption by users around the globe, social media and especially Twitter has become an important communication channel in times of emergency.

The ubiquitousness and convenience of portable devices such as smartphones and tablets, enable users to report an emergency they are observing in real-time. As a result, many agencies, including governments, disaster relief NGOs, as well as media outlets have become increasingly interested in monitoring Twitter posts (or tweets) to discover breaking events from ground zero.

However, due to the huge volume of tweets posted (estimated to be over 350,000 tweets per minute), it is impossible to classify these tweets manually. Therefore, agencies have turned to machine learning models to help them automatically monitor and filter out tweets that are about real disasters. These much smaller subset of tweets can then be analyzed by humans as a basis for further actions.

### 1.3 Project Evaluation
The model results will be evaluated using the F1 score. The F1 score is the harmonic mean of precision and recall and it is calculated as:

$$F1 = 2 * \frac{precision\, * \,recall}{precision\, + \,recall}$$

Where

$$precision = \frac{True \, Positives}{True\, Positives \, + \, False \,Positives}$$

$$recall = \frac{True \,Positives}{True\, Positives \, + \, False \,Negatives}$$
