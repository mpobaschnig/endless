cmake_minimum_required(VERSION 4.0.0)

set(VERSION 0.1.0)

set(CMAKE_CXX_STANDARD 26)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_EXTENSIONS OFF)

project(endless VERSION ${VERSION})

add_executable(${PROJECT_NAME}
    src/main.cpp
)
