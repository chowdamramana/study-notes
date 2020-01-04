*  date (no option) : With no options, the date command displays the current date and time, including the abbreviated day name, abbreviated month name, day of the month, the time separated by colons, the time zone name, and the year.
* example : 
       Command: 
       $date
       Output: 
       Tue Oct 10 22:55:01 PDT 2017
#  syntax   ---->   $(date +%[format-option])
* example :
    TODAY=$(date +"%d-%b-%Y")
    output :
        12-dec-2019
* List of Format specifiers used with date command :
%D: Display date as mm/dd/yy.       
%d: Display the day of the month (01 to 31).       
%a: Displays the abbreviated name for weekdays (Sun to Sat).
%A: Displays full weekdays (Sunday to Saturday).
%h: Displays abbreviated month name (Jan to Dec).
%b: Displays abbreviated month name (Jan to Dec).
%B: Displays full month name(January to December).
%m: Displays the month of year (01 to 12).
%y: Displays last two digits of the year(00 to 99).
%Y: Display four-digit year. 
%T: Display the time in 24 hour format as HH:MM:SS.
%H: Display the hour.
%M: Display the minute.
%S: Display the seconds.