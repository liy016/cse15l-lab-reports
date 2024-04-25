# Lab Report 2
## Part1:
![image](part1.jpg)<br>
![image](part1(2).jpg)<br>
1. method: `handleRequest`.
2. `handleRequest`: `url.getPath()` = `"/add-message"`,`url.getQuery()` = `"s=Hello&user=jpolitz"`,`chatMessages` = `""`<br>
`String.split`: `"s=Hello&user=jpolitz"`<br>
`String.equals`: `"s"`, `"user"`<br>
`String.isEmpty`: `"Hello"`, `"jpolitz"`<br>
`String.+=`: `"jpolitz: Hello\n"`<br>
3. `chatMessages` changes from `""` to `"jpolitz: Hello\n"`<br>
![image](part1(3).jpg)<br>
1. method: `handleRequest`.
2. `handleRequest`: `url.getPath()`= `"/add-message"`, `url.getQuery()` = `"s=How%20are%20you&user=yash"`, `chatMessages` = `"jpolitz: Hello\n"`<br>
`String.split`: `"s=How%20are%20you&user=yash"`<br>
`String.equals`: `"s"`, `"user"`<br>
`String.isEmpty`: `"How are you"`, `"yash"`<br>
`String.+=`: `"jpolitz: Hello\nyash: How are you\n"`<br>
3. `chatMessages` changes from `"jpolitz: Hello\n"` to `"jpolitz: Hello\nyash: How are you\n"`<br>
## Part2:
![image](part2.jpg)<br>
![image](part2(2).jpg)<br>
![image](part2(3).jpg)<br>
## Part3: 
In week2 lab, I learned about the URLHandler interface, which allows for flexible handling of different types of URLs within a web server application. Additionally, in week3 lab, I gained a deeper understanding of SSH keys and SCP, particularly in the context of secure remote server access and file transfer. Learning how to generate, manage, and utilize SSH keys for authentication and SCP for secure file transfer enhanced my proficiency in securely interacting with remote servers and transferring files between local and remote environments.
