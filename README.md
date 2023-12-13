#  Understanding Trends and Temporal Evolution of Covid-19 Literature


This study aims to help policy-makers by providing useful insights about the domain areas most impacted during the Covid-19 pandemic. Some of the most
discussed domain during pandemic include Education, Mental health, Healthcare, Children, Technology, lockdown and Mortality as suggested by exploratory text and extensive literature data analysis done in this project.

#  methodology


##  1. Binary Classification
![image](https://github.com/mahrukhS/Trend-Prediction-Using-Covid-19-Literature/assets/66876079/1848f9a8-0864-4a56-ab5a-d6afbe349b0e)

The Binary Classification is divided into following steps: 
  ###### 1. Data Collection
  ###### 2. Data Filteration
  ###### 3. Text Preprocessing
  ###### 4. Separation of Covid-19 literature using LSTM
  ###### 5. Separation of Covid-19 literature using Machine Learning Classifiers
        
               /**** M Classifiers include SVM, Logistic Regression, Ada Boost, 
                XG Boost, KNN, Naive Bayes, Decision Tree, Random Forest   ****/
 
##  2. Multiclass Classification

![image](https://github.com/mahrukhS/Trend-Prediction-Using-Covid-19-Literature/assets/66876079/4d813368-1788-4c59-80c9-33d02d68328c)

Multiclass classification is applied on covid-separated papers. LDA Topic modelling assigns a topic to each paper based on the domain that fits best.
Multiclass Classification includes the following steps:
  ###### 1. Exploratory text analysis of covid-sepated literature
  ###### 2. Data Preparation using Natural Language Processing
                  
         /***Tokenization, dictionary, Bag-of-words (BOW) corpus ****/
         
  ###### 3. Latent Dirchlet Allcation (LDA) Topic Modelling
 
##  3. Exploratory Data Analysis (EDA): Exploring and visualising trends

![image](https://github.com/mahrukhS/Trend-Prediction-Using-Covid-19-Literature/assets/66876079/17bba26d-915f-4739-95e4-73638afeab71)

###### 1. Covid-19 Trends
###### 2. Worldwide Vaccine Trends 

# Results and Discussion 
  ###### 1. Evaluating Binary Classifier Performance Evaluation
            /*** ML Classifiers Performance ***/
            
|**Collective ROC of ML Classifiers**| **Graphical Comparison of ML Classifiers' Performance**|
| ----------------------------------- | ----------------------------------- |
| ![image](https://github.com/mahrukhS/Data-Modelling/assets/66876079/c5955b4a-5e52-4d78-b1da-6f11035551cd)|![image](https://github.com/mahrukhS/Data-Modelling/assets/66876079/543be38e-2d97-44a0-a688-4d86e49148bf) |

    /*** Among ALL 8 ML Classifiers: XG-Boost Performed Best ***/
| **Heat Map of XG-Boost**            |     **ROC of XG-Boost**             |
| ----------------------------------- | ----------------------------------- |
|![image](https://github.com/mahrukhS/Data-Modelling/assets/66876079/0398aeea-996d-4281-b410-e9e65d1d859d)|![image](https://github.com/mahrukhS/Data-Modelling/assets/66876079/902e776e-407c-46dd-bce6-110623545cb2)|

        LSTM Performance: Title-Trained LSTM and Abstract-Trained LSTM
|**Title-Trained LSTM Heat Map**| **Abstract-Trained LSTM Heat Map**|
| ----------------------------------- | ----------------------------------- |
|![image](https://github.com/mahrukhS/Data-Modelling/assets/66876079/95a2c7fd-2bfe-40fb-b138-afde9bc42239)|![image](https://github.com/mahrukhS/Data-Modelling/assets/66876079/a9a459df-6f87-4f1e-ae5f-aeba85bc3b48)|

|**Title-Trained LSTM ROC**| **Abstract-Trained LSTM ROC**|
| ----------------------------------- | ----------------------------------- |
|![image](https://github.com/mahrukhS/Data-Modelling/assets/66876079/ad4a5502-ccb6-4698-ae8c-c90bedf703e3)|![image](https://github.com/mahrukhS/Data-Modelling/assets/66876079/2c34bb6c-40e1-4d89-9eb9-555dfdc8c726)|

        Performance Comparison of XG-Boost and LSTM
<p align="center">
<img src="https://github.com/mahrukhS/Data-Modelling/assets/66876079/25c0232f-b3c0-4896-b0ad-a9bfc9300d6f.type" width="500" height="300" >
</p>


###### 2. Multiclassification Performance Evaluation
            /***LDA Performance Evaluation***/

