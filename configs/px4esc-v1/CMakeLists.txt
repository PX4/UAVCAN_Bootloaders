add_library(px4esc-v1
	boot.c
	led.c
)
target_link_libraries(px4esc-v1 drivers_bootloaders)