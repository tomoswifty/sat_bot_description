# sat_bot_description

## URDFを表示させ，Gazeboを起動する
```
ros2 launch sat_bot_description display.launch.py
```

## SLAMを実行してmapを表示させる
```
ros2 launch slam_toolbox online_async_launch.py
```

## voxel Markerを表示させる
```
ros2 run nav2_costmap_2d nav2_costmap_2d_markers voxel_grid:=/local_costmap/voxel_grid visualization_marker:=/my_marker
```

## navigationを実行する
```
ros2 launch nav2_bringup navigation_launch.py params_file:=/home/sugimoto/ros2_ws/src/sat_bot_description/config/nav2_params.yaml
```