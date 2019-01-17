# Recommender_system
Recommender System using Auto Encoders

## AutoEncoders
Despite its somewhat initially-sounding cryptic name, autoencoders are a fairly basic machine learning model. Autoencoders (AE) are a family of neural networks for which the input is the same as the output. They work by compressing the input into a latent-space representation, and then reconstructing the output from this representation.

Despite the fact, the practical applications of autoencoders were pretty rare some time back, today data denoising and dimensionality reduction for data visualization are considered as two main interesting practical applications of autoencoders. With appropriate dimensionality and sparsity constraints, autoencoders can learn data projections that are more interesting than PCA or other basic techniques.

For more on AutoEncoders -https://towardsdatascience.com/deep-inside-autoencoders-7e41f319999f 
https://towardsdatascience.com/autoencoders-bits-and-bytes-of-deep-learning-eaba376f23ad

The dataset that we are using is 1 million movie reviews which is freely available to download
https://grouplens.org/datasets/movielens/

All the details regarding the dataset is included in the dataset floder.

Our goal is built a recommender system to provide personalized information by learning the user’s interests from traces of interaction with that user.We have used the Auto Encoder Model of the Deep Learning to achieve the task.
