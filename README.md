# Decision-Tree-ClassificationAssume that you wish to buy a car and you use a dataset to check whether your decision
of buying a model is acceptable or not. The dataset has attributes describing buying
price, maintenance cost, number of doors, capacity(number of persons), lug boot, and
safety and one binary attribute, profitable describing target value. Assume all the
attributes are categorical. Download the data from here.

(a) Train your decision tree classifier on the train-data (where you will use “profitable”),
using the impurity measure Information Gain. Test your model on test-data (where
the “profitable” label is unseen). After prediction, report the performance of the
model. Write your program such that it prints out the decision tree, in a particular
format. For example, assume that your decision tree looks like the following - the
attribute “price” is the root node and “maintenance” is the 2nd level node and
“capacity” is the third level node (under maintenance = low). “yes” and “no”
specifies the final value of “profitable”. Then the program should print out the
decision tree as follows: price = low | maintenance = low | capacity = 4 : yes |
maintenance = high : no where subsequent levels are at increasing indentations
from the left.
(b) Repeat the experiment using the decision tree algorithm implemented in Sci-kit
Learn. Report the performance on test data.
(Use the notebook file to experiment with the code)
