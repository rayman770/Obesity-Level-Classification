# Obesity-Level-Classification
![obesity](https://www.thepharmaletter.com/media/image/obesity_big-2.jpg)

- **Dataset Source**
    - https://archive.ics.uci.edu/ml/datasets/Estimation+of+obesity+levels+based+on+eating+habits+and+physical+condition+


- **Context of Dataset**
    - The dataset includes data for the estimation of obesity levels of individuals from Mexico, Peru and Colombia based on their eating habits and physical condition.
    - The dataset contains 2,111 records and 17 attributes, one of which is NObesity (Obesity Level) as the class attribute. 
        - Insufficient Weight 
        - Normal Weight 
        - Overweight Level I 
        - Overweight Level II 
        - Obesity Type I 
        - Obesity Type II 
        - Obesity Type III.
    - 77% of the data was generated synthetically using the Weka tool and the SMOTE filter, 23% of the data was collected directly from users through a web platform.


- **Attribute Information**
    - Gender = Gender
    - Age = Age
    - Height = Height
    - Weight = Weight
    - family_history_with_overweight = Family histroy with overweight
    - FAVC = Frequent consumption of high caloric food
    - FCVC = Frequency of vegetables consumption
        - 1: Never
        - 2: Sometimes
        - 3: Always
    - NCP = Number of main meals
    - CAEC = Consumption of food between meals
    - SMOKE = Smoking status
    - CH2O = Daily water consumption
        - 1: Less than a liter
        - 2: Between 1 and 2 L
        - 3: More than 2 L
    - SCC = Calories consumption monitoring
    - FAF = Physical activity frequency
        - 0: No phyiscal activity
        - 1: 1 or 2 days
        - 2: 3 or 4 days
        - 3: 5 or more days
    - TUE = Time using technology devices
        - 0: 0 - 2 hours
        - 1: 3 - 5 hours
        - 2: More than 5 hours
    - CALC = Consumption of alcohol
    - MTRANS = Transportation used
    - NObeyesdad = Obesity Type  _**(Class Attribute)**_
    

- **Table of Content**
    - Preparing Dataset
        - Importing Dataset
        - Cleaning Synthetic Values and Preprocessing
    
    - Descriptive Analysis
        - Exploring Each Type of Variables
        - Correlation Heatmap
        
    - Predictive Analysis
        - Principal Component Analysis
        - Important attributes based on F-statistic
        - Regression Analysis (Linear)
            - Predicting Weight based on Height and Obesity Type
        - Regression Analysis (Logistic)
            - Predicting Obesity Type (Class Attribute)
        - Classification Analysis (Naive Bayes)
            - Predicting Obesity Type (Class Attribute) based on Continuous Variables (Age & Weight)
        - Classification Analysis (Decision Tree)
            - Predicting Obesity Type (Class Attribute)
        - Classification Analysis (Support Vector Machine)
            - Predicting Obesity Type (Class Attribute) based on Continuous Variables (Age & Weight)
        - Clustering Technique (Kmeans)
        - Clustering Technique (Spectral Clustering)
