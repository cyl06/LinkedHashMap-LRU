cmake_minimum_required(VERSION 3.29)
project(LinkedHashMap_LRU)

set(CMAKE_CXX_STANDARD 14)

include_directories(lru)

add_executable(LinkedHashMap_LRU
    lru/class-integer.hpp
    lru/class-matrix.hpp
    lru/exceptions.hpp
    lru/lru.hpp
    lru/src.hpp
    lru/utility.hpp
    test/1.cpp
    test/2.cpp
    test/4.cpp
    test/5.cpp
    test/6.cpp
    test/8.cpp)
