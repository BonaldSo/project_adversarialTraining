ADVERSARIAL TRAINING EXAMPLE

We investigate the performance of adversarial training. It is divided into 4 parts. First, we train a model to classify 10 different classes. After training, we can see that each class is clearly separated in the umap plot. It shows that it works quite well after training. And secondly, we use the same model to test adversarial data. We observe that the model did poorly with adversarial examples when the umap plot is like a mess. Thirdly, we train the model again, but with adversarial examples this time. We can see that after training, it did poorly when classifying normal examples, the umap plot is still like a mess. Lastly, we use the model to test adversarial data. We can see that even though it is not exactly divided into 10 classes, but more than half of the examples belonging to the same class are lying near to each other.


