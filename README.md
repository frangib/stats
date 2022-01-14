# KNN K=1
Simple example to test K-nearest neighbours with K=1.

## How to:
1. Open the knn.html with your browser.
2. Click on the big square to add points to a 2D space (that is, to add training data). Each point has a label associated which can be changed with the buttons labeled from 0 to 3 (for a total of 4 classes).
3. Click on train and the clickable surface will be painted in each corrdinate with the most likely class it belongs to.

## Notes:
1. The bitmap that forms on top of the clickable surface is the distance matrix. It is mirrored along it's diagonal after clicking train.
2. Since the approach is KNN with K = 1, a certain coordinate will belong to the class of the closest training point.

## Results:

