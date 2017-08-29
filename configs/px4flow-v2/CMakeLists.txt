add_library(px4flow-v2
	boot.c
	led.c
)
target_link_libraries(px4flow-v2 drivers_bootloaders)