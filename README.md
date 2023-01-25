# ValueEval-SemEval2023
SemEval 2023. ValueEval: Identification of Human Values behind Arguments


In this report we will assess the use of multiple technique to tackle the SemEval23 Human Value Detection challenge. This task consists
of classifying whether or not a given textual argument belongs to a given human value category. This task uses a set of 20 value categories
compiled from the social science literature. Given the fact that a textual argument could belong to multiple human value categories,
it is a Multi-Label classification task. 
Two approaches have been tested: Transformer-based, with multiple architectures and Extreme Gradient Boosting. Our results suggest that
the Transformer-based approach outperforms the XGBoost method on this task, achieving better overall performance in terms of precision,
recall and F1-score, obtaining in our best configuration (based on RoBERTa) a Macro F1-Score of 0.42.


## Structure of the repository

In the Project Report there is a complete description of the work done in order to achieve the obtained results, whereas in the
notebook there is the code implemented.