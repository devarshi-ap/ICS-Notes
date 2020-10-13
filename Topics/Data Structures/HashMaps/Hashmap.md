# ```HashMaps``` import java.util.HashMap
Hashmaps store items in key/value pairs (equivalent of Python's Dictionaries)\
<br>
HashMap is known as HashMap because it uses a technique called **_Hashing_** - \
technique of converting a large String to a small String that represents the same String. A shorter value helps in indexing and faster searches

<br>
In ArrayLists, you learned that Arrays store items as an ordered collection, and you have to access them with an index number.
A Hashmap however, stores items in "key/value" pairs where you can access the 'value' if you provide the 'key'.
<br>

Hashmaps can store different types: 
- (**String** keys && **Integer** values) or the same type (**String** keys && **String** values)
<br>
 

##### ```Creating a Hashmap```
```Java
// Syntax of creating hashmap:    HashMap<Key Type, Value Type> hashmapName = new HashMap<Key Type, Value Type>();

HashMap<String, String> capitalCities = new HashMap<String, String>();
HashMap<String, Integer> people = new HashMap<String, Integer>();
```
<br>


##### ```Adding to Hashmap```
```Java
// to add items to it, use the 'put()' method and specify the key followed by the value:

capitalCities.put("England", "London");
capitalCities.put("Germany", "Berlin");
 
people.put("LeBron", 35);
people.put("Kobe", 42);
    
//remember the type of the key&value have to correspond to the order you declared in the HashMap<Key type, Value Type> respectively
```
<br>


##### ```Accessing Items```
```Java
// To access a value in the HashMap, use the get() method and refer to its key:

capitalCities.get("England");   //checks capitalCities for key:"England" and returns value:"London"
people.get("Kobe");             //checks people for key:"Kobe" and returns value:42
```
<br>


##### ```Removing Items```
```Java
// To remove an item, use the remove() method and refer to the key:

capitalCities.remove("England");    //removes the England/London pair
people.remove("LeBron");            //removes the Lebron/35 pair


// To remove all items, use the clear() method:

capitalCities.clear();
people.clear();
```
<br>


##### ```Replacing Values```
```Java
// To replace a value, use the replace() method and provide the old value's key and the new Value:

capitalCities.replace("England", "newCapital");      //replaces England/London pair with England/newCapital
people.replace("LeBron", 27);                       //replaces Lebron/35 pair with Lebron/27
```
<br>


##### ```Retrieving```
```Java
// To retrieve all the keys in the Hashmap:

capitalCities.keySet();     // ["England", "Germany"]
people.keySet();            // ["LeBron", "Kobe"] 


// To retrieve all values in the Hashmap:

capitalCities.values();     // ["London", "Berlin"]
people.values();            // [35, 42]
```
<br>


##### ```Checking for Key/Value```
```Java
// To check if the Hashmap has a specific Key (returns true/false) :

capitalCities.containsKey("Vietnam");     // False
people.containsKey("LeBron");            // True


// To check if the Hashmap has a specific Value (returns true/false) :

capitalCities.containsValue("Berlin");      // True
people.containsValue(23);                  // False
```
<br>



##### ```Size```
```Java
// To find out how many items there are, use the size method:

capitalCities.size();     // 2
people.size();            // 2
```
<br>



##### ```Looping over HashMap```
```Java
// Use a for-each loop to iterate through the items of a HashMap.
// Note: Use the keySet() method if you only want the keys, and use the values() method if you only want the values:

// Print keys
for (String i : capitalCities.keySet()) {
    System.out.println(i);
}


// Print values
for (String i : capitalCities.values()) {
  System.out.println(i);
}
```
<br>
