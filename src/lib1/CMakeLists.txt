
include_directories(inc)

set(LIB_1_HEADERS inc/lib1/fun1.h)
set(LIB_1_SOURCES src/fun1.cpp)

add_library(lib1 STATIC ${LIB_1_HEADERS} ${LIB_1_SOURCES})