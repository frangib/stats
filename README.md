# KNN K=1
Simple example to play around with K-nearest neighbours with K=1.

## How to:
1. Open the knn.html with your browser.
2. Click on the big square to add points to a 2D space (that is, to add training data). Each point has a label associated which can be changed with the buttons labeled from 0 to 3 (for a total of 4 classes).
3. Click on train and the clickable surface will be painted in each corrdinate with the most likely class it belongs to.

## Notes:
1. The bitmap that forms on top of the clickable surface is the distance matrix of the added points. It is mirrored along its diagonal after clicking train.
2. Since the approach is KNN with K = 1, a certain coordinate will belong to the class of the closest training point.

## Results:
![1](https://user-images.githubusercontent.com/44316116/149491715-16013ff6-e62f-4adb-92da-a41a2f605e68.png)
![4](https://user-images.githubusercontent.com/44316116/149491701-f1fbf0b5-3f1c-4487-a06b-2bf8a164f921.png)
![3](https://user-images.githubusercontent.com/44316116/149491707-26f2e053-c014-4682-939d-5fa49ed1ffcc.png)
![2](https://user-images.githubusercontent.com/44316116/149491711-bd9d6eb4-62f4-4b80-a1f9-7265591150a2.png)

## Some distance matrices:
![dm3](https://user-images.githubusercontent.com/44316116/149492499-56d750eb-be34-45d9-b2f4-5329ec96d577.png)
![dm1](https://user-images.githubusercontent.com/44316116/149492507-d885d69f-1ae4-4a05-a67b-d79831833168.png)
![dm2](https://user-images.githubusercontent.com/44316116/149492506-6c8c4741-3a40-40a5-ad6b-394d3ad30c25.png)

