# Thesis

This is a thesis project made by Farah Mallah, a DataScience student at Kristianstad university, Kristianstad, Sweden.

It creates a Dataset of TSP instances based on the cities of sweden and then allows you to train and use a Machine learning model (Linear Regression) to predict the Tenure of Tabu Search that can give the optimal route when solving TSP.

## How to run

1. Load the Anaconda .yaml environment in the folder named "environments" to your Anaconda Navigator.
2. Make sure all the ipynb files have that environment chosen as a kernel.
3. Get a google API key with your account.
4. Add the key to a .env file the you create.
5. Head to buildingDS_secondPart.ipynb and after you decide how many instances you want to create, click RunAll. This will automatically run buildingDS_firstPart and buildingDS_secondPart sequentially and add the instances to the "TSP_instances.csv" Dataset.
6. Go to predictTenure.ipynb and click RunAll to create the ML model and get the results of training it on the Dataset.
