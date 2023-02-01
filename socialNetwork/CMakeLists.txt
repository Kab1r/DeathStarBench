cmake_minimum_required(VERSION 3.5)
project(social_network_microservices)

set(CMAKE_CXX_STANDARD 14)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_FLAGS "-O3")
set(CMAKE_INSTALL_PREFIX /usr/local/bin)

add_subdirectory(src)
#add_subdirectory(test)
#enable_testing()

# add_definitions(-DISOLATE_COMPOSE_POST)
# add_definitions(-DISOLATE_TEXT_HANDLER)
# add_definitions(-DISOLATE_USER_TIMELINE)
