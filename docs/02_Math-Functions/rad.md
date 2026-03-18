# rad

```pcm
rad(number)
```

## Description

Converts a given number from degrees to radians.

> Since Calypso X.Y

## Parameters

| Name     | Type            | Optional | Description                               |
| -------- | --------------- | -------- | ----------------------------------------- |
| `number` | Integer, Double | No       | number to convert from degrees to radians |

## Return Value

_Integer, Double_ - radian equivalent of the given value from degrees

## See Also

* [deg](deg.md)

## Examples

```pcm
val = 60
display(rad(val))

// 1.047198
```
