cmake_minimum_required(VERSION 3.21)
project(CVSamples)

set(CMAKE_CXX_STANDARD 14)

add_executable(CVSamples main.cpp CVEndianHandler.cpp CVEndianHandler.h CVIOHandler.cpp CVIOHandler.h CVBitOperate.cpp CVBitOperate.h)
