


# Startup Success Prediction Using Machine Learning

## Overview
This project explores the use of machine learning algorithms to predict the success of startups. Given the high failure rate of startups, predictive models can provide valuable insights to investors and venture capitalists by analyzing startup data. The machine learning models use features such as funding rounds, acquisition status, and location to determine whether a startup is likely to succeed.

## Features
- **Algorithms Used**: 
  - Support Vector Machine (SVM)
  - Random Forest Classifier (RF)
  - LightGBM Classifier (LGBM)
  - Decision Tree Classifier (DT)
- **Dataset**: Two datasets (`train.csv` and `test.csv`) are used for training and testing the models.
- **Performance Achieved**: The precision accuracies for the models were as follows:
  - SVM: 87.05%
  - Random Forest: 72.87%
  - LGBM: 94.76%
  - Decision Tree: 77.84%

## Results
- ### Each script will output:

  - **Precision, recall, and F1 scores.**
  - **Confusion matrix.**
  - **Visual plots for model performance.**
## Conclusion
This project successfully implements several machine learning models to predict the success of startups based on historical data. The LightGBM model provided the highest accuracy (94.76%) and can be used to guide early-stage startups or investors in decision-making processes.

## Future Work
- **Extend the dataset to include additional features such as market size, competition, or economic factors.**
- **Deploy the model as a web-based tool for real-time startup success prediction.**
