CU_SET_PATH("CMAKE_CHARACTER_TOOLS_DIR" "${CMAKE_CURRENT_LIST_DIR}")

AC_ADD_SCRIPT("${CMAKE_CURRENT_LIST_DIR}/src/character_tools.cpp")

AC_ADD_SCRIPT_LOADER("CharacterTools"      "${CMAKE_CURRENT_LIST_DIR}/src/loader.h")

AC_ADD_CONFIG_FILE("${CMAKE_CURRENT_LIST_DIR}/conf/character_tools.conf.dist")

message("-- CHARACTER TOOLS CONFIGURED --")
