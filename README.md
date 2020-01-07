# HelloGithub

<https://duddel.github.io/HelloGithub>

[![Build Status](https://travis-ci.org/duddel/HelloGithub.svg?branch=master)](https://travis-ci.org/duddel/HelloGithub)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/66d5f7a4e30d48929adf073a90d70a39)](https://www.codacy.com/app/duddel/HelloGithub?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=duddel/HelloGithub&amp;utm_campaign=Badge_Grade)

My learning project to test out some GitHub and CI topics

## Status

-   simple C++11 CMake project
-   building with Travis CI on Linux with gcc, clang and Windows (MSVC)
-   tags are deployed to GitHub Releases by Travis CI
-   documentation is deployed to `gh-pages` branch by running this workflow: [.github/workflows/docs.yml](.github/workflows/docs.yml)

## Lessons Learned

-   Deploy from Travis CI to GitHub:
    -   create a _Personal access token_ in GitHub settings
    -   use _Travis command line client_ (that Ruby tool) to encrypt the token
    -   add it with _secure:_ as _api_key_ to .travis.yml
    -   **see:** Travis docs "deployment to GitHub Releases"
