# Ackermann Steering Controller

Controller for the Ackermann steering drive mobile base. 

Detailed user documentation can be found in the controller's [ROS wiki page](http://wiki.ros.org/ackermann_steering_controller)

## Publish executed twist command

**cmd_vel_out** (geometry_msgs/TwistStamped)

Available when "publish_cmd" parameter is set to True. It is the Twist after limiters have been applied to the controller input.
