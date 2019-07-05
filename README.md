# Machine-Learning

Over a period of nine years in deep space, the NASA Kepler space telescope has been out on a planet-hunting mission to discover hidden planets outside of our solar system.

I developed multiple machine learning models in order to see which models were the most accurate.

Some models used scaled data others did not.
MinMaxScaler was used to scale the data.

Random forest models performed the best in terms of accuracy.

Model	                    Scaled	   Test Score
Random Forest (n_est = 180)	No	      89.57
Random Forest (n_est = 200)	No	      89.52
Random Forest (n_est = 100)	No	      89.43
Random Forest (n_est = 20)	No	      88.96
Random Forest (n_est = 20)	Yes	      86.41
Random Forest (n_est = 200)	Yes	      85.91
Random Forest (n_est = 100)	Yes	      85.82
Random Forest (n_est = 180)	Yes	      85.64
SVC (Gridsearch)	          Yes	      85.64
SVC	                        Yes	      84.68
Tree	                      No	      84.5
Logistic	                  Yes	      84.21
KNN	                        Yes	      82.3
Tree	                      Yes	      77.72
KNN	                        No	      65.9
Logistic	                  No	      65.14

