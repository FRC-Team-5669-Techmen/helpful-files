# Data types
```java
/* * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * *
 * An int (short for integer) can hold positive and negative whole numbers.
 * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * */
int anInt = 0;
int anotherInt = 10;
int thirdInt = -17;

/* * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * *
 * A double can hold positive and negative decimal numbers. Remember that 12 is
 * an int, but 12.0 is a double!
 * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * */
double aDouble = 0.5;
double anotherDouble = 10.0;
double thirdDouble = -17.4315;
double fancyDouble = 4.7e10; //Doubles can also use scientific notation.

/* * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * *
 * A boolean can hold a true / false value and nothing else.
 * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * */
boolean aBoolean = true;
boolean anotherBoolean = false;
boolean thirdBoolean = false; //Seriously, true and false are the only values.

/* * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * *
 * A char (short for character) can hold a single character (a letter, number,
 * or symbol, basically anything you can type on a QWERTY keyboard). Remember 
 * that 'Z' is a char, but "Z" is a string! Also remember that '8' is a char, 
 * but 8 is an int!
 * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * */
char aChar = 'Z';
char anotherChar = '8';
char thirdChar = '!';

/* * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * *
 * A String (remember, it is capitalized) holds text. (Think of it as a bunch of
 * chars strung together, end-to-end.) Remember that "Z" is a String, but 'Z' is
 * a char! Also remember that "8" is a String but 8 is an int! Finally, remember
 * that "10.0" is a string, but 10.0 is a double!
 * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * */
 String aString = "Z";
 String anotherString = "8.0";
 String thirdString = "Hello there, this is a sentence.";
```

# Math operators
```java
int y;
y = 3 + 2; // + adds numbers
y = 3 - 2; // - subtracts numbers
y = 3 * 2; // * multiplies numbers
y = 3 / 2; // / divides numbers
y = 3 % 2; // % finds the remainder of the division of two numbers.

/* * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * *
 * Remember that the type of data used on both sides of the operator effects
 * the data type of the result. For example:
 * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * */
3.0 / 2.0; // = 1.5
3.0 / 2;   // = 1.5
3 / 2.0;   // = 1.5
3 / 2;     // = 1, because integers cannot hold decimal parts.
```

# Logical operators
```java
boolean a;
a = 3 == 2; // == compares two values, and returns true if they are equal.
            // DO NOT MIX THIS UP WITH =, WHICH ASSIGNS VALUES TO VARIABLES.
a = 3 != 2; // Opposite of ==, returns true if the two values are not equal.
a = 3 > 2;  // Returns true if the left is greater than the right.
a = 3 < 2;  // Returns true if the left is less than than the right.
a = 3 >= 2; // Returns true if the left is greater than or equal to the right.
a = 3 <= 2; // Returns true if the left is less than or equal to the right.
a = !true;  // ! returns the opposite of whatever comes after it.
a = true || false; // Returns true if either the left or the right or both is true.
a = true && false; // Returns true if both the left and the right side is true.
```