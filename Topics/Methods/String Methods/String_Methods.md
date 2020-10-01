# String Methods

##### ```toLowerCase()``` converts a string to lower case letters.
```
txt.toLowerCase()
```

  
##### ```toUpperCase()``` converts a string to upper case letters.
```
txt.toUpperCase()
```


##### ```length()``` returns int value of the number of characters in string. The length of an empty string is 0
```
String txt = "hello";
int x = txt.length(); //5
```


##### ```contains()```Finds out if a string contains a sequence of chars. Returns true if the chars exist; false if not.
```Java
String myStr = "Hello";
myStr.contains("Hel");   // true
myStr.contains("e");     // true
myStr.contains("Hi");    // false
```


##### ```equals()``` Compares two strings, and returns true if the strings are equal, and false if not.
###### ```equalsIgnoreCase()``` Compare strings to find out if they are equal, ignoring case differences

```Java
String myStr1 = "Hello";
String myStr2 = "Hello";
String myStr3 = "Another String";
myStr1.equals(myStr2); // Returns true because they are equal
myStr1.equals(myStr3); // false
```


##### ```compareTo()```
###### ```compareToIgnoreCase()```
Returns An int value:\
0 if the string is equal to the other string.\
< 0 if the string is lexicographically less than the other string.\
\> 0 if the string is lexicographically greater than the other string (more characters).
```Java
String myStr1 = "Hello";
String myStr2 = "Hello";
myStr1.compareTo(myStr2); // Returns 0 because they are equal
```


##### ```indexOf()``` returns the index of the first occurrence of specified char(s) in a string
##### ```lastIndexOf()``` returns the index of the last occurrence of specified char(s) in a string
```
String myStr = "Hello planet earth, you are a great planet.";
myStr.lastIndexOf("planet");  //36
```


##### ```concat()``` appends (concatenate) a string to the end of another string
```
String firstName = "Barry ";
String lastName = "Allen";
firstName.concat(lastName); //Barry Allen
```


##### ```replace()``` searches string for specified char(s), and returns new string where specified char(s) are replaced
```
String myStr = "Hello";
myStr.replace('l', 'p');  //replace(searchFor, ReplaceWith)
//returns "heppo"
```


##### ```trim()``` removes whitespace from both ends of a string. This method does not change the original string
```
String myStr = "       Hello World!       ";
myStr.trim(); //"Hello World!"
```


##### ```startsWith()``` checks whether a string starts with the specified char(s).
##### ```endsWith()``` checks whether a string ends with the specified char(s).
```
String myStr = "Hello";
System.out.println(myStr.startsWith("Hel"));   // true
System.out.println(myStr.startsWith("llo"));   // false
System.out.println(myStr.endsWith("o"));     // true
```


##### ```charAt()``` returns the char at the specified index in a string
```
String myStr = "Hello";
char result = myStr.charAt(0);  //'H'
```


##### ```split()``` splits a string at a specified char and creates an array; parameter is what's being removed. 
If you split a string and an int, they both become strings so convert using Integer.valueOf()
```
String text = "first second third fourth";
String[] pieces = text.split(" ");    //{"first", "second", "third", "fourth"}  
```


##### ```subString()``` returns a substring of this string; from at the first index to the second (exclusive); otherwise extends to the end of this string
```
String str = "Hello world!";
str.substring(0, 5);     //"Hello"
str.substring(6);        //"world!"
```
