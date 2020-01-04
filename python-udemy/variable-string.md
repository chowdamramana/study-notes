VAR = VALUE      >>>> we can give space before and after (=)
dont assign a values to pre defined python keys
example:
  print = 150     >>> it shows error, becuase print is keyword in python
we can provide values to no of variables at atime
* a,b,c = 1,2,3

# strings
for repreent strings we use " or '
name = "my name"    or 'my name'
* for long strings we use '''(3 single quotes)

* long_string = ''' something
      new  
    ok---ok
      new
     thing   '''

# type conversion
a = 100      it is integer
b = str(a)   coverting integer to string
c = float(b)   converting string to float
d = int(c)     converting float to integer

# in python if we want to print RAW text or string we use r infront of string
example :
print(r'C:\\Windows\Users\alexb\')
output :
    C:\\Windows\Users\alexb\

* or else if we want to eliminate any perticular special character in sting we use ( \ ) backslash infront of special character
example: 
print("new word \"added\" recently")
output : new word "added" recently 

# formatted string
which allows multiple substitutions and value formatting. This method lets us concatenate elements within a string through positional formatting and keyword formatting. use it instead of concatenation.

* if we want to formatting a string use f in front of string 
in formatted string we use custom or dynamic variable in brackets
* we want dynamic or custom statement use formatted string. it will changed based on the users input

name = "my name"
age = "my age"
print(f"hello {name}.your age is {age}.")
output: hello myname.your age is my age. 
         or
print("hello {}.your age is {}".format (name,age))