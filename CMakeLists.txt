cmake_minimum_required(VERSION 3.10)
project(math)

file(GLOB_RECURSE MATH_SOURCES CONFIGURE_DEPENDS "src/*.cpp")
add_library(math STATIC ${MATH_SOURCES})

target_include_directories(math PUBLIC include)

if(CMAKE_PROJECT_NAME STREQUAL PROJECT_NAME)
    include(FetchContent)
    FetchContent_Declare(
            googletest
            GIT_REPOSITORY https://github.com/google/googletest.git
            GIT_TAG        v1.14.0
    )
    FetchContent_MakeAvailable(googletest)
    add_subdirectory(tests)
endif()