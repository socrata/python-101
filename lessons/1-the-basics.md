# The Basics #

Python tends to mostly be used for short programs that are called
"scripts".

Scripts are just a series of commands to be executed by the computer.


## The Shell ##

IDLE starts up what's called a "shell" or "interpreter".

A shell is just a prompt that you can type commands into, that will
print the results automatically.


Unlike inside the IDLE shell, if you write a script like:
```python
x = 9
x * x
```

It won't print anything, it will just spend the time to do the computation.

Note that the commands in the file don't start with `>>>`.  If you
copy and paste code from the IDLE shell you will need to remove those
leading `>` s.


To print things you need to use the `print` command.

For example:
```python
x = 9
print(x * x)
```

Will print `81` out, even if you save it to a file and run it.


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
surrounded by (single or double) quotation marks.

The following are all strings:
```python
"42" # Not the number 42, but the string "42".
"foo"
'bar' # Also a string, 
"Hello"
"Python"
"..."
```


Generally a program that prints the string "Hello, World!" is
the traditional first program you write a language.

(Some variation of this goes back to at least 1974.)


## Hello, World!##

```python
print("Hello, World!")
```

Now try creating a "hello world" script yourself.

From inside of IDLE do "File > New File" then write and your "hello
world" program (feel free to copy from above).


When you save your program, create a folder to keep all of your
scripts for this class.

It can be wherever you want, but I suggest
creating a "python-101" folder inside of "Documents".

Save your program as "hello.py".


After saving the file, you can run it by going to "Run > Run Module"
or by pressing F5 (with the default MacOS settings, this will require
pressing fn + F5).


Congratulations, you've just written your first program!


So now you can use Python like a pocket calculator, and can print out
text, instead of writing it inside of a text file.

How about we play with something a bit more useful.


## Combining Strings ##

Combining strings is called "concatenation".

To concatenate two strings just use the `+` operator.

```python
>>> "open" + 'data'
'opendata'
>>> 'so' + 'crata'
'socrata'
>>> "Good " + "morning" + "!" # Note the space after "Good".
```



If you want to combine a string with a number you get an error.

```python
>>> "the answer is: " + 6 * 7
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
TypeError: Can't convert 'int' object to str implicitly
```

So, how do we do this?

First we need another tool.

We need to use a function.


## What are Functions? ##

Functions are pre-defined pieces of code that you can run on different
arguments (basically, placeholders in the code).

They're pretty much the same as the functions you learned in math class
(log, sin, tan, etc), except they don't always return a value.


## Calling Functions ##

We've actually already seen one function, the `print` function.

We call `print` with a string as its argument (inside of its
parenthesis), and it, well, prints it out.

```python
>>> print("I am an argument!")
I am an argument!
```


## Converting Numbers to Strings ##

To make a number into a string call the `str` function.

Using this we can now display a string with dynamic information.

```python
>>> str(6 * 7)
'42'
>>> "The answer is: " + str(6 * 7)
'The answer is: 42'
```


## Try it Yourself ##

Write a script of your own that prints out a string using dynamic
information.

Save it as "answer.py" before running it.


## Multiple Arguments ##

Some functions can actually take multiple arguments.  Again, `print`
turns out to be an example.  It prints its arguments separated
by spaces.

```
>>> print("One and one and one is", 1 + 1 + 1)
One and one and one is 3
```

Arguments are separated by a comma.


## What's in it for me? ##

This course is a work in progress, and I'd like to give you the tools
to solve problems you have in your daily life.

Give any examples of problems you'd like to solve, either here, or in
the `#python-101` channel
