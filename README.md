# ALS_algorithm_adaptation_Spark

This is the final project for my Database Management class at Ecole Polytechnique (MSc Data Science, 2019-2020).
I worked with 2 classmates ([Tommy Tran](https://github.com/TommyTranX) and Constantin Vodé) to implement the Alternating Least Square (ALS) Matrix Factorization algorithm (used for recommender systems) with Spark.

We started from the paper "Fast Matrix Factorization for Online Recommendation with Implicit Feedback" (X.He, H.Zhang, M.Kan, T.Chua, National University of Singapore, 2017), which you can find in this repository.

The paper shows that ALS algorithm can be easily parallelized, but no MR implementation is provided. Our work consisted in developing a Spark version of the algorithm and performing experimental analysis on one of the datasets used by the paper.
