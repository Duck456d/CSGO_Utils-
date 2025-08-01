cmake_minimum_required(VERSION 3.12)
project(CS2_Research_Tool LANGUAGES CXX)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(memory_tool
    main.cpp
)

# Для Windows-сборки
if(WIN32)
    target_link_libraries(memory_tool PRIVATE kernel32.lib user32.lib)
endif()
