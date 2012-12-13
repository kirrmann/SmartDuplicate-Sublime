SmartDuplicate
======================

SmartDuplicate is a Sublime Text 2 plugin that allows duplicating lines while changing certain keywords.


Note
----

This is very early in development therefore there is a very limited amount of keywords. Also this is my first contact
with Python. I am pretty sure I did not do it in the most efficient or _pythony_ way possible.


Shortcut
--------

**[CTRL+d]** duplicates line using smart duplicate

_Note: I am aware I am overwriting a default keyboard shurtcut - but I found this very convinient and logical._


Supported keywords
------------------

* width <=> height (case insensetive)
* .x <=> .y
* .[word]X <=> .[word]Y  (any word ending in a capital X or Y)

__Once again: work in progress. Constantly expanding and fine tuning the keywords__


Motivation
----------

I'm a front-end developer. It's been too many times that I duplicate a line and then go through and change all the
`.height` to `.width`. In the manner of __automate all the things__ I thought I write a little plugin for the editor
of my choice.

Let me know what you think. No _you suck_-emails please.