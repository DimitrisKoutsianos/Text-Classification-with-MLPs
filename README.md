# Text Classification using MLPs

This assignment was part of my Text Analytics Course of the M.Sc. in Data Science program of the Athens University of 
Economics and Business. It was a group assignment with the two other group members being my classmates Despoina Angelonidi
and Eirini Mylona. It is a continuation of the previous assignment, [found here](https://github.com/DimitrisKoutsianos/Text-Classification-With-Traditional-ML-Models)

We once more decided to use the [movie review dataset](https://www.cs.cornell.edu/people/pabo/movie-review-data/) which is released 
by the Cornell University.

This time we first trained a Dummy Classifier and a SVM Classifier with the same parameters found from the Grid Search we performed
on the previous assignment, and a MLP utilizing `keras`, the parameters of which we tuned using `keras-tuner`.

As before, we present the learning curves of the MLP, as well as the Precision-Recall Curves of both the `positive` and the `negative` classes.