cmake_minimum_required(VERSION 3.20)
project(Assignment1)

set(CMAKE_CXX_STANDARD 14)

set(CMAKE_RUNTIME_OUTPUT_DIRECTORY build)

add_executable(<executable_name> source/<executable_source_file> lib/<executable_header_file>)
# example: add_executable(GammaCorrection source/GammaCorrection.cpp lib/MImageClass.h)