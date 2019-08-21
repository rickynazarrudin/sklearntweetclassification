**Sklearn Tweet Classification**

This project does a text classification by using three classes of the datasets. I use several machine learning algorithm provided by sklearn and cross-validate each algorithm to get the best one. 
But before doing the classification, i have to be able to deal with the challenge of the datasets. The content within the datasets can not be used directly, because the content still contain 'trash' information such as (@, #, RT, username, punctuation, local abbreviations, etc)
So i have to clear the data first. Here is the main step i did during this project.

1. Load dataset
2. Clear dataset from unnecessarry characters (@,#. etc)
3. Words normalization (yg > yang, dgn > dengan)
4. Stopwords
5. Stemming
6. Train
7. Test
8. Report

