^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package sick_scan2
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.1.0 (2019-10-22)
-------------------
* First version of a ROS2 driver for the SICK TiM family.

0.1.1 (2019-10-22)
-------------------
* Integration Test for Bloom

0.1.2 (2019-10-22)
-------------------
* Porting to "Dashing"

0.1.7 (2020-04-16)
------------------
* retrial bloom release
* Merge pull request `#8 <https://github.com/SICKAG/sick_scan2/issues/8>`_ from clalancette/fixes
  Fixes for CMakeLists.txt to build on the buildfarm.
* Fixes for CMakeLists.txt to build on the buildfarm.
  A few things done in here:
  1.  Change CMake required version back to 3.5
  2.  Remove unnecessary dependency on pthreads
  3.  Remove duplicate boost dependency.
  4.  Make sure to find_package(diagnostic_updater) before use.
  Signed-off-by: Chris Lalancette <clalancette@openrobotics.org>
* Trying to figure out problem with the build farm
  build farm reports: 23:10:29 /usr/bin/ld: cannot find -lpthreads
* -pthread option added to build receipt
* Add pthreads dependancy
  This addition is triggered by reading
  'https://stackoverflow.com/questions/31948521/building-error-using-cmake-cannot-find-lpthreads'
* pthread dep. added to CMakeLists.txt
* removed unnecessary dependency from cmakelist.txt
* Contributors: Chris Lalancette, Michael Lehning

0.1.3 (2019-10-23)
-------------------
* Integration of TiM781 and TiM781S

0.1.6 (2020-04-16)
-------------------
* New retrial of bloom release

