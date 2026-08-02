# Assignment Operators in C#

## Definition

Assignment operators are used to assign a value to a variable or update the value of a variable.

## Why do we use Assignment Operators?

Assignment operators make the code shorter and easier to read.

Example:

Instead of writing:

```csharp
a = a + 5;
```

We can write:

```csharp
a += 5;
```

Both statements do the same work.

## Assignment Operators

| Operator | Meaning |
|----------|---------|
| = | Assign a value |
| += | Add and assign |
| -= | Subtract and assign |
| *= | Multiply and assign |
| /= | Divide and assign |
| %= | Modulus and assign |

## Example

`a += 5` means:

```csharp
a = a + 5;
```

`a -= 3` means:

```csharp
a = a - 3;
```

`a *= 2` means:

```csharp
a = a * 2;
```

`a /= 4` means:

```csharp
a = a / 4;
```

`a %= 2` means:

```csharp
a = a % 2;
```

## Key Points

- Assignment operators assign or update values.
- They are shortcut operators.
- They make code clean and easy to read.
