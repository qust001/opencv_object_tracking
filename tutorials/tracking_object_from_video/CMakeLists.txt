cmake_minimum_required(VERSION 2.8)
project( trackObjectColor )
find_package( OpenCV REQUIRED )
add_executable( trackObjectByColor track_object_color.cpp )
target_link_libraries( trackObjectByColor ${OpenCV_LIBS} )
