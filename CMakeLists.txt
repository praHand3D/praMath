add_library(math STATIC
        src/Matrix.cpp
        src/Vec.cpp)

target_include_directories(math PUBLIC include)