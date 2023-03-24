# link_prediction_networkx

To practise Network Analysis using [The Marvel Universe Social Network](https://www.kaggle.com/datasets/csanhueza/the-marvel-universe-social-network/code?select=hero-network.csv) data. Following some of fellow contributors data preprocessing to gain an understanding how to work with network graph data. The notebooks in Marvel showed good network analysis but did not apply Link Prediction. 

Using references from other sites and examples, this notebook is an attempt to apply Link Prediction. 2 methods have been found using NetworkX to generate the features or in-built algorithm to do the link predictions. The first uses NetworkX to generate different features based on centrality and then proceed to use classifying algorithm to predict the outcome [1]. The second uses NetworkX built in algorithm such as Jaccard Coefficient, Adamic-Adar and Prederential Attachment to predict the outcome [2]. So I'll try both methods and see the result and analyse the performances.

A third and possible alternative would be to consider using Graph Neural Network (GNN). To attempt GNN, I'd use the same dataset but on another notebook. 

[1] [NetworkX Link Prediction](https://www.kaggle.com/code/mastmustu/networkx-link-prediction)   
[2] [Graph Learning](https://maelfabien.github.io/machinelearning/graph_4/)
