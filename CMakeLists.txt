#
# Copyright 2024 NXP
#
# SPDX-License-Identifier: MIT
#

if (CONFIG_MCUX_COMPONENT_middleware.freertos.freertos-plus-tcp)
    mcux_add_source(
        SOURCES source/*.* source/include/*.*
    )
    mcux_add_include(
        INCLUDES source/include
    )
endif()
