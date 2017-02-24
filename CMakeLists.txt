cmake_minimum_required(VERSION 2.4.6)
#################################################################################
project ()
#SET(CMAKE_BUILD_TYPE Release)
SET(MY_COMILE_FLAGS "-std=c++11 -Wall -Wextra -fPIC" )
SET(MY_LINK_FLAGS "")
INCLUDE_DIRECTORIES(include)
#################################################################################
########################## Lib, exe definations #################################
add_library()
add_executable()
target_link_libraries()
#################################################################################
SET(EXECUTABLE_OUTPUT_PATH ${PROJECT_SOURCE_DIR}/bin)
SET(LIBRARY_OUTPUT_PATH ${PROJECT_SOURCE_DIR}/lib)
SET(CMAKE_EXE_LINKER_FLAGS  "${MY_LINK_FLAGS} ${CMAKE_EXE_LINKER_FLAGS}")
SET(CMAKE_CXX_FLAGS "${MY_COMILE_FLAGS} ${CMAKE_CXX_FLAGS}")
