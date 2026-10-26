add_library(mylib test_lib.cpp)

target_include_directories(mylib PUBLIC ${PROJECT_SOURCE_DIR}/lib)
