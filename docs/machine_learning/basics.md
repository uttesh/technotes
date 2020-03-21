Machine learning High-level steps involved.

1. Import Data
2. Clean the Data
3. Split the data into Training/Test sets data
4. Create a Model/Engine
5. Train the Model
6. Make Predictions
7. Evaluation and Improve

### 1. Import Data

We will import the data from the file system, most of them will be in CSV format or any file format

### 2. Clean the Data

We have to remove the bad data such as duplicate data, irrelevant, incomplete in the file or some cases we need to convert the text-based values to the numerical, otherwise, model/engine will learn the bad pattern, which will affect the accuracy of the prediction and lead to the wrong result as well.

### 3. Split the data into Train/Test data

We should have lots of input data for the model to learn. In the input data, we should able to divide it into 2 sets of training and testing data sets. Training will have 80% of the data and the test data set will be 20% of data.

More the Traning data prediction accuracy level will be good.

### 4. Create a Model/Engine

We need to create a model to analyze the data, there are n-number of algorithms are there for the analysis and processing, each of them will have its pros/cons on the different type of datasets for accuracy and performance.

The algorithm will decide based on the kind of problem we are trying to solve input data. there are libraries to perform this algornthm, we no need to write from scratch. a most popular one is scikit-learn

### 5. Train the Model

We need to provide the training data to the model to learn the pattern and predict the data.

### 6. Make Predictions

Once the model is trained, the model will predict the data it can be accurate or not, depending on the training data and algorithm chosen as per the data set.

### 7. Evaluation and Improve

Measure the model prediction accuracy, if the accuracy below 0.7, then we need to change algorithm/ increase train data to get the proper accuracy or proper result for the current problem we are trying to solve





