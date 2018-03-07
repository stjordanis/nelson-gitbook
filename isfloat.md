



isfloat


isfloat

Return true if variable var is a single or double matrix.

## Syntax

- res = isfloat(var)

## Input argument

 - var - a variable

## Output argument

 - res - a logical: true or false

## Description

<b>isfloat</b> returns a logical 1 if the argument is a single or double matrix and a logical 0 otherwise.

## Examples

```Nelson
A = 3;
res = isfloat(A)
```
```Nelson
A = single(3);
res = isfloat(A)
```

## See also

isa.md isa, single.html single, isdouble.md isdouble.
## History

|Version|Description|
|------|------|
|1.0.0|initial version|


## Author

Allan CORNET


