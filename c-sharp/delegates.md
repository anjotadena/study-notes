# Delegates
- Serve as the foundation for callback in .NET. They are reference types that hold references to methods with compatible signatures.
- Allow us to pass methods as arguments to other methods, thereby enabling to to achieve dynamic invocation.

## Func
- takes up to 16 input parameters and returns a value
`c#
Func<int, int, int> multiply = (a, b) => a * b;
int product = multiply(4, 6); // false
`

## Action
- Takes one or more input parameters but doesnt return anything
`c#
Action<int, int> add = (a, b) => Console.WriteLine(a + b);
add(3, 5); // Outputs: 8
`

## Predicate
- Used to represents a method that takes an input parameter and returns a Boolean value indicating whether the input satisfies a certain condition.
`C#
Predicate<string> isLong = s => s.Length > 5;
bool result = isLong("Hello, World!"); // false
`

