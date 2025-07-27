# ROS2 Humble Notes

These are the notes I've taken during my ROS2 learning journey. My main resources are the official [ROS2 Humble](https://docs.ros.org/en/humble/index.html) documentation and the [RoboticsBackEnd](https://www.youtube.com/@RoboticsBackEnd) YouTube channel.

---
## Workspaces:
* Add `concol_argcomplete.bash` to `~/.bashrc` (`source /path/concol_argcomplete.bash`)
* Run `colcon build` inside the `/path/workspace_name/src` directory 
* Add `setup.bash` to `~/.bashrc` (`source /path/workspace_name/install/setup.bash`)

## Packages:
* Command to create a pkg: `ros2 pkg create <pkg-name> <flags>`:
    * `--build-type`: `ament-python` or `ament-cmake`
* Always remember to add the description, maintainer, license and dependencies to the `package.xml` file.

