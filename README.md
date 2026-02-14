# Machine Learning and Pattern Recognition – Lab 5  

## Aim of the Lab
The objective of this lab is to detect human faces from images using Haar-cascade classifiers and extract meaningful features (Hue and Saturation) from detected face regions. It uses kNN means to visualize clustering results and analyse model behavior. 

## Methodology
The lab contained the main steps that include:

1. Face Detection: Used OpenCV’s Haar-cascade classifier to detect faces from input images and convert images to grayscale for robust face detection

2. Feature Extraction: Converted face regions from BGR to HSV color space then extracted mean Hue and Saturation values as feature vectors

3. Clustering: Applied k-Means clustering on extracted features and identify natural groupings of faces based on color characteristics

4. Template Classification: Extracted features from a template image and assign the template to the nearest cluster using the trained k-Means model

5. Visualization: Plotted clustered faces in Hue–Saturation space and display centroids and the classified template image

## Results and Observations
- Faces were successfully detected and clustered into two distinct groups
- Hue and Saturation proved effective for differentiating visual patterns
- The template image was correctly assigned to the closest cluster
- Visualization clearly showed separation between clusters and centroids

## Repository Contents
- `Lab 5-Spring 2026.ipynb` – Completed Jupyter notebook with code, outputs, analysis, and answers  
- `README.md` – Documentation summarizing the lab  
- `Figure1.png`, `Figure2.jpg` – Output visualizations from the notebook  

## Key Learnings
1. Practical application of distance-based learning methods
2. Understanding the impact of feature selection on clustering
3. Experience with k-Means and OpenCV
4. Visualization of clustering results for interpretation
5. 
## Conclusion
This lab provides practical insight into distance-based classification and clustering techniques. By combining face detection, feature extraction, and k-Means clustering, the experiment demonstrated how unsupervised learning can be applied to real-world image analysis tasks.

