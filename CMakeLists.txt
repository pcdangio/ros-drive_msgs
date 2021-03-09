cmake_minimum_required(VERSION 3.0.2)
project(drive_msgs)

# Find catkin and package dependencies.
find_package(catkin REQUIRED
  message_generation)

# Add message files.
add_message_files(
  FILES
  ackermann_state.msg)

# Generate messages.
generate_messages()

# Build catkin package.
catkin_package(CATKIN_DEPENDS message_runtime)