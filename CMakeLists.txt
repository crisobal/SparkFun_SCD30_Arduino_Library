#set(COMPONENT_SRCDIRS

set(COMPONENT_SRCS
        src/SparkFun_SCD30_Arduino_Library.cpp
        )

set(COMPONENT_ADD_INCLUDEDIRS
        src/
        )

list(APPEND COMPONENT_REQUIRES "arduino")

register_component()

list(APPEND DEFINITIONS "ESP32")

#target_compile_definitions(${COMPONENT_NAME} PUBLIC ${DEFINITIONS})
