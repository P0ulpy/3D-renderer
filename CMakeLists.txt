cmake_minimum_required(VERSION 3.24)
set(CMAKE_TOOLCHAIN_FILE ${CMAKE_SOURCE_DIR}/vcpkg/scripts/buildsystems/vcpkg.cmake)

project(3d-renderer)

set(CMAKE_CXX_STANDARD 20)

SET(EXECUTABLE_TARGET_NAME 3d-renderer-test)

add_executable(${EXECUTABLE_TARGET_NAME}
    main.cpp
)
