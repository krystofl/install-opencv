# install-opencv
**An easy-to-use script to install opencv on linux-based systems**

To install opencv (C++ & Python) with the default options (*my* default options),
just run
```
./install_opencv.py
```

The script may ask you for your sudo password.

To see available options, run `./install_opencv.py --help`.

The code seems to work fine on Ubuntu 16.04, but is not thoroughly tested.


## Prerequisites

The script runs in python3; you can install it by running `sudo apt-get install python3`
on Debian-based systems (such as Ubuntu).

The code seems to work fine on Ubuntu 16.04, but is not thoroughly tested.

## options
Run `./install_opencv.py --help` to see the full list of options.

By default, the script will attempt to install opencv's prerequisites.
To disable this behaviour (useful if you've already installed them yourself, for example),
use the `-p` flag.
