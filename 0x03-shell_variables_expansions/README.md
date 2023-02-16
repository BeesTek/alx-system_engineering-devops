0. alias ls="rm *" is a script that creates an alias with name and value ls and rm * respectively.
1.echo hello $USER is a script that prints hello user, where user is the current linux user.
2.PATH=$PATH /action is a script that adds /action into PATH. /action being the last directory the shell looks into when looking for a program.
3.echo $((`echo $PATH | grep -o ":/" | wc -l`+ 1)) is a script that counts the number of directories in a path.
4.printenv is a script that lists environment variables.
5.set is a script that lists all local and environment variables and functions.
6. BEST="School" is a script that creates a new global variable.
7. export BEST="School" is a script that creates a global variable.
8. echo $(($TRUEKNOWLEDGE +128)) is a script that prints the result of 128 with the value stored in the environment variable TRUEKNOWLEDGE.
9. echo $(($POWER / $DIVIDE)) is a script that prints the result of POWER divided by DIVIDE.
10. echo $(($BREATH**$LOVE)) is a script that displays the result of BREATH to the power LOVE.
11. echo $((2#BINARY)o) is a script that converts a number from base 2 to base 10.
12.      
