# Python Starter's Pack
This document is a help for someone that start in Python, we are using Python **2.7**.

## Python "Hello World"
How to print a statement, in this case the output will be Hello World.
```python
print "Hello World"
```

## Variable Assignment
How to assign a variable (=) and to calculate a new variable.

In this example, BMI stands for Body Mass Index and the calculation is
> BMI = (Weight in Kilograms / (Height in Meters x Height in Meters))

```python
height = 1.79
weight = 68.7
bmi = weight / height ** 2
print bmi
```
Output :

 21.443

## Python Data Types
- float : Real numbers
- int : integer numbers
- str : String, text
- bool : True, False
- list : Collection of values in any types and can contain different types (in [])
- dict : Collection of values by key, value and can contain only one datatype (in {})

## Packages
### Install a package
For Windows
1. Install pip (if it's not already installed) [here](http://pip.readthedocs.org/en/stable/installing/)
2. On the terminal (cmd) write ```pip install _package_name ```

### Import a Package
In your Python script, at the start of the script write
```python
import package_name
```

You can also import only a function of a package.

```python
from package_name import function_name
```

## Comparison Operators
Keywords: **<**, **>**, **<=**, **>=**, **==**, **!=**

```python
print bmi
```
Output:

array([ 21.852, 20.975, 21.75 , 24.747, 21.441])

```python
bmi > 23
```
Output:

array([False, False, False, True, False])

```python
bmi[bmi > 23]
```
Output:

array([ 24.747])

## Boolean Operators
Keywords : **and**, **or**, **not**
```python
x = 12
x > 5 and x < 15
```
Output:

True

## Control Flows
Keywords: **if**, **else**, **elif**
```python
z = 3
if z % 2 == 0 :
  print "z is divisible by 2"
elif z % 3 == 0 :
  print "z is divisible by 3"
else :
  print "z is neither divisible by 2 nor by 3"
```
Output:
z is divisible by 3

## Loops
Keywords: **for**, **while**

```python
fam = [1.73, 1.68, 1.71, 1.89]
for height in fam :
  print(height)
```

Output:

1.73

1.68

1.71

1.89

# Python Help
The following part of this document will show external documentation for Python.

## DataCamp
DataCamp provides a excellent framework to learn R or Python with short videos followed by practical exercices. Here is a list of Python courses available with the audience that should attend the course.

### Intro to Python for Data Science
This course is for someone that begain in Python. You will learn basic trics as data types, how to handle lists, how to install and load packages and basic commands in Numpy, a Python package to handle arrays.

[Link](https://www.datacamp.com/courses/intro-to-python-for-data-science)

### Intermediate Python for Data Science
This course is for somebody that already have some experience in Python. In this course you will have the basics in Matplotlib which is a library for making plots. You will learn more about dictionaries, loops, control flow. This course concludes with an interesting Case Study where you will integrate what you learn in the first two courses.

[Link](https://www.datacamp.com/courses/intermediate-python-for-data-science)

### Python Data Science Toolbox
This course will push your Python skills further. At the end of this course you will be able to write your own functions (arguments, lambda, scope, nested functions and so on).

[Link](https://www.datacamp.com/courses/python-data-science-toolbox-part-1)

### Importing & Cleaning Data
This course is for someone that needs to deal with different sources of data. This course will show you how to deal with sevral file types such as .txt, csv, Excel, SAS, Matlab, importing files from the Internet, how to interact with API's. The course concludes with a real life example of how to interact with Twitter's API.

[Part  1](https://www.datacamp.com/courses/importing-data-in-python-part-1)

[Part 2](https://www.datacamp.com/courses/importing-data-in-python-part-2)

### Introduction to Databases in Python
This course is for someone that wants to use Python to interact with databases. The course use a library called SQLAlchemy. This library translate Python into SQL. So you won't learn SQL in this course. But you will learn how to query and write into a database with SQLAlchemy.

[Link](https://www.datacamp.com/courses/introduction-to-relational-databases-in-python)

### pandas
This course is for someone that already know about Python and wants to know a powerfull package to handle data in Python. By completing this course you will gain skills for Exploratory data analysis with pandas (inspect your data, creating basic plots and so on). The two courses conclude with a Case Study where you can wrap-up your learnings.

[pandas Foundations](https://www.datacamp.com/courses/pandas-foundations)

[Manipulating DataFrames with pandas](https://www.datacamp.com/courses/manipulating-dataframes-with-pandas)

### Introduction to Data Visualization with Python
This course is for intermediate Python programmers. The course covers two libraries for data viz : Matplotlib and Seaborn. You will learn to do basic and advanced visualizations.

[Link](https://www.datacamp.com/courses/introduction-to-data-visualization-with-python)

## CodinGame
This website provide a ludic way of learning Python. You can improve the way you code algorithms by practicing coding video games.

[Website](https://www.codingame.com)

## Data Aspirant
This website is more for Data Scientists. The website give some interesting libraries for Data Science.

### Links

[Packages for Data Science](http://dataaspirant.com/2014/11/01/python-packages-for-datamining/)

[Linear Regression](http://dataaspirant.com/2014/12/20/linear-regression-implementation-in-python/)

[Recommendation Engine](http://dataaspirant.com/2015/01/24/recommendation-engine-part-1/)

## Other Links
Here is other links with tutorials in Python

[Data Visualisation with ggplot](https://dansaber.wordpress.com/2016/10/02/a-dramatic-tour-through-pythons-data-visualization-landscape-including-ggplot-and-altair/)

[Machine Learning](https://getpocket.com/redirect?url=http%3A%2F%2Fblog.socialcops.com%2Fengineering%2Fmachine-learning-python&formCheck=877552b708e11c0dfec3f455882573e5)

[Python for Data Science Tutorial](https://www.analyticsvidhya.com/blog/2016/01/complete-tutorial-learn-data-science-python-scratch-2/)


[Time Series with pandas](http://earthpy.org/pandas-basics.html)


[Use Google Analytics API with Python](http://www.marinamele.com/use-google-analytics-api-with-python)
