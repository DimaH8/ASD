cmake_minimum_required(VERSION 3.1)

# Name of project
# CHANGE THIS NAME IN YOUR PROJECT
set(PROJECT_NAME "Lab2Queue")

# create project
project(${PROJECT_NAME})


set(SOURCE_FILES
		main.cpp
		dequeue.cpp
		dequeue.h
)

add_executable(${PROJECT_NAME} ${SOURCE_FILES})