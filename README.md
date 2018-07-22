# iCaRL
A problem with the existing learning strategies is the fact that an existing network which was already trained on a particular class cannot be used to classify objects belonging to a different class.

If we choose to retrain our network on the new class, it automatically forgets the properties of the old class, because the weights get overridden. 

To overcome such problem, we come up with a  new training strategy, iCaRL, that allows learning in a class-incremental way.

Dataset Used: CiFAR10
Number of Classes: 10 
Number of Training Examples: 50,000
Number of Test Examples: 10,000

Parameters Used: 500 exemplars
No. of Epochs: 50
Batch Size: 75

Accuracies obtained:
Training Accuracy: 78 %
Test Accuracy: 68 %
