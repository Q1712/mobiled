# mobiled
Mobile daemon and utilities to manage phone-, gps-, sync- a.s.o. functionality on free mobile devices like the GTA04, Pyra and Neo900.

# Goals
This project is still in the very very early development stage, and even the goals are still subject to change.

## daemon
A deamon communicating via /dev with the hardware, on demand as well as listening for events (e.g. incoming calls) on one side. then on the other side providing an unified interface.

### a simple configuration file to specify the command the daemon executes according to events
Should be as simple as an event name followed by anything to be run by /bin/sh -c
might get a little more complex as some events might have additional data that needs to be passed to the command-line (e.g. phone number on incoming calls).

### an eventlog
To be written to a human readable (well, nerd-readable) file, and kept in a computer readable format to be exportable/searchable
both have to be easily configurable, and even possible to turn off for privacy reasons.

### a contact repository
So that events can be associated with a person or a company (e.g. display a name instead of a number for an incoming call)
and so that it can be synced with other devices or just other programs (e.g. importing contacts from thunderbird, exporting contacts to pidgin, a.s.o.)

## utils

### mobilectr
A command-line interface to perform all actions the deamon is capable of

### X utils
Various utils for X, including:

- A status-icon dockable application.
- A dialling pad
- Contact browser
- Contact editor
- Event browser (by category e.g. call-history)

### importer/exporter
at least one importer/exporter as an example candidates are:

- vCard import/export
- iCal import/export

### sync with other applications
at least one importer/exporter as an example candidates are:

- Pidgin: import messages as events, buddies as contacts, extend existing buddies with additional information (e.g. phone nummber)
- Thunderbird: e-mails as events, sync thunderbird- and mobile- contacts

# Future goals
Anything is possible, here are a few ideas

## TBD

# Development status
TBD

# Help needed
This is about actually getting involved. I don't want any monetary donations, if you want to donate money i can recommend a lot of other projects more deserving and more in need of donations.

## Devices to test it on
TBD

## Spell checking
Corrections appreciated. I don't make mistakes on purpose, I am just dyslexic.

To be continued…
