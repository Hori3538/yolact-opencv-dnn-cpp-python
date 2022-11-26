cmake_minimum_required(VERSION 3.1)
project(yoloact_opencv_dnn_cpp)
find_package( OpenCV REQUIRED )
add_executable(main.out main.cpp)
target_link_libraries(main.out ${OpenCV_LIBS})

# MESSAGE(WARNING "prefix ${CMAKE_PREFIX_PATH}")    
# MESSAGE(WARNING "version ${OpenCV_VERSION}")
# MESSAGE(WARNING "install path ${OpenCV_INSTALL_PATH}") 
# MESSAGE(WARNING "config path ${OpenCV_CONFIG_PATH}") # look at the output of this message
# MESSAGE(WARNING "opencv path ${OpenCV_DIR}") # look at the output of this message
# MESSAGE(WARNING "include dirs ${OpenCV_INCLUDE_DIRS}")
# MESSAGE(WARNING "libs ${OpenCV_LIBS}")
