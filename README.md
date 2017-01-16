# mobiled
mobile daemon and ultilitys to manage phone-, gps-, sync- a.s.o. functionality on free mobile devices like the GTA04, Pyra and Neo900

# Goals
This progect is still in the very very early development stage, and even the goals are still subject to change.

## daemon
A deamon comunicating via /dev with the hardware, on demand as well as lisening for events (e.g. incomming calls) on one side. then on the other side providing an unified interface.

### a simple configuration file to specefy command the daemon executes acording to events
should be as simple as an event name followed by anything to be run by /bin/sh -c
might get a little more complex as some events might have aditional data that needs to be passed to the command-line (e.g. phonenumber on incomming calls)

### an eventlog
to be written to a human readable (well, nerd-readabel) file, and kept in a computer readable format to be eportable/searchable
both have to be easyly configurable, and even possible to turn off for privacy reasons.

### a contact reposetory
so that events can be assioated with a person or a company (e.g. display a name instead of a nummber for an incomming call)
and so that it can be synced with other devices or just other applications (e.g. inporting contacts from thunderbird, exporting contacts to pidgin, a.s.o.)

# Future goals
anything is posible, here are a few ideas

## TBD

# Development status
TBD

# Help needed
this is about actualy geting involeved. i dont want any money donatinons, if you want to donate money i can recomend a lot of other projects more deserving and more in need of donatins.

## Devices to test it on
TBD

## Spell checking
any corrections are appriciated. i dont make these mistakes on porpes, i am just dislexic.

to be continued...
