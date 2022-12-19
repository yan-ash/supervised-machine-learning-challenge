# supervised-machine-learning-challenge
### Background:

Lending services companies allow individual investors to partially fund personal loans as well as buy and sell notes backing the loans on a secondary market.

I will be using this data to create machine learning models to classify the risk level of given loans. Specifically, I will be comparing the Logistic Regression model and Random Forest Classifier.

### Retrieve the data
The data set used : lending_data.csv which located in the Resources folder.
Declare the X and y varible 
### Split the data into Training and Testing Data sets and Scale the dataset
![image](https://user-images.githubusercontent.com/109451707/208414986-09c3a0cc-400e-470a-9eb0-9da03424d04a.png)

### Create, Fit and Compare Models
![image](https://user-images.githubusercontent.com/109451707/208415161-4d37c18a-307d-4b54-93cb-56ac8d0752a8.png)

As we can see from the test data score is 0.9942. As a result of the classification_report, we could see Precision is 1.00.
![image](https://user-images.githubusercontent.com/109451707/208416806-e203c915-bf9e-4d0c-b25a-1c333e9a68b9.png)

### Loop through different K value to find which has the highest accuracy, create the Knn_model and fit the model and the Testing accuracy score is 0.994.
![image](https://user-images.githubusercontent.com/109451707/208416911-44779f99-37e5-4210-b2e0-3255dd9d9751.png)

### Train a Radom Forest Classifier model and we could see from the result below: 0.9920.
![image](https://user-images.githubusercontent.com/109451707/208416953-f5201f74-1284-4e1d-9d9e-e5b2317ed4d4.png)

### Found the important features below to see which factor has the most important influrence on helping the lending service companies to give loans.
![image](https://user-images.githubusercontent.com/109451707/208416986-88c71736-e7df-4b20-81b0-f3490bb02572.png)

