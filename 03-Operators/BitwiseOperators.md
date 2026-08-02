# Bitwise Operators in C#

## Definition

Bitwise operators are used to perform operations on individual bits (0 and 1) of numbers.

## Why do we use Bitwise Operators?

Bitwise operators are used when we need to work directly with binary values. They are mostly used in low-level programming and memory operations.

## Binary Representation

Computers store numbers in binary form.

Example:

```
5 = 0101
3 = 0011
```

---

# Bitwise Operators

| Operator | Name | Description |
|----------|------|-------------|
| & | Bitwise AND | Both bits must be 1 |
| | | Bitwise OR | Any one bit is 1 |
| ^ | Bitwise XOR | Different bits give 1 |
| ~ | Bitwise NOT | Reverses bits |
| << | Left Shift | Moves bits left |
| >> | Right Shift | Moves bits right |

---

# 1. Bitwise AND (&)

### Rule:
Both bits must be 1 to get result 1.

Example:

```
5 = 0101
3 = 0011

  0101
& 0011
------
  0001
```

Result:

```
5 & 3 = 1
```

---

# 2. Bitwise OR (|)

### Rule:
If any one bit is 1, result is 1.

Example:

```
5 = 0101
3 = 0011

  0101
| 0011
------
  0111
```

Result:

```
5 | 3 = 7
```

---

# 3. Bitwise XOR (^)

### Rule:
If bits are different, result is 1.

Example:

```
5 = 0101
3 = 0011

  0101
^ 0011
------
  0110
```

Result:

```
5 ^ 3 = 6
```

---

# 4. Bitwise NOT (~)

### Rule:
NOT reverses bits.

Example:

```
5 = 0101

~0101
```

0 becomes 1 and 1 becomes 0.

---

# 5. Left Shift (<<)

### Rule:
Bits move to the left and zeros are added on the right.

Example:

```
5 = 0101

5 << 1

0101 → 1010
```

Result:

```
5 << 1 = 10
```

---

# 6. Right Shift (>>)

### Rule:
Bits move to the right.

Example:

```
10 = 1010

10 >> 1

1010 → 0101
```

Result:

```
10 >> 1 = 5
```

---

# Key Points

- Bitwise operators work on binary values.
- They operate on individual bits.
- They are different from logical operators.
- They are used in low-level programming.
