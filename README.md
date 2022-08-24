# Backtracking-Graph
The graph was created analyzing the linux events using sysdig 

## Objective
In an operating system, a process can read or write into a file. Again, a socket can create a process. So, there is a connection between these 3 things. In this project, I have created backtracking graph which shows the connection in between those 3 with a simple example. 
 - I have downloaded a project from github
 - The project is downloaded using wget, which is connecting with the socket
 - Then that is unzipped using tar. That is reading from the zip file and writing into the Web-Development-Project-master file
 
These connections are crealy visible in my graph generated using this project from a linux system,
 ![backtracking graph](https://user-images.githubusercontent.com/26908164/186519192-c90d27ae-cb4e-4209-96de-799b11b944ec.PNG)
 
 **Using this backtracking graph, we can extract the hindered files during an attack in an industry floor.**
