cmake_minimum_required(VERSION 4.0)
project(Hash)

set(CMAKE_CXX_STANDARD 14)

include_directories("HashMapStudents(Updated)")

add_executable(Hash
        "HashMapStudents(Updated)/HashMap.cpp"
        "HashMapStudents(Updated)/HashMap.h"
        "HashMapStudents(Updated)/HNode.cpp"
        "HashMapStudents(Updated)/HNode.h"
        "HashMapStudents(Updated)/main.cpp"
        "HashMapStudents(Updated)/voice.cpp"
        "HashMapStudents(Updated)/voice.h")
