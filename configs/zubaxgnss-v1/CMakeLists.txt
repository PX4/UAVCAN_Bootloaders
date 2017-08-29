add_library(zubaxgnss-v1
	boot.c
	led.c
)
target_link_libraries(zubaxgnss-v1 drivers_bootloaders)