project(main)

include_directories(src/)

file(GLOB PROJECT_SRC src/*.c)

add_executable(${PROJECT_NAME} ${PROJECT_SRC})

