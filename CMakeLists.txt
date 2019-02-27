cmake_minimum_required(VERSION 3.2)

project(HelloGithub)

# enable c++11 (or later) and disable extensions
set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_EXTENSIONS OFF)

# add executable target
add_executable(${CMAKE_PROJECT_NAME}
    src/main.cpp
)
