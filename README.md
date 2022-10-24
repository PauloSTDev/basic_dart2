# Dart
## Variables and Values Assignments
### Naming Variables:
Variables names can be any valid letter, word or even sentence but it can not start with a number, the number can be at the middle or at the end. We can use underline at the beginning, we can not use at the end and at the middle of a variable. We can not use any operator(+, - ...) or any special caracter in your variable name. Private variables has a underline at the beginning(_variable).
## Classes
We can not use underline at the middle or at the end, just at the beginning, making the class private, the beginning letter must to be uper case, we can use uper case at the middle or at the end.

❗ All the packages, libraries, directories and source files will be named with lower case, usying underline to separe the words ❗

## Operators in Dart
### Arithmatic Operators
Are used for mathematical calculations.

add/plus = +

Subtract = -

Unary minus = -expr

Multiply = *

Divide = /

Divide, for returning an integer result only = ~/ (print(10 ~/ 3) = 3)

and Modulo = % (print(89%9) = 8) Get the remainder of an integer division

(+) Also used to concatenate two or more strings (print("5"+"5") = 55)

(*) Also used to multiply (print("a"*5) = aaaaa)

### Increment and Decrement Operators
Dart supports both prefix and postfix increment and decrement operators as other languages.

--decrement or decrement-- is the same thing = 1 - variable

++increment or increment++ is the same thing = 1 + variable

### Equality and Relational Operators
Are used to compare if both values are equal ou not and to check relation if one value is grater ou lesser than other value and always returns true ou false.

#### Equality Operators:
Equal ==

Not equal != 

#### Relational Operators:
Greater than >

Less than <

Greater than or equal to >=

Less than or equal to <=

### Type Test Operators
Used for testing data type and specifying library prefix

as: Typecast and to specify prefix (import "package:lib/lib.dart" as libraryName)

is: Returns true if the object, variable or value has the specified type (if (produtcPrice is double){})

is!: Returns false if the object, variable or value has the specified type (if (produtcPrice is! double){})

Using is and is! we can check if the object, variable or value of specific type or not
### Assignment Operators
Are used to assign value to variable (variable = value, fistNumber = 10). If we want to set value to a variable only if the variable is null then we can use null assignment operator (variableName ??= value, firstName ??= "Paul").

We can use ?? too (variable = variable ?? value) If the variable is null so the value will be assigned to the variable.

### Compound Assignment Operators
Combine an operation with an assignment, always are combined with an assignment operator and arithmetic operator or relational operator.

### Logical Operators
You can invert or combine boolean expressions using the logical operators
! Invert values

|| Logical OR

&& Logical AND

### Bitwise and Shift Operators
Used to manipulate the individual bits of numbers in Dart

& AND

| OR

^ XOR

<< Left Shift

e >> Right Shift

### Conditional Expression Operators
Dart has two operators that let you concisely evaluate expressions that might otherwise require if-else  statements

?: Interrogation signed with Colon

?? Double Interrogation

When you need to assign a value based on a boolean expression, consider using => ?:

If the boolean expression tests for null, consider using => ??

Example: condition ? expr1 : expr2 == If the condition is true, evaluates expr1(and returns its value); otherwise, evaluates and returns the value of expr2:

Example: expr1 ?? expr2 == If expr1 is non-null, returns its value; otherwise, evaluates and returns the value of expr2.

### Keywords
63 Keywords until now: https://dart.dev/guides/language/language-tour#keywords

### Types in Dart
There are four kinds of data: Text, Number, Boolean and Custom Type(User Defined Type)

In Dart text Type is data is  called String type data,
there are classifications in Number Type data.
Booleans are  True and False.
And Custom Type can be all together.

There are 8 built-it types in dart based on complexity: numbers, strings, booleans, lists (also known as arrays), sets, maps, runes(for expressing Unicode characters in a string) and symbols.

### Number
Unlike other languages, Dart has only two number type data and those are int and double

Example:

int firstNumber = 10;

double secondNumber = 10.5;

If you want to work with fraction data then  the data type must be double.

We can use toStringAsFixed() method for fixing digits after fraction:

123.456.toStringAsFixed(2);

result => "123.46"

### String

A dart String is a sequence of UTF-16 code units. You can use either single or double quotes to create a string.

String text1 = "Something";

String text2 = 'Something';

Use forward slash to escape character if you use quotation insingle quote literal.

String text1 = "It´s something";

String text2 = 'It\´s something';

You can put the value of an expression inside a string by using ${expression}.

String text = 'string interpolation';

print('Dart has ${text}, which is very handy.');

if the expression is a identifier you can skip {}.

print('Dart has $text, which is very handy.');

You can concatenate strings using adjacent string literals or the + operator.

String text = 'String '

'concatenation'

"works even over line breaks. ";

print(text + "More String");

Triple quote: 

String text1 ='''Multi-line strings, it will use...
the lines that you need.''';

String text2 = """Also a multi-line strings"""

You can create a "raw" string by prefixing it with r:

String text = r'In a raw string, not even \n gets special treatment.';

### Booleans

Dart has a type named bool to represent bo0lean values. The boolean literals are true and false, which are both compile-time constants.

### List

We can call list of object as well

var numberList = [1, 2, 3];

List<String> stringList = ["Paulo", "Santos"];

### Sets

Unauthorized collection of unique items:

var colors= {'blue', 'red', 'yellow'};

Set<String> colors2= {'blue', 'red', 'yellow'};
  
### Maps

Object that associates keys and values that can be any values, value can be duplicate but key must be unique:
  
var object = {
   //key : value
  'first' : 1,
  'second' : 'String',
  'third': '3'
 };
  
You can create the same Map using a Mpa constructor:
  
var object = Map();
  
object['first'] = 1;
  
object['second'] = 'String';
  
object['third'] = '3';

### Runes

In Dart Runes are the UTF-32 code points of a string, Runes helps creating emojis.

![2022-10-24 13_14_49-DartPad](https://user-images.githubusercontent.com/67521304/197574833-58c15706-9ee6-4172-b575-10d53527dd40.png)
  
### Symbols
  
In Dart, Symbols are basically an object representation of either an identifier or operator.  The symbols in dart are opaque and dynamic string names that cannot be changed and remains constant throughout the compile time.
  
There´s not much information found in Dart Official Documentation: https://api.dart.dev/stable/2.18.3/dart-core/Symbol-class.html, but there´s in geeksforgeeks: https://www.geeksforgeeks.org/dart-symbols/


