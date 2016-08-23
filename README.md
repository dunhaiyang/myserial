# myserial
boost串口读取 MPU9250 and ROS publish imu data，catkin，ubuntu14.04，ros indigo。

compile
$catkin_make

run
$rosrun myserial myserialpub
or
$rosrun myserial pub_imu
$rostopic echo /imu
