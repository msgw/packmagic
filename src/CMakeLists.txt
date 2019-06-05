set(PACKMAGIC_SOURCES
    packmagic.h
    packmagic.cpp
)

add_library(packmagic STATIC ${PACKMAGIC_SOURCES})

target_include_directories(packmagic PUBLIC $<BUILD_INTERFACE:${CMAKE_CURRENT_SOURCE_DIR}>)