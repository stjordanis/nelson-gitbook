



isstruct


isstruct

Return true if variable var is a structure.

## Syntax

- res = isstruct(var)

## Input argument

 - var - a variable

## Output argument

 - res - a logical: true or false

## Description

<b>isstruct</b> returns a logical 1 if the argument is a struct (structure) and a logical 0 otherwise.

## Examples

```Nelson
A = 1;
res = isstruct(A)
```
```Nelson
B = struct();
res = isstruct(B)
```
```Nelson
C.a = 1;
C.B = 'hello';
res = isstruct(C)
```

## See also

isa.md isa, struct.html struct.
## History

|Version|Description|
|------|------|
|1.0.0|initial version|


## Author

Allan CORNET


