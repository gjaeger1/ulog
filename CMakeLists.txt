cmake_minimum_required(VERSION 3.5)

if(NOT ULOG_SKIP_TESTS)
	add_subdirectory(tests)
endif()

add_subdirectory(src)
