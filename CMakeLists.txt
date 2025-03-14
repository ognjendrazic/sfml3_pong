cmake_minimum_required(VERSION 3.16)

project(sayHello)

add_executable(sayHello main.cpp)

# Find the SFML package with the required components
find_package(SFML 2.5 COMPONENTS system window graphics REQUIRED)

target_link_libraries(sayHello sfml-system sfml-window sfml-graphics)