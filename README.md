# Decision-Tree-Simulation-in-Python
I try to run a simple Decision Tree simulation of Movie collectiond data by finding out how each independent variables affect budget. Using python, we can visualize the result of the decision.

1. import related libraries

![text image](https://github.com/altheanabila/Decision-Tree-Simulation-in-Python/blob/main/pic1.png)

2. Extracting the data [Movie_regression.csv](https://github.com/altheanabila/Decision-Tree-Simulation-in-Python/blob/main/Movie_regression.csv) into pandas dataframe

![textimage](https://github.com/altheanabila/Decision-Tree-Simulation-in-Python/blob/main/pic2.png)

3. Treat the missing value by replacing with mean.

![textimage](https://github.com/altheanabila/Decision-Tree-Simulation-in-Python/blob/main/pic3.png)
![text image](https://github.com/altheanabila/Decision-Tree-Simulation-in-Python/blob/main/pic4.png)

4. Creating dummy variable, for variable with string value

![textimage](https://github.com/altheanabila/Decision-Tree-Simulation-in-Python/blob/main/pic5.png)

5. Define X variable and y variable

![text image](https://github.com/altheanabila/Decision-Tree-Simulation-in-Python/blob/main/pic6.png)

6. Use test train split with test size: 0.2

![text image](https://github.com/altheanabila/Decision-Tree-Simulation-in-Python/blob/main/pic7.png)

7. import decision tree regressor, and define prediction of y

![text image](https://github.com/altheanabila/Decision-Tree-Simulation-in-Python/blob/main/pic8.png)

8. Find mean squared error and r2 score, define dot data

![text image](https://github.com/altheanabila/Decision-Tree-Simulation-in-Python/blob/main/pic9.png)

9. Display regression tree graph

![textimage](https://github.com/altheanabila/Decision-Tree-Simulation-in-Python/blob/main/pic10.png)

![text image](https://github.com/altheanabila/Decision-Tree-Simulation-in-Python/blob/main/pic11.png)
