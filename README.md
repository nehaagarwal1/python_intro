# python_intro

Array- An array is a special variable that can hold more than one value at a time. Both the list and array look similar but one major difference is that an array is optimized for arithmetic computations.

Syntax -  arr = np.array([1,2,3])

 

Matrix-A Matrix is a 2-Dimensional array. It has both rows and columns. The horizontal arrangement of data is known as row and the vertical arrangement of data is known as column.

Syntax - mat = np.array([[1,2,3,1],[4,5,6,4],[7,8,9,7]])

The above code will create a matrix (mat) with 3 rows and 4 columns

|1,2,3,1|
|4,5,6,4|
|7,8,9,7|


# Table for mathematical functions and their corresponding numpy functions:

Mathematical Functions	Numpy Functions  
log10(x)	numpy.log10()
loge(x)	numpy.log()
log2(x)	numpy.log2()
exp(x)	numpy.exp()
sin(x)	numpy.sin()
cos(x)	numpy.cos()
tan(x)	numpy.tan()

# Matrix operations mainly involve three algebraic operations which are the addition of matrices, subtraction of matrices, and multiplication of matrices.

Addition: 
To add matrices, they must be of identical order. Below is one example of matrix addition for 2x2 matrices -

![image](https://github.com/user-attachments/assets/28a493df-7bfd-4289-9ddd-fc72e322c4ed)

Subtraction:
Similarly, to subtract matrices, they must be of identical order. Below is one example of matrix subtraction for 2x2 matrices -

![image](https://github.com/user-attachments/assets/7ab3b376-151b-49bd-80a6-69c59bbaf50c)

Multiplication:
There are two types of multiplication for matrices: scalar multiplication and matrix multiplication.

The term scalar multiplication refers to the product of a real number and a matrix. In scalar multiplication, each entry in the matrix is multiplied by the given scalar(that is a number). Below is one example of scalar multiplication where alpha is a scalar -

![image](https://github.com/user-attachments/assets/cbd6b027-8453-45a9-b2fa-e3d4e02ef25c)

For matrix multiplication, the number of columns in the first matrix equals the number of rows in the second matrix. Below is one example of matrix multiplication for 2x2 matrices -

![image](https://github.com/user-attachments/assets/a3b111b4-059d-4aa5-84da-f5bcd79b0b3e)


# What is a Distribution?
A distribution is a collection of data or values on a variable. It is simply the spread of the data which shows all possible values of the dataset and how they occur. We can represent the distribution of data graphically by arranging the values in ascending order and applying some appropriate functions.

 

Uniform distribution
A uniform distribution is a statistical distribution where the data contains an infinite number of equally likely measurable values and it can take any real value within a specified range.

Consider, we are generating some random numbers between 10 and 20. Within this interval, there are infinitely many values ( e.g 10.01, 10.001, 10.0001, 12.01, etc. up to 20) from which we will be choosing some numbers randomly. Now, each of these values has an equal chance of getting selected by us. So, if we list down the probabilities and plot a graph it will look like below



There are two types of uniform distribution - discrete and continuous. 

 

Normal distribution
Let’s begin with an example -

Height(in ft) : 3, 3, 4, 4, 4, 5, 5, 5, 5, 5, 6, 6, 6, 7, 7

Here, the average (mean) height is :

(3+3+4+4+4+5+5+5+5+5+6+6+6+7+7)/15 = 5

We can see that the data having the average (mean) value tends to be more frequent while data having values that are away from the mean are less and less frequent. So if we plot these data points, we will get a graph something like below -


It is clear that the data in this situation tend to clump around the mean and it creates a bell-shaped curve with most of the values in the middle. This type of data is called normally distributed.

In our case, the data has mean = 5 and standard deviation = 1.21. When a normal distribution has mean = 0 and standard deviation = 1, we call it ‘Standard Normal Distribution’


![image](https://github.com/user-attachments/assets/e757ba0c-82f7-4ae9-a911-ae9f097742a4)


