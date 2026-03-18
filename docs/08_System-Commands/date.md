# date

```pcm
date()
date(number)
```

## Description

Provides a text based date based on input given.

> Since Calypso X.Y

## Parameters

| Name     | Type    | Optional | Description                                          |
| -------- | ------- | -------- | ---------------------------------------------------- |
| `number` | Integer | Yes      | Only accepts the following values: `0`, `1`, and `2` |

## Return Value

Depending on the number passed to the function, will get the following _String_ returned:

| Value                  | Result                   | Example           |
| ---------------------- | ------------------------ | ----------------- |
| `0` (Default if empty) | Full text date           | `January 1, 2026` |
| `1`                    | ISO Standard Date Format | `2026-01-01`      |
| `2`                    | Filename safe output     | `2026_01_01`      |

## Notes

* notes

## See Also

* [dateAndTime](#)
* [time](#)

## Examples

```pcm
example
```

> **Deprecated** since Calypso deprecated.since  
> deprecated.message
