# Online Shoppers Intention Prediction
The goal of this project is to design a machine learning classification system that is able to predict the purchasing intention (make a purchase or not) of a visitor to a store's website.

## Data Description
The data used in this analysis is an Online Shoppers Purchasing Intention data set provided from an ecommerce site. The data set was formed so that each session would belong to a different user in a 1-year period to avoid any tendency to a specific campaign, special day, user profile, or period.

The Dataset contains 12,330 records and 18 features (17 input and 1 output variable).

## EDA
Below are some of the highlights observed:

![2023-03-24](https://user-images.githubusercontent.com/117505903/227653006-68967867-573b-4101-8a51-eda4e6ba3309.png)

![2023-03-24 (2)](https://user-images.githubusercontent.com/117505903/227653237-a4cb219f-08da-405e-8103-de065e05632c.png)

![2023-03-24 (3)](https://user-images.githubusercontent.com/117505903/227653341-abdc2d48-7613-472d-8b7e-7465316915af.png)

## Modelling
* Predictive models used are Logistic Regression, KNeighbors Classifier, SVM, Decision Tree and Random Forest Classifier.
* Hyperparameter Tuning for the model with the best performance - Random Forest.
* Inspect Feature importance (Top 10 features)
* Evaluate with Cross Validation.

## Conclusion
* In this project, we trained models that can classify visitors to a store's website, and predict if they are likely to make a purchase on the website or not.
* Five (5) learning classifiers (Logistic Regression, KNN, SVM, Decision Tree and Random Forest) were tested.
* The Random Forest Classifier had the best performance with an accuracy of 90% and F-1 Score of 62%.
* The Page Values Feature was found to be the most important feature in determining the purchase intention of a website visitor. Other important features include the Exit rate, Bounce rate, type of pages visited as well as the duration spent on the pages.
* The cross validation result shows that the Random Forest Classifier is able to generalize to new data.

![Untitled](https://user-images.githubusercontent.com/117505903/227655014-e5e7602c-6b7f-43e0-b42c-1fd9b1d23c78.png)
