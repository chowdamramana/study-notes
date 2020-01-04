# conditions
* mathmatical comparision
* string comparision
* filesystem related tests

# mathmatical comparision
-eq  equal to
-ne not equal to
-gt greater then
-lt less then
-ge greater then or equal to
-le less then or equal to




* 
if [ condition ]                 >>>> SPACE B/W CONDITION AND BRACKETS
then
    statements when condition is true
else
    statements when condition is true
fi

* 
if [ condition ]
then
    statements when condition is true
elif [ condition ]
then
    statements when condition is true
elif [ condition ]
then
    statements when condition is true
else
    statements when the no previously typed condition were true

# or 
if [ condition ]; then                          >>>>>> prefer this type of structure reduce the lines of code.
    statements when condition is true     
fi

# AND with if statement
if [ condition ] && [ condition ]; then
    statements for when the both conditions were true
fi

# OR with if statements
if [ condition ] || [ condition ]; then
    statements for when atleast one condition is true
fi

# negate if condition
if [ ! condition]; then
    statements when condition is not true
fi

if ! [ condition ]; then
    statements when condition is true
fi







