目录
├── CMakeLists.txt
├── launch
│   ├── amcl.launch.xml                  #启动amcl节点及参数配置
│   └── turtlebot3_navigation.launch     #启动turtlebot3，启动map_server，启动AMCL及设置参数，启动move_base及设置参数
├── maps                                 #地图目录
│   ├── map.pgm
│   └── map.yaml
├── package.xml
├── param                                #move_base参数定义
│   ├── base_local_planner_params.yaml   #TrajectoryPlannerROS参数设置
│   ├── costmap_common_params.yaml       #代价地图参数
│   ├── dwa_local_planner_params.yaml    #DWAPlannerROS参数设置
│   ├── global_costmap_params.yaml       #全局代价地图参数
│   ├── local_costmap_params.yaml        #本地代价地图参数
│   └── move_base_params.yaml            #导航参数
└── rviz
    └── turtlebot3_nav.rviz              #RVIZ设置
