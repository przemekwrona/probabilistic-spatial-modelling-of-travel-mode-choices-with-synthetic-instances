# Abstarct

Understanding travel mode choices (TMCs) and the conditions influencing these decisions is crucial for promoting sustainable  transportation, including the use of public transport.
One method to explain TMCs is through machine learning models trained with real trip data. 
Importantly, much of the existing research in transport modelling using machine learning algorithms has primarily focused on evaluating model performance through aggregate accuracy metrics.
Moreover, the number of real trip records collected through surveys is inevitably limited. 
However, a promising direction involves combining the representation of model outputs in terms of the probability or odds of selecting a particular mode of transport with the presentation of these values as a function of geographic location.

Hence, in this work we propose a method providing spatial distribution of predicted travel mode choices. 
The method we propose takes advantage of two categories of trip datasets: real-world data and synthetic data.
The real-world survey data are used to train a classification model predicting travel mode choices, which is subsequently employed to predict probabilities for the trips present in a much larger synthetic dataset ensuring higher spatial density of trips. 
We compare the use of machine learning and logistic regression for the analysis of the spatial distribution of the likelihood of choosing a particular mode of transport. 
Importantly, we consider exact trip end point coordinates rather than zone centroids and consider time-dependent rather than static level-of-service attributes.
The analysis reveals the spatial variability of choices caused by e.g. time-dependent walking distances needed to use public transport.
