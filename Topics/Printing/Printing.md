# Formatting with printf()

The method is part of the java.io.PrintStream class and provides String formatting similar to the printf() function in C.


## Syntax
    System.out.printf(format, arguments);   
               [format] -  text marked up with % formatters
            [arguments] - variables/values separated by commas corresponding to the occurences of the % formatters
    
    
    Formatters:
            %d - int
            %f - double
                %.2f - 2 decimals places after period (3.141592653589 -> 3.14)
            %c - char
            %s - string
            %b - boolean
            %n - newline
    
    
    ex.     System.out.printf("%d %f %c %s %b %n", int, double, char, string, boolean);
            System.out.printf("Hello %s!%n", "World");

                In this example, %s is reaplced by the first argument (the only one): "World". Then follows %n which is a new line.
