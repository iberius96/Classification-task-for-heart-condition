### Project Rationale and Objective

The initial idea for the development of this projects came from the desire of obtaining a deeper understanding of tree-based algorithms and in how they can be utilized to construct models capable of making predictions in the context of supervised machine learning. One of the best ways to try an have an insight in the inner workings of any algorithm is to make an attempt at the development (from scratch) of a custom version of it. Because of this reason the main focus of this project will be in the development of an implementetion of the CART (Decision Tree) and Random Forest algorithms. Said implementetion will be developed in Python and a baseline will be established using comparable algorithms coming from the Sklearn library in order to assess the general quality of the custom implementetion.

A dataset related to the medical domain (The Cleveland Heart Disease dataset) has been chosen to construct the machine learning models that we are going to use in this project. This particular choice aims at simulating how these types of algorithms could be employed in a real-world scenario. One of the main advantages of tree-based algorithms is their ease of understanding for individuals that are not well versed in the domain of machine learning. The medical field is a perfect example of how Decision Trees could offer an easily understandable solution for medical professionals seeking for help in spotting patients at risk of having an heart condition.

### Brief Description

The dataset used in this project is the Cleveland Heart Disease dataset originally published in the UCI Machine Learning Repository. The dataset contains a snapshot of the clinical profile on admission to the hospital of more than 300 patients, together with a label indicating if an heart condition was discovered after admission.

### Features

- age: Age in years
- sex: Sex
    - Value 0: female 
    - Value 1: male
- cp: Chest pain type
    - Value 0: typical angina
        - Meets all three of the following characteristics:
            - Substernal chest discomfort of characteristic quality and duration
            - Provoked by exertion or emotional stress
            - Relieved by rest and/or nitroglycerine
    - Value 1: atypical angina
        - Meets two out of the three characteristics
    - Value 2: non-anginal pain
        - Meets one or none of the three characteristics
    - Value 3: asymptomatic
- trestbps: Resting blood pressure in mm Hg (millimiters of mercury) on admission to the hospital
- chol: Serum cholestoral in mg/dl
- fbs: Fasting blood sugar > 120 mg/dl 
    - Value 0 = false
    - Value 1 = true
- restecg: Resting electrocardiographic results
    - Value 0: normal
    - Value 1: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV)
    - Value 2: showing probable or definite left ventricular hypertrophy (left pumping chamber that has thickened and may not be pumping efficiently) by Estes' criteria
- thalach: Maximum heart rate achieved
- exang: Exercise induced angina 
    - Value 0 = no
    - Value 1 = yes
- oldpeak: ST depression induced by exercise relative to rest
- slope: the slope of the peak exercise ST segment
    - Value 0: upsloping
    - Value 1: flat
    - Value 2: downsloping
- ca: number of major vessels colored by flourosopy
- thal: Thalassemia (blood disorder in which the body makes an abnormal form or inadequate amount of hemoglobin)
    - Value 0: normal 
    - Value 1: fixed defect
    - Value 2: reversable defect
- Condition: 
    - Value 0: heart condition not present 
    - Value 1: heart condition present

## Acknowledgements

### Creators

1. Hungarian Institute of Cardiology. Budapest: Andras Janosi, M.D.
2. University Hospital, Zurich, Switzerland: William Steinbrunn, M.D.
3. University Hospital, Basel, Switzerland: Matthias Pfisterer, M.D.
4. V.A. Medical Center, Long Beach and Cleveland Clinic Foundation: Robert Detrano, M.D., Ph.D. 

### Donor

David W. Aha (aha '@' ics.uci.edu) (714) 856-8779 