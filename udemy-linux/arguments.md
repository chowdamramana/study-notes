$0 => script name
$1 => first argument                  echo $1    >>>> it prints first argument
$2 => second argument      
..                        >>>> this are positional arguments
..
$n => nth argument

$@ => all arguments expands as "$1""$2""$3" and so on    >>>> use most for go through each script command
$* => all arguments expand as one string "$1 $2 $3"  >>> it have internal field separater (IFS) default IFS is space 
* we can specify at script by IFS=","   >>> in their field separator is ,
$# => arguments count
$? => for exit status

# if we want to eliminate any special characters use \ infront of special character
* exmaple : echo " all arguments with \$@ : $@ "

# inode : it contain the information (metadata) about a regural file and directory 
* it contain the following information
    File types ( executable, block special etc )
    Permissions ( read, write etc )
    UID ( Owner )
    GID ( Group )
    FileSize
    Time stamps including last access, last modification and last inode number change.
    File deletion time
    Number of links ( soft/hard )
    Location of ile on harddisk.
    Some other metadata about file 