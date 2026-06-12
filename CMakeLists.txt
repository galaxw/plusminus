cmake_minimum_required(VERSION 3.10)

project(plusminus)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

# Add GUI and CLI components
add_subdirectory(src/gui)
add_subdirectory(src/cli)