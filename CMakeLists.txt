cmake_minimum_required(VERSION 2.8)
project(hello)
add_executable(hello helloWorld.cpp)

install( TARGETS hello DESTINATION usr/bin/)
