# PROJECT(Hello)
# MESSAGE(STATUS "This is my test: " ${PROJECT_BINARY_DIR})
# set(EXECUTABLE_OUTPUT_PATH ${PROJECT_BINARY_DIR}/bin)
# add_executable(main main.cpp)


# Static libraries and Dynamic libraries
PROJECT(HELLO)
set(LIBRARY_OUTPUT_PATH ${PROJECT_SOURCE_DIR}/lib)
ADD_SUBDIRECTORY(src)