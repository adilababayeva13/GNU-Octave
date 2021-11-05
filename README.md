# GNU Octave

-GNU Octave is a script-based computer langugage, primarily aiming at solving algebric and differential equations.

- It has numerous built-in functions and various plotting capabilities.

- It also aallows for developing user-defined functions.

- It is a free software, and highly compatible with Matlab.

### Download Octave or read the documentation:

https://www.gnu.org/software/octave/

## Help & Lookfor & doc

```
 help name
  help --list
 ```

Display the help text for name.

For example, the command help help prints a short message describing the help command.
Given the single argument --list, list all operators, keywords, built-in functions, and loadable functions available in the current session of Octave. 

```
lookfor str
lookfor -all str 
```

Search for the string str in the documentation of all functions in the current function search path.

By default, lookfor looks for str in just the first sentence of the help string for each function found. The entire help text of each function can be searched by using the "-all" argument. All searches are case insensitive. 

```
 doc function_name
 doc
```
Display documentation for the function function_name directly from an online version of the printed manual, using the GNU Info browser.

If invoked without an argument, the manual is shown from the beginning. 