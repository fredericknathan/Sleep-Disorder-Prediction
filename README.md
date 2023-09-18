# Sleep-Disorder-Prediction

## The Dataset
https://www.kaggle.com/datasets/uom190346a/sleep-health-and-lifestyle-dataset

This dataset covers several factors that can lead a person to experience sleep disorders. These factors includes:
1. Person ID: A unique ID asigned to each person to differentiate oen person to another
2. Gender: The gender of the person (Male/Female)
3. Age: The age of the person (Years)
4. Occupation: The occupation of the person
5. Sleep Duration: How long the person sleeps in a day (Hours)
6. Quality of Sleep: A score ranging from 1-10, rating the person's quality of sleep (1-10)
7. Physical Activity Level: How long a person engage in physical activity daily (Minutes)
8. Stress Level: A score ranging from 1-10, rating the person's stress level (1-10)
9. BMI Category: The BMI category of the person (Underweight, Normal, Overweight, Obese)
10. Blood Pressure: The blood pressure measurement of the person (Systolic/Diastolic)
11. Heart Rate: Resting heart rate of a person in a minute (Beats per minute/bpm)
12. Daily Steps: Number of steps the person takes in a day
13. Sleep Disorder: The sleep disorder category of the person (None, Insomnia, Sleep Apnea)

## Results
After doing a few data pre-processing, the data is ready to be fit with the machine learning models.
The models that I choose to fit the data are:
1. Random Forest Classiffier
2. Decision Tree
3. Gradient Boosting
4. Support Vector Classifier (SVC)
5. K-Nearest Neighbors (KNN)
6. Naive Bayes
7. Extreme Gradient Boosting (XGBoost)
8. LightGBM
9. Logistic Regression
10. Ada Boost

The result comes as such:
![image](https://github.com/fredericknathan/Sleep-Disorder-Prediction/assets/91310022/2e995e7f-a94b-4eff-8a85-aa6792e40ab9)
With Random Forest, Gradient Boosting, XGBoost, and LightGBM all having the accuracy of 93%, it is safe to say that these machine learning algorithms has out performed the others when it comes to this dataset.
