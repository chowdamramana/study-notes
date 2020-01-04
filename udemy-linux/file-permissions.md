read = 4,
write = 2,
execute = 1,
chmod 777 filename.sh  >> R-W-X permission to all
1) user    2) group   3) other members

chmod +x filename.sh   >> executable permission to all
chmod u+x filename.sh  >> executable permission to USER only    

u = user
g = group
o = others

# note : executing the shell-script from different directory or location " EXPORT THE PATH OF FILE" 
to EXPORT THE PATH from current working directory
    export PATH=$PATH:$(pwd)


*    #!/bin/bash   >>  /bin/bash is location of interpreter bash
*  interpreter :  An Interpreter directly executes instructions written in a programming or scripting language without                      previously converting them to an object code or machine code
compiler : it's converts source code into machine code( object language )

