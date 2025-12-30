##Toaday learned 
1.Standard Streams:stdin,stdout,stderr
a)stdin(standard input)0
b)stdout(standard output)1
c)stderr(standard err)2
2.Redirecting stdout and stderr
By using '>' and '>>' we can redirect stdout and stderr
ex:du -h IMG_1234.jpg IMG_12345.jpg 1>out.txt  2> error.txt
here one .jpg files exist and other does not exist consicutively Now stdout is redirect in the 'out.txt 'and stderr will redirectes in 'error.txr' 
If file not exist than it will be created
3.Redirecting stderr to stdout:why we are doing this ?
Because it allows easily store both stderr ,stdout in the same file.
Right now we have to provide filename  multiple time.
ex:du -h IMG_1234.jpg IMG_12345.jpg 1>out.txt  2> out.txt
to Redirect stderr to stdin 
[command] >out.txt 2>&1
we use this 
Difference between commands
1.[command] >out.txt 2>&1
2.[command] 2>&1 >out.txt
case 1: first stdout redirected to the file named out.txt and then the stderr is redirected to where the stdout is present.
case 2: stderr is redirected to the where the stdour is present than stdout is redirected to th file named out .txt.
4.Redirecting stdin
some program take input 
cat,wc -l.
toh redirecting kaise hota hai 
cat <file.txt
This is all that i have learned today.



