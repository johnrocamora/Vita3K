add_library(SceLibGameUpdate STATIC include/SceLibGameUpdate/exports.h src/SceGameUpdate.cpp)
target_include_directories(SceLibGameUpdate PUBLIC include)
target_link_libraries(SceLibGameUpdate PRIVATE module)
