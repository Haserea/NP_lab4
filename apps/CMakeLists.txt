if(WIN32)
	set(COMMON_DEPENDENCIES wsock32 ws2_32)
else()
	set(COMMON_DEPENDENCIES "")
endif()


add_subdirectory("udp")
