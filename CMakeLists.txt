cmake_minimum_required(VERSION 3.15)
project(CDemo C)

set(CMAKE_C_STANDARD 99)
set(-DCMAKE_SH="CMAKE_SH-NOTFOUND")

add_executable(CDemo main.c libs/libs.c libs/libs.h)