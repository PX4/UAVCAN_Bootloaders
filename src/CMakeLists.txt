add_library(drivers_bootloaders
		arch/stm32/board_identity.c
		arch/stm32/drivers/can/driver.c
		common/boot_app_shared.c
		common/nuttx_stubs.c
		fs/flash.c
		protocol/uavcan.c
		sched/timer.c
		uavcan/main.c
		util/crc.c
		util/random.c
	)
add_dependencies(drivers_bootloaders nuttx_build)

include_directories(include)
target_include_directories(drivers_bootloaders INTERFACE include)
