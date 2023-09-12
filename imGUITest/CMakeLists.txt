# CMakeList.txt : CMake project for imGUITest, include source and define
# project specific logic here.
#

# Add source to this project's executable.
add_executable (imGUITest "imGUITest.cpp" "imGUITest.h" "UseImGUI.cpp" "UseImGUI.h")

if (CMAKE_VERSION VERSION_GREATER 3.12)
  set_property(TARGET imGUITest PROPERTY CXX_STANDARD 20)
endif()

# TODO: Add tests and install targets if needed.
