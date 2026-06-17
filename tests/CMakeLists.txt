add_executable(kvstore_tests test_main.cpp)
target_link_libraries(kvstore_tests gtest_main)
include(GoogleTest)
gtest_discover_tests(kvstore_tests)