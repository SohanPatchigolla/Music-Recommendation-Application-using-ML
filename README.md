# Steps taken in order to predict an output:

# Pre Processing

The model uses K Means algorithm to cluster similar songs based on numerous song fearures.

This Project contains extensive data analysis to find the best features while training the model. 
I used univariate and bivariate analysis to find the corelation between features and what affects the similarity between songs.

![image](https://user-images.githubusercontent.com/70202348/173811955-cbc725d2-062c-4f4b-9a1e-217e6bb26e35.png)

# Training 

Then, I created a mini model to fit only one feature in the model.

![image](https://user-images.githubusercontent.com/70202348/173812127-f4fb34ca-4b6b-4966-a63d-c618aa78cd43.png)

Finally, I saved the labels of the clusterred data in a new csv file to reduce computation time in the future.

![image](https://user-images.githubusercontent.com/70202348/173812251-438718a8-4a9e-4e51-bcf6-04560f6b27d2.png)

# Predictions

I created a menu driven program to take user input and recommecd the top 5 closes songs.

![image](https://user-images.githubusercontent.com/70202348/173812584-7c081e9f-1ca5-4be1-807d-30f75d17bf48.png)

# Note:
This program follows unsupervised learning method, it does not need a testing dataset to predict outputs.
