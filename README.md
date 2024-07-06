# Computer Vision: Stereoscopy and Disparity Map Generation

## Context
This project was carried out as part of the computer vision course at the International Francophone Institute, within the Interactive Systems Engineering program, Intelligent and Multimedia Systems (SIM) option. The main objective of this project is to implement image matching techniques to generate a disparity map, thus providing a three-dimensional perception of the scene.

## Materials and Methods
For this project, we used two stereoscopic images processed with the OpenCV library for Python. The SIFT (Scale-Invariant Feature Transform) algorithm was used to detect key points in the images due to its robustness to scale and rotation transformations. The matches were then filtered with the RANSAC (Random Sample Consensus) algorithm to eliminate incorrect matches and obtain a robust estimation of the fundamental matrix.

## Exercise Instructions
1. Calculate SIFT points on both images.
2. Match the key points.
3. Filter the matches with RANSAC.
4. Calculate the fundamental matrix.
5. Calculate the epipoles and epipolar lines.
6. Visualize the results.

## Results
The results show precise matches in areas with distinct and repetitive features, such as patterns on books and boxes. Incorrect matches were reduced thanks to the application of RANSAC, which allowed for a better estimation of the fundamental matrix. The generated disparity map shows the depth difference between the two stereoscopic images.

## Conclusion
The exercise objectives were achieved, with a successful implementation of key point detection, matching, filtering, and fundamental matrix calculation techniques. The results are as expected and demonstrate the effectiveness of the methods used. Future improvements could include the use of more advanced matching techniques and the optimization of RANSAC parameters.

## Author
Mouhammad Thahir Ousmane

## Supervision
Professor NGUYEN Thi Oanh
