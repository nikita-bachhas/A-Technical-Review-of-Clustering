# A-Technical-Review-of-Clustering
This project analyses different clustering methods over three different datasets 

## Functionality
1. Cleaning and Preprocessing of datasets: Plotted pairplots, heatmaps and histograms for the three datasets to pre-analyse the data and to identify which variables to exclude  
2. Used the elbow method to use the K-means algorithm to analyse the three datasets
3. Plotted a dendrogram to use the Agglomerative Hierarchical algorithm to analyse the three datasets
4. Plotted a k-distance graph to use the DBScan algorithm to analyse the three datasets
5. Compared and evaluated the three methods to identify the advantages and disadvantages of using each clustering method

## Documentation 
All documents can be found under the [Documentation](https://github.com/nikita-bachhas/A-Technical-Review-of-Clustering/tree/main/Documentation) folder
1. Detailed report of the project: [A Technical Review of Clustering.pdf](https://github.com/nikita-bachhas/A-Technical-Review-of-Clustering/blob/main/Documentation/A%20Technical%20Review%20of%20Clustering.pdf)

## Datasets
All datasets can be found under the [Datasets](https://github.com/nikita-bachhas/A-Technical-Review-of-Clustering/tree/main/Datasets) folder
1. [Frequent Flyer Program](https://github.com/nikita-bachhas/A-Technical-Review-of-Clustering/blob/main/Datasets/FrequentFlyerProgram.xls): This dataset contains information about the behaviour of NZ Airline’s FFP customers. We have dropped two variables: PartnerTrans and FlightTrans. The models are built with the following variables: AwardMiles, EliteMiles, PartnerMiles, FlyingReturnsMiles, and EnrollDuration.
2. [Mall Customer](https://github.com/nikita-bachhas/A-Technical-Review-of-Clustering/blob/main/Datasets/Mall_Customers.csv): This dataset contains the basic information about the customers. None of the attributes has a good correlation among them and hence we used all the numeric variables when building the clustering models.
3. [Wine](https://github.com/nikita-bachhas/A-Technical-Review-of-Clustering/blob/main/Datasets/wine.csv): This dataset contains information about different types of wines. Total Phenols, Ravanoids, Hue, OD280 and Proline show a strong negative correlation with the class label. Ash_Alcanity has a positive correlation with Ash. Therefore, we dropped the variables - Ash_Alcanity, OD280, and Proanthocyanins- when we built the clustering models.

## Developed by
1. Ang Shu Hui
2. Bachhas Nikita
3. Srinivas Shruthi
4. Unnikrishnan Malavika
