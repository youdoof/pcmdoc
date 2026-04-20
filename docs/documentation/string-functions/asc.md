# asc

```pcm
asc(character)
```

## Description

Provides the ASCII code from given character string

## Parameters

| Name        | Type   | Optional | Description                                      |
| ----------- | ------ | -------- | ------------------------------------------------ |
| `character` | String | No       | Character string from which to derive ASCII code |

## Return Value

_Number_ - the ANSI/ASCII integer value of `character`

## Notes

- Seems to relate to ANSI codes when getting into extended characters&hellip;
- The inverse of [chr](chr.md)

## See Also

- [chr](chr.md)

## Examples

```pcm
asc("°") // 176
```
