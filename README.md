# Ex.07 JavaScript - Simple Calculator
## AIM
  To write a program in JavaScript for implementing a simple calculator.

## ALGORITHM
### STEP-1
  Open notepad and type the HTML code.

### STEP-2
  Define a function to implement the simple calculator.

### STEP-3
  Using branching statements to find the corresponding operation.

### STEP-4
  Open the file in a browser and verify the output.
  
## CODE
```<html>
<head>
<script type="text/javascript">
function calc()
{
var a=prompt("Enter 1st Value");
var b=prompt("Enter 2st Value");
var op=prompt("Enter Operation to Perform 1.Addition 2.Subtraction 3.Multiplication 4.Division");
var d;
if(op==1)
{
d=a+b;
alert(d);
}
else if(op==2)
{
d=a-b;
alert(d);
}
else if(op==3)
{
d=a*b;
alert(d);
}
else if(op==4)
{
d=a/b;
alert(d);
}
else
{
alert("Invalid Operation");
}
}
</script>
</head>
<body onload="calc()">
<h1>
Simple Calculator
</h1>
<hr color="pink">
<p> 
Enter option for doing the corresponding operation
</p>
</body>
</html>
```


## OUTPUT
![assignment71](https://github.com/Sujitha73/Ex07_Web-Design/assets/129753050/ed6ac5cb-bab5-4e05-8737-9208b1297e50)
![assignment72](https://github.com/Sujitha73/Ex07_Web-Design/assets/129753050/bb14ffb9-eb8f-4d9c-a07b-5ad2c1706377)
![assignment73](https://github.com/Sujitha73/Ex07_Web-Design/assets/129753050/1d9a7e27-40b3-4dad-a69e-c297db4dae5a)
![assignment74](https://github.com/Sujitha73/Ex07_Web-Design/assets/129753050/35a61c4c-cfce-49ab-8c58-7f0a521956a1)
![assignment75](https://github.com/Sujitha73/Ex07_Web-Design/assets/129753050/71d02a26-8c21-471f-be9e-9ca3eb5a1f88)


## RESULT
  Implementation of a Simple Calculator using JavaScript is done successfully.
