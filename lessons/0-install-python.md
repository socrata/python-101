# Lesson 0 #

A sort of pre-lession, just to get Python installed, and the
environment set up.


## Download + Install Python ##


### 1. Install Active-Tcl 8.5 ###

Visit the
[ActiveTcl Download Page](http://www.activestate.com/activetcl/downloads)
and download the "Mac Disk Image (DMG)" from the "8.5.18.0" row.

**Don't click the big button, it's the wrong version.**


After the `.dmg` file has downloaded, run the installer, all of the
default options are fine for what we're doing.

If you get an error complaining that the installer is from an
"unidentified developer", right click on the file and choose "Open".

It will then ask if you're sure, because security.


### 2. Install Python 3.4 ###

Visit the [Python Download Page](https://www.python.org/downloads/)
and click the yellow button that says "Download Python 3.4.3" at the top of the page.

Once the `.pkg` file has downloaded, run the installer, and again all
of the default options are fine for what we're doing.


## Running Python ##

To start an interactive Python session, run the program called "IDLE"
from the Launchpad.


You may want to change your font settings, as the default text is
*tiny*.

To do that click on the "IDLE" menu and select "Preferences...", then
under the "Fonts/Tabs" settings you should be able to increase the
font size.  

Unless you have much better eyesight than I do, you'll
probably want to bump it up to at least 12 point.


The default font of "Courier" is fine, if you want to change it,
because this is code, you will want a mono-spaced (typewriter style)
font, so that all of your code lines up evenly.


### Do Some Math ###
Try some things.  

Some simple stuff you can do is basic math.


In Python, most mathematical operators work the way you learned in
school.

```python
>>> 1 + 1 + 1
3
>>> 2 * 2
4
>>> 5 / 2
2.5
>>> 6 * 5 + 20 - 1
49
>>> 6 * -2.5
-15
```


You can also assign things to variables, if you want to do more
complicated math.


This will create a variable named `x` and store the value `3` in it.

```python
>>> x = 3
>>> x
```

You can think of variables like boxes that hold values inside of them.


You can also give variables new values.

```python
>>> x = 6 * 7
>>> x
6
>>> x * x
1764
>>> x = 9
>>> x
9
>>> x * x
81
```


## Slack ##

Make sure to join the Slack channel `#python-101`, if you want to post
links or ask questions some time other than lectures/office hours.

I'll do my best to follow the channel during working hours.


Next time we'll cover doing things that are more fun than simple arithmetic.
