cmake_minimum_required(VERSION 3.20)
enable_testing()
include(cmake/CL-Core.cmake)
message(${ae2f_IS_SHARED})
message(${ae2f_packcount})
message(${ae2f_LIBPREFIX})

project(CL-Core-Template VERSION 0.1.5 LANGUAGES C CXX)

if(NOT TARGET ${PROJECT_NAME})
    message(${PROJECT_NAME})
endif()