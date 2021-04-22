# rgd_point
ROS Package based on C++ Script to change a sensor::msgs into a pcl::PointCloudXYZRGB Message

# Inputting the /Velodyne_points topic
$ rosrun rgd_point pub_pcl PointCloud:=/Velodyne_points

# Check the list of ROS Topic available
$ rostopic list 

# Save the ros topic in a pts file 
$ rostopic echo <topic> -p > <filename>.pts 

# Save the ros topic in a pcd file 
$ rostopic echo <topic> -p > <filename>.pcd 

# Save the ros topic in a csv file 
$ rostopic echo <topic> -p > <filename>.csv
 
