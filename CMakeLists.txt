cmake_minimum_required(VERSION 3.0.0)   # CMake version check
project(SeFleetMngr)                    # Create project "SeFleetMngr"
set(CMAKE_CXX_STANDARD 17)              # Enable c++17 standard

# Currently we only compile "main.cpp".
# Add "<Module>.cpp" to the list for each module you need to compile.
# For example, to add "Application.cpp" and "Vehicle.cpp":
# set(SOURCE_FILES main.cpp Application.cpp Vehicle.cpp)
set(SOURCE_FILES main.cpp)

# Add executable target with source files listed in SOURCE_FILES variable
add_executable(SeFleetMngr ${SOURCE_FILES})