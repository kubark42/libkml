This is a clone of libkml (http://libkml.googlecode.com/). 

[![Build Status](https://travis-ci.org/kubark42/libkml.svg?branch=master)](https://travis-ci.org/kubark42/libkml)

* It fixes several Linux compilation issues
* Adds support for the Style tag embedded in Placemark.

A sparse libkml documentation is on the project wiki:
http://code.google.com/p/libkml/w/list

Special thanks to gumdal for importing libkml to git.

Steps to build

        git clone https://github.com/kubark42/libkml.git
        cd libkml
        ./autogen.sh
        mkdir build
        cd build
        ../configure
        make
        sudo make install

If there are any problems, please start an issue. 
