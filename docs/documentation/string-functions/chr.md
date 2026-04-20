# chr

```pcm
chr(number)
```

## Description

Provides the character string from given ASCII code

## Parameters

| Name     | Type   | Optional | Description                                      |
| -------- | ------ | -------- | ------------------------------------------------ |
| `number` | Number | No       | ASCII code from which to derive character string |

## Return Value

_String_ - the character string from given ASCII code `number`

## Notes

- Seems to relate to ANSI codes when getting into extended characters&hellip;
- The inverse of [asc](asc.md)

## See Also

- [asc](asc.md)

## Examples

```pcm
msg = "Rotate by 90" + chr(176)
display(msg) // Rotate by 90°

tab = chr(9)
display("Hello" + tab + "World!") // Hello        World!F
```
