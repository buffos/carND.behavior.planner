project(BehaviorPlanner)

cmake_minimum_required (VERSION 3.5)

add_definitions(-std=c++11)

# set(CMAKE_CXX_FLAGS "-Wall")

add_executable(behaviorPlanner
    "src/road.cpp"
    "src/vehicle.cpp"
    "src/main.cpp"
)