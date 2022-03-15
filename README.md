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



