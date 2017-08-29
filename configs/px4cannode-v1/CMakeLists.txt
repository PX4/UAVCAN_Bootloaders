add_library(px4cannode-v1
	boot.c
	led.c
)
target_link_libraries(px4cannode-v1 drivers_bootloaders)