
#Abstract
 
Credit risk prediction with accuracy in the dynamic real world is always a crucial task in the finance industry, as incorrect prediction can lead to loss in billions of dollars along with rise in inflation and market downfall. While most of the Machine models make predictions based on application level itself with a large number of insignificant features, we have experimented with GNN[2] and LLMs based approaches[1] which take in account similarity between applicants and accumulate its relationships to provide improved feature embedding and provide better performance for Machine Learning Models. We have also experimented with a Multi-model ensemble[4] of various advanced classification models such Neural Network, Random Forests, KNN, etc and performance experiments on Explainable AI[4] where we are gauging which features have higher weightage or significance for specific predictions. Lastly, we have to handle class imbalance[3] and dimensionality reduction to have more accurate predictions required for dynamic real work data. Experiments based on above approaches have shown promising results with accuracy surpassing industry benchmarks within required standard of confidence intervals providing more efficient and robust models suitable to incorporate uncertainty of the real world.
Models and Architecture Details
Advance Models:
Graph Neural Network: Graph of customer relationship is created using cosine similarity score of threshold greater than 80 percent. Corresponding graph is then passed to Graph Neural Network for more efficient feature representation as well as classifying high risky customers with improved accuracy. Graph Neural Networks improve feature embedding by combining neighbour customers having high similarity to provide more generalised representation, improving gap between decision boundaries of two classes resulting in efficiency classification of clients.
[7]
 
Large Language Models(LLMs): Natural Language based customer profiling[1] is done by transforming data points in the dataset into language representation which can easily be learned by LLMs like BERT and provide mode enhanced representation of feature embedding which can be easily classified using a dense classification layer. We have LLMs trained on a given dataset as the model was able to represent features in terms of more core embedding level taking into consideration relationship between features as well as weighting importance of feature considering large previous history of word relationship as well as improving its classification. 
Feature Transformation(Customer profiling): 
Datapoint is convert into natural sentence for LLMs to provide efficient representation
 
 
Multi Model Ensemble Learning: In this method, we are combining multiple models such as Logistic Classifier, SVM, Random forest, SGD, leading to learning different data points distribution by different algorithms and effectively providing more generalised results which improves overall performance of credit prediction.[4]

Deep Neural Network:  Multilayer deep neural network is used to learn non linear mapping of feature vectors to output. Multiple dense layers leading to learning of more intricate features extraction which passed to final decision boundary leads to improving overall efficiency of credit default classification.

Diversity Models:
Naive Bayes(Probabilistics): It is based on bayes’ theorem with assumption of features independence utilising Probabilistics based approach for classification.
KNN (Non parametric):  It is a non-parametric model following majority rule by taking neighbourhood points into consideration while classification data points.

Standard Models:
Logistics Regression:  Binary classification using logistic function for accurately prediction probabilities of specific class to have efficient decision boundary.
SVC: It maximised the decision boundary between data points of two different classes by transforming data points into representation spaces using various kernels. 

Tree Based Models
Random Forest: Combined multiple random decision trees combining different possibilities and providing more generalisation in the final credit decision. 
XGBOOST: It is an efficient version of tree model using gradient boosting algorithm for providing overall optimization of trees at each incremental level.
