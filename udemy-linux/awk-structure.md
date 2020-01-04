awk 'BEGIN{code_in_begin_section} {code_in_main_body} END{code in end section}' filename.txt
awk -f awk-filename input-file      >>> -f to give awk commands in file
awk -F ":" '{print$0}' newfile.txt      >>>> -F is to give input field separater
    ex: new name given  >>i/p        >>>>> if already same field separator exists it removes it
        new:name:given   >>>o/p
awk '{print NR,$0}' newfile.txt   >>> it print no of records ( line numbers )

# if we want to print anything with respect to perticular line

awk -F ":" '/any-word-in-that-line/ {print $1,$2}' newfile.txt

# TO print print all lines exept search line

awk -F ":" '!/any-word-in-that-line/ {print $1,$2}'

awk '{print NF}' newfile.txt      >>> it prints no 0f fields
 * $NF prints last field
 * $(NF-1) prints second from last
 * $(NF-n) prints nth from last

# awk with if
awk -F ":" '{if (condition) print $0}'   or
awk -F ":" '{if (condition) {print $0}}'


