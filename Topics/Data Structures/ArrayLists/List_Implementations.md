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


##### ```Find Smallest Number``` can be altered to find largest
Iterates through list using for-loop (index will be used), compares values and saves the smallest number to a variable
```Java
// To alter for finding largest instead, flip the sign in the if-statement and change the variable name and print statement

int smallest = list.get(0);

for(int i = 0; i < list.size() - 1; i++) {

    int number = list.get(i);
    if (smallest > number) {             
        smallest = number;
    }
}

System.out.println("The smallest number: " + smallest);
```
<br>
