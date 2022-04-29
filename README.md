# BASIC RECOMMENDER SYSTEM
Author: KIM DINH LOC  
Main solutions: RDD - Alternating Least Squares  
Implementation time: a day  
Data: MoviesLen 100K, 1M, 10M  
Evaluation function: RMSE, NDCG, HITRATE, MAE
Algorithm: ALS in Pyspark.MLib  
Result:   
MovieLens 1M ratings:  
 - RMSE: (iterations 20, rank 7, lambda 0.05): The RMSE is 0.8624043509387181  
 - NDCG: (iterations 20, rank 10, lambda 0.15): The NDCG is 0.9999259423752931  
 - HIT RATE: (iterations 20, rank 40, lambda 0.1): The HIT RATE is 0.026995693938390197

MovieLens 100k ratings:  
 - MAE: (iterations 20, rank 3, lambda 0.05): The best MAE is 0.7354813932904432  

MovieLens 10M ratings:
 - MAE: (iterations 20, rank 3, lambda 0.1): The MAE is 0.6852721427881018  
