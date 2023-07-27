PROJECT(sddl)
cmake_minimum_required(VERSION 3.1.2)

set(USE_JSON false)

set(CMAKE_VERBOSE_MAKEFILE TRUE)

include(${CMAKE_BINARY_DIR}/conanbuildinfo.cmake)

include_directories(${CONAN_INCLUDE_DIRS_TBB})

link_directories(${CONAN_LIB_DIRS_TBB})

CONAN_BASIC_SETUP(TARGETS)

# ADD_EXECUTABLE(${CMAKE_PROJECT_NAME} test_package.cpp)
# TARGET_LINK_LIBRARIES(${CMAKE_PROJECT_NAME} ${CONAN_LIBS})




