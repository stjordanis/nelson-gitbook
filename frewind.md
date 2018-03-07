



frewind


frewind

Set position of stream to the beginning.

## Syntax

- frewind(fid)

## Input argument

 - fid - an integer value: file descriptor

## Description


  <p><b>frewind</b> puts the pointer at the beginning of file</p>


## Example

```Nelson
fileID = fopen([tempdir(), '/frewind.txt'],'wt');
fprintf(fileID, 'son is beautiful.');
frewind(fileID);
fprintf(fileID, 'sun');
fclose(fileID);
R = fileread([tempdir(), '/frewind.txt'])
```

## See also

fclose.md fclose.
## History

|Version|Description|
|------|------|
|1.0.0|initial version|


## Author

Allan CORNET


