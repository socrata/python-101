# The Basics #

Python tends to mostly be used for short programs that are called
"scripts".

Scripts are just a series of commands to be executed by the computer.


Unlike inside of IDLE, if you write a script like:
```python
x = 9
x * x
```

It won't print anything, it will just spend the time to do the computation.

Note that the commands in the file don't start with `>>>`.  If you
copy and paste code from IDLE you will need to remove those leading
`>` s.


To print things you need to use the `print` command.

For example:
```python
x = 9
print(x * x)
```

Will print `81` out, even if you save it to a file.


Now try creating a script yourself.

From inside of IDLE do "File > New File" then write and save your
program (feel free to copy and paste from above).


After saving the file, you can run it by going to "Run > Run Module"
or by pressing F5 (with the default MacOS settings, this will require
pressing fn + F5).


## Comments ##

Comments are notes to yourself, or other programmers, they're ignored
by the computer.

Comments start with a `#` and continue to the end of the line they're
on.

```python
# Comments can start at the beginning of the line.
print(2015) # Or anywhere in the middle of it.
```


## Strings ##

Strings are a series of characters (letters, numbers, etc) that are
surrounded by quotation marks.

The following are all strings:
```python
"42" # Not the number 42, but the string "42".
"foo"
"bar"
"Hello"
"Python"
"..."
```
