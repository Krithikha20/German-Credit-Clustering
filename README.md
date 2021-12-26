# German-Credit-Clustering
This repository aims at clustering the German Credit dataset and classify the customers based on Risk variable.

- EDA steps are performed followed by dimensionality reduction . 
- Clustering with K-means is implemented. 
- Data is classified using SVC.

### Visualization

- <b>PCA</b> 
  - A 3d view of the clusters segmented is got. We see that the clusters are well formed and segmented.
  ![Clusters](https://user-images.githubusercontent.com/94810983/147398606-79f9c5bd-496f-42b0-9777-70d79dc910b0.PNG)
  
- <b>Scatter plot</b> 
  - Visualization of clusters are done using scatter plot with first and second components.
  - We see that 3 clusters looks reasonable to identify similar samples within our data.
  ![image](https://user-images.githubusercontent.com/94810983/147398587-028fcc02-bbf5-418d-a646-83640b6f992a.png)


- <b>Explained Variance</b>
  -  Plotting of explained variance by components is visualized.
  -  It can be infered from the below image, the first two components are able to retain the original information accounting to 85% of the total and all the 3 components accounts to almost 100%.
![image](https://user-images.githubusercontent.com/94810983/147398644-2b510c89-d308-480f-91b2-4a1706da564f.png)
