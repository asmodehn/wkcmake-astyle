cmake_minimum_required(VERSION 2.8)

Project(AStyle CXX)

add_executable(astyle src/ASBeautifier.cpp src/ASLocalizer.cpp src/astyle.h
		      src/ASEnhancer.cpp src/ASLocalizer.h src/astyle_main.cpp
		      src/ASFormatter.cpp src/ASResource.cpp src/astyle_main.h
)
install( TARGETS astyle
	 RUNTIME DESTINATION bin
)
