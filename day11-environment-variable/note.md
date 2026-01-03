##Today learned about 
1:Shell,CLI
2:some important environment variable HOME,PWD,USER
3:Creating ,overwriting,deleting environment variable.
Now will talk in detail:
 


Shell:outer layer of an operating system which takes command from the user and transalets into the form in which the kernal can under stand
It can also displays the result of those commands to the user.

CLI:Text based interface that allows to interact with the system.


We can display the all environment variable by using the command 'env'.
if we want to access single environment variable 
we can use the command:echo "${HOME}"

TO set /unset environment variable
For creating we can use :
export VAR=vlaue 
vor deleting we can use
unset VAR
For overwrite an existing variable
VAR=new value


