---
title: Scratch eXtension for Poppy Ergo Jr. Robot
github: https://eesh.github.io/scratch-test/
logo: scratchx-default.png
short_desc: This Scratch extension lets you control and record the movement of the Poppy Ergo Jr. robot and also capture images from the robots camera.
---

### Features

* Control the movement

* Record the movement

* Play recorded movements

* Capture images

* Recognize any AR hamming code

### Libraries

* <a href="https://github.com/nodeca/pica">Pica</a> for image manipulation

* <a href="http://cs.stanford.edu/people/karpathy/convnetjs/">ConvnetJS for digit recognition</a>

### Purpose

Poppy Ergo Jr. is an open-source robot kit developed by the Flowers lab at Inria, France (<a href="https://www.poppy-project.org">https://www.poppy-project.org"</a> and <a href="https://www.poppy-education.org">https://www.poppy-project.org"</a>, CC-BY-SA). It is a low cost arm designed for education, easy to build and modify. The robot was originally designed to be programmed with Snap, a variant of Scratch that allows creation of custom blocks.

With the release of Scratch 2.0, anyone can create custom Scratch extensions that introduce new blocks and features to the Scratch environment. Since Scratch extensions are developed in JavaScript, a lot of other JavaScript based libraries could be used to develop additional features.

This extension allows the robot to recognize digits that are shown to it. It also allows the robot to capture images which can be used with image recognition services to identify the context. The extension also extends the AR hamming code recognition ability of the robot to recognize _any_ AR hamming code unlike it's counterpart which can only recognize 3 unique codes.
