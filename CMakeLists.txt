cmake_minimum_required(VERSION 3.16)
project(
  MY_TEST_PROJECT # Name of project. MY_TEST_PROJECT is a placeholder
  VERSION 1.7.6
  LANGUAGES Fortran)

# Set name of executable. MY_EXECUTABLE_NAME is just a placeholder.
set(EXECUTABLE_NAME "MY_EXECUTABLE_NAME")

# A whitespace separated list of all source files
set(FILES "MAIN.FOR" "FILE1.FOR")

# Define the executable (Don't change this line).
add_executable(${EXECUTABLE_NAME} ${FILES})
