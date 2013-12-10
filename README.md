# Quake KTX Server

## Overview
1. Clone this repo `git clone https://github.com/rictorres/quake1-ktx.git` or download the [zipball](https://github.com/rictorres/quake1-teamfortress/archive/master.zip)
2. Run `./start-ktx` (it will be attached to a different screen called `qw-ktx`, useful if you're using SSH)
3. Profit!


## Requirements
- Linux server (preferably Ubuntu)
- SSH
- Screen


## Installation
```
$ sudo apt-get update
$ sudo apt-get install screen
$ chmod 755 start-qw
```


## Running
```
./start-ktx
RUNNING KTX PUBLIC SERVER ON PORT 27510
```


## Additional info
- To get a list of `screens` in use:
  `$ screen -list`
- To re-attach the screen
  `$ screen -r qw-ktx`
- To detach the screen and go back to your original SSH session
  `CTRL + A + D`


## Credits
- [SLUSAMSON](http://www.bluemunkey.com/?p=124)

[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/rictorres/quake1-ktx/trend.png)](https://bitdeli.com/free "Bitdeli Badge")

