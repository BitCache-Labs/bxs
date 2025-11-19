cmake_minimum_required(VERSION 3.16)
project(bxs)

set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_library(bxs INTERFACE)
target_include_directories(bxs INTERFACE "include")