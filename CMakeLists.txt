cmake_minimum_required(VERSION 3.22)
project(dungeon)

set(CMAKE_CXX_STANDARD 17)

find_package(raylib CONFIG REQUIRED)
find_package(glfw3  CONFIG REQUIRED)
if(APPLE)
    set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fsanitize=address")
elseif(UNIX)
    set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -pthread -fsanitize=address -fsanitize=undefined")
endif()

add_executable(dungeon dungeon.cpp globals.h graphics.h images.h utilities.h)
target_link_libraries(dungeon PRIVATE raylib glfw)
