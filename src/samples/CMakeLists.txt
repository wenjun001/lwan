if (NOT ${CMAKE_BUILD_TYPE} MATCHES "Coverage")
	add_subdirectory(freegeoip)
	add_subdirectory(techempower)
	add_subdirectory(hello)
	add_subdirectory(hello-no-meta)
	add_subdirectory(clock)
endif()
