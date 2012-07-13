# Project Description

This code lets your computer monitor lego blocks on a base plate using a webcam. It will interpret the positions of the blocks and translate it into OSC (Open Sound Control) messages. The end result is something like this:

See http://vimeo.com/45026119

*TODO*: Add description of dimensions of the base plate, what to change
if your base plate is of a different size

# Preparation

## install python dependencies

sudo apt-get install python-pypm python-liblo python-opencv

*TODO* (Separate instructions for Windows?)

## initialization

Point your webcam at the lego base plate. Make sure there is enough light and that it's neatly positioned.

Now, you need to generate a file which tells the webcam where the base plate is:

python initialize.py

This should bring up a windows displaying the webcam's picture. Using your mouse,
click the four corners of the base plate (up-left, up-right, down-right, down-left)

*TODO* does the order of clicking the corners matter?

# Set up a program capable of receiving OSC messages

*TODO* list programs which are capable of doing this, preferably with
instructions for at least one such program.

## Give it a try

Run 'python step.py', and change the pattern by moving 2x2 blocks on the base plate

