# Conditionals

##### ```Operators```
```Java
> greater than
>= greater than or equal to
< less than
<= less than or equal to
== equal to
!= not equal to

&& : and
|| : oro
!  : not
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

##### ```For```
```Java
for (int i = 0; i <= 10; i++) {
    System.out.println(i);
}
//counts up to 10.
//initializes i, checks expression, increments i.
```
<br>

##### ```For-Each``` (arrays)
```Java

for (type var : array) 
{ 
    //code
}
//Initialize "var", the variable used to store each Integer in list as it iterates.

//ex. This example finds the sum of numbers in list
    for(int val: listOfNumbers) {
        sum += val;
    }
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
<br>

##### ```Do-While```
```Java
do{
    System.out.println(i);
    i++;
} while(i < 5);

//same as above while-loop where it counts up to 5.
//do-while will run code then check expression whereas while-loops need the expression to be true to enter.
//if the expression at the bottom is true, it will jump to the top and work it's way down again.
```
<br>

##### ```Continue```
```Java
while (true) {
    System.out.println("Insert positive integers");
    int number = sc.nextInt());

    if (number <= 0) {
        System.out.println("Unfit number! Try again.");
        continue;
    }
    System.out.println("Your input was " + number);
}

//While-true loops are handy when the program has to repeat a functionality until the user provides certain input
//Continue; breaks out of the inner loop and goes to the top of the outer loop.
//See more in the Misc. Section: ICS NOTES/TOPICS/MISC
```
<br>

##### ```Switch-Case```
```Java
switch(value){
    case x:
        //code
        break;
    case y:
        //code
        break;
    default:
        //code
}
//value can be int/double/string etc...
//if the value is x, then it will do the code in case x. The [break;]'s help escape the conditional
//if value isn't x or y, then it will do the code in default.
```
<br>

##### ```Modulo```
```Java
7 % 2

//prints the remainder, 1
//can be used to check if even (x % 2 == 0) or odd (x % 2 == 1)
```
<br>

##### ```Try-Catch```
```Java
try{
    //code block
} catch(Exception e) {
    //code block to handle errors
}
//tries the code in the try code block. If it throws an exception, the catch {}'s will catch the error
//and run the code in the code block instead of throwing an error.
/*Exception e can be replaced with:
- ArithmeticException
- FileNotFoundException
- ArrayIndexOutOfBoundsException
- SecurityException
*/
```
<br>
