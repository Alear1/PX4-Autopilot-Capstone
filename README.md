# PX4-Autopilot-Capstone

Place "peregrine" folder into PX4-Autopilot/Tools/sitl_gazebo/models

Place "13112_peregrine" into PX4-Autopilot/ROMFS/px4fmu_common/init.d-posix/airframes
add the line "13112_peregrine" to the list in CMakeLists.txt located at PX4-Autopilot/ROMFS/px4fmu_common/init.d-posix/airframes

Place "peregrine.main.mix" into PX4-Autopilot/ROMFS/px4fmu_common/mixers-sitl
add the line "peregrine.main.mix" to the list in CMakeLists.txt located at PX4-Autopilot/ROMFS/px4fmu_common/mixers-sitl

add "peregrine" to the list of models at approx line 94 of sitl_target.cmake located at PX4-Autopilot/platforms/posix/cmake
