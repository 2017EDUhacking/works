```
CompTIA Linux+ Complete Study Guide
(Exams LX0-101 and LX0-102)
Roderick W. Smith
2010 
http://mse.mn/uploads/laws/ab2c7b287105fab8158de502c50ac645d34a3a5c.pdf
```

### Chapter 1 n Exploring Linux Command-Line Tools
```

1. You type a command into bash and pass a long filename to it, but after you enter the command, 
you receive a File not found error message because of a typo in the filename. 
How might you proceed?
A. Retype the command, and be sure you type the filename correctly, letter by letter.
B. Retype the command, but press the Tab key after typing a few letters of the long filename 
   to ensure that the filename is entered correctly.
C. Press the Up arrow key, and use bash’s editing features to correct the typo.
D. Any of the above.

2. Which of the following commands is implemented as an internal command in bash?
A. cat   B. echo   C. tee  D. sed

3. You type echo $PROC, and the computer replies Go away. What does this mean?
A. No currently running processes are associated with your shell, so you may log out
without terminating them.
B. The remote computer PROC isn’t accepting connections; you should contact its administrator to correct the problem.
C. Your computer is handling too many processes; you must kill some of them to regain
control of the computer.
D. You, one of your configuration files, or a program you’ve run has set the $PROC environment variable to Go away.

4. What does the pwd command accomplish?
A. It prints the name of the working directory.
B. It changes the current working directory.
C. It prints wide displays on narrow paper.
D. It parses Web page URLs for display.

5. In an xterm window launched from your window manager, you type exec gedit. 
What will happen when you exit from the gedit program?
A. Your shell will be a root shell.
B. The gedit program will terminate, but nothing else unusual will happen.
C. Your X session will terminate.
D. The xterm window will close.

6. What is the surest way to run a program (say, myprog) that’s located in the current working directory?
A. Type ./ followed by the program name: ./myprog.
B. Type the program name alone: myprog.
C. Type run followed by the program name: run myprog.
D. Type /. followed by the program name: /.myprog.

7. How does man display information by default on most Linux systems?
A. Using a custom X-based application
B. Using the Firefox Web browser
C. Using the less pager
D. Using the Vi editor

8. You want to store the standard output of the ifconfig command in a text file (file.txt) for
future reference, and you want to wipe out any existing data in the file. How can you do so?
A. ifconfig < file.txt
B. ifconfig >> file.txt
C. ifconfig > file.txt
D. ifconfig | file.txt

9. What is the effect of the following command?  $ myprog &> input.txt
A. Standard error to myprog is taken from input.txt.
B. Standard input to myprog is taken from input.txt.
C. Standard output and standard error from myprog are written to input.txt.
D. All of the above.

10. How many commands can you pipe together at once?
A. 2 B. 3  C. 4  D. An arbitrary number

11. You want to run an interactive script, gabby, which produces a lot of output in response to
the user’s inputs. To facilitate future study of this script, you want to copy its output to a
file. How might you do this?
A. gabby > gabby-out.txt
B. gabby | tee gabby-out.txt
C. gabby < gabby-out.txt
D. gabby &> gabby-out.txt

12. A text-mode program, verbose, prints a lot of spurious “error” messages to standard error.
How might you get rid of those messages while still interacting with the program?
A. verbose | quiet
B. verbose &> /dev/null
C. verbose 2> /dev/null
D. verbose > junk.txt

13. How do the > and >> redirection operators differ?
A. The > operator creates a new file or overwrites an existing one; the >> operator creates
a new file or appends to an existing one.
B. The > operator creates a new file or overwrites an existing one; the >> operator
appends to an existing file or issues an error message if the specified file doesn’t exist.
C. The > operator redirects standard output; the >> operator redirects standard error.
D. The > operator redirects standard output; the >> operator redirects standard input.

14. What program would you use to display the end of a configuration file?
A. uniq
B. cut
C. tail
D. wc

15. What is the effect of the following command?
$ pr report.txt | lpr
A. The file report.txt is formatted for printing and sent to the lpr program.
B. The files report.txt and lpr are combined together into one file and sent to standard output.
C. Tabs are converted to spaces in report.txt, and the result is saved in lpr.
D. None of the above.

16. Which of the following commands will number the lines in aleph.txt? (Select all that apply.)
A. fmt aleph.txt
B. nl aleph.txt
C. cat -b aleph.txt
D. cat -n aleph.txt

17. Which of the following commands will change all occurrences of dog in the file animals.txt to mutt in the screen display?
A. sed –s “dog” “mutt” animals.txt
B. grep –s “dog||mutt” animals.txt
C. sed ‘s/dog/mutt/g’ animals.txt
D. cat animals.txt | grep –c “dog” “mutt”

18. You’ve received an ASCII text file (longlines.txt) that uses no carriage returns within
paragraphs but two carriage returns between paragraphs. The result is that your preferred
text editor displays each paragraph as a very long line. How can you reformat this file so
that you can more easily edit it (or a copy)?
A. sed ‘s/Ctrl-M/NL/’ longlines.txt
B. fmt longlines.txt > longlines2.txt
C. cat longlines.txt > longlines2.txt
D. pr longlines.txt > longlines2.txt

19. Which of the following commands will print lines from the file world.txt that contain matches to changes and changed?
A. grep change[ds] world.txt
B. sed change[d-s] world.txt
C. od “change’d|s’” world.txt
D. cat world.txt changes changed

20. Which of the following regular expressions will match the strings dig and dug but not dog?
A. d.g   
B. d[iu]g
C. d[i-u]g
D. di*g
```
