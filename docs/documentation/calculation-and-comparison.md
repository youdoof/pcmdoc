# Calculation &amp; Comparison Operators

## Arithmetic

| Operator | Result         |
| :------- | :------------- |
| `+`      | Addition       |
| `-`      | Subtraction    |
| `*`      | Multiplication |
| `/`      | Division       |
| `**`     | Exponential    |

### Arithmetic Examples

```pcm
foo = 2
bar = 5

// Addition -- of numbers AND concatenation of strings
display(foo + bar) // 7
display("Hello" + "Goodbye") // HelloGoodbye

// Subtraction
display(foo - bar) // -3

// Multiplication
display(foo * bar) // 10

// Division
display(foo / bar) // 0.400000

// Exponential
display(foo ** bar) // 2^5, which is 32
```

## Boolean Comparison

| Operator | Result                   |
| :------- | :----------------------- |
| `<`      | Less Than                |
| `>`      | Greater Than             |
| `<>`     | Not Equal To             |
| `==`     | Equal To                 |
| `>=`     | Greater Than or Equal To |
| `<=`     | Less Than or Equal To    |

### Notes

* All return the `Boolean` values (`#!pcm true` or `#!pcm false`)
* Can compare `Numbers` and `Strings`
  * Can compare `Booleans` with Equal To (`==`) or Not Equal To (`<>`)

### Boolean Comparison Examples

```pcm
foo = 2
bar = 5

// Number Examples
display(foo < bar) // true
display(foo > bar) // false
display(foo <> foo) // false
display(foo == foo) // true
display(bar >= foo) // true
display(bar <= bar) // true

// String Examples
display("foobar" == "baz") // false
display("foobar" <> "") // true

// Numbers & Strings do not combine, be careful
display(0 == "0") // false
display("0" == 0) // false
```
