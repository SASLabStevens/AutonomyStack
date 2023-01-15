

## mocap inclusion

https://docs.px4.io/main/en/ros/external_position_estimation.html 
https://docs.px4.io/main/en/ros/offboard_control.html#on-board-processor-and-wifi-link-to-ros-recommended

VICON MoCap data-type ==> PX4 data-type (uORB topics)

we need to use MAVLink message to map the MoCap data into uORB topics.


The messages should be streamed at between 30Hz (if containing covariances) and 50 Hz.
If the message rate is too low, EKF2 will not fuse the external vision messages.

The following MAVLink "vision" messages are not currently supported by PX4:
GLOBAL_VISION_POSITION_ESTIMATE (opens new window), VISION_SPEED_ESTIMATE (opens new window), VICON_POSITION_ESTIMATE(opens new window)


## Reference Frames
PX4 uses FRD (X Forward, Y Right and Z Down) for the local body frame as well for the reference frame.
When using the heading of the magnetometer, the PX4 reference frame x axis will be aligned with north,
so therefore it is called NED (X North, Y East, Z Down). 
The heading of the reference frame of the PX4 estimator and the one of the external pose estimate will not match in most cases.
Therefore the reference frame of the external pose estimate is named differently, it is called MAV_FRAME_LOCAL_FRD.

## voxl <--> PX4 and (External UDP Mavlink Connections)
https://docs.modalai.com/voxl-vision-px4-telemetry/
All mavlink communication with PX4 is ultimately done over a **1Mbps UART** connection and the mavlink packet parsing
& error checking is accelerated & buffered by VOXL’s sDSP for ultra-efficient handling of large data rates. 
**Up to 16 simultaneous UDP** connection are supported at once!
