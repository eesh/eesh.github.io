---
title: Chord - A Class Management Android application [WIP]
github: https://github.com/eesh/Chord-Node
logo: nodejs-default.png
short_desc: Users/Professors create a group for a class which generates a unique code. Students of the class can use this unique code to access the class group in the application. Class group can be used for communication, assignments, and material distribution.
---

### Purpose

At SRM University, communication between professors and students is usually done via a common WhatsApp group or Email. Students tend to personally meet, text or call the professors for any questions. Collection of assignments is usually done physically or via email. In the beginning of a class every semester, the professors or students volunteer to create a common group on WhatsApp. Since WhatsApp is based off a phone number system, many students may be unwilling to share their personal number with other unknown students.

Chord is a solution that addresses these problems. A professor simply creates a group within the application and shares the unique code and passphrase shown upon group creation with the students of the class. The students use these details to register themselves to the class. Using chord, professors can post announcements and set assignment deadlines. The professors can also distribute any class related materials through the application. Students can use this application to submit assignments and ask questions. To promote active discussion, students can choose to be anonymous to other students.

### Features

* Create and manage class groups

* Sign up to classes using the unique code and passphrase

* Share class materials

* Set assignment deadlines

* Submit assignments

* Ask questions or discuss anonymously

### Libraries

* Firebase for on demand communication

* Express framework for API development

* Amazon S3 for file storage

* bcrypt for hashing passwords

* mongoose for mongodb

* body-parser to parse request body
