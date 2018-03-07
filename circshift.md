



circshift


circshift

Circular shift

## Syntax

- R = circshift(M, N)
- R = circshift(M, N, DIM)

## Input argument

 - M - a variable
 - N - shift
 - DIM - dimension to operate

## Output argument

 - R - result of 'circshift'.

## Description


  <p><b>circshift</b> computes circular shift.</p>


## Example

```Nelson
x = [10, 20, 30; 40, 50, 60; 70, 80, 90];
circshift (x, 1
circshift (x, -2))
```

## See also

repmat.md repmat, reshape.md reshape.
## History

|Version|Description|
|------|------|
|1.0.0|initial version|


## Author

Allan CORNET


