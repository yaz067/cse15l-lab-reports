# Lab5 Report  
## Use 'diff'  

Use 'diff' on the results of running a bash.  
The screeshot show below:
![](./1.png)  

## Implemetations  
There are two implemetations are not correct, screeshots show below:  
### 1.  
The first test output: 
![](./2.png)  
The expected output like this:  

This is our expected output ```"/f&ouml;&ouml;"```
![](./9.png)  
Corresponding md file:  
![](./6.png)  
md file content:  
![](./10.png)  
Demostration:  
Code needs to fix, for two programs we need to fix the case like quotation mark inside parenthesis. Quotation mark is like comment inside the link.  
The line between 33 and 43, we need fix the code handle this case.
![](./11.png)  
### 2.  
The second test output:
![](./3.png)
The expected output like this:  

This is our expected output ```"No Link"```
![](./13.png)
Corresponding md file:  
![](./14.png)  
md file content:  
![](./12.png)  
Demostration:  
The code only view the content between first left parenthesis and first right parethesis. It does't check if the link is corect.   
Code still need to fix, we still need add more code between line 33 and 43.  
![](./11.png)



