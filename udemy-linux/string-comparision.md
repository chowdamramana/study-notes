[ "$str1" = "$str2" ]       [ "$str1" = "hello" ]
[ "$str1" != "$str2" ]      [ "$str1" != "hello" ]
# or
[[ $str1 = $str2 ]]         [[ $str1 = "hello" ]]
[[ $str1 != $str2 ]]        [[ $str1 != "hello" ]]

###  

[ -z "str1" ]    returns true if str1 is an empty string
[ -n "str1" ]    returns true if str1 is a non-empty string

# -z to check string is empty or not
# -n to check the string is non-empty or not


# in system existing commands values we can take values of commands directly without executing the commands
* examples:
    $(whoami)       user=$(whoami)
    $(ps)           processlist=$(ps)
    $(ls)

# if we want do multiple works at a time we use {} brackets
* examples
    mkdir {new,old}
    touch {one.sh,two.sh} or touch new{.pdf,.img}
    touch new{1..9}    >>> it creates new1,new2,... new9 files
    touch file{[5-9],[2][0-9]}.txt     >>> it creates file5..9 and file20..29
# sring comparison with wild card
[[ $str==patter_with_wild_card ]]    
* exampels :
    [[ $str==file[0-9].txt ]]
    [[ $str==rich* ]]
