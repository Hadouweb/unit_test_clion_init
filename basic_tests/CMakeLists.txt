include_directories(${gtest_SOURCE_DIR}/include ${gtest_SOURCE_DIR})

add_executable(runBasicTest
        basic_check.cpp)

target_link_libraries(runBasicTest gtest gtest_main)
