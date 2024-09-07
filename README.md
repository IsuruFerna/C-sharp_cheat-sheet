# C# cheat sheet

## How to print a string

`Console.WriteLine("Hello World!");`

`Console.Write("Congratulations!");`

`Console.Write(" ");`

`Console.Write("You wrote ypur first lines of code.");`

## Use integer literals
`Console.WriteLine(123);`

## Use floating-point literals

`Float Type    Precision
----------------------------
float         ~6-9 digits
double        ~15-17 digits
decimal        28-29 digits`

To create a float literal, append the letter F after the number. In this context, the F is called a literal suffix. The literal suffix tells the compiler you wish to work with a value of float type. You can use either a lower-case f or upper-case F as the literal suffix for a float.

Notice that the float data type is the least precise, so it's best to use this data type for fixed fractional values to avoid unexpected computation errors.

`Console.WriteLine(0.25F);`

To create a double literal, just enter a decimal number. The compiler defaults to a double literal when a decimal number is entered without a literal suffix.

`Console.WriteLine(2.625);`

To create a decimal literal, append the letter m after the number. In this context, the m is called a literal suffix. The literal suffix tells the compiler you wish to work with a value of decimal type. You can use either a lower-case m or upper-case M as the literal suffix for a decimal.

`Console.WriteLine(12.39816m);`

## Use Boolean literals
`Console.WriteLine("true");`

`Console.WriteLine(true);`

## Variable name examples

`char userOption;`

`int gameScore;`

`decimal particlesPerMillion;`

`bool processedCustomer;`


The `var` keyword tells the compiler to infer the data type of the variable based on the value it is initialized to.
You'll likely see the var keyword as you read other people's code; however, you should use the data type when possible.

## Character escape sequences

An escape character sequence is an instruction to the runtime to insert a special character that will affect the output of your string. In C#, the escape character sequence begins with a backslash \ followed by the character you're escaping. For example, the \n sequence will add a new line, and a \t sequence will add a tab.

`Console.WriteLine("Hello\nWorld!");`

`Console.WriteLine("Hello\tWorld!");`

![image](https://github.com/user-attachments/assets/18371438-59c7-45b5-8c97-a5fcdcd9e3af)
![image](https://github.com/user-attachments/assets/74249812-b877-4fbf-bbc7-e398d2694d9e)
![image](https://github.com/user-attachments/assets/3514a5c9-609e-48d1-8673-a41971dc5236)

![image](https://github.com/user-attachments/assets/9052d09c-e1ea-48c1-ac1e-ac3a83dcfcc4)

### Start c# project in vs code
![image](https://github.com/user-attachments/assets/79a5e1dd-f9a5-4ced-9fc4-5fd74b26b9c4)

once you changed the code you have to build the project before running

![image](https://github.com/user-attachments/assets/aab13d97-4ca1-4fe3-9e51-836c99aa2838)

run the code

![image](https://github.com/user-attachments/assets/fe802ec8-9872-4aa3-bdf4-79bddb25d6af)





