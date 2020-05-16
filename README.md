
#### This project aims at creating a highly explainable while accurate model to predict whether or not a payment made by a pharmaceutical or a medical device company is a research grant. The datasets used are the 2017 Program Year Open Payments Dataset released by Centers for Medicare & Medicaid Services. By default, there are 166 features, but some of them are leaking the target information and always lead to a perfect score in terms of a variety of metrics, whereas some others don’t contribute too much to the prediction power but just make the model unnecessarily complicated. With appropriate feature selection and feature engineering, a single feature is picked to build the final model which is not only highly interpretable but also reaches an Average Precision of 94.86% over an imbalanced test dataset with size of 56350. ####

#### Please visit https://kundata.github.io/HighlyInterpretableModelforPaymentCategoryPrediction/index.html to see more details on the demo of building a highly interpretable quasi-optimal prediction model step by step. ###


