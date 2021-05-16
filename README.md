# bspdropterm
![posix-compliant](https://img.shields.io/static/v1?label=posix&message=compliant&color=blue&style=for-the-badge) &nbsp;

A simple script to provide drop down terminal functionality for bspwm. 
## Installation and Usage
Put the script in your `$PATH`. Main functions:
1. Initialise drop down terminal:
```bash
bspdropterm --init
```
2. Toggle visibility of drop down terminal
```bash
bspdropterm --toggle
```
These commands are meant to be executed with the help of a hot-key daemon, for instance, `sxhkd`, `xbindkeysrc`, etc. I have the following lines in my `sxhkdrc`:
```cfg
mod1 + e
    bspdropterm --toggle
```
## Dependencies
* xdotool
