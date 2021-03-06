# Melbourne Housing Prediction Project
**Python v3.6 (not compatible with 2.7)**

**Setup**
- Download [Python](https://www.python.org/downloads/) to run the code.
- Download [Anaconda](https://www.anaconda.com/download/) for environment management.
- Download [VSCode](https://code.visualstudio.com/download) or a text editor of your choice.

1. Download the CSV file from kaggle [here](https://www.kaggle.com/anthonypino/melbourne-housing-market?)

2. Follow instructions and definitions in commented code

3. This is a test of the Gradient Boosting algorithm to determine how capable it is of predicting housing prices given a set of training data. Results vary greatly based on the hyperparameters of the algorithm. Feel free to play with the variables as much as you like. Data varies each time the operation is run because of the shuffling and separation of training versus test data.

4. Expected results are approximately that Gradient Boosting given these hyperparameters will allow you to be within ~$100,000 on training data and within ~$150,000 on test data. These numbers indicate that there may be some overfitting with the training data, but are within reason considering the data range of prices is $8 million. A large percent of the houses prices are over 7 figures as well, so $150k variance is reasonable.

5. The ModelTesting.py dumps a pkl file after being run which is used by InidividualPrediction.py to determine potential based on given input. Any modifications to ModelTesting will result in a different evaluation when running IndividualPrediction. Parameters are already entered, but can be changed to test new data points.
*Sample address used: 8 Keeshan Ct, Altona VIC 3018, Australia*

6. **Optional** *Takes significantly longer to run* - GridTesting.py is an algorithmic adjustment that takes a set of potential parameters for each hyperparameter and attempts to take the most optimal combination of the potential options you've set before it. In testing, it takes much longer as it has to evaluate each option before deciding on the most optimal combination outcome. Suggestion: Set a low, medium, and high option for each hyperparameter.
