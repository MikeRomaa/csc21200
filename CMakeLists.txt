cmake_minimum_required(VERSION 3.25)
project(csc212)

set(CMAKE_CXX_STANDARD 17)

add_executable(bag bag/bag_demo.cpp bag/bag.cpp)

add_executable(project1 project1/stats_exam.cpp project1/stats.h project1/stats.cpp)
add_executable(project2 project2/sequence_exam.cpp project2/sequence.h project2/sequence.cpp)
add_executable(project3 project3/sequence_exam.cpp project3/sequence.h project3/sequence.cpp)
add_executable(project4 project4/sequence_exam.cpp project4/sequence.h project4/sequence.cpp project4/node.h project4/node.cpp)
add_executable(project5 project5/rec_test.cpp project5/rec_fun.h project5/rec_fun.cpp)
add_executable(project6 project6/bag_exam.cpp project6/bintree.h project6/bag.h)
