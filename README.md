# Breast-Cancer-Identifier-Neural-Network
This program takes data such as: 
radius (mean of distances from center to points on the perimeter)
texture (standard deviation of gray-scale values)
perimeter
area
smoothness (local variation in radius lengths)
compactness (perimeter^2 / area - 1.0)
concavity (severity of concave portions of the contour)
concave points (number of concave portions of the contour)
symmetry
fractal dimension ("coastline approximation" - 1)
from a female's breasts being examined for a tumor where it is taught to identify if the tumor is cancerous or not. 

I used a traditional neural network with using relu as my activation. My best accuracy was 99% (220/223). If you have any suggestions to make this better please let me know. I have jsut started my jouney and hope to learn more.

Also before running, you need to have the data.csv downloaded before running. This is the data that the network looks at. 

For credit I got this data from KAGGLE: https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data
This data came from the UC Irvine Machie learning repository
