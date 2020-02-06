# Hands-on Titanic Dataset
<p align="center">
  <img width="50%" height="50%" src="https://image.thanhnien.vn/768/uploaded/baovinh/2018_10_24/titanic_edqo.jpg">
</p>


This is the time I tried implementing machine learning models on Jupyter Notebook, given by CoderSchool, with the rule of not using `PClass`, `Sex` and `Age`. As suggested by my instructor, i mainly referenced this awesome tutorial on Kaggle - [Interactive Data Science Tutorial](https://www.kaggle.com/helgejo/an-interactive-data-science-tutorial).


## About the Dataset
This dataset is a part of the legendary ML competition, that is likely to be a `hello-world` project for anyone who wants to get started with data science projects.

In this challenge, the participants are asked to build a predictive model that answers the question: "What sort of people were more likely to survive?", using the profile data of the passengers themselves.

The fame of this dataset comes along with a lot of useful and novel solutions that anyone can learn from.

## My Approach


Within this work, I plotted some fundamental graphs with the help from the tutorial and manually built a decision tree based on previous examples in class. During the implementation, there are 2 different types of variables needed to be handled properly: numeric and categorical types.
- For categorical features, there are `Name`, `Cabin` and `Tickets` that contain too many unique values. These features are then encoded by extracting more information from the values themselves. Ex: 
    - `Title` extracted from `Name`
    - `Cabin` category from the `Cabin` number
    - `Ticket` class from the `Ticket` number
- However, as a result, only the `title` extracted from `Name` can help increase the generalization of the model.
