cmake_minimum_required(VERSION 3.13)
project(Zork)


set(CMAKE_CXX_STANDARD 14)

add_executable(Zork
        Character.cpp
        Command.cpp
        Room.cpp
        item.cpp
        Parser.cpp
        ZorkUL.cpp
        CommandWords.cpp
        )