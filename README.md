# Reading Groups

[![Build Status](https://drone.io/github.com/cargokult/ReadingGroups/status.png)](https://drone.io/github.com/cargokult/ReadingGroups/latest)

Reading Groups app helps with discovery and facilitation of (technical) Reading Groups in your company.

## Features
* see tech books
* propose reading groups
* see current reading groups
* see past reading groups

## Todo
* ~~add firebase dependency~~
* ~~follow firebase tutorial~~
* how to organize activities and fragments
* pass json events
* book structure

## Domain
* books
* reading groups
* user profiles
* user books

### Book
* see goodreads api

### User Profile
* name
* avatar

### User Books
* wants to read
* read

### Reading Group
* book
* facilitator
* interval
* participants

### Reading Group state machine
* proposed
* active
* finished

## Context
[app]

## Container
[auth]-----[app]-----[firebase]

## Integration
* firebase
* Goodreads api
* ADS
* emails

## Monitoring
* https://www.parse.com/

## Resources
* https://www.iconfinder.com/icons/185628/book_icon#size=512
* https://www.iconfinder.com/icons/71619/book_moleskine_notes_pure_icon#size=512
