#What are conditional statements? 

####Conditional statements are the set of commands used to perform different actions based on different conditions. 

###In JavaScript we have three conditional statements:
####If statement - use this statement if you want to execute a set of code when a condition is true.
####If...else statement - use this statement if you want to select one of two sets of lines to execute.
####Switch statement - use this statement if you want to select one of many sets of lines to execute.


##Code Examples:

```
  var num = window.prompt("Grade:", 0);
  grade = parseInt(num);
  if (grade > 90) 
  {
     document.write("A")
  }
  else if (grade > 80)
  {
     document.write("B")
  }
  else if (grade > 70)
  {
     document.write("C")
  }
  else if (grade > 60)
  {
     document.write("D")
  }
  else
  {
     document.write("F")
  }
```

```
switch (expr) {
  case "Oranges":
    console.log("Oranges are $0.59 a pound.");
    break;
  case "Apples":
    console.log("Apples are $0.32 a pound.");
    break;
  case "Bananas":
    console.log("Bananas are $0.48 a pound.");
    break;
  case "Cherries":
    console.log("Cherries are $3.00 a pound.");
    break;
  case "Mangoes":
  case "Papayas":
    console.log("Mangoes and papayas are $2.79 a pound.");
    break;
  default:
    console.log("Sorry, we are out of " + expr + ".");
}

console.log("Is there anything else you'd like?");
```


##Combining Conditions with Logical Operators:

Often, you'll want to check a variable for more than one possible value, or check more than one variable at once. JavaScript includes logical operators, also known as Boolean operators, for this purpose. Using a logical operator, you can combine them into a single statement.

The three logical operators are: 
```
The logical "OR" operator ( || ) combines the conditions in which only one condition must be true.

if (phone == "" || email == "") window.alert(''Something's Missing!");
```

```
The logical "AND" operator ( && ) combines the conditions such that all must be true.

if (phone =="" && email == "") window.alert("Both are Missing!");
```

```
The third logical operator is the exclamation mark (! =), which means NOT and can be used to invert an expression. 

if (phone != "") alert("phone is OK");

```

##Resources:

http://www.cev.washington.edu/lc/CLWEBCLB/jst/js_conditionals.html
http://www.garrettmedia.com/mission/javascript_presentation/javascript_presentation9.htm

###If/Else:

https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/if...else
http://webcheatsheet.com/javascript/if_else_switch.php

###Switch:

https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/switch
http://stackoverflow.com/questions/4082204/javascript-conditional-switch-statement