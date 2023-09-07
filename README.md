# statectl

`statectl` is a friendly shell script for managing a computer's state, intended to be
- portable
- friendly, with human language
- powerful

Its primary demographic is UNIX-like systems without systemd or elogind.

The script *must* be ran with root permissions. The intended way to do this is to create an exception for `statectl` for your user within sudo/doas, but that is entirely down to the user.

## TODO
- Create man page
- Find out how portable `shutdown` is 
- Allow for `shutdown` timers
- Address TODOs within the script
