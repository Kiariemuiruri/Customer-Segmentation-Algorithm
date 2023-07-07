# Customer-Segmentation-Algorithm
This is an Unsupervised Algorithm to segment customers in regard to their common transaction and behaviour information.
KMeans algorithm is used to learn this common pattern and cluster the customers into segments that will help the business plan for their advertisements and product placement.
Six clusters are learned by KMeans with the least Squared Sum of Error (SSE). Dataset dimension is reduced with t-SNE to create a 2D visual of the clusters as below:
<br>
!['t-SNE clusters visual](https://github.com/Kiariemuiruri/Customer-Segmentation-Algorithm/blob/main/t-SNE%20visual.png)
<br>
The objectives of this project were:
* Train an Unsupervised model in practice
* Segment customers according to their similarities in transactions and purchase patterns
* Use t-SNE for dimensionality reduction to aid plotting of a 2D visual
* Create a Pickle file for model deployment
