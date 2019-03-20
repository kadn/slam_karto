1. karto_slam.launch  加入了 <param name="use_sim_time" value="true" />，然后在运行 bag时候 加上  --clock参数
2. karto_slam.launch  加入了 <rosparam command="load" file="$(find slam_karto)/config/mapper_params.yaml" />

