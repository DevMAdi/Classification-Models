
# Classification

This is a form of  _predictive modelling technique_  which investigates the relationship between a  **dependent**  (target) and  **independent**  variable (s) (predictor). This type of modelling is generally use to yield class of given data points such as find if gender is male or female given weight, height, body shape, BMI where former is **dependent**  variable and later are  **independent**  variables.

This repo. contains regression models such as

-   **Logistic Regression**

> estimate (guess) the probability of an event occurring having been given some previous data. **Logistic Regression** works with binary data, where either the event happens (1) or the event does not happen(0).

-   **K-Nearest Neighbors (K-NN)**

> a classifier algorithm where the learning is based “how similar” is a **data** (a vector) from other

-   **Support Vector Machine (SVM)**

> performs classification by finding the hyperplane that maximizes the margin between the two classes. The **vectors** (cases) that define the hyperplane are the **support vectors**.

-   **Kernel SVM**

> linear SVM can only find best fit/hyperplane for lineally separable dataset. For non linear dataset, we need to try different things
>  1. go to high dim. space. Take dataset & add extra dimension in space we are dealing with & in doing so make our dataset linear separable.
>  2. kernel trick to do these things in computationally more efficient way. without going to high dimension.

-   **Naive Bayes**

> A **naive Bayes** classifier is an algorithm that uses **Bayes**'
> theorem to classify objects. **Naive Bayes** classifiers assume
> strong, or **naive**, independence between attributes of data points. Popular uses of **naive Bayes** classifiers include spam filters, text analysis and medical diagnosis.

-   **Decision Tree Classification**

> **Decision tree** builds **classification** or **regression** models in the form of a **tree** structure. It breaks down a dataset into smaller and smaller subsets while at the same time an associated **decision tree** is incrementally developed. The final result is a **tree** with **decision** nodes and leaf nodes that helps to predict class

 - **Random Forest Classification**
> algorithm consisting of many decisions trees. It uses bagging and feature randomness when building each individual tree to try to create an uncorrelated **forest** of trees whose prediction by committee is more accurate than that of any individual tree.
