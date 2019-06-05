cmake_minimum_required (VERSION 3.12)

set(CMAKE_CXX_STANDARD 17)

project(packmagic)

include(CTest)

add_subdirectory(deps)

enable_testing()

add_subdirectory(src)

add_subdirectory(test)
