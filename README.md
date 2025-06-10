# Luding Suspension Bridge Pedestrian Movement Analysis
Parametric curve modeling of pedestrian movement on the **Luding Suspension Bridge** using **PCA** and polynomial fitting in 3D space. Includes data visualization, dimensionality reduction, projection, and reconstruction in the original coordinate system.  
This project analyzes the movement of pedestrians across the **Luding Suspension Bridge** in China using a dataset of 3D coordinates. The bridge follows a catenary curve and is modeled using dimensionality reduction and curve fitting techniques in $R^3$  
The main objectives of the project include:
- Importing and visualizing the raw 3D data points.
- Applying **Principal Component Analysis (PCA)** to identify the plane in which the curve lies.
- Projecting the data onto this plane for simplification.
- Finding an orthogonal transformation to align the plane with a coordinate plane.
- Fitting a polynomial curve to the projected data using Gaussian approximation.
- Reconstructing the curve in the original coordinate system using inverse transformations.

The final output is a parametric equation representing the curve in $R^3$, along with the matrix of coefficients in the chosen polynomial basis.
This repository contains all the code, visualizations, and mathematical steps involved in achieving these goals.




