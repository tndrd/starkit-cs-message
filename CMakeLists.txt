cmake_minimum_required(VERSION 3.5)
set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_FLAGS "-g")

project(starkit-cs-message)

add_library(CsMessage Src/CsMessage.cpp)
target_include_directories(CsMessage PUBLIC Inc/)