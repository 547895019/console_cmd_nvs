idf_component_register(SRCS "console_nvs.c"
                    INCLUDE_DIRS "."
                    PRIV_REQUIRES console nvs_flash bootloader_support spi_flash
                    WHOLE_ARCHIVE)
