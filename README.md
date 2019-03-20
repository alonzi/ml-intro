# ml-intro
This repo contains materials for a introductory workshop to machine learning in python with sci-kit learn.

## Who am I?
* [Data Scientist with the Data Science Institute](https://dsi.virginia.edu/people/peter-alonzi)
* I like to be interrupted with questions! Please jump right in.

## Welcome to the UVA Library
* [Research Data Services](https://data.library.virginia.edu/)
* [Workshop Series](https://data.library.virginia.edu/training/)
 
## Getting Python
* [Windows](https://www.anaconda.com/download/#windows)
* [Mac](https://www.anaconda.com/download/#macos)

## Getting scikit-learn
* https://scikit-learn.org/stable/
* https://scikit-learn.org/stable/install.html
  * <pre>pip install -U scikit-learn</pre>
  * <pre>conda install scikit-learn</pre>

## Test system
The <code>$</code> means bash prompt. The <code>>>></code> means python prompt. The indented bullets represent output.
* <code> $ python --version </code>
  * <code> Python 3.7.1 </code>
* <code> $ python </code>
* <code> >>> import sklearn </code>
  *  <code> >>> </code>


# Goals for Today
1. Get scikit-learn running
2. Get comfortable with scikit-learn and machine learning workflows with  it
3. Learn how to look up help

## Outline (3 examples)
1. [Linear Regression](https://scikit-learn.org/stable/auto_examples/linear_model/plot_ols.html#sphx-glr-auto-examples-linear-model-plot-ols-py)
2. help resources
    1. scikit-learn documentation
    2. stack overflow
3. [Logistic Regression](https://scikit-learn.org/stable/auto_examples/linear_model/plot_iris_logistic.html#sphx-glr-auto-examples-linear-model-plot-iris-logistic-py)
    

# Linear Regression
The first example we will look at is from the scikit-learn webpage. The focus is pedagogical and on the main components of the machine learning workflow. Because this is a fundamental example. We are not teaching the best practices. To  understand the  best practices you  first need some undertanding of the building blocks.

* [Linear Regression Example](https://scikit-learn.org/stable/auto_examples/linear_model/plot_ols.html#sphx-glr-auto-examples-linear-model-plot-ols-py) 
    1. Import packages
    2. Load the data
    3. Split the data into training/testing
    4. Split the targets into training/testing
    5. Create linear regression object
    6. Train the model
    7. Make predictions
    8. Evaluate
    9. Visualize
    
# Getting Help
It is essential to learn how to get help without the delay of waiting for another person to respond.  To suceed in this endeavor you must be able to solve your own problems with the help of reference materials. You will encounter a combination of components that is unique and requires a hand tailored solution. However each individual component is  likely already  solved and understood through use of tools readily available online. The key is to know how to use those tools and how to discern high quality information from low quality information.

### scikit-learn documentation
The best way to navigate the scikit-learn documentation is with google. It is critical to know how to compose a google search. For example if you are going to use the function "sklearn.linear_model.LogisticRegression" the proper way to search is:
* <code>documentation sklearn logisticregression</code>
* ![]()


# How to Practice
Check out this page from the scikit-learn mothership.
* https://scikit-learn.org/stable/auto_examples/index.html

1. Recreate the example yourself
2. Ask a friend to review the code
  * [People centric guide to code review](https://phauer.com/2018/code-review-guidelines/)
  * [Code centric guide to code review](https://www.ibm.com/developerworks/rational/library/11-proven-practices-for-peer-review/)
