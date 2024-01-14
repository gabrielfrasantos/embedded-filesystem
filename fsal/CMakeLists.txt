add_subdirectory(interfaces)

if (EMBEDDED_FILESYSTEM_INCLUDE_FATFS)
    add_subdirectory(fatfs)
endif()