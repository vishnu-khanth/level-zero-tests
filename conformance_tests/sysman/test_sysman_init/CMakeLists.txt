#
#Copyright(C) 2023-2024 Intel Corporation
#
#SPDX - License - Identifier : MIT
#

add_lzt_test(
    NAME test_init_sysman
    GROUP   "/conformance_tests/tools/sysman"
    SOURCES
    src/test_init_sysman.cpp
    src/main.cpp
    LINK_LIBRARIES level_zero_tests::logging level_zero_tests::utils)

add_lzt_test(
    NAME test_init_sysman_after_core
    GROUP   "/conformance_tests/tools/sysman"
    SOURCES
    src/test_init_sysman_after_core.cpp
    src/main.cpp
    LINK_LIBRARIES level_zero_tests::logging level_zero_tests::utils)

add_lzt_test(
    NAME test_init_sysman_before_core
    GROUP   "/conformance_tests/tools/sysman"
    SOURCES
    src/test_init_sysman_before_core.cpp
    src/main.cpp
    LINK_LIBRARIES level_zero_tests::logging level_zero_tests::utils)
    