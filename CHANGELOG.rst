^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package pcl_conversions
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.1.4 (2013-07-13)
------------------
* Fixup dependencies and CMakeLists.txt:

  * Added a versioned dependency on pcl, fixes `#1 <https://github.com/ros-perception/pcl_conversions/issues/1>`_
  * Added a dependency on pcl_msgs, fixes `#2 <https://github.com/ros-perception/pcl_conversions/issues/2>`_
  * Wrapped the test target in a CATKIN_ENABLE_TESTING check

0.1.3 (2013-07-13)
------------------
* Add missing dependency on roscpp
* Fixup tests and pcl usage in CMakeList.txt

0.1.2 (2013-07-12)
------------------
* small fix for conversion functions

0.1.1 (2013-07-10)
------------------
* Fix find_package bug with pcl

0.1.0 (2013-07-09 21:49:26 -0700)
---------------------------------
- Initial release
- This package is designed to allow users to more easily convert between pcl-1.7+ types and ROS message types
