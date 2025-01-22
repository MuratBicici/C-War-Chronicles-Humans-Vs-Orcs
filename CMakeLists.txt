cmake_minimum_required(VERSION 3.29)
project(PROLAB_PROJECT_CLION_1 C)
set(CMAKE_C_STANDARD 99)
add_executable(PROLAB_PROJECT_CLION_1 main.c)

set(CURL_INCLUDE_DIR "C:/Users/Murat/vcpkg/installed/x64-windows/include")
set(CURL_LIBRARY "C:/Users/Murat/vcpkg/installed/x64-windows/lib/libcurl.lib")
include_directories(${CURL_INCLUDE_DIR})
target_link_libraries(PROLAB_PROJECT_CLION_1 ${CURL_LIBRARY})

set(RAYLIB_INCLUDE_DIR "C:/Users/Murat/vcpkg/installed/x64-windows/include")
set(RAYLIB_LIBRARY "C:/Users/Murat/vcpkg/installed/x64-windows/lib/raylib.lib")
include_directories(${RAYLIB_INCLUDE_DIR})
target_link_libraries(PROLAB_PROJECT_CLION_1 ${RAYLIB_LIBRARY})