cmake_minimum_required(VERSION 3.27)
project(test CXX)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED on)

set(INC_FILES
   
)

set(SRC_FILES
 
)

include_directories("inc")

add_executable(${PROJECT_NAME} "main.cpp" ${INC_FILES} ${SRC_FILES})
