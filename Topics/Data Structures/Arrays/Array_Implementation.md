# Array Implementation References
Here are some ways you can manipulate arrays to do some handy dandy things

<br>

##### ```Compute Sum and Average of Array Elements```
Iterates through array, adds each element to sum and increments count by 1 then determines average by dividing the two.
```Java
int[] array = {10, 20, 30, 40, 50, 10};
double sum = 0, count = 0;

for( int x : array) {
    sum += x;
    count++;
}

double average = sum/count;

System.out.println("Sum : " + sum);
System.out.println("Average : " + average);
```
<br>


##### ```Maximum and Minimum```
Sort method rearranges int array from least to greatest where the min is the first number and max is the last
```Java
int[] nums = {10, 7, 1, 24, -9, -2, 0, 89, -101};
Arrays.sort(nums);

System.out.println("Minimum = " + nums[0]);
System.out.println("Maximum = " + nums[nums.length-1]);
```
<br>
