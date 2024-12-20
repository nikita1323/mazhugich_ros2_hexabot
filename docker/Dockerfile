# This is an auto generated Dockerfile for ros:desktop
# generated from docker_images_ros2/create_ros_image.Dockerfile.em
FROM ros:humble-ros-base-jammy

# install ros2 packages
RUN apt-get update && apt-get install -y --no-install-recommends \
    ros-humble-desktop=0.10.0-1* \
    && rm -rf /var/lib/apt/lists/*

RUN apt-get update && apt-get install -y \
    ros-humble-rviz2 \
    && ros-humble-turtle-tf2-py\
    && ros-humble-tf2-ros\
    && ros-humble-tf2-tools\
    && ros-humble-turtlesim \
    && rm -rf /var/lib/apt/lists/*

RUN echo "source /opt/ros/humble/setup.bash" >> /root/.bashrc