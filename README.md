# BharatIntern_01
SMS Classifier 

In this project i have tried to make a SMS classifier which works on Kmeans Classifier and using NLTK libraries text preprocessing is done.

These are the steps I have used to make this classifier 

1. Data Cleaning 
2. EDA 
3. Text Preprocessing 
4. Model Building 
5. Evaluation 
6. Improvement 
8. Deploy using streamlit


First data cleaning is done by deleting Unwanted values or by removing missing / null values,
Then EDA (Exploratory Data Analysis) is done to check the distribution of the data and see what columns can be used to make the model which would have the best result.
Text Prepreocessing is done by stemming , removing special characters , removing punctuation marks. Convert to lowercase before applying all these. 
Model building includes creating a kmeans model, which works the best for textual classification in this case. 
Evaluation consists of determining the result of the model created , and then interpreting it for further improving.
Improvement consists of applying different improvement methods to increase the performance and precision of the model,
Deployment is done by using streamlit, which is a free and open-source framework to rapidly build and share beautiful machine learning and data science  web apps.

This repo consists of 
1. Model.pkl 
2. Dataset 
3. Jupyter notebook
4. vectorize.pkl
5. app.py
6. requirements.txt
7. setup.sh



To run this code , run app.py ,which would launch a local website ,  on which you can enter the data and perform the prediction 
