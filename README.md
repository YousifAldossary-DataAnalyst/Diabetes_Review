# Diabetes_Review

### Overview

In this project I aim to find a way to predict if a person has Diabetes. The task is straight forward find the best correlations, then create comparison between Prediction and having Diabetes. by that I will test the correlation of a person by age and BMI, then I will move in with the rest of the data and see any commen relations to Diabetes. my personal Goal here is create some analytical thinking.

###### Dataset collected from: https://www.kaggle.com/pritsheta/diabetes-dataset/tasks

- Attributes
    - 'Pregnancies', 
    - 'Glucose', 
    - 'BloodPressure', 
    - 'SkinThickness', 
    - 'Insulin',
    - 'BMI', 
    - 'DiabetesPedigreeFunction', 
    - 'Age', 
    - 'Outcome'

I have a small medical back ground so I dug deep into the medical research about Diabetes and I found there are two types I and II. Type I symptoms tend to come on quickly and be more severe. where as Type II:

- Symptoms
    - Increased thirst
    - Frequent urination
    - Extreme hunger
    - Unexplained weight loss
    - Presence of ketones in the urine (ketones are a byproduct of the breakdown of muscle and fat that happens when there's not enough available insulin)
    - Fatigue
    - Irritability
    - Blurred vision
    - Slow-healing sores
    - Frequent infections, such as gums or skin infections and vaginal infections

With more reading I found out that *insulin and glucose* are main factor of cause of type 2 diabetes. Risk factors for prediabetes and type 2 diabetes are: 

- Causes
    - 'Age', 
    - 'Weight', 
    - 'Inactivity', 
    - 'Family history', 
    - 'bnormal cholesterol and triglyceride levels',
    - 'ethnicity' 

######  Research source: https://www.mayoclinic.org/diseases-conditions/diabetes/symptoms-causes/syc-20371444

As I know from *NASM School*, I learned that the cause of Diabetes is high BMI, Blood pressure, weight and age are factors of diabetes.
Therefore, I know the the outcome here is diabetes type II. Clearly, Pregnancies are unrelated but based on the given data I must find related informations.

- Reference:<br>
    1. https://scikit-learn.org/stable/modules/generated/sklearn.metrics.confusion_matrix.html
    2. https://towardsdatascience.com/understanding-the-confusion-matrix-and-how-to-implement-it-in-python-319202e0fe4d
