cmake_minimum_required(VERSION 2.6)
project(capi_zlib)
add_executable(test_zlib zlib_api.cpp zlib_api_test.cpp)
include_directories(../..)
include_directories(.)
