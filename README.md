# Diamond-Price-and-Quality-prediction

Link for the dataset used in this project:https://www.kaggle.com/ronil8/diamond-price-prediction-dataset**


Result of all the algorithm used in this predictive modelling of diamond price and quality prediction:
a.MSE,MAE,RMSE value for regression data:
1.RandomForestRegressor:
MSE: 313629.07056677254
MAE: 285.01803467501617
RMSE: 560.0259552616936
2.AdaBoostRegressor:
MSE: 1589836.0503452853
MAE: 921.7152439392019
RMSE: 1260.8870093490873
3.GradientBoostingRegressor:
MSE: 512093.7359420602
MAE: 387.732982512005
RMSE: 715.6072497830497
4.XGBRegressor:
MSE: 517963.49568217865
MAE: 390.5980194453889
RMSE: 719.6968081645066
5.LinearRegression:
MSE: 1918378.6107652846
MAE: 841.1202940736883
RMSE: 1385.0554540397595
6.SVM:
MSE: 11480936.806199664
MAE: 1954.4744923406818
RMSE: 3388.3531112030905

ii.Accurcay value of all the algorithm for classification data:
1.RandomForestClassifier: 79%
2.AdaBoostClassifier: 67%
3.GradientBoostingClassifier: 76%
4.XGBClassifier: 74%
5.LogisticRegression: 59%
6.SVM: 62%


Conculsion:For Regression as well as for classification in both cases 'RandomForest' algorithm performed very well in comparision to other algorithm.To improve the result more toward better side can be done with the help of Hyper parameter optimization or tuning technique like Randomizedsearchcv,Gridsearchcv(Non-Automated) and Genetic-Algorithm:TpotClassifier(Automated method) with this we can improve the result more toward better side
