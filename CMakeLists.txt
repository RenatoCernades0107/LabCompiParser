cmake_minimum_required(VERSION 3.26)
project(LabCompiParser)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(LabCompiParser
        svm.cpp
        svm.hh
        svm_parser.cpp
        svm_parser.hh
        svm_run.cpp)
