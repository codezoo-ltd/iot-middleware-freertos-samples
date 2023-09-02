set(req driver freertos log)

idf_component_register(
    SRCS dht11.c
    INCLUDE_DIRS .
    REQUIRES ${req}
)
