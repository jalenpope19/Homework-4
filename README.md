# Homework-4

Introduction:
The goal is to predict whether a given car is 'profitable' or not based on four categorical attributes: 'price', 'maintenance', 'capacity', and 'airbag' without using any built-in modules.

Dataset:
There are two datassets and they are provided from Canvas. The training data is labeled "trainData" and the testing data is labeled "testData". They are used to evaluate performance.

Tasks:
A. Train the decision tree classifier on the training data using the Random and Gini Index methods to decide on the splitting attribute.
B. Print the decision tree using code. The code will print out in a particular format similar to the example below.

price = low    # One branch of root node

| maintenance = low    

            | capacity = 4 : yes         # Reach the decision
            
| maintenance = high : no         # Reach the decision

price = high    # The other branch of root node

| …
       |….
|…
       |….
