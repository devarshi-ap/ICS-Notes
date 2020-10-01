## Ternary Operator

##### The Java ternary operator functions like a simplified Java if statement. 

* The ternary operator consists of a condition that evaluates to either true or false, plus a value that is returned if the condition is true and another value that is returned if the condition is false.

##### Format
 - System.out.println( expression ? "true" : "false");
 - System.out.println( expression ? "true" : expression2 ? "false" : "maybe");

##### Here are some simple Java ternary operator examples:
    
```Java
System.out.println( (a > b) ? ("A") : (b < a) ? ("B") : ("Tie") );
String name = stringName.equals("uppercase") ? "JOHN" : "john";
```
    

* ? checks if statement is true; if yes, print what follows the question mark
* : separates the "arguements". If the first one is false, it goes to second argument
