# format

```pcm
format(number)
```

## Parameters

| Name     | Type   | Optional | Description                              |
| -------- | ------ | -------- | ---------------------------------------- |
| `number` | Number | No       | Integer or Double to convert to a string |

## Return Value

_String_ - string representation of given `number`

## Notes

- when `number` is a _Double_, there will be a trailing "d" character in the resultant string

## See Also

- Data Types

## Examples

```pcm
display(format(3.14))    // "3.14d"
display(format(3))       // "3"
display(format(12.3456)) // "12.3456d"
```
