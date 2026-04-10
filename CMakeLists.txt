#
# Copyright 2024-2026 NXP
#
# SPDX-License-Identifier: BSD-3-Clause
#

if (CONFIG_MCUX_COMPONENT_middleware.freertos.freertos-plus-tcp)
    mcux_add_source(
        SOURCES ../freertos-plus-tcp-upstream/source/*.*
                ../freertos-plus-tcp-upstream/source/include/*.*
    )
    mcux_add_include(
        INCLUDES ../freertos-plus-tcp-upstream/source/include
    )
endif()
