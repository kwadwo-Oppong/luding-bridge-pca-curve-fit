# luding-bridge-pca-curve-fit
Parametric curve modeling of pedestrian movement on the Luding Suspension Bridge using PCA and polynomial fitting in 3D space. Includes data visualization, dimensionality reduction, projection, and reconstruction in the original coordinate system.
\section*{Luding Suspension Bridge Pedestrian Movement Analysis}

This project analyzes the movement of pedestrians across the \textbf{Luding Suspension Bridge} in China. Using a dataset of 3D coordinates, we model the bridge's catenary curve through dimensionality reduction and curve fitting techniques in $R^3$.

\subsection*{Project Objectives}

Our main goals for this project include:
\begin{itemize}
    \item \textbf{Importing and Visualizing Data}: Bringing in and displaying the raw 3D data points.
    \item \textbf{Dimensionality Reduction with PCA}: Applying \textbf{Principal Component Analysis (PCA)} to identify the plane where the bridge's curve primarily lies.
    \item \textbf{Data Projection}: Projecting the 3D data onto this identified plane to simplify the analysis.
    \item \textbf{Coordinate Alignment}: Finding an orthogonal transformation to align the plane with a standard coordinate plane.
    \item \textbf{Curve Fitting}: Fitting a \textbf{polynomial curve} to the projected data using Gaussian approximation.
    \item \textbf{Curve Reconstruction}: Reconstructing the fitted curve back into the original 3D coordinate system using inverse transformations.
\end{itemize}

\subsection*{Project Output}

The final output of this project is a \textbf{parametric equation} representing the bridge's curve in $R^3$, along with the matrix of coefficients in the chosen polynomial basis.

This repository contains all the code, visualizations, and detailed mathematical steps used to achieve these objectives.




