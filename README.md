# install-ros2 problem and solution

### Ros2 Installation

_for the installation I followed the ROS2 Humble Hawksbill installation ._

1. Ros2 Humble Hawksbill installation [https://docs.ros.org/en/humble/Installation.html](https://docs.ros.org/en/humble/Installation.html)
 during the installation I run to this problem
   ```sh
   W: GPG error: http://packages.ros.org/ros2/ubuntu focal InRelease: The following signatures couldn't be verified because the public key is not available: NO_PUBKEY F42ED6FBAB17C654
E: The repository 'http://packages.ros.org/ros2/ubuntu focal InRelease' is not signed.
N: Updating from such a repository can't be done securely, and is therefore disabled by default.
N: See apt-secure(8) manpage for repository creation and user configuration details.

   ```
 the solution 
1. first update
   ```sh
   sudo apt update
   ```
2. install the build essential package
   ```sh
   sudo apt install build-essential
   ```
