# C# Symbols

## Bitwise OR (|) vs Logical OR (||)

In C#, the "|" and "||" symbols are used as bitwise OR and logical OR operators, respectively.

1. ```Bitwise OR (|)```:

The ```|``` symbol is a bitwise OR operator, which performs a bitwise OR operation between the individual bits of two operands.

Example:

```csharp
int a = 5;  // Binary representation: 0101
int b = 3;  // Binary representation: 0011

int result = a | b;  // Binary result: 0111 (7 in decimal)
```

2. ```Logical OR (||)```:

The ```||``` symbol is a logical OR operator, which is used to perform a logical OR operation between two boolean expressions. It returns true if at least one of the expressions is true.

Example:

```csharp
bool condition1 = true;
bool condition2 = false;

bool result = condition1 || condition2;  // Result: true
```

In summary, ```|``` is a bitwise OR operator that operates on individual bits, while ```||``` is a logical OR operator that works on boolean values.

## Null-coalescing Operator (??)

In C#, the ```"??"```, known as the null-coalescing operator, is used to provide a default value for a nullable type or expression. It is a shorthand way to check if a value is null and, if so, provide an alternative default value.

The syntax is as follows:

```csharp
result = expression1 ?? expression2;
```

Here's how it works:

If ```expression1``` is non-null, the result is ```expression1```.
If ```expression1``` is null, the result is ```expression2```.

Here's an example:

```csharp
int? nullableNumber = null;
int result = nullableNumber ?? 42;

Console.WriteLine(result); // Output: 42
```

In this example, if ```nullableNumber``` is null, the value of 42 will be assigned to the ```result``` variable. If ```nullableNumber``` is non-null, its value will be assigned to result. The null-coalescing operator is a concise way to handle null checks and provide default values.

