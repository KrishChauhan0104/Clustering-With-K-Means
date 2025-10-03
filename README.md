# Mall Customer Segmentation Using K-Means
## Project Overview
This project applies unsupervised learning to segment mall customers based on their demographic and spending behavior. It uses K-Means clustering, PCA for visualization, and evaluates cluster quality using the Elbow Method and Silhouette Score.

---
## Dataset
- Source: [Mall_Customers.csv](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)
- Features: ```pythonCustomerID```, ```pythonGender```, ```pythonAge```, ```pythonAnnual Income```, ```pythonSpending Score```

---
## Workflow Summary
- Load and preprocess data (drop ID, encode Gender, scale features)
- Apply PCA for optional 2D visualization
- Use Elbow Method to find optimal number of clusters
- Fit K-Means and assign cluster labels
- Visualize clusters in PCA space
- Evaluate clustering using Silhouette Score
  
