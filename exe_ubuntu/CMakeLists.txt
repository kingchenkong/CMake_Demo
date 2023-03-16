### Specify the minimum version.
cmake_minimum_required(VERSION 3.10)

### Specify the project info.
project(_exe)

### executable file name: ref to project 
add_executable( ${PROJECT_NAME}  
    src/main.cpp 
    src/utils.h 
    src/Window.h
)

### Declare the library target.
# add_library(${PROJECT_NAME} SHARED
#     src/attempt.cpp
#     src/attempt.h
# )

### Specify C++11 standard
set(CMAKE_CXX_STANDARD 11)

