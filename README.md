# Communist

 One-command remote terminal sharing for pair programming with your team. Your laptop is the people's laptop, comrade.

## Requirements

The client machines just need Ruby >= 1.8.7 and sshd running. `guest account stuff TBD`

The bridge server should allow sudo access for `lsof` and `netstat` for the user group in question.

## TODO

Everything. Communist is in the proof-of-concept stage right now. Specifically:

* Automatically launch wemux upon begin of listening and connection to remote machine 
* Better usage and config from command-line

