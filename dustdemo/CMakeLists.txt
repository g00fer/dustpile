cmake_minimum_required (VERSION 3.7)
set (CMAKE_CXX_COMPILER gcc)
project (Dustpile)

# Set Version Number
set (Dustpile_VERSION_MAJOR 1)
set (Dustpile_VERSION_MINOR 0)
set (Dustpile_VERSION_DETAIL 0)


#add the executable
add_executable (Dustpile main.c)

