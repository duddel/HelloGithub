# HelloGithub

[![Build Status](https://travis-ci.org/duddel/HelloGithub.svg?branch=master)](https://travis-ci.org/duddel/HelloGithub)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/66d5f7a4e30d48929adf073a90d70a39)](https://www.codacy.com/app/duddel/HelloGithub?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=duddel/HelloGithub&amp;utm_campaign=Badge_Grade)

My learning project to get started with GitHub and Travis CI.

## Goals

Make a simple executable that is built by **Travis CI** using CMake.

## Status

-   CMake **(works)**
-   C++11 support **(works)**
-   building on Linux with gcc **(works)**
-   building on Linux with clang **(works)**
-   building on Windows with MSVC **(works)**
-   deploying to GitHub Releases **(works)**

## ToDo

-   building on Windows with MinGW-w64 **(fails** _due to CMake "sh.exe is in your PATH" error_)
-   how to change compiler on _os: windows_ to MinGW other than specifying CMake generator: _-G "MinGW Makefiles"_?

## Lessons Learned

-   Deploy from Travis CI to GitHub:
    -   create a _Personal access token_ in GitHub settings
    -   use _Travis command line client_ (that Ruby tool) to encrypt the token
    -   add it with _secure:_ as _api_key_ to .travis.yml
    -   **see:** Travis docs "deployment to GitHub Releases"
