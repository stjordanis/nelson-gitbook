



issingle


issingle

Return true if variable var is a single matrix.

## Syntax

- res = issingle(var)

## Input argument

 - var - a variable

## Output argument

 - res - a logical: true or false

## Description

<b>issingle</b> returns a logical 1 if the argument is a single matrix and a logical 0 otherwise.

## Examples

```Nelson
A = 3.6;
res = issingle(A)
```
```Nelson
B = single([1 ; 3]);
res = issingle(B)
```

## See also

isdouble.md isdouble, single.md single.
## History

|Version|Description|
|------|------|
|1.0.0|initial version|


## Author

Allan CORNET


