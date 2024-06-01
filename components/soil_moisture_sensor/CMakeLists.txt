cmake_minimum_required(VERSION 3.16)


set(srcs "src/soil_moisture_sensor.c")
idf_component_register(SRCS ${srcs}
                       INCLUDE_DIRS "include"
                       REQUIRES esp_adc)