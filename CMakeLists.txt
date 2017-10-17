cmake_minimum_required(VERSION 2.8)

project(boostThreadsAsio)
add_executable(${PROJECT_NAME} "main.cpp")

target_link_libraries(${PROJECT_NAME} boost_system boost_thread)
