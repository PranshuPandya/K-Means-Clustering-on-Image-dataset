## Project Title: K-Means Image Clustering with Feature Extraction on MNIST

**Overview**

This project explores the application of K-Means clustering to the MNIST handwritten digits dataset. We implement K-Means from scratch and evaluate the impact of different feature extraction techniques (raw pixels, PCA, HOG) on clustering performance.

**Prerequisites**

- Python 3.x
- Libraries:
    - scikit-learn
    - OpenCV (cv2)
    - matplotlib
    - NumPy
    - seaborn (optional, for better visualizations)

Note: The notebook will install the required libraries in the first cell.

MNIST Dataset: it will be automatically downloaded(it is already there in the dataset folder of the repository)
Notebook Structure

- K-Means Clustering Theory:
    - Brief explanation of K-Means clustering concepts.
    - Intuition behind the algorithm.
- Implementation from Scratch:
    - Code for a custom K-Means implementation.
- Dataset Introduction (MNIST):
    - Description of the MNIST dataset.
    - Sample visualizations of the images.
- Feature Extraction:
    - Rationale for using feature extraction before clustering.
- Implementation and comparison of:
    - Raw pixel data
    - Principal Component Analysis (PCA)
    - Histogram of Oriented Gradients (HOG)
- Clustering and Evaluation:
    - K-Means clustering applied with each feature representation.
    - Visualization of clusters.
    - Evaluation using metrics like silhouette score and confusion matrices.
- Results and Conclusions:
    - Summary of findings (key points from the section you provided).
    - Insights into the effectiveness of different feature extraction techniques.

**How to Run**

Execute the notebook cells in order. It will download the requirements and the dataset automatically when needed.

**References**

K-Means Clustering Intuition: A Simple Explanation of K-Means Clustering: https://www.analyticsvidhya.com/blog/2020/10/a-simple-explanation-of-k-means-clustering/
HOG: Medium Article - HOG Feature Descriptor: https://medium.com/@dnemutlu/hog-feature-descriptor-263313c3b40d