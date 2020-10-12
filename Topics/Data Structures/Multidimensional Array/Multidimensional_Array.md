# Multidimensional Array
Don't be alarmed by the name, they are simply arrays that contain other arrays; so like a nested array.
<br>


##### ```Declaration```
```Java
//To declare a 2d array, enter the [#rows][#columns] like so:

int[][] multiples = new int[4][2];          // 2D int array with 4 rows and 2 columns
String[][] cities = new String[3][3];       // 2D String array with 3 rows and 3 columns


//make sure to specify atleast the first dimension (rows):

int[][] wrong = new int[][];    // not OK, you must specify 1st dimension
int[][] right = new int[2][];   // OK

```
<br>


##### ```Initialization```
```Java
//To initialize a 2d array, use Array Literal Notation:

//int array with 3 rows and 3 columns
int [][] sample = {
       {1, 2, 3}, 
       {4, 5, 6}, 
       {7, 8, 9}
};


//int array with 3 rows and 4 columns
int[][] a = {
      {1, 2, 3}, 
      {4, 5, 6, 9}, 
      {7}, 
};

```
<br>

![2d-array-variable-length](https://user-images.githubusercontent.com/59234436/95795286-fee68200-0cb7-11eb-8617-6d3e7478e785.jpg)

<br>


##### ```Accessing Elements```
```Java
//To access elements, specify the index of the row and column (starts at 0 like 1d array):

int [][] sample = {{1, 2, 3}, {4, 5, 6}, {7, 8, 9}};

int x = sample [2][0]       // 3rd row, 1 element; x=7
```
<br>
