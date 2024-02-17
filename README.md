# C# Symbols

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

