# Lab2 Report


1st bug  

![](./2.png)  
![](./3.png)
Link to failure test file:  
[failure-bug1](https://github.com/yaz067/markdown-parse/blob/main/t1.md)


The terminal output like this:  
![](./1.png)

## Demostration:   
Because the link format in this .md file has no parenthesis, only has [], then an exception will occur. I add if-else statment to prevent the program from continuing to run in this case.  

This bug will change the index parenthesis to -1, so programe will throw IOException.



___  


2nd bug


![](./2.png)  
![](./3.png)  
Link to failure test file(2 files):  
[failure-bug2](https://github.com/yaz067/markdown-parse/blob/main/t2.md)  


The terminal output like this:  
![](./t2.png)  
## Demostration:   
 Bug2: The failure inducing input "a link(google.com)" is a incorrect format of the link in github command. However, this would casue a bug to appear because the program right now would only consider the content if the parenthesis exists. If does not matter whether the brackets exists or not. However, this is definitely a type of bug which would cause the incorrect format of link to still appear in output as the correct link. That is the symptom caused by this bug.

___
3rd bug


![](./6.png)  
Link to failure test file:  
[failure-bug3](https://github.com/yaz067/markdown-parse/edit/main/t3.md)  

The terminal output like this: 
![](./t3.png)  
## Demostration:   
Bug 3: "[a link]      (google.com)" is another type of failure inducing input in this program. Since there exists some indentation after the close bracket. The program should not output the actual link within the parenthesis. This is a bug which is causing by the index of closed bracket and open parenthesis. 
