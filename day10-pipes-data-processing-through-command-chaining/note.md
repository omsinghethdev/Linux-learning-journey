##Today learned piped and commonly unsed tools
1:Pipes
By using pipes we can pass output of one command as the input of other program
2 Some commonly used tools
a)tee:used with pipe to creat standard output and write it to a file at same time.
b)sort,uniq:
'sort':sort the content in a file or stdin
'sort -r':sort in reverse alphabetical order
'sort -n':sort numbers in numeric order
'sort -c':check wether the contents in a file are sorted and find unsorted elements.
'sort -k column_number':sort data by a specific column.
uniq:removes duplicate lines.
c)grep:finds the pattern in output or file
grep -F 'pattern' file.txt
d)tr
to replace(on a character level)
ex:echo 'bash'|tr 'b' 'd'
we can also use range in it.
e)rev
it reverse the string
f)cut
g)sed

