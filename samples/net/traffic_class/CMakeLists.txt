cmake_minimum_required(VERSION 3.13.1)

include($ENV{ZEPHYR_BASE}/cmake/app/boilerplate.cmake NO_POLICY_SCOPE)
project(traffic_class)

target_sources(app PRIVATE src/main.c)

include($ENV{ZEPHYR_BASE}/samples/net/common/common.cmake)
