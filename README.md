# myserial
boost串口读取 MPU9250 and ROS publish imu data，catkin，ubuntu14.04，ros indigo。

compile
$catkin_make

run
$roscore
$rosrun myserial myserialpub
or
$rosrun myserial pub_imu
$rostopic echo /imu
此时，实测 /imu频率只有30HZ,默认设置是60HZ。 

$rosrun myserial pub_imu_revised
$rostopic echo /imu
实测/imu达到60HZ.
