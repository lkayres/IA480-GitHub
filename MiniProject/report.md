# Average Daily Screen Time for Children

The data was obtained from the website Kaggle. It is titled **"Average Daily Screen Time for Children"** and includes the following variables:
- Age
- Gender
- Screen time type (recreational or educational)
- Day type (weekday or weekend)
- Average screen time hours
- Sample size

## Research Question
Is the average number of screen time hours affected more by age, gender, screen time type, or day type?

## Target Variable
The target variable is **average screen time hours**.

## Key Predictor Features
The key predictor features are:
- Age
- Gender
- Screen time type
- Day type

## Data Cleaning
Data cleaning was very limited, as the dataset was already well-structured and free of errors. When building the model, the variable **"sample size"** was removed, as it was not necessary for the machine learning model.

## Train/Test Split
The data was split into 80% for training and 20% for testing.

## Model Performance
The model performed very well with the following metrics:
- **RMSE**: 0.285
- **MSE**: 0.081
- **R² value**: 97.676%

## Conclusion
**Age** is the best predictor of average screen time hours.
