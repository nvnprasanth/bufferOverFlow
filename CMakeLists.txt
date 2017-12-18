cmake_minimum_required(VERSION 2.8)

project(bufferOverFlow)
set(CMAKE_C_FLAGS "-fno-stack-protector -m32 -z execstack")
add_executable(bufferOverFlow bufferOverFlow.c)
