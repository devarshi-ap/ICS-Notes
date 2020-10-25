# ArrayList Implementation References
Here are some ways you can manipulate lists to do some handy dandy things.
If you aren't familiar with methods and how to use them, worry not. Just focus on the code inside the first curly braces.
The names are super generic, making it super duper simple to read and analyze.

<br>

##### ```Compute Sum```
Iterates through array, adds each element to sum and increments count by 1 then determines average by dividing the two.
```Java
public static int sum(ArrayList<Integer> ListOfNumbers) {
    int sum = 0;
    
    for (int num: ListOfNumbers) {
        sum += num;
    }
    return sum;
}
```
<br>
