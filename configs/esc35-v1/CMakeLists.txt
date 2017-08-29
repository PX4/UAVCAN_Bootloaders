add_library(esc35-v1
	boot.c
	led.c
)
target_link_libraries(esc35-v1 drivers_bootloaders)