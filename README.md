HelloGithub
===

[![Build Status](https://travis-ci.org/duddel/HelloGithub.svg?branch=master)](https://travis-ci.org/duddel/HelloGithub)


My learning project to get started with GitHub and Travis CI.

## Goals

Make a simple executable that is built by **Travis CI** using CMake.

## Status

* CMake **(works)**
* C++11 support **(works)**
* building on Linux with gcc **(works)**
* building on Linux with clang **(works)**
* building on Windows with MSVC **(works)**

## ToDo

* building on Windows with MinGW-w64 **(fails** *due to CMake "sh.exe is in your PATH" error*)
* how to change compiler on *os: windows* other than specifying CMake generator: *-G "MinGW Makefiles"*?
* use CMake ExternalProject to add a 3rd party library to the build 
