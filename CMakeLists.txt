cmake_minimum_required(VERSION 3.5)

idf_component_register(SRCS "Adafruit_SCD30.cpp"
                       INCLUDE_DIRS "."
                       REQUIRES arduino adafruit_busio adafruit_sensor adafruit_ssd1306)

project(adafruit_scd30)
