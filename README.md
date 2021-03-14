# monthly-prod-wastage-ML
Using Machine Learning To Predict Resource Wastage Occurring At Drilling Sites
Drilling prospects in the United States are heavily dependent on the economic cycle.
Optimizing the process is very desirable for energy producers to maximize profits overall and/or
minimize wastage of valuable products - whether it be oil or gas. The goal of this work is to
analyze well site data from different formations in order to develop models that predict how
much water will be used in the drilling process (operating costs for the drilling company), and
predict how much flaring/venting will occur per well. In this paper, the performance of four
data-driven models with different structures including a Artificial Neural Network (ANN),
K-Nearest Neighbor Regression (KNN), Decision Tree Regression (DTR), and a Random Forest
Regression (RFR) are calculated to project future usage of water in drilling and amount of
product either vented/flared. The returned scores from the models are determined using
Monte-Carlo Cross Validation Method (MCCVM). Results show that performance of the
Artificial Neural Network is the best as it manages to compute an R^2 score for all the different
formations, however the model returns poor R^2 scores across all the formations analyzed. 
Random Forest Regression serves to be the most practical algorithm as it returns consistently
high R^2 scores and only was unable to compute one R^2 score due to the low amount of data
available for that calculation. The results of this work can be used in future regulations in
monitoring the amount of water used in drilling or how much gas is vented and or flared. The
results can also be applied to future drilling processes by companies drilling for oil/gas in any of
the formations that were studied, allowing them to optimize their drilling process.
