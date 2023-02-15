0. alias ls="rm *" is a script that creates an alias with name and value ls and rm * respectively.
1.echo hello $USER is a script that prints hello user, where user is the current linux user.
2.PATH=$PATH /action is a script that adds /action into PATH. /action being the last directory the shell looks into when looking for a program.
3.echo $((`echo $PATH | grep -o ":/" | wc -l`+ 1)) is a script that counts the number of directories in a path.
4.printenv is a script that lists environment variables.
5.
