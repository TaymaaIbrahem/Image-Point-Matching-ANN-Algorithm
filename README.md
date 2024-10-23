# Image-Point-Matching-ANN-Algorithm

I'm excited to present my latest project on enhance Image Point Matching, Classification, and Prediction, completed in collaboration with my partner, Ragda Samnia, for our Machine Learning course. In this project, we successfully implemented both the Approximate Nearest Neighbor (ANN) and K-Nearest Neighbors (KNN) algorithms from scratch to match points between images and classify observations based on their image origins.

# Project Goal
We were tasked with finding matching points between two sets of observations stored in CSV files. Each observation represented a point sampled from an image, consisting of 132 characteristics, including coordinates (Y, X), scale, angle, and 128 additional features. Our objective was to find, for each point in the second file, an identical point in the first file.

# Approach
We built Locality Sensitive Hashing (LSH) and Randomized KD-Trees (RKDT) data structures completely from scratch to support our ANN implementation. These structures allowed our ANN model to efficiently match points between images, identifying corresponding points across different scenes. We also implemented the KNN algorithm for comparison.

# Key Highlights
Performance Optimization: We fine-tuned the ANN parameters, achieving optimal performance with k=2 for the algorithm.
Validation: The correctness of the ANN model was validated using the ratio method.
Visualization: Using the Pillow library, we displayed the top 10 best matches between image pairs, highlighting corresponding pixels to visually assess the accuracy of the results.

# How to View the Results
To see the matching results, open ml1.html and scroll down to view images of the matching points.
Alternatively, download ml1.ipynb and the accompanying files to run the code in an environment like Colab.

# Conclusion
Our evaluation of both ANN and KNN for image analysis yielded promising results. By adjusting parameters and thoroughly testing our models, we achieved strong performance in matching points between images, enhancing classification accuracy.
