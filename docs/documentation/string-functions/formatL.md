# formatL

```pcm
formatL(number)
formatL(number, totalCharacters, decimalPlaces)
```

## Parameters

| Name            | Type   | Optional | Description                                                   |
| --------------- | ------ | -------- | ------------------------------------------------------------- |
| number          | Number | No       | The number to be converted to left-justified string           |
| totalCharacters | Number | Yes      | Total number of characters of the final left-justified string |
| decimalPlaces   | Number | Yes      | Total number of decimal places to display                     |

## Return Value

_String_ - **rounded**, left-justified string of the given `number`

## Notes

- if `totalCharacters` and `decimalPlaces` are not provided, default is 4 decimal places
- the decimal point `.` is not considered for `totalCharacters`

## See Also

- [format](format.md)
- [formatR](formatR.md)

## Examples

```pcm
foo = 1.234567

display(formatL(foo))           // "1.2346
display(formatL(foo, 10, 2))    // "       1.23"
display(formatL(foo, 6, 6))     // "1.234567"
```
