---
title: Flask server to generate AR Hamming Codes
github: https://github.com/eesh/HammingGeneratorServer
logo: python-default.png
short_desc: Python Flask server to generate AR Hamming codes for the Poppy Ergo Jr. extension
---

### Libraries

* <a href="http://flask.pocoo.org/">Flask framework for python</a>

* <a href="https://pypi.python.org/pypi/hampy/1.4.1">Hampy Hamming code generator</a>

### Purpose

Poppy Ergo Jr. is an open-source robot kit developed by the Flowers lab at Inria, France (<a href="https://www.poppy-project.org">https://www.poppy-project.org"</a> and <a href="https://www.poppy-education.org">https://www.poppy-project.org"</a>, CC-BY-SA). It can be controlled using a Snap extension or a Scratch extension. The Scratch extension was developed by LifeLong Kindergarten group at MIT Media Labs.

The robot currently has a feature to detect AR hamming codes. Unfortunately, the feature is currently hard-coded to detect only 3 unique codes in the official library. During the development of the Scratch extension, we modified the source to support the detection of any code. At the time, there was no user-friendly way to generate these AR codes.

This flask server simply shows a webpage where the user has to provide a number/code as an input and the server returns an image of the AR code as the output. This image can be locally saved or printed so it can be used with the robot.

### Instructions

_Note:
You need python to run this server._

<br />

First, open terminal or command prompt and change the directory to the root of this project.

Then, run the following command:

``` bash
python HammingGenerator.py
```

<br />
then simply go to <a href="http://127.0.0.1:5000/generate">http://127.0.0.1:5000/generate</a> from the internet browser.
