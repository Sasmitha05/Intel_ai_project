Iris Flower Clustering using K-Means

📚 Project Description
This project applies K-Means Clustering on the classic Iris dataset to group flowers into distinct clusters based on their physical characteristics: sepal length, sepal width, petal length, and petal width.

The Iris dataset contains 150 samples of flowers from three species — Setosa, Versicolor, and Virginica. However, in this project, species labels are excluded during clustering to simulate an unsupervised learning scenario. The objective is to evaluate whether K-Means can successfully identify natural groupings that correspond to the actual species.

🛠️ Key Steps
Data Preprocessing: Loaded the dataset, checked for missing values, and scaled the features using StandardScaler.
Clustering: Applied K-Means algorithm to group the flowers into clusters.
Optimal K Selection: Used the Elbow Method (WCSS plot) and optionally the Silhouette Score to determine the ideal number of clusters.
Visualization: Reduced dimensions using PCA (Principal Component Analysis) for 2D visualization of clusters.
Cluster Evaluation: Compared the resulting clusters with the actual species labels to assess how well K-Means separated the species.

📊 Expected Outcome
Identification of three distinct clusters representing the three species.
Insights into how well the physical characteristics of the flowers allow for species separation using unsupervised clustering.
Visualizations demonstrating the separation of clusters in reduced dimensions.

🔗 Technologies Used
Python
Pandas
Scikit-learn
Seaborn
Matplotlib

📁 Dataset
The project uses the Iris dataset, which is publicly available.

📈 Visualization Example
Elbow Method plot to select optimal K.
2D scatter plot of clusters using PCA.

🔍 Key Learnings
Application of K-Means Clustering on real-world data.
Importance of feature scaling in clustering.
Evaluating cluster quality using Silhouette Score.
Visualizing high-dimensional data using PCA.
Comparing unsupervised clusters to known class labels for evaluation.

🚀How to Run
1.Clone the repository.
2.Install the required libraries using:
      pip install -r requirements.txt
3.Run the main script:
      python iris_clustering.py
4.View the plots and clustering results in the console.
