

# system

# dos

# unix

Shell command execution.

## Syntax

- status = system(command)
- status = dos(command)
- status = unix(command)
- [status, output] = system(command)
- [status, output] = dos(command)
- [status, output] = unix(command)
- [status, output] = system(command, '-echo')
- [status, output] = dos(command, '-echo')
- [status, output] = unix(command, '-echo')

## Input argument

 - command - a string: command to execute in command shell.

## Output argument

 - status - an integer value: exit code value of the command.
 - output - a string: output of the command.

## Description


  <p><b>system</b> sends a string to the operating system for execution. Standard output and standard errors of the shell command are written in the calling shell.</p>
  <p><b>[status, output] = system(command, '-echo')</b> forces the output to the Command Window, even though it is also being assigned into a variable.</p>
  <p>Callback functions cannot be called until <b>system</b> command is not finished.</p>
  <p>Nelson will convert characters to the encoding that your operating system shell accepts (ANSI on Windows by default, UTF-8 on others systems).</p>
  <p>command can be interrupted with <b>CTRL-C</b> key, in this case status code returned will be 130 (128 + SIGNINT).</p>


## Examples

```matlab
[s,w] = system('dir');
[s,w] = system('dir','-echo');
```
To detach an system command, include the trailing character, &, in the command argument.
```matlab
[s,w] = system('notepad &');
```

## See also

[winopen](winopen.md).
## History

|Version|Description|
|------|------|
|1.0.0|initial version|


## Author

Allan CORNET



