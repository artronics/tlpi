# TODO: Wire this for targets
add_custom_command(OUTPUT ename.c.inc
        COMMAND ./Build_ename.sh
        WORKING_DIRECTORY ${CMAKE_CURRENT_SOURCE_DIR})

add_library(tlpi SHARED get_num.c error_functions.c)