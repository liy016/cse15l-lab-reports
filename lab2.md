# Lab Report 2
## Part1:
![image](part1.jpg)<br>
### screenshots of `/add-message?s=Hello&user=jpolitz`
![image](part1(2).jpg)<br>
1.The method is `handleRequest(URI url)`and main method.<br>
2.The relevant argument is `url`, which have the value of `new URL("http://localhost:4000/add-message?s=Hello&user=jpolitz")`. The relevant field of class is `String chatMessages`, which is initialized to an empty.<br>
3.`String chatMessages` changes from `""` to `"jpolitz: Hello"`<br>
### screenshots of `/add-message?s=How are you&user=yash`
![image](part1(3).jpg)<br>
1.The method is `handleRequest(URL url)`and main method.<br>
2.The relevant argument is `url`, which have the value of `new URL("http://localhost:4000/add-message?s=How are you&user=yash")`. The relevant field of class is `String chatMessages`, which has the value `"jpolitz: Hello"` stored.<br>
3.`String chatMessages` changes from `"jpolitz: Hello\n"` to `"jpolitz: Hello\nyash: How are you"`<br>
## Part2:
![image](part2.jpg)<br>
![image](part2(2).jpg)<br>
![image](part2(3).jpg)<br>
## Part3: 
In week2 lab, I learned about the URLHandler interface, which allows for flexible handling of different types of URLs within a web server application. Additionally, in week3 lab, I gained a deeper understanding of SSH keys and SCP, particularly in the context of secure remote server access and file transfer. Learning how to generate, manage, and utilize SSH keys for authentication and SCP for secure file transfer enhanced my proficiency in securely interacting with remote servers and transferring files between local and remote environments.
