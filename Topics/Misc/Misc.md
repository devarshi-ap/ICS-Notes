# Miscellaneous

##### ```Random Number```
```Java
int dieRoll = (int)(6 * Math.random() ) + 1;    //b/n 1-6 inclusive
```
<br>

##### ```Break;``` used to break out of all loops (nested included). Anything below a break; is unreachable code and will cause an error
```Java
for (int i = 0; i <= 10; i++) {
    if (i == 4) {
      break;
    }
    System.out.println(i);
}

//iterates from 0-10. If it's 4, it ends the loop
```
<br>

##### ```Continue;``` breaks one iteration (in the loop), if a specified condition occurs, and continues with the next iteration in the loop. Anything below a break; is unreachable code and will cause an error
```Java
for (int i = 0; i < 10; i++) {
    if (i == 4) {
      continue;
    }
    System.out.println(i);
}

//iterates from 0-10. If it's 4, it jumps out of the if-statement and to the for-loop and continues iterating
//think of it as if though it jumps to the top of the loop
```
<br>

##### ```Swapping Values;```
```Java
int a = 7, b = 10;
            
a ^= b;
b ^= a;
a ^= b;

//Now, a=10, b=7
```
<br>


##### ```Import Keyword```
The import keyword is used to import a package, class or interface.
```Java
// You can import just the classes you need from a package. Just provide an import statement for each class that you want to use:
// Import the Scanner class from the Java API
import java.util.Scanner;

// Another option is to import everything at the same level in a package using import packageName.*.
import java.util.*;

// Below I've provided a list with useful classes to import and their key uses.
```
<br>


class | highlight
----|--------------
java.lang.String | used to create / operate immutable string literals
java.lang.Exception | helps deal with exception and error handling
java.util.ArrayList | implementation of array data structure
java.util.HashMap | implementation of a key-value pair data structure
java.lang.Object | contains early methods like equals, hashcode, clone, toString, etc
java.util.Date | used to work with date and current time
java.util.Iterator | allows use of an 'Iterator' object that can be used to loop through Lists and HashSets
