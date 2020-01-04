# In 3 ways we can assign value to variable
1 Explicit defination : VAR=value    >>>> we dont want to give any spaces after and before equal symbol
2 read command :  read VAR           >>>  we can take value from user input 
3 command substitution : VAR=$( pwd )
# in linux we dont want to give any spaces before and after equal symbol

greeting=hello everyone            >>> everyone word taken as command
# by giving spaces between the words it will take next word as a command so use double quotation marks
greering="hello everyone"             >>> it is right way

read NAME                               >>> it is noraml way of command
read -p "enter your name :" NAME             >>> "enter your name :" is hint text
# Here we read the data along with some hint text . The hint text helps the user in what he/she has to enter . -p here stands for the prompt . The hint text also called the prompt text.
read -n 5 -p "only we can enter specific length( ex : 5 ) of character only : " NAME 
# This -n option allows the user to enter only the specific length of characters.It won’t allow you to enter more than the given number of characters.
read -s -p "entered text was not visible to user :" PASSWORD
# This option -s means secret or secure whatever is used to read the sensitive data. Generally, when you type entering the data it appears in the terminal. But with this option the text won’t appear in terminal

by using $VAR-NAME we can use the value of the variable
"my name" >> newfile.txt             >>>> my name is redirecting to the file
* 0 for input , 1 for output, 2 for error
* example : "my name" 2>> newfile.txt         >>>> we directing the error to the file
$NAME < somefile.txt                  >>>> taking the value from the file
# > is allow rewrite, >> it is not allow override to the file, it adds th data to the existence data