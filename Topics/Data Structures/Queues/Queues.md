# ```Queues``` import java.util.Queue;  |   java.util.LinkedList;
Java Queues order elements in a FIFO (First In First Out) manner.
In FIFO, first element is removed first and last element is removed at last.

<br>

To help visualize Queues, parallel it to a line at backyard bbq (or anything where people line up for something), where you give bbq
to the person infront of the line. After, they've been served, they leave the line. Queues work in just that way!

<br>

##### ```Declaration```
```Java
//To declare a Queue, include the type of the content it will hold (Integer, String, etc..) and the queue name followed by new LinkedList<>():

Queue<Type> queueName = new LinkedList<>();
Queue<Integer> numbers = new LinkedList<>();
Queue<String> bbqLine = new LinkedList<>();
```
<br>


##### ```Adding to Queue```
```Java
//to add to queue, queueName.add(x)
//Note that the first thing added is first in Queue

numbers.add(24);
numbers.add(23);
numbers.add(32);
//24,23,32

bbqLine.add("Kobe");
bbqLine.add("Jordan");
bbqLine.add("Shaq");
//"Kobe", "Jordan", "Shaq"
```
<br>


##### ```Removing from Queue```
```Java
//to remove from queue, queueName.poll()
//removes first thing in queue; which is 24 (numbers) and Kobe (bbqLine)

numbers.poll();
//23,32

bbqLine.poll();
//"Jordan", "Shaq"
```
<br>


##### ```Peeking```
```Java
//to simply see the 'head' (first element) of queue- but not remove it, use queueName.peek();

numbers.peek();
//24

bbqLine.peek();
//"Kobe"
```
<br>


##### ```Size of Queue```
```Java
//returns amount of things in queue

numbers.size();
//3

bbqLine.size();
//3
```
<br>


##### ```Check for Element```
```Java
//return true/false whether or not the element specified is in the list; using queueName.contains(x)

numbers.contains(23);   //true
numbers.contains(30);   //false

bbqLine.contains("Jordan");   //true
bbqLine.contains("Curry");   //false
```
<br>


##### ```Convert to Array```
```Java
//to convert a queue to an array of the same type, use toArray() method like so:

numbers.toArray();    //numbers is now [24, 23, 32] where 24 is index 0
bbqLine.toArray();    //bbqLine is now ["Kobe", "Jordan", "Shaq"] where kobe is index 0
```
<br>


##### ```Iterating Queue```
```Java
// There are multiple ways to iterate through Queues
// Method 1: convert queue to array and traverse via for-each loop:

numbers.toArray();
for (Integer n : numbers) {
    System.out.println(n);
}



// Method 2: Queues also have an inbuilt iterator which can be used to iterate through the Queue.
// First,                     import java.util.Iterator;
// Create iterator object:    Iterator<Type> iteratorName = queueName.iterator();

Iterator<Integer> itr = numbers.iterator();

// hasNext() returns true if the queue has more elements
while (itr.hasNext())
{
    // next() returns the next element in the iteration
    System.out.println(itr.next());
}

```
<br>
