set(PACKMAGIC_UNITTEST_SOURCES
    main.cpp
)

add_executable(packmagic_unittest ${PACKMAGIC_UNITTEST_SOURCES})

target_link_libraries(packmagic_unittest
    packmagic
)

add_test(unittest COMMAND packmagic_unittest)