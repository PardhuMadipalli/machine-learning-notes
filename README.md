# Machine learning notes
*Theoretical and practical concepts of machine learning*

## Reducing overfitting
### Regularization
We penalize the parameters as they become bigger. There are L1 and L2 regularization techniques as mentioned in [this article](https://towardsdatascience.com/l1-and-l2-regularization-methods-ce25e7fc831c).

## Fitting larger networks in memory
### Gradient check-pointing
During the back-propogation for a small network we generally store all the computed values. But this is a problem in deep networks. So we have to efficient store and recompute some nodes 
to balance compute and memory. See this [TensorFlow medium article](https://medium.com/tensorflow/fitting-larger-networks-into-memory-583e3c758ff9).

## Evaluation
### Perplexity
It is a variation of cross-entropy loss function where it shows how confused or perplexed the model is making the prediction. Is it confident enough? [Reference](https://huggingface.co/learn/nlp-course/chapter7/3#perplexity-for-language-models)

