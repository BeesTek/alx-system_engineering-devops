0. echo "Hello, World" is a script that prints "Hello, World" 
1. echo '"(Ôo)'\' is a script that displays a confused smiley. the single quotes used is to escape special characters
2. cat /etc/passwd is a script that displays the '/etc/passwd' of a file
3. cat /etc/passwd /etc/hosts  is a script that displays both '/etc/passwd /etc/hosts'
4. tail /etc/passwd is a script that displays the last 10lines of the '/etc/passwd' file
5. head /etc/passwd is a script that displays the first 10lines of the '/etc/passwd ' file
6. head -3 iacta | tail -1 is a sript that displays the third line of the iacta file which is in a working directory
7. echo "Best School" > echo "Best School" >  \\\*\\\\"'\"Best School\"\\'\\\\\*\$\\\?\\\*\\\*\\\*\\\*\\\*\:\) is a script that creates a file  named  \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text Best School. The special characters are being escaped using backslashes, single and double quotes respectively.
8. ls -la > ls_cwd_content is a scipt that overwrites into the file ls_cwd_content a result of the ls -la command
9. tail -n | iacta >> iacta is script that duplicates the last line of the file iacta which will be in a working directory.
10. find . -type -name "*.js" -delete is a script that deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.
11. find . -type d -not -name '.' | wc -l is a script that counts the number of directories and sub-directories in the current directory. The current and parent directories should not be taken into account and hidden directories should be counted
12. ls -t1 | head is a script that displays the 10 newest files in the current directory.
13. sort | uniq -u is a script that takes a list of words as input and prints only words that appear exactly once.
14. grep -i "root" /etc/passwd is a script that display lines containing the pattern “root” from the file /etc/passwd.
15. grep -i "bin" /etc/passwd is a script that display the number of lines that contain the pattern “bin” in the file /etc/passwd.
16. grep -iA 3 "root" /etc/passwd is a script that display lines containing the pattern “root” and 3 lines after them in the file /etc/passwd.
17. grep -v "bin" /etc/passwd is a script that display all the lines in the file /etc/passwd that do not contain the pattern “bin".
18. grep -1 '^[a-z]' /etc/ssh/sshd_config is a script that display all lines of the file /etc/ssh/sshd_config starting with a letter.
19. tr "A" "Z" | tr "c" "e" is a script that replace all characters A and c from input to Z and e respectively.
20. tr -d "Cc" is a script that  removes all letters c and C from input.
21. rev is a script that reverses its input                                                                                            
