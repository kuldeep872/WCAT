# WCAT
It is used to display or make a copy content of one or more files in terminal

commands:

1.wcat filepath => displays content of the file in the terminal 

2. wcat filepath1 filepath2 filepath3... => displays content of all files in the terminal(contactinated form) in the given order.
  
4.wcat -s filepath => convert big line breaks into a singular line break

5.wcat -n filepath => give numbering to all the lines

6.wcat -b filepath => give numbering to non-empty lines

7.wcat filepath > filename2path => put all the content of filename into filename2 by overriding and also creates filename2 if it doesn't exist.

8.wcat filename2path >> filename2path => append all the content of filename into filename2

9.node wcat -s filename > filename2 =>get the file content of filename remove large spaces and save the output in filename2

