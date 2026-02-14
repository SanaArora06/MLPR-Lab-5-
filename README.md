# Machine Learning and Pattern Recognition Lab 5  

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

<img width="639" height="451" alt="Figure1" src="https://github.com/user-attachments/assets/4e154eb8-3fe2-4aae-81fc-32e90f810698" />
The model took as input the image of plaksha faculty and distinguished between all of them. It detected 30 faces of plaksha faculty and clustered them based on hue and saturation. It used k-Means clustering to identify the faculty based on different facial features. It seperates the data points into two clusters with each cluster plots in 2D feature space. Additionally, the model also has labels, legends and grid for interpretation as well as easier understanding.

<img width="716" height="390" alt="Screenshot 2026-02-14 at 4 28 01 PM" src="https://github.com/user-attachments/assets/759e0703-247b-44c0-a03d-b5c42b3832bb" />

Next up, an image of Shashi Tharur was added so that we can identify which category he lies in and which class he is more biased towards. Once the image of Shashi Tharur was processed, model used distance-based clustering on the facial image. Haar-cascade classifier accurately detected faces and enhabled reliable feature extraction. K-means clustering grouped faces into two distinct clusters based on color characterstics, with clearly identifiable centroids. The template image was correctly classified by assigning it to nearest cluster in feature space which helps to validate the effectiveness of chosen features and distance-based approach. 

<img width="730" height="401" alt="Screenshot 2026-02-14 at 4 47 39 PM" src="https://github.com/user-attachments/assets/7a4d32b7-7b5a-4178-b79c-27fa399792d5" />

## Repository Contents
- `Lab 5-Spring 2026.ipynb` – Completed Jupyter notebook with code, outputs, analysis, and answers  
- `README.md` – Documentation summarizing the lab  
- `Figure1.png`, `Figure2.jpg` – Output visualizations from the notebook  

## Key Learnings
1. Practical application of distance-based learning methods
2. Understanding the impact of feature selection on clustering
3. Experience with k-Means and OpenCV
4. Visualization of clustering results for interpretation

## Conclusion
This lab provides practical insight into distance-based classification and clustering techniques. By combining face detection, feature extraction, and k-Means clustering, the experiment demonstrated how unsupervised learning can be applied to real-world image analysis tasks.

