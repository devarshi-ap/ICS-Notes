# Custom Methods

##### ```Creating and Calling Methods```
```Java
// A method must be declared within a class. It is defined with the name of the method, followed by parentheses ().
// Java provides some pre-defined methods (println()) but you can also create your own methods to perform certain actions:

// You can create a simple method like so:

public static void myMethod() {
    System.out.println("hello");
}

/* so every time you call this method using myMethod(), it will print "hello". It's much cleaner and organized.
   Some special words in the example above:
      public - can be accessed by other (disregard it for now)
      static - (disregard it for now)
      void - no value is returned using the 'return' keyword. If something is returned, you'd replace it with the type (String, etc)
      myMethod() - name of your custom method
*/

//to call this method:

myMethod();   //prints out "hello" just like that. Don't put this in a println(); you're already printing it
```
<br>


##### ```Method Parameters```
```Java
// Information can be passed to methods as parameter. Parameters act as variables inside the method.
// Parameters are specified in the parentheses after the method name.
// You can have as many as you want, just separate them with a comma.

// The following takes an int parameter called age as a parameter. In the method call, put an int value in the ()'s.
// This will assign the int age paramter a value of whatever number you type in:

public class MyClass {
  static void myMethod(int age) {
    System.out.println("I am " + age + " years old.");
  }

  public static void main(String[] args) {
    myMethod(17);           //will print out "I am 17 years old"
    myMethod("Seventeen");  //will throw error because the parameter is supposed to be int, as specified in teh MyMethod definition
  }
}
```
<br>


##### ```Multiple Parameters```
```Java
//You can have as many parameters as you wish:

public class MyClass {
  static void myMethod(int age, String name, double weight) {
    System.out.println("My name is " + name + ", I am " + age + " years old, and I weight " + weight + "Kg's");
  }

  public static void main(String[] args) {
    myMethod(17, "dev", 69.96);   //will print out "My name is dev, I am 17 years old, and I weight 69.96Kg's"
    myMethod("dev", 69.96, 17);   // this won't work as you have to pass int age, string name, and double weight parameters IN THAT ORDER
  }
}
```
<br>


##### ```Return```
```Java

```
<br>


##### ```Void```
```Java

```
<br>
