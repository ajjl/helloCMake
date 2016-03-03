cmake_minimum_required( VERSION 2.6 )
project ( hello )
add_executable( hello helloWorld.cxx )

include(CTest)
add_test(does_it_run hello )
