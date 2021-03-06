

# all

all of the elements of a matrix satisfy some condition.

## Syntax

- R = all(M)
- R = all(M, dim)

## Input argument

 - M - a matrix.
 - dim - a integer value: dimension along it works.

## Output argument

 - R - a logical matrix.

## Description


  <p><b>all</b> returns true if all of the elements of a matrix satisfy some condition.</p>


## Example

```matlab
all([33, 22; 11, 0])
all([33, 22; 11, 0], 2)
```

## See also

[any](any.md).
## History

|Version|Description|
|------|------|
|1.0.0|initial version|


## Author

Allan CORNET



