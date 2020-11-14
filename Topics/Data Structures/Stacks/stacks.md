# ```Stacks``` import java.util.Stack;
Stacks are an abstract data type with a bounded(predefined) capacity.

<br>

To help visualize Stacks, parallel it to a stack of video games, where the first element added to the stack is at the bottom. Every time you add a video game, it gets added ontop of the stack.

<br>

##### ```Declaration```
```Java
// To declare a Stack, include the type of the content it will hold (Integer, String, etc..) and the Stack name followed by new LinkedList<>():

Stack<_Type_> _name_ = new Stack<_Type_>();
Stack<String> games = new Stack<String>();
```
<br>



##### ```Adding to Stack```
```Java
// to add to stack, stackName.add(x);
// Note that the first thing added is at bottom of stack

games.add("Call of Duty");
games.add("Genshin Impact");
games.add("Pokemon");
//the games stack from bottom to the top:  "Call of Duty", "Genshin Impact", "Pokemon"
```
<br>



##### ```Accessing Values```
```Java
// to get a value from stack, stackName.get(index)
// where index 0 is the bottom

games.get(0);   //"Call of Duty"
games.get(1);   //"Genshin Impact"
games.get(2);   //"Pokemon"
```
<br>



##### ```Removing from Stack```
```Java
// for the stack data structure you can only remove the element at the top (last element in stack)
// to do so, use stackName.pop();

games.pop();      // pop() popped the top element out (pokemon) and now leaves us with "Call of Duty","Genshin Impact"
games.pop();     // "Call of Duty"
games.pop();    // Empty now
```
<br>



##### ```Peeking```
```Java
//to simply see the top (last element) of the stack- but not remove it, use stackName.peek();

games.peek();   // "Pokemon"
```
<br>



##### ```Check for Element```
```Java
//return true/false whether or not the element specified is in the stack; using stackName.contains(x);

games.contains("Genshin Impact");   //true
games.contains("Assassins Creed");   //false
```
<br>



##### ```Check If Empty```
```Java
//to check if stack is empty, stackName.empty(). returns true or false

games.empty();   //false
```
<br>



##### ```Size```
```Java
//to check how many elements are in the stack (size), use stackName.size()

games.size();   //3

games.pop();
games.size();   //2; pop() removed the top element
```
<br>
