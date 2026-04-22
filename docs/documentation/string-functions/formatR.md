# formatR

```pcm
formatR(number)
formatR(number, totalCharacters, decimalPlaces)
```

## Parameters

| Name            | Type   | Optional | Description                                                    |
| --------------- | ------ | -------- | -------------------------------------------------------------- |
| number          | Number | No       | The number to be converted to right-justified string           |
| totalCharacters | Number | Yes      | Total number of characters of the final right-justified string |
| decimalPlaces   | Number | Yes      | Total number of decimal places to display                      |

## Return Value

_String_ - **rounded**, right-justified string of the given `number`

## Notes

- if `totalCharacters` and `decimalPlaces` are not provided, default is 4 decimal places
- the decimal point `.` is not considered for `totalCharacters`

## See Also

- [format](format.md)
- [formatL](formatL.md)

## Examples

```pcm
foo = 1.234567

display(formatR(foo))           // "1.2346
display(formatR(foo, 10, 2))    // "       1.23"
display(formatR(foo, 6, 6))     // "1.234567"
```
