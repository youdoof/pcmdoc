# deg

```pcm
deg(number)
```

## Description

Converts a given number from radians to degrees.

> Since Calypso X.Y

## Parameters

| Name     | Type            | Optional | Description                               |
| -------- | --------------- | -------- | ----------------------------------------- |
| `number` | Integer, Double | No       | number to convert from radians to degrees |

## Return Value

_Integer, Double_ - degree equivalent of the given value from radians

## See Also

* [rad](rad.md)

## Examples

```pcm
val = 1.04719755
display(deg(val))

// 60.0000
```
