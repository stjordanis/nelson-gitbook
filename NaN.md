



NaN


NaN

Creates an Not-a-Number

## Syntax

- NaN
- nan
- NaN(n)
- NaN(n, m)

## Input argument

 - n - a variable: n-by-n matrix
 - m - a variable: n-by-m matrix

## Description


  <p><b>NaN</b> returns the IEEE symbol NaN (Not a Number).</p>
  <p><b>NaN</b> is the result of operations which do not produce a well defined numerical result.</p>
  <p>Beware, you must never compare <b>NaN</b> with <b>NaN</b>, in this case, please use <b>isnan</b>.</p>


## Examples

```Nelson
NaN
```
```Nelson
3 + NaN
```
```Nelson
NaN != NaN
isnan(NaN)
```

## See also

isnan.html isnan.
## History

|Version|Description|
|------|------|
|1.0.0|initial version|


## Author

Allan CORNET


