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
