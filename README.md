# Urban Planning with Machine Learning: Clustering Cities from Satellite Imagery

## Project Overview
This project implements a custom K-means clustering algorithm to identify and cluster urban centers from night-time satellite imagery. The algorithm processes 64x64 grayscale images to locate illuminated areas, representing cities, and calculates distances between these clusters. The project aims to aid urban planning by providing insights into the spatial distribution of urban centers.

## Problem Statement
Given a 64x64 grayscale image with white dots representing illuminated areas, the goal is to locate these dots and cluster them to identify cities. Subsequently, calculate the distances between these clustered city centers.

## Approach
- **Image Processing**: Converted the satellite image into a 2D NumPy array for easy manipulation.
- **Clustering**: Implemented K-means clustering algorithm from scratch to group illuminated areas into distinct clusters representing cities.
- **Optimal Clusters**: Used the Elbow Method to determine the optimal number of clusters.
- **Distance Calculation**: Calculated distances between the identified clusters (city centers).

## Key Features
- **Custom K-means Clustering**: Implemented without using external libraries like Scikit-learn.
- **Elbow Method**: Used to find the optimal number of clusters.
- **Distance Metrics**: Calculated distances between city centers to analyze urban connectivity.
- **Visualization**: Plotted the clusters and their centroids on a graph for clear representation.

## Technologies Used
- **Python**: Main programming language used.
- **NumPy**: For numerical operations and array manipulations.
- **Pillow**: For image processing.
- **Matplotlib**: For data visualization.
- **Pandas**: For data handling and manipulation.

## Getting Started
### Prerequisites
- Python 3.x
- NumPy
- Pillow
- Matplotlib
- Pandas

### Installation
Clone the repository:
```bash
git clone https://github.com/yourusername/Urban-Planning-ML-Clustering.git
cd Urban-Planning-ML-Clustering
pip install -r requirements.txt
