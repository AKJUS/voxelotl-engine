cmake_minimum_required(VERSION 3.24)
set(CMAKE_OSX_DEPLOYMENT_TARGET "13.6" CACHE STRING "Minimum MacOS version" FORCE)
set(CMAKE_Swift_LANGUAGE_VERSION 5)
project(voxelotl LANGUAGES C OBJC Swift VERSION "0.1.0")

add_subdirectory(External/SDLSwift)
add_subdirectory(Sources/Voxelotl)
