仿真命令
roslaunch mcl_3dl test.launch map_pcd:=/home/xcy/Downloads/LOAM1/cloudGlobal.pcd use_bag_file:=true bag_file:=/home/xcy/catkin_ws/bigBagWithVideo2020-06-22-16-22-01.bag 
 
rosservice call /global_localization
