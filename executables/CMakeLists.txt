add_executable( dummy
  dummy.cpp
 )
 
add_executable( base-sim
  base-sim.cpp
 )

target_link_libraries(
  base-sim 
  RobotDART::Simu
  RobotDART::Magnum
  )
