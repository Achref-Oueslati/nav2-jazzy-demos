# Navigation2 Tutorials and Demos

ROS 2 navigation examples and plugins, including costmap filters, GPS waypoint
following, LiDAR ground segmentation, pure-pursuit control, custom behavior and
planner plugins, and a sample robot description.

The examples are based on the official Nav2 documentation:
<https://docs.nav2.org/>.

Build from this directory in a ROS 2 Jazzy environment:

```bash
source /opt/ros/jazzy/setup.bash
rosdep install --from-paths . --ignore-src -r -y
colcon build --symlink-install
source install/setup.bash
```

Consult each package's launch files and configuration for its specific
simulation, hardware, and runtime requirements.

The GPS waypoint demo uses placeholder map-provider keys in its Mapviz
configuration. Add valid provider credentials locally before using tile maps.
