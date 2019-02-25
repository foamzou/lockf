# lockf

## About
A tool from [freebsd](http://sources.freebsd.org/RELENG_7/src/usr.bin/lockf/). Use the tool, can ensure that only one process is running at a time.

## Usage
* lockf [-ks] [-t seconds] file command [arguments]
* e.g. ./lockf -s -t 0 /tmp/foam.lock php 1.php
* for more, `man lockf` after install

## Install
cd src
make && sudo make install

## Thanks
[Tsung's Blog](https://blog.longwin.com.tw/2009/03/debian-linux-make-install-lockf-2009/)
