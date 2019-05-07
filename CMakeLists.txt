project(testgtest)
cmake_minimum_required(VERSION 2.8)

find_package(GTest REQUIRED)
include_directories(${GTEST_INCLUDE_DIRS})

add_executable(testgtest testgtest.cpp)
target_link_libraries(testgtest ${GTEST_LIBRARIES})
