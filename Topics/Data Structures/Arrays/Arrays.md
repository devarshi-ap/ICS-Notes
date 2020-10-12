# Arrays
Arrays are used to store multiple values in a single variable, instead of declaring separate variables for each value.

<br>

##### ```Declaration```
```Java
//To declare an array, define the variable type with square brackets:

String[] cars;
int[] numbers;
```
<br>


##### ```Initialization```
```Java
//To insert values to it, we can use an Array Literal - place the values in a comma-separated list, inside curly braces:

String[] cars = {"Volvo", "BMW", "Ford", "Mazda"};
int[] numbers = {10, 20, 30, 40};


//Initializing an empty array with a specified number of spaces:

int[] anArray = new int[10]

```
<br>


##### ```Accessing Elements```
```Java
//You access an array element by referring to the index number (arrays start at 0):

String[] cars = {"Volvo", "BMW", "Ford", "Mazda"};
System.out.println(cars[0]);
//prints Volvo

//Make sure the index you provided is exists or else you'll get a IndexOutOfBoundsError
//Empty arrays hold "null" values by default
```
<br>
