# Conditionals

##### ```Operators```
```Java
> greater than
>= greater than or equal to
< less than
<= less than or equal to
== equal to
!= not equal to
```
<br>

##### ```If```
```Java
if (EpxressionTrue) {
    System.out.println("do this");
}
```
<br>

##### ```If-Else```
```Java
if (EpxressionTrue) {
    System.out.println("do this");
} else {
    System.out.println("or else do this");
}
```
<br>

##### ```Else-If```
```Java
if (EpxressionTrue) {
    System.out.println("do this");
    
} else if (additional condition){
    System.out.println("or else do this");
    
} else {
    System.out.println("or else do this");
}

//if the [if] is true, it will print "do this" and the program will skip the elseif and else.
//if the [if] is false, it will move onto the [elseif] and check if it's true. If it's true, it will skip the else.
//if neither the [if] or [elseif] is true, it will by default run the else.
//You can as many [elseif]'s you want between the [if] and the [else] !
```
<br>

##### ```While```
```Java
int i=0;
while(i < 5) {
    System.out.println(i);
    i++;
}
//while [i] is less than 5 it will print the value of [i] and then add one to i.
//a while loop will keep on running the code inside until the argument is false.
//Make sure you have an exit card (break;) for the while loop or else you'll end up with an infinite loop
```
