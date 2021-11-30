# ROS2_driver_lidar
ROS2 (foxy) driver package for Lidar on Jetson


# Install dependencies
```
sudo apt-get update
sudo apt-get install -y libyaml-cpp-dev
sudo apt-get install -y libpcap-dev
```

# compile
``` 
git clone https://github.com/zhj-buffer/ROS2_driver_lidar.git
colcon build
```

# luanch
```
ros2 launch rslidar_sdk start.py
```
