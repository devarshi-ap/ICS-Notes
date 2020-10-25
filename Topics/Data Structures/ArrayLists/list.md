# ```ArrayLists``` import java.util.ArrayList;
The ArrayList, or simply list, is a resizable array; elements can be added and removed from an ArrayList whenever you want.
<br>

Where as with arrays, the size cannot be modified ((if you wanted to add or remove elements from an array, you'd have to create a new one)

<br>

##### ```Declaration```
```Java
//To declare a list, import the class mentioned above and write the declare the following:

import java.util.ArrayList;   // import the ArrayList Class

ArrayList<_listType_> _listName_ = new ArrayList<_listType_>();   // Create an ArrayList object

ArrayList<Integer> numbers = new ArrayList<Integer>();
ArrayList<String> cars = new ArrayList<String>();
```
<br>


##### ```Add Items```
```Java
// To add elements to the ArrayList, use the add() method:
listName.add("item");

numbers.add(1);
numbers.add(2);
numbers.add(3);   //numbers now has [1, 2, 3]

cars.add("Maserati");
cars.add("BMW");
cars.add("Ferrari");    //cars now has ["Maserati", "BMW", "Ferrari"]
```
<br>


##### ```Accessing Items```
```Java
// To access an element in the list, use the get() method and refer to the index number (starts at 0 just like arrays):
listName.get(index);


numbers.get(0);   // 1
cars.get(2);      // "Ferrari"
```
<br>


##### ```Changing Items```
```Java
// To modify an element, use the set() method and refer to the index number and the new element:
listName.set(index, "newValue");


numbers.set(0, 23);          // numbers now has [23, 2, 3]
cars.set(0, "Infiniti");      // cars now has ["Infiniti", "BMW", "Ferrari"]

// make sure the index you are trying to change exists and that the new value is the same type as the list type
```
<br>


##### ```Removing Items```
```Java
// To remove an element, use the remove() method and refer to the index number:
listName.remove(index);


numbers.remove(2);       // numbers now has [1, 2] because 3 at index 2 was removed
cars.remove(1);         // cars now has ["Maserati", "Ferrari"] because "BMW" at index 1 was removed


// To remove all elements in the list, use the clear() method:
listName.clear();

numbers.clear();  // list is now empty
cars.clear();
```
<br>


##### ```Size```
```Java
// To find out how many elements an ArrayList have, use the size method
listName.size();


numbers.size();       // returns 3
cars.size();         // returns 3
```
<br>


##### ```Sorting List (+reverse)```
```Java
// A useful class in the java.util package is the 'Collections' class, which includes the sort() method for sorting lists //alphabetically (uppercase take priority over lowercase) or numerically (least to greatest)
//You will however need to import the class:
 
import java.util.ArrayList;
import java.util.Collections;     // Import the Collections class


/*
Lets say we have 2 lists:
    'nums' which has [3, 7, 8, 2, -1, -10, 0]
    'cars' which has ["Volvo", "BMW", "Ford", "Mazda", "aye"]
*/

Collections.sort(nums);     // new nums list: [-10, -1, 0, 2, 3, 7, 8]
Collections.sort(cars);     // new cars list: ["BMW", "Ford", "Mazda", "Volvo", "aye"]


// To sort in reverse order {greatest to least} and descending alphabetical order, add a Collections.reverseOrder()
// to the Collections.sort() call as a second argument like so:

Collections.sort(nums, Collections.reverseOrder());     // new nums list: [100, 8, 7, 3, 2, 0, -1, -10]
Collections.sort(cars, Collections.reverseOrder());     // new cars list: ["aye", "Volvo", "Mazda", "Ford", "BMW"]
```
<br>


##### ```Iterating Through List```
```Java
// There are two ways of looping through a list: a for-loop, and a for-each loop:


// A for-loop is useful when you need to make use of the index feature.
for (int i = 0; i < cars.size(); i++) {
    System.out.println(cars.get(i));
}


// A for-each loop is more convenient and quicker as it doesn't need indices.
for (String i : cars) {
      System.out.println(i);
}
```
<br>
