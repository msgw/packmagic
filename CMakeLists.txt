cmake_minimum_required (VERSION 3.12)

include(build/msgw-build.cmake)

project(packmagic)

include(CTest)

add_subdirectory(deps)

enable_testing()

add_subdirectory(src)

add_subdirectory(test)
