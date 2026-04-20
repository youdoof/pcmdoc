# cr

```pcm
cr()
```

## Return Value

_String_ - carriage return, new line

## Notes

- A reliable way to get the correct carriage return &amp; new line characters without using [`chr`](chr.md), particularly for Windows

## Examples

```pcm
display("First Line", cr(), "Second Line")
// First Line
// Second Line
```
