^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package graph_msgs
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.2.1 (2026-08-03)
------------------
No message definitions changed in this release; it is CI, packaging and
licensing only.

* ci: unblock and broaden the ros2 matrix for Rolling/Resolute (`#20 <https://github.com/PickNikRobotics/graph_msgs/issues/20>`_)
  Set ``fail-fast: false``, move the rolling job to ``ROS_REPO: testing`` on
  Ubuntu Resolute and mark it non-blocking, and add jazzy, kilted and lyrical
  coverage. The matrix previously tested two of the five distros this branch
  ships to.
* Update GitHub Actions to use latest versions (`#18 <https://github.com/PickNikRobotics/graph_msgs/issues/18>`_)
* Update the build and format workflows (`#15 <https://github.com/PickNikRobotics/graph_msgs/issues/15>`_)
* Bump the minimum CMake version to 3.10
* Humble CI and formatting updates (`#10 <https://github.com/PickNikRobotics/graph_msgs/issues/10>`_)
* Add LICENSE file (`#9 <https://github.com/PickNikRobotics/graph_msgs/issues/9>`_)
* Contributors: Jafar Abdi, Nathan Brooks, Vatan Aksoy Tezer, mosfet80

0.2.0 (2021-09-14)
------------------
* Port to ROS 2 (`#5 <https://github.com/PickNikRobotics/graph_msgs/issues/5>`_)
* Contributors: Dave Coleman, Henning Kayser, Tyler Weaver, Vatan Aksoy Tezer

0.1.0 (2014-10-24)
------------------
* Added header / timestamp
* Contributors: Dave Coleman

0.0.3 (2014-05-30)
------------------
* Release to indigo
* Spelling fix
* Contributors: Dave Coleman

0.0.2 (2014-04-07)
------------------
* Initial commit
