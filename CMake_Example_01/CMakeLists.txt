# Sets the minimum required version of cmake for a project.
cmake_minimum_required(VERSION 3.5)

# Sets the name of the project, and stores it in the variable PROJECT_NAME.
project("Mein Hello World projekt")

# Adds an executable target called <name> to be built from the source files listed in the command invocation
add_executable(Main main.cpp)