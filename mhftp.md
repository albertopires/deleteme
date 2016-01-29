---
layout: page
title: MhFTP

---

## Multi-homed File Transfer Protocol ##

MhFtp is a tool to allow file transfer over a multi-homed host, that is, a host
with more than one Internet link, using one or more links, summing up of all
bandwidths.

### Compiling ###

As of this moment, this version is tested on 64bit Linux and requires:

* GNU g++ 4.8
* libssl-dev 1.0.1f
* Electric Fence (optional)

It's possible to compile MhFtp on older version of g++, although it may necessary
to comment the compile options **-pedantic** and **-std=c++11** on your Makefile.


``CFLAGS=-Wall -g #-pedantic -std=c++11``

and then, just run make.

For more information:
[Documentation](http://albertopires.github.io/deleteme).

### Contributing
For now it's just me, so I'll try to keep it simple. Basically **master** branch
will have the latest (hopefully stable) version, and there will be a **next**
branch where I'll work on upcoming features.

So, fork it and have fun.

![vim_created](http://www.vim.org/images/vim_created.gif)
