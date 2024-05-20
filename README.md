#Detailed Explanation of the Script

This script automates the process of loading a CSV file, identifying important columns, standardizing data, performing PCA, and clustering with KMeans. 
It then visualizes the results interactively using Plotly and Streamlit, making it an accessible tool for data exploration and analysis. 
The  PCA and KMeans helps simplify complex data into understandable clusters in the form of 0,1,2,3 clusters

#The script starts by importing necessary libraries; mentioned in the script
#The script attempts to identify a column that represents population groups, using common names like 'Population', 'population', 'Group', or 'group'

##Applies KMeans clustering to the principal components to group the data into clusters.
##Adds the cluster labels to the DataFrame.
##Why KMeans is chosen:
.....
##KMeans is a simple and efficient clustering algorithm that partitions data into K distinct clusters based on feature similarity.
##It is easy to implement and interpret, making it suitable for this visualization task.

Run Command:
python pca_population_interactive.py

Second Command:
streamlit run pca_population_interactive.py
