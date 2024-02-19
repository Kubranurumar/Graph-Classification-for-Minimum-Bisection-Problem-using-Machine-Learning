# Graph-Classification-for-Minimum-Bisection-Problem-using-Machine-Learning
The graph bisection problem involves dividing a given graph G = (V, E) into two equal-sized subsets V-1 and V-2, aiming to minimize the number of edges crossing between them. This cut between V-1 and V-2 is quantified by the size of the cut. The objective is to achieve the smallest cut possible, referred to as the bisection width of the graph. This problem is recognized as NP-complete. 

The main objective of the project is to provide a solution for NP-hard problems, which cannot be solved using traditional algorithms. The focus is on the graph bisection problem, and a machine learning model is employed to predict the solution with high accuracy. 

During the study, graphs of various types are generated with a large and random range of node numbers. Two primary graph representation techniques, namely Node2vec and Deepwalk, are utilized. 

To identify the best model, various models suitable for classification problems are investigated, and the LazyPredict library is used. After research, it is decided to use AdaBoost Classification, Random Forest Classification, and XGBoost Classification models. 

GridSearchCV and RandomizedSearchCV tools are employed to select the best model parameters, aiming to achieve the optimal model. Six evaluations are conducted by matching graph representations with models, and the goal is to obtain the best combination. 

The combination that provides the best performance is determined as Random Forest model and the dataset created with deepwalk representation technique, and it is presented as an optimal solution to the graph bisection problem. 



