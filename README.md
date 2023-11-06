# Polynomial Regression
## 1 Data:
The csv file contains the times of solving a 4x4 Rubik's Cube, as the number of solutions increases, the time to solve decreases.
Data from csv file is transform to DataFrame type. time of cube solve from format minutes:seconds:milliseconds is changed to seconds.

## 2 Model
Model use second degree of **Polynomial Regression** to predict future progress of solving cube 4x4.
