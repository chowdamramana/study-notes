# note : functions types use   (most of the cases)
* inbuilt functions use like  function-name(variable)
* for user defined function   function-name(value)
* for list methods            variable.function-name() 

# if we want to import inbuilt python funtion
* first we have to import that function first.

import <function name>
example:
* import math
* math.sqrt(10)    or

* we want to use inbuilt functions in python for variables use it by (variable.<inbuilt-function-name>)
name = "my name"
print(name.upper())       output: MY NAME
mobile-no = input("enter your mobile no:")
print(mobile-no.len())    output : example 10
        or
length_of_mobile_no = len(mobile_no)
print(length_of_mobile_no)
output : 10

# note:when providing string argument go with quotation marks " or ' 

*** python have a inbuilt mathmatical functions 
we import functions by 
import math
math.<math-operation>         math-operation examample: sqrt(x),factorial(x),cos(x)

# user defined function
def <function-name>:
    commands

* if we printing something in your UDF hello(), you don’t really need to return it.( when we use print command at end of statement their is no need to use return command )

* if we want to print result of the function use return statement.
* example:
    def hello():
        print("Hello World") 
        return("hello")
output: hello world

* functions immediately exit when they come across a return statement, even if it means that they won’t return any value
  The return statement is used to exit a function and go back to the place from where it was called

# when we call the function with function name it returns its output.
* example:
def plus(a,b):
  sum = a + b
  print (sum, a)
plus(3,4)

output:
   7 3

# function arguments in python
* Default arguments                   def plus(a,b = 2,5):

* Required arguments                  def plus(a,b):
                                        return a + b
                                      plus(2,1)

* Keyword arguments                   def plus(a,b):
                                       return a + b
                                      plus(a=1, b=2)

* Variable number of arguments        def plus(*args):
                                         return sum(args)
                                      plus(1,4,5)

# lambda function 
Anonymous functions are also called lambda functions in Python because instead of declaring them with the standard def keyword, you use the lambda keyword

double = lambda x: x*2

double(5)      output: 10

# * usage of lambda
  lambda <argument>: <expression or instruction that gets evaluated and returned> or <commands or statements>

* example:
sum = lambda x, y: x + y;
 sum(4,5)        output : 9


# Using main() as a Function
If we have any experience with other programming languages such as Java, you’ll know that the main function is required to execute functions
* example:
def main():
  hello()
  print("This is a main function")

main()

# if function doesn't have a print command (operation will be done but user doesn't get any output)
example:
def absolute_value(num):
	"""This function returns the absolute
	value of the entered number"""

	if num >= 0:
		return num
	else:
		return -num

# Output: 2
print(absolute_value(2))

# Output: 4
print(absolute_value(-4))



# 