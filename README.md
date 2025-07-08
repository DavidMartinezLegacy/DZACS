# 🚀 DZACS

## 1️⃣ 项目简介
> 本项目是一个基于 **ROS Noetic** 开发的全国大学生智能汽车竞赛渡众车车对抗赛开源功能包，主要实现：

- 底盘控制（转向、云台、驱动电机等）
- 传感器数据采集与发布（雷达、IMU、轮速计、摄像头等）
- 建图与定位
- 导航与路径规划
- 裁判系统通信
- 地图保存
- 路径保存
- 靶标识别

---
## 2️⃣ 工作空间目录结构
```
|--dzacs
    |-- build
    |-- devel
    |-- src
        |--clear_costmap_recovery
        |--dzactuator
        |--dzjudgment
        |--dzsavepath
        |--move_base
        |--navigation_msgs
        |--resource
        |--rknn_pt
        |--rplidar_ros
    |-- README.md
    |-- CHANGELOG.rst
```
### 📌 各目录说明：
- **src/**：存放所有源码包的目录，主要包括自定义功能包与第三方依赖包。
- **build/**：编译过程中产生的中间文件目录。
- **devel/** ：存放开发环境设置、可执行文件等。
- **README.md**：项目说明文档，记录工作空间的搭建、功能描述等内容。
- **CHANGELOG.rst**:更新日志记录
[gmapping](https://wiki.ros.org/gmapping)
[move_base](https://wiki.ros.org/move_base)
[MapTools](https://github.com/6-robot/waterplus_map_tools)
