cmake_minimum_required(VERSION 2.6)

# Locate gtest
find_package(GTest REQUIRED)
include_directories(${GTEST_INCLUDE_DIRS})

# Link runTests with the stuff we want to test
add_executable(runTests squareRoot_test.cpp)
target_link_libraries(runTests ${GTEST_LIBRARIES} pthread)