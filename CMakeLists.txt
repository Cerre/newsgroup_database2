cmake_minimum_required(VERSION 3.0)

# Set project name
project(news_db2)

set(CMAKE_CXX_STANDARD 11)
set(CMAKE_CXX_STANDARD_REQUIRED True)

include_directories(src)
add_executable(main.out src/main.cc)
