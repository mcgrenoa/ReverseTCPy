## ReverseTCPy
**ReverseTCPy** is a Python 3 based reverse TCP tool.

## Motivation
I started this project for three main reasons:
1. To learn to program using Python.
2. Create a way to gain a shell without being detected by Defender on Win10.
3. Stop being such a script kiddy and learn something new.

## Build status
[![Build Status](https://travis-ci.org/mcgrenoa/python-reverse-tcp.svg?branch=master)](https://travis-ci.org/mcgrenoa/python-reverse-tcp)

## Installation & Usage
Listener:
If you need to change the port or host IP, then open it with a text editor.

*`git clone https://github.com/mcgrenoa/python-reverse-tcp`
*`cd ReverseTCPy`
*`python3 listener.py`

Client:
If you need to change the port or host IP, then open it with a text editor. 

**If you want to run the client on Windows without install Python, you can use pyinstaller. Make sure you have any options set correctly!**
Pyinstaller can be found [here](https://www.pyinstaller.org/).

To package the client with pyinstaller:

*`pyinstaller -D -w path/to/file/`

If you want to run the client **using** python:

*`python3 client.py`

## Credits
Thanks to Bucky for giving me someplace to get started with this project. [Bucky's Youtube](https://www.youtube.com/user/thenewboston)
Thanks to port443 on reddit for helping me fix a lot of my code. [port443's Reddit](https://www.reddit.com/user/port443)
