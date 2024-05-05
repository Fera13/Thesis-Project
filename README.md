# Thesis

This is a thesis project made by Farah Mallah, a DataScience student at Kristianstad university, Kristianstad, Sweden.

It creates a Dataset of TSP instances based on the cities of sweden and then allows you to train and use a Machine learning model (Linear Regression) to predict the Tenure of Tabu Search that can give the optimal route when solving TSP.

## How to run

1. Load the Anaconda .yaml environment in the folder named "environments" to your Anaconda Navigator.
2. Make sure all the ipynb files have that environment chosen as a kernel.
3. Create a google API key with your account.
4. Add the key to a .env file the you create.
5. Head to create_DS.ipynb and after you decide how many instances you want to create, click RunAll. This will automatically run the other needed files that hold the other needed parts and functions sequentially. The results will be added to the "TSP_instances.csv" Dataset.
6. Go to predictTenure.ipynb and click RunAll to create the ML model and get the results of training it on the Dataset.

# Code Sources and Inspiration

## Calculating eps:

- https://medium.com/@tarammullin/dbscan-parameter-estimation-ff8330e3a3bd
- https://kneed.readthedocs.io/en/stable/parameters.html
- https://www.kaggle.com/code/tanmaymane18/nearestneighbors-to-find-optimal-eps-in-dbscan

## DBSCAN/ metrics:

- https://scikit-learn.org/stable/auto_examples/cluster/plot_dbscan.html
- https://geoffboeing.com/2014/08/clustering-to-reduce-spatial-data-set-size/
- https://medium.com/analytics-vidhya/clustering-geo-location-dbscan-cadb33b0442e
- https://scikit-learn.org/stable/auto_examples/cluster/plot_dbscan.html#sphx-glr-auto-examples-cluster-plot-dbscan-py
- https://stackoverflow.com/questions/62215910/how-to-get-the-centroids-in-dbscan-sklearn
- https://www.geeksforgeeks.org/ml-intercluster-and-intracluster-distance/
- https://stackoverflow.com/questions/52403793/perimeter-of-a-2d-convex-hull-in-python
- https://blogs.sas.com/content/iml/2022/11/02/area-perimeter-convex-hull.html

## min_samples:

- https://www.kdnuggets.com/2020/04/dbscan-clustering-algorithm-machine-learning.html

## API calls:

- https://medium.com/how-to-use-google-distance-matrix-api-in-python/how-to-use-google-distance-matrix-api-in-python-ef9cd895303c
- https://www.linkedin.com/pulse/calculating-distances-using-python-google-maps-r%C3%A9gis-nisengwe/
- https://github.com/googlemaps/google-maps-services-python/blob/master/tests/test_distance_matrix.py
- https://www.geeksforgeeks.org/python-calculate-distance-duration-two-places-using-google-distance-matrix-api/
- https://stackoverflow.com/questions/45479728/calculate-distance-between-2-points-in-google-maps-using-python

## Nearest Neighbors for initial solution:

- https://jupyter.brynmawr.edu/services/public/dblank/jupyter.cs/FLAIRS-2015/TSPv3.ipynb
- https://www.youtube.com/watch?v=G8a8bJuQxnw&ab_channel=JamesHamblin

## Tabu Search:

- https://www.geeksforgeeks.org/what-is-tabu-search/
- https://jmsallan.netlify.app/blog/2023-02-03-prompting-chatgpt-to-build-a-tabu-search-algorithm/
- https://medium.com/@m.kaleia/tabu-search-gentle-introduction-46c479eb6525
- https://the-algorithms.com/algorithm/tabu-search
