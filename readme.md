# HyperBRKGA

To test HyperBRKGA with Bayesian Walk as the Exploitation Method simply run the following command:

python main_BW.py datasets/rectangles_train.csv datasets/rectangles_val.csv 1.0

This will run 10 generations of HyperBRKGA on the rectangles dataset, with 10 individuals in the population and exploitation_method_BO.py as the exploitation method.

The first parameter, "datasets/rectangles_train.csv", is the location of the training dataset. The second parameter is the location of the validation set. The third parameter, "1.0", corresponds to the parameter r of the Training Reduction Strategy.

To run the same test with Random Walk as the Exploitation Method, run:

python main_RW.py datasets/rectangles_train.csv datasets/rectangles_val.csv 1.0
