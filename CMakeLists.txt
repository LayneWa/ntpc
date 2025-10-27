project(ntpc)

set(NTP_SRC
    ${CMAKE_SOURCE_DIR}/ntpc.c
)
add_executable(ntpc ${NTP_SRC})
install(PROGRAMS ntpc DESTINATION bin)