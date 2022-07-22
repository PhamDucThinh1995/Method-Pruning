# Method-Pruning
>It is the method to optimize the inference 

## Decision Tree Classifier in ScikitLearn
>https://scikit-learn.org/stable/modules/generated/sklearn.tree.DecisionTreeClassifier.html

## What is pruning?
> Pruning is one of the method to optimize the model. Model pruning is the art of **discarding** those weights that do **not signify** a model’s performance. Carefully pruned networks lead to their better-compressed versions and they often become suitable for on-device deployment scenarios. It leads to a better accuracy of the model by Accelerating Inference. A tree that has too many branches and layers *can result* in overfitting of the training data.
> Pre-pruning: also known as Early Stopping Rule. Avoids generating overly complex subtrees which overfit the training data.
> Post-pruning: means to prune after the tree is built. You grow the tree entirely using your decision tree algorithm and then you prune the subtrees in the tree in a bottom-up fashion.

## Link for reference:
> Theories: https://blog.paperspace.com/neural-network-pruning-explained/#:~:text=Pruning%20methods%20differ%20in%20the%20amount%20of%20the,of%20pruning%20according%20to%20a%20more%20complex%20function.
> Theories + Tensorflow : https://towardsdatascience.com/scooping-into-model-pruning-in-deep-learning-da92217b84ac
> Theories + google colab : https://github.com/Pradnya1208/Pruning-Decision-Trees
