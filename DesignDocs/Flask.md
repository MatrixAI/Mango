#[Flask](http://flask.pocoo.org/docs/0.10/installation/#installation) Installation

1. Install pip on Archlinux using: sudo pacman -S python-pip


[how to install pip](http://ask.xmodulo.com/install-pip-linux.html)

[mariafoo@mango-zero ~]$ sudo pacman -S python-pip
resolving dependencies...
looking for inter-conflicts...

Packages (3): python-3.4.2-1  python-setuptools-1:7.0-1  python-pip-1.5.6-2

Total Download Size:    15.03 MiB
Total Installed Size:   84.46 MiB

:: Proceed with installation? [Y/n] Y
:: Retrieving packages ...
 python-3.4.2-1-armv6h     13.6 MiB   405K/s 00:35 [######################] 100%
 python-setuptools-1...   316.1 KiB   661K/s 00:00 [######################] 100%
 python-pip-1.5.6-2-any  1094.1 KiB   481K/s 00:02 [######################] 100%
(3/3) checking keys in keyring                     [######################] 100%
(3/3) checking package integrity                   [######################] 100%
(3/3) loading package files                        [######################] 100%
(3/3) checking for file conflicts                  [######################] 100%
(3/3) checking available disk space                [######################] 100%
(1/3) installing python                            [######################] 100%
Optional dependencies for python
    python-setuptools [pending]
    python-pip [pending]
    sqlite [installed]
    mpdecimal: for decimal
    xz: for lzma [installed]
    tk: for tkinter
(2/3) installing python-setuptools                 [######################] 100%
(3/3) installing python-pip                        [######################] 100%

2. Install virtualenv using: sudo pip install virtualenv

[mariafoo@mango-zero myproject]$ sudo pip install virtualenv
Downloading/unpacking virtualenv
  Downloading virtualenv-1.11.6-py2.py3-none-any.whl (1.6MB): 1.6MB downloaded
Installing collected packages: virtualenv
Successfully installed virtualenv
Cleaning up...
