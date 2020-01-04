ways of math in linux 
* let
* (( ))    >>> double paranthsis
* [ ]
* expr 
* bc 

# let method
* let number=1+2
    ouput : 3
* let 5*5
    output : 25

# basic math on the Linux CLI is a using double parenthesis.
number=$(( 1 + 2 ))  r  $(( 1 * 2 ))   r   $(( 1 - 2 ))   r  $(( 1 / 2 )) 
echo $number  or  echo `number`         >>>> by using grave accent or backtick ( `` ) instead of $(doller symbol) 
output : 3
# expr method 
The expr command evaluates expressions and prints the value of provided expression to standard output.
  $(expr 3 + 5)
  $(expr 15 % 3)
  $(expr 5 \* 3)
  $(expr 5 – 3)
  $(expr 20 / 4)               >>>> give space before and after of math operand
  $(expr 5 = 5)
  $(expr 8 != 5)
  $(expr 8 \> 5)              >>>>>> our created things $ is enough, when we using linux created ones use  $()
  $(expr 8 \< 5)
  $(expr 8 \<= 5)

# Assignment Operators
var = value : Assign the vale to the variable
var += value : similar to var = var + value
var -= value : similar to var = var – value
var *= value : similar to var = var * value
var /= value : similar to var = var / value
var ^= value : similar to var = var ^ value
var %= value : similar to var = var % value

# for increment 
* var++
# for decrement
* var-- 