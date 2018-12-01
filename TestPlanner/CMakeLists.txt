cmake_minimum_required(VERSION 3.12)
project(TestPlanner)

set(CMAKE_CXX_STANDARD 14)

add_executable(TestPlanner main.cpp Projects.cpp Projects.h Paper.cpp Paper.h Exam.cpp Exam.h)