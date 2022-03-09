cmake_minimum_required(VERSION 3.5)

idf_component_register(SRCS "Adafruit_Sensor.cpp"
                       INCLUDE_DIRS "."
                       REQUIRES arduino Adafruit_BusIO Adafruit_Sensor Adafruit-SSD1306)

project(Adafruit_SCD30)
