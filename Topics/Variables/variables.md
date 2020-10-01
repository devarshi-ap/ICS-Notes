### Reading Variables Using Scanner (in)

int | sc.nextInt();
----|--------------
double | sc.nextDouble();
String | sc.nextLine();
char | sc.char().charAt(0);
boolean | sc.nextBoolean();


###### Variable Conversion:
    String -> Int : Integer.valueOf(string)
    Int -> String : Integer.toString(int)

    String -> Double : Double.valueOf(string)   [also for Int -> Double (int parameter)]
    Double -> String : String.valueOf(double)   [also for Char -> String (char parameter)]

    String -> Boolean : Boolean.valueOf(string)
    Boolean -> String : String.valueOf(boolean)


###### Ex.
    String valueAsString = "42";
    int value = Integer.valueOf(valueAsString);
    System.out.println(value); //prints 42, but as an int
