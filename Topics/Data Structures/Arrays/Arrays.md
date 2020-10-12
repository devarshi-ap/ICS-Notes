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


##### ```Changing Array Elements```
```Java
//To change the value of a specific element, refer to the index number:

String[] cars = {"Volvo", "BMW", "Ford", "Mazda"};
cars[0] = "Ferrari";

//now the cars array looks like {Ferrari, BMW, Ford, Mazda}
```
<br>


##### ```Array Length```
```Java
//To find out how many elements an array has, use the 'length' method:
//**Not to be mistaken for 'length()' method which is a string method**


String[] cars = {"Volvo", "BMW", "Ford", "Mazda"};
System.out.println(cars.length);
// Outputs 4
```
<br>


##### ```Iterating over an Array```
```Java
//You can loop through the array elements with the for loop, and use 
//the 'length' method to specify how many times the loop should run :


String[] cars = {"Volvo", "BMW", "Ford", "Mazda"};

for (int i = 0; i < cars.length; i++) {
    System.out.println(cars[i]);
}

//starts at index (i) = 0, accesses and prints the value of cars at index i.
//goes up to cars.length which is 4. Make sure its i < cars.length and not
//i <= cars.length because it will run once more after i=4 and throw an IndexOutOfBoundsError
```
<br>


##### ```Iterating using For-Each loop```
```Java
/*There is also a "for-each" loop, which is used exclusively to loop through elements in arrays:

for (type variable : arrayname) {
  code
}

this loop goes through the array 1 by 1 and assigns it to the variable.
*/

String[] cars = {"Volvo", "BMW", "Ford", "Mazda"};

for (String i : cars) {
    System.out.println(i);
}

//this prints out all the elements in the array
```
<br>
