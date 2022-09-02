# CMakeList.txt : CMake project for F-calculator-CMake, include source and define
# project specific logic here.
#
cmake_minimum_required (VERSION 3.8)

project ("F-calculator-CMake")

# Add source to this project's executable.
add_executable (F-calculator-CMake "F-calculator-CMake.cpp" "F-calculator-CMake.h")

if (CMAKE_VERSION VERSION_GREATER 3.12)
  set_property(TARGET F-calculator-CMake PROPERTY CXX_STANDARD 20)
endif()

# TODO: Add tests and install targets if needed.
