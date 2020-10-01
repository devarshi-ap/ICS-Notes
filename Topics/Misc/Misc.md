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
