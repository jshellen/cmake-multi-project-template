
set(APP_2_SOURCES src/main.cpp)

add_executable(app2 ${APP_2_SOURCES})
target_link_libraries(app2 lib1)
target_link_libraries(app2 lib2)
