1. How would you define machine learning?
ML is a field of study in which computers learn to complete a task without being explicitely programmed to. In a different definition, given Experience E, Task T and a Performence Measure P, a programm is said to learn if with E in regard to T its P improves.

2. Can you name four types of applications where it shines?
Spam filters, image recognition technology, speach recognition technology, detecting abnormalities in certain activity (e.g. credit card fraud).

3. What is a labeled training set?
A labeled training set is a data set sed for training a model in which each element is already labeled with a belonging to a certain class. So each element already has a solution (label) attached to it.

4. What are the two most common supervised tasks?
Classification and target value prediction.

5. Can you name four common unsupervised tasks?
Visualisation, dimensionality reduction, novelty and anomaly ddetection.

6. What type of algorithm would you use to allow a robot to walk in various unknown terrains?
A reinforcement learning algorithm.

7. What type of algorithm would you use to segment your customers into multiple groups?
A clustering algorithm.

8. Would you frame the problem of spam detection as a supervised learning problem or an unsupervised learning problem?
Supervised learning.

9. What is an online learning system?
Online learning means that the model is trained incrementaly, being fed small instances of data.

10. What is out-of-core learning?
Out-of-core learning means learning by going thought a large batch of sequencially (in smaller batches), which would not fit in the machines memory as a whole.

11. What type of algorithm relies on a similarity measure to make predictions?
Instance-based learning algorithms.

12. What is the difference between a model parameter and a model hyperparameter?
Unlike model parameter, hyperparameter stays constant throughout model training.

13. What do model-based algorithms search for? What is the most common strategy they use to succeed? How do they make predictions?
--

14. Can you name four of the main challenges in machine learning?
Insufficient Quantity of Training Data, Nonrepresentative Training Data, Overfitting and Underfitting the Training Data

15. If your model performs great on the training data but generalizes poorly to new instances, what is happening? Can you name three possible solutions?
The model is clearly overfit. The first solltion wolud be to split the data into a training and a testing sets and test the model accuracy before uusing it on real data. The second way would be regularization. Another soluution would be to choose a different model.

16. What is a test set, and why would you want to use it?
A test set is sed to measure the accuracy of a trained model before sing it with real data. You would want to use it to avouid overfitting with the training set.

17. What is the purpose of a validation set?
A validation set is an "intemidiate" set between the training and the test sets. It is used to test and fine-tune the hyperparameters.

18. What is the train-dev set, when do you need it, and how do you use it?
A set used to evaluate the correctness of the model and the training set.

19. What can go wrong if you tune hyperparameters using the test set?
The model will be overfit.
