# Math Methods  ```import java.lang.Math;```

##### ```xxxValue()``` returns the primitive data type that is given in the signature.
```Java
int x = 5;

x.byteValue();
x.doubleValue();
x.longValue();
x.shortValue();
x.floatValue();
```
<br>

##### ```parseInt()``` used to get the primitive data type of a certain String.
```Java
int x =Integer.parseInt("9");        //x = 9
double c = Double.parseDouble("444");  //c = 444
```
<br>

##### ```abs()``` gives the absolute value of the argument.
```Java
int a = -8;
double d = -100;

Math.abs(a);  //8
Math.abs(d);  //100.0
```
<br>

##### ```ceil()``` returns the smallest integer that is greater than or equal to the argument.
```Java
double d = 4.3;
double x = -100.678;   

Math.ceil(d);   //5.0
Math.ceil(f);   //-100.0
```
<br>

##### ```floor()``` returns the largest integer that is less than or equal to the argument.
```Java
double d = 4.3;
float f = -100.678; 

Math.floor(d);   //4.0
Math.ceil(f);    //-101.0
```
<br>

##### ```rint()``` returns the integer [double.0] that is closest in value to the argument. Parameter must be double
```Java
double d = 100.675;
double e = 100.500;
double f = 100.200;

Math.rint(d);   //101.0
Math.rint(e);   //100.0
Math.rint(f);   //100.0
```
<br>

##### ```round()``` returns the closest long or int to the argument. Parameter must be double or float
```Java
double d = 100.675;
double e = 100.500;
float f = 100;

Math.round(d);   //101
Math.round(e);   //101
Math.round(f);   //100
```
<br>

##### ```min()``` gives the smaller of the two arguments
```Java
Math.min(5, 10);            //returns 5
Math.min(12.123, 12.456);   //returns 12.123
```
<br>

##### ```max()``` gives the larger of the two arguments
```Java
Math.max(5, 10);            //returns 10
Math.max(12.123, 12.456);   //returns 12.456
```
<br>

##### ```exp()``` returns the base of the natural logarithms, e, to the power of the argument. Double as parameter
```Java
double x = 11.635;

Math.exp(x);   //exp(11.635) is 112983.831
```
<br>

##### ```log()``` returns the natural logarithm of the argument.
```Java
double x = 11.635;

Math.log(x);   //log(11.635) is 2.454
```
<br>

##### ```pow()``` returns the value of the first argument raised to the power of the second argument.
```Java
Math.pow(12, 2);   //144
```
<br>

##### ```sqrt()``` returns the square root of the argument.
```Java
Math.sqrt(144);   //12
```
<br>

##### ```cbrt()``` returns the cube root of the argument.
```Java
Math.cbrt(125);   //5.0
```
<br>

##### ```sqrt()``` returns the square root of the argument.
```Java
Math.sqrt(144);   //12
```
<br>

trig ratio | code *double type parameter | return value
-----------|------|-------------
sin | Math.sin(x) | returns sinX
cos | Math.cos(x) | returns cosX
tan | Math.tan(x) | returns tanX
asin | Math.asin(y) | returns arcsinX
acos | Math.acos(y) | returns arccosX
atan | Math.atan(y) | returns arctanX
<br>

##### ```PI()``` returns the value of pi to the 15th decimal.
```Java
double area = Math.PI * (radius * radius);    //Math.PI acts as 3.14... itself
```
<br>

##### ```toDegrees()``` converts the argument (radians) value to degrees. Double as parameter
```Java
double x = 45.0;

Math.toDegrees(x);    //2578.3100780887044
```
<br>

##### ```toRadians()``` converts the argument (degrees) value to radians. Double as parameter
```Java
double x = 45.0;

Math.toRadians(x);    //0.7853981633974483
```
<br>

##### ```random()``` used to generate a random number between 0.0 and 1.0
```Java

Math.floor(Math.random()*100) + 1;  //100 is the ending value. 1 is the starting value. Inclusive
int dieRoll = (int)(6 * Math.random() ) + 1;    //b/n 1-6 inclusive
```
<br>
