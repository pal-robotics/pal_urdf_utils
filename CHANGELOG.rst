^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package pal_urdf_utils
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

2.6.1 (2026-04-07)
------------------
* Temporary fix for realsense mesh
* Contributors: Aina

2.6.0 (2026-03-30)
------------------
* Port realsense D435 and D455 to new Gazebo
* update depth camera
* New gazebo
* Contributors: thomas.peyrucain, thomaspeyrucain

2.5.5 (2026-03-11)
------------------
* remove system plugin from talos imu
* remove sensor plugin from all laser xacro gazebo
* remove sensors system plugin from model declaration
* Contributors: thomasung

2.5.4 (2026-01-29)
------------------
* Use package instead of find for meshes lookup
  This change avoids errors when visualizing the robot in rviz2 from a
  remote host instead of directly inside the robot
* Contributors: Noel Jimenez

2.5.3 (2026-01-26)
------------------
* use radians instead of degree to define angles
* Reapply "Merge branch 'tun/feat/update-sensor-gazebo' into 'humble-devel'"
  This reverts commit 1cb56a2ae5fe6d407cfa800d7deb3553e43aac79.
* Contributors: Noel Jimenez, thomasung

2.5.2 (2026-01-23)
------------------
* Revert "Merge branch 'tun/feat/update-sensor-gazebo' into 'humble-devel'"
  This reverts merge request !26
* Contributors: Noel Jimenez

2.5.1 (2026-01-22)
------------------
* small fix to prevent ghost obstacles
* remove gazebo version check property
* avoid duplicate definition of the camera config
* remove gazebo version parameter from macros
* set gazebo default version to classic for structure sensor
* migrate structure sensor to new gazebo
* add gazebo parameter to sick tim 571
* Contributors: thomasung

2.5.0 (2026-01-09)
------------------
* Migrate openni camera to new gazebo
* Contributors: Noel Jimenez

2.4.1 (2025-12-12)
------------------
* changing name mesh
* fixing laser
* Contributors: susannamastromauro

2.4.0 (2025-12-09)
------------------
* Adapt interaction_sensors and laser for new gazebo
* Contributors: Noel Jimenez

2.3.6 (2025-12-05)
------------------
* Fix xtion_pro_live mesh paths
* Use find for searching packages for meshes
* Contributors: Noel Jimenez

2.3.5 (2025-11-25)
------------------
* Merge branch 'omm/talos_imu_fix' into 'humble-devel'
  Added needed config so IMU follows ROS 2 conventions
  See merge request robots/pal_urdf_utils!21
* Added needed config so IMU follows ROS 2 conventions
* Contributors: Sai Kishor Kothakota, Óscar Martínez

2.3.4 (2025-11-11)
------------------
* Fix FT orientation
* Contributors: thomaspeyrucain

2.3.3 (2025-10-22)
------------------
* Fix gazebo ft sensor name
* Contributors: sofieblankers

2.3.2 (2025-08-28)
------------------
* Typo in t265 urdf
* Contributors: antoniobrandi

2.3.1 (2025-08-27)
------------------
* Update realsense_t265.urdf.xacro
* Contributors: antoniobrandi

2.3.0 (2025-08-27)
------------------
* update mesh
* add realsense t265
* add realsense cameras gazebo
* uniform realsense cameras
* Contributors: antoniobrandi

2.2.4 (2025-07-23)
------------------
* Add pi utils urdf
* Contributors: Aina Irisarri

2.2.3 (2025-07-07)
------------------
* fix collision tg30
* fix error not visualize laser model in rviz
* Contributors: andreacapodacqua

2.2.2 (2025-06-25)
------------------
* Fix meshes paths
* Contributors: Aina

2.2.1 (2025-06-18)
------------------
* Switch to gpu_ray due to an issue with the omni_base detecting its own collision boxes
* Contributors: thomaspeyrucain

2.2.0 (2025-06-17)
------------------
* support namespaces
* Contributors: antoniobrandi

2.1.1 (2025-06-12)
------------------
* fix ydlidar params
* Contributors: andreacapodacqua

2.1.0 (2025-06-04)
------------------
* Fix path for ft_sensor
* Fix camera gazebo
* Add cameras for talos
* Add talos ati and imu
* Add meshes folder in CMake
* Change path fro ft_sesnors
* Change path for both courier bases files
* Restructure meshes following urdf structure
* Reestructure urdf sensor
* Add pmb3 sensors
* Add sensor files for ari and specific bases
* Add imu urdf
* Update year
* Add imu sensor
* Add ft sensor files from pal_sea_arm_description
* Update path for tiago v1 ft sensor
* Change path for ftsensor ros2_control xacro
* Move sensors to pal_urdf_utils package
* Contributors: Aina

2.0.1 (2023-12-19)
------------------
* Add website tag
* Add xml version
* Contributors: Noel Jimenez

2.0.0 (2023-11-22)
------------------
* Merge branch 'port-to-ros2' into 'humble-devel'
  Port package.xml and CMakeLists.txt
  See merge request robots/pal_urdf_utils!2
* Change branch name in contributing
* add contributing.md
* Add licence
* Update extensions of files to .urdf.xacro
* Remove ament python dependency
* Port package.xml and CMakeLists.txt
* Contributors: David ter Kuile, davidterkuile

0.0.1 (2023-10-18)
------------------
* Merge branch 'feat/use_urdf_utils' into 'master'
  Remove unecessary files + update materials
  See merge request robots/pal_urdf_utils!1
* Add new color and adapt Orange
* Remove unecessary files + update materials
* wip testing
* fix plugin_imu
* wip testing
* add gazebo plugins
* project upload
* [empty] Initial commit
* Contributors: Jeremie Deray, Jordan Palacios, thomaspeyrucain
