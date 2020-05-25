# PredictingBusesRequiredLSTM
**<h1>Predicting Number of Buses using LSTM**

Data analysis and deep learning will be used to create a model ,based on the given dataset , which will help identify the total number of buses required in order to accomodate the traffic in the future.

The dataset used has been imported from kaggle. Given below is the link for the
same.

[Adealide Transport Data](https://https://www.kaggle.com/rednivrug/unisys/kernels)

The data is of the metropolitan city Adealide. The data of this module is relatively simplified as it does not contain any missing values. We will
import the dataset using the required libraries and then perform EDA , in order to understand which of the given factors are playing a major role in determining
the load,such that the deep learning algorithm can perform to its best of abilities. The dataset will be divided into test set and training set.

The data file contains the following parameters:
* **TripID**: Unique identity of trip
* **RouteId**:Value representing the transport route
* **StopID**:Unique identity of stop
* **StopName**: Name of given stop
* **WeekBeginning**: Date reperesenting first day of any week
* **NumberofBoarding**:Count of all boarding's occured at this stop for the named trip over the previous week.
