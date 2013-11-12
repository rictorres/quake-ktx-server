# Quake KTX Server

1. Clone this repo or download the [zipball](https://github.com/rictorres/quake1-ktx/archive/master.zip)
2. Run `./start-ktx` (it will be attached to a different screen called `qw-ktx`, useful if you're using SSH)
3. Profit!


## Requirements
- Linux server (preferably Ubuntu)
- SSH
- Screen

## Installation

`admin@quake:~$ sudo apt-get update
admin@quake:~$ sudo apt-get install screen
admin@quake:~$ chmod 755 start-qw`

## Additional info

- To get a list of "screens" in use:
  `screen -list`
- To re-attach the screen
  `screen -r qw-ktx`


## Credits
- [SLUSAMSON](http://www.bluemunkey.com/?p=124)