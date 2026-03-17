# clfhousepricing project (California House Pricing Prediction)

## Goal: Predict the median house value for California districts, expressed in hundreds of thousands of dollars ($100,000) by using various housing parameters.

## Housing parameters:
```
- MedInc        median income in block group
- HouseAge      median house age in block group
- AveRooms      average number of rooms per household
- AveBedrms     average number of bedrooms per household
- Population    block group population
- AveOccup      average number of household members
- Latitude      block group latitude
- Longitude     block group longitude
```

## Software and tool requirement
1. [Github Account](https://github.com)
2. [Heroku Account](https://heroku.com)
3. [VS Code IDE](https://code.visualstudio.com/)
4. [GitCLI](https://git-scm.com/book/en/v2/Getting-Started-The-Command-Line)

### Step 1:

Create a new environment for the project

```
conda create -p venv python==3.7 -y
```
Activate it

```
conda activate venv/
```

### Step 2:

Load the california housing dataset
Prepare the complete dataset and check its info and stats

### Step 3:

Check missing values

### Step 4:

Perform Exploratory Data Analysis:
- Correleation and multicollinearity.
- Plot pairplot to visualize correlation.
- Plot independent and dependent features to visualize their correlation.

### Step 5:

- Independent and dependent feature segregation.
- Train test split
- Scaling of independent features
- dump the scaler in a pickle file

### Step 6:

Model Building:
- Train the train dataset using linear regression
- Predict on test data

### Step 7:

Checking performance of model:
- Comparing actual test target data and predicted test data
- Plotting residual graph
- Calculate mean absolute error, mean squared error, root mean squared error
- Calculate R2 and adjusted R2

### Step 8:

Predict on new data: 
- If single point data, reshape it to single row and multiple features.
- Scale the data using the transform method
- now do the prection using predict method

### Step 9:

- Dump the model in a pickle file
- Can load this pickle file in any file later on and perform predictions.

### Step 10:

Create a [requirements.txt](requirements.txt) file which contains all libraries that needs to be installed.

