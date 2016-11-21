cmake_minimum_required(VERSION 2.8)
project(exampleDebugProject)

set(CMAKE_INSTALL_PREFIX ${CMAKE_CURRENT_SOURCE_DIR}/install)
set(CMAKE_MODULE_PATH ${CMAKE_CURRENT_SOURCE_DIR}/modules)

add_subdirectory(src)
