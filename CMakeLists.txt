add_library(SmartRC-CC1101-Driver-Lib-Pico
ELECHOUSE_CC1101_SRC_DRV.cpp
)

target_include_directories(SmartRC-CC1101-Driver-Lib-Pico PUBLIC
	.
)

target_link_libraries(SmartRC-CC1101-Driver-Lib-Pico pico_stdlib hardware_spi)