
1) Alternate commands using sed
	1) sed -n '3!p' filename
	2) sed n '/word/{
		p
		} filename
	3) sed -n '$p' filename 
grep -c "" filename '* J,y , q
c) s
ed'2q' filename p p ; (p y y,;J ‹ygpJ
d) sed'$!d' filename pJ ; J;,I
e) grep -v 'word' filename p ; pJ '

2) Consider "people" is the name ofthefile. The contents of file is as follows
Hai everyone
Hai Boby
Haipriya
Prlya Hai

a) Write a sed script to print how many times the word "Hai" used ln the starting of a line in the file "people"

b) Write a sed script to print only the llnes which contain "Hai" in the above file mentioned

c) Delete only the last line of the above file using sed

d) Delete all the lines other than the last line in the given file using sed

e) Delete ie whole file content using sed

3) Consider the file "snap" below
[ s a + s o o
And frame your sedscripts inorder to get these patteilis below

4) Write a script to display only Emb or Vlsi user accounts, each field must be sepearted by

5) Alternate coiniiiands
a)cat > filenaine.txt "
b)cat >> flleiiaine.txt ' * 

6) List all the files (exculde director1e5) using sed

7)Wi ite sed command toextracta list of user naines from thepassword file

8) Use the cut& paste comman$s loswap fields2 and 3 ln my table". (Call it mytable) tabs to separate the fields'(3)
1425 Ravi 15.65
4320 Ramu 26.27
. 6830 Sita 36.15

9) Writea script to convert decimal number in to binary,hexadecimal,octal

10) Writea script to reversea number using functions

11)Writea script to check whether the given number is amstrong or not

12)Write shell Script to lmplement library functionality using dialog utillty lR WhlGh "ctl C, ctl Z" should be deactivated.
Menu-items and action according to select menu-item is as follows:
i. Issuea book
ii. Returna book
iii. Deletea book.
Each ofthe above options should havea sab ineiia that asks for the name ofthe book and then echotfie actioñ (hat is done. Explain the working of thecommands used and the conditionalstatement used in the scripts

1)The file named a.txt which has 4 fields/ columns, where as each field is separated by a tab and
that field contains some data like below

Player Country Ranking Average
Ram USA 105 25
Rag UK 115 26
Pat IND 234 23
Sah  425 24
Tat USA 344 28
Rat BRZ 536 29

Solve the scripts below using awk only?

a)Display only 2nd field data, that should be like this
USA
UK
IND
USA
BRZ

b)Use the awk builtin variable to eleminate the player who didnt mention his country from the
sample given

c)Number all the lines in the sample file

d)Write a script to count the number of lines in the file

e)Write the awkscript which will be able to give you the given below as output if u take the given
a.txt file as sample input
Name:Country:Ranking:Average
Ram:USA:105:25
Rag:UK:115:26
Pat:IND:234:23
Sah::425:24
Tat:USA:344:28
Rat:BRZ:536:29

2)Explain the below variables with examples
a)NF,NR b)OFS,FS c)ORS,RS d)FILENAME,FNR

3)Use the awk script to print the users who have the default shell as bash

4)Using dialog utility write a script to implment ATM functionality. Let it offer the user the
choice of Cash withdrawal,Cash Remitting ,Change Password,Third party transfer and exit. Once
the user has made a choice, have the program ask the user for necessary information,in such a
way that his current password is "123" and the total amount in his account is Rs 20000/-. If the
user input is wrong means it has to work accordingly.

conditions:
(1)title-ATM machine
(2)backtitle:-SBI BANK
(3)Only for exit it need to come out of the utility
(4)Cash Withdrawal ,cash remitting and third party transfer you need to show the balance amount.

5)Write a script using functions which reads a number in units of seconds and converts it to the
units hours:minutes:seconds and prints the result to standard output.
Your script must prompt for re-input if a negative value is input

6)Consider the below file p1.txt as your sample file and write scripts using sed
one two two three
two four five
five six two two
125
five two six
12

a)Change only the second occurance of "two" in all the lines to "twothree"
b)print the last line of a file
c)print only the first two lines
d)Delete only the 7th and 9th line of a file
e)print only the odd numbers in the file

7)Consider this as the input file and write the scripts with out using awk, sed and grep
1:1=2
2:2=4
3:3-9
4:4=16

a)output file must be like the one below
1+1=2
2+2=4
3+3-9
4+4=16

b)print the first field alone
c)print the second field alone

8)Write the alternate comands using awk
(a)cut -d"." -f1,2 file
(b)cat filename

9)Write the alternate comands using sed
(a)cat filename | tr -d "[0-9]"
(b)cat filename
(c)sed '3q' filename

10)Write a script to change any decimal number to Hex,oct,binary. During the excecution of the
script the signals Ctrl+C and Ctrl+z should not interrupt.

4. Explain the difference between until and while with an example.

5. Use grep and explain each
a) How do you search for a string inside a directory?
b) How do you search for a string in a directory with the subdirectories?
c) How will you list only the empty lines in a file?
d) count the total number of the pattern "o" in the file.

6. Write sed scripts that will do the following.
a) That will delete every line that starts with a T.
b) Print the all the line numbers in which string1 is present in the file "test".
c) Replace the whole line that has the string1 with only stirng2.
d) Substitute "Bangalore" with "Manipal" only for the first occurrence in the line.
e) Replace "y" with "Y"

7. For the following command, store the output in out. File and error in error. File and explain
the script. COMMAND:( du 'which bash' ; echo1 "welcome")

Subject: Linux and Scripting Languages
Duration: 90 Minutes
Course: III MSc Tech (EMB A)/III ITM/III ESIGELEC
Marks: 50

1. Explain any 2 features of Linux operation and List out the 2 drawbacks of shell scripting

2. What is the importance of cron command. Execute the script backup.sh" 00:30 hrs on 1st of jan, june and
December" using cron command.

3. For the following command, store the output in out.file and error in error.file and explain the script.
COMMAND:( du 'which bash' ; echo1 "welcome")

4. Use wild cards and explain the resultant scripts
a) List all the files ending with "h"
b) Remove all the files having "i" as second letter in the folder
c) Give only execute permission to the owner or user of all the files starts with "a"
d) Copy all the files in directory "/rose" with .sh as extension to "/pre" named directory

5. Explain the difference between until and while loop with an example

6. Write a command using grep,
a. To select the lines from the file1 that have exactly three characters
b. To select the lines from the file1 that have minimum 3 characters to maximum 5 characters long.
c. To count the number nonblank lines in the file1
d. To select the lines from the file1 that have only the string "UNIX".
e. To select the lines from the file1 that do not start with A to G

7. Write the bash script and explain using the below given guidelines
a) Get the filename and pattern from the user
b) Check the file is exist or not, if not create the file (the file name entered by the user)
c) Check the file is having execute permission or not.
d) Count the number of lines in the file entered by the user
e) Count the total number of times the pattern appears in the file

8. Get the three numeric values from the user and Find the biggest among three numbers using positional
parameter, if user gives other than 3 values, it has to print invalid parameter.

REG.NO:
Subject: Linux and Scripting Languages
Duration: 90 Minutes
Marks: 50

1. Define the term Shell and Process,

2. Explain the importance of at command with an example

3. Compare Absolute path and Relative path with relevant example.

4. Write a shell scripts
a. To display the message Good Morning"/"Good Afternoon"/"Good Evening" based on
time.
b. To get a number from the user in units of seconds and converts it to the unit
hours:minutes:seconds and prints the result to standard output.Your script must prompt
for re-input if a negative value is input
c. To get the user name as input and check user account is exists or not if already exists
display "account exists" otherwise creates the account.
d. To find whether given file exist or not, file name is supplied as command line argument,
also check for sufficient number of command line argument

5. Write a shell script using GREP command, explain the script
a. Count total number of blank lines
b. Find the line that end with the pattern "end"
c. Search recursively all files and directories under given directory for the pattern "script"
d. Pick all the lines that has 100 characters in length.
e. List all the lines in the file that contain the pattern "$"

6. Write a shell command to do the following
a. To count total number of files/directories starts with "a"
b. To Copy all the contents of the directory "me2015" to "backup15"
c. To create an alias for clear command as "c"
d. To List all the files in your directory in long format saving the output in a file called
all my files
e. Assign the read and write permission to the owner and the read permission to
the group and others for the file "file1".