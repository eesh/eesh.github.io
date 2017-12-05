---
title: SRM Venue Management - NodeJS backend
github: https://github.com/eesh/SRM-Venue-Management
logo: nodejs-default.png
short_desc: NodeJS + Express backend of the SRM Venue Management System.
---

### Technologies/Libraries

* NodeJS

* Mongoose client for MongoDB

* Whirlpool for hashing

* Express for REST API framework

* body-parser to parse the request body

### Purpose

Throughout the year, a lot of events are organised at SRM University. These events are conducted at different venues within the university. These venues have to be reserved by event organizers well in advance to ensure the venue’s availability and to avoid any future conflicts. The reservation of venues at SRM University is done by hand and the reservation records are still physically maintained by the people that are in-charge of different venues. In case of unavailability of a venue, the event organizers must call different venue administrators to find out if the venues are available. This is a tedious and time taking task. Sometimes there may be changes in reservations. A low priority reservation may have to be replaced with a higher priority one or the venue may not be open on the day of reservation. In such cases, communication between involved parties can be difficult. Confirmation of reservation may require constant follow ups by the event organizers.

In order to solve this issue, we create a web server  that can store and manage reservation records. A mobile application acts as an interface between the users and the web server. The users use the mobile application to see a list of available venues in the University campus. They can also see if there are any existing reservations for their required venues. An administrator can confirm or deny reservations. This reduces the number of personnel required to manage venue reservation as only an administrator is required. The system also lists reservations with conflicting times to make it easy for the administrator to confirm or deny reservations. Communication issues are also solved by using notification services that send notifications via Email and Firebase Cloud Messaging in real-time so the users need not follow up with phone calls. Reason for changes are also listed in the notifications.

The key advantage of using this system over other existing systems is its ability to learn over time. We make use of a supervised learning algorithm in order to teach the system what kind of reservations are usually confirmed and what reservations are not. By doing so, the system will be able to help the administration take decisions and function autonomously.
