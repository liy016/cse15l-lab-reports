# Lab Report 1
## Share an example of using the command with no arguments.
![image](noarguments.jpg)
>
command `cd`: <br>
>
absolute path before command was run: `/c/Users/HUAWEI`.<br>
>
Explanation: Running `cd` command with no arguments changes the current directory to the user's home directory.<br>
>
Output: It has no output and the directory changes to the user's home directory.<br>
>
command `ls`:<br>
>
absoluate path before command was run: `/c/Users/HUAWEI`.<br>
>
Explanation: Running `ls` with no arguments lists the contents of the current directory.<br>
>
Output: It display lists of files and directories in my laptop.<br>
>
command `cat`:<br>
>
absolute path before command was run: `/c/Users/HUAWEI`.<br>
>
Explanation: Running `cat` command with no arguments tries to display the contents of a non-existent file that the terminal will wait for my input something.<br>
>
Output: It is error, because it does not display anything and users can quit with ctrl z.<br>
>
## Share an example of using the command with a path to a directory as an argument.
![image](file.jpg)
command `cd ./lecture1`:<br>
>
absolute path before command was run: `/c/Users/HUAWEI`.<br>
>  
Explanation: Running `cd ./lecture1` changes the current directory to the specified directory.<br>
> 
Output: It has no output, because the directory only changes to the user's home directory.<br>
> 
command `ls ./lecture1`:<br>
>
absoluate path before command was run: `/c/Users/HUAWEI`.<br>
>    
Explanation: Running `ls ./lecture1` lists the contents of the specified directory.<br>
>    
Output: `Hello.class  Hello.java  messages/  README`.<br>
> 
command `cat ./lecture1`:<br>
>
absoulate path before command was run: `/c/Users/HUAWEI`.<br>
> 
Explanation: Running `cat ./lecture1` tries to display the contents of a directory, which is not allowed.<br>
> 
Output: It is error. `cat: ./lecture1: Is a directory`, indicating that `directory`is a directory.<br>
>
## Share an example of using the command with a path to a file as an argument.
![image](directory.jpg)
> 
command `cd messages`:<br>
>
absoluate path before command was run: `/c/Users/HUAWEI`.<br>
> 
Explanation: Running `cd messages` tries to change the current directory to a file, which is not allowed.<br>
> 
Output: It is error. `bash: cd: messages/en-us.txt: Not a directory`, indicating that `messages/en-us.txt` is not a direcory.<br>
> 
command `ls messages`:<br>
>
absoluate path before command was run: `/c/Users/HUAWEI`.<br>
> 
Explanation: Running `ls messages/en-us.txt` displays the contents of the specified file.<br>
> 
Output: `messages/en-us.txt`<br>
> 
command `cat messages/en-us.txt`:<br>
>
absoluate path before command was run: `/c/Users/HUAWEI`.<br>
> 
Explanation: Running `cat messages/en-us.txt messages/es-mx.txt messages/zh-cn.txt` displays the contents of the specified file.<br>
> 
Output: `Hello World!` `¡Hola Mundo!` `你好世界`.

