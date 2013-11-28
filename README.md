Reading Groups
==============

Reading Groups app helps with discovery and facilitation of (technical) Reading Groups in your company.

### Features
* see tech books
* propose reading groups
* see current reading groups
* see past reading groups

### Todo
* ~~add firebase dependency~~
* ~~follow firebase tutorial~~
* how to organize activities and fragments
* pass json events
* book structure

### Domain
* books
* reading groups
* user profiles
* user books

#### Book
* see goodreads api

### User Profile
* name
* avatar

### User Books
* wants to read
* read

#### Reading Group
* book
* facilitator
* interval
* participants

### Reading Group state machine
* proposed
* active
* finished

### Context
[app]

### Container
[auth]-----[app]-----[firebase]

### Integration
* firebase
* Goodreads api
* ADS
* emails

### Monitoring
* tbd
