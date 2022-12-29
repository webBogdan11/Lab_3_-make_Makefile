cmake_minimum_required(VERSION 3.22.1)

project(CLearn)
add_library(helloStatic STATIC main.cpp foo.cpp foo.h)
add_executable(CLearn main.cpp foo.cpp)

