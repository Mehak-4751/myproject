# car price prediction
To be able to predict used cars market value using machine learning models.

Screenshots-
Input -
 ![image](https://user-images.githubusercontent.com/84508881/133804638-1e5983b2-4ec3-4061-87f0-e44739deb8a7.png)
 ![image](https://user-images.githubusercontent.com/84508881/133804598-1e7eddd7-f9de-4894-b691-fe2ce67d44b6.png)
	Fig1. Input screen of project which contains input like how many kms driven,fuel type etc.

Output-
 ![image](https://user-images.githubusercontent.com/84508881/133804530-9172176c-cb36-43c4-83cf-45dc49ccbb88.png)
	Fig2. Output screen of project which tells the selling price of car


Methodologies-
1)Data Preprocessing:
![image](https://user-images.githubusercontent.com/84508881/133804407-18296809-86ac-4555-b8ce-ad0d36d4bdf1.png)
Fig3. Data preprocessing steps for car price prediction

2) Data Training and Modelling:
To train and develop a model, first of all, we need to the dependent and independent variables. To find these variables, first I used to find the correlation between the variables of the output and then separates my variables into two different axes we call it x and y where the x-axis contains all the independent variable and y-axis having the dependent variable, in our model its selling price of the Used Cars.
Using sklearn.model_selection library and its train_test_split function, further this dataset is distributed in the train-test dataset using RandomizedSearchCV tuning of this model is done to find the best hyperparameters for our model prediction. 

3) Proposed Model:
![image](https://user-images.githubusercontent.com/84508881/133804338-277e3f36-8973-45fe-b3ee-7b8794e4e4c3.png)
Fig4. Fowchart of proposed model

4) Model Prediction and cross-validation:
![image](https://user-images.githubusercontent.com/84508881/133804140-e17a2196-38f4-4231-bdac-0bc5d834b5b1.png)
Fig5. Step by step explaination of model prediction


Novelty of project -
This model is based on the machine learning algorithms and we were trying to predict the selling price of the used cars based on the dataset provided at Kaggle. To predict this dataset we used two machine learning algorithms i.e. Random Forest and Extra Tress Regressor. The prediction of this model is further compared with the test dataset created by picking random values from the original dataset and the evaluation of the prediction is
further evaluated using different methods. After a complete evaluation of the predictive model, we can conclude that the accuracy of this model is very and Random Forest and Extra Tree Regression is one of the best algorithms for regression problems. These two algorithms are highly accurate and fast in prediction irrespective of the size of the dataset.

Live Link -
http://127.0.0.1:5000/
