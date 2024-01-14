if (EMBEDDED_FILESYSTEM_INCLUDE_FATFS)
    add_subdirectory(fatfs)
endif()

if (EMBEDDED_FILESYSTEM_INCLUDE_LITTLEFS)
    add_subdirectory(littlefs)
endif()