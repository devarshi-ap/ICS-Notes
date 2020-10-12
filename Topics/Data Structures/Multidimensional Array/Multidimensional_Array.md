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
