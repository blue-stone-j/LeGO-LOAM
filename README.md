# LeGO-LOAM-noted

* 原代码位置：https://github.com/RobustFieldAutonomyLab/LeGO-LOAM

* 论文名称：LeGO-LOAM Lightweight and Ground-Optimized Lidar Odometry and Mapping on Variable Terrain

* lego-LOAM论文介绍中文版：https://zhuanlan.zhihu.com/p/115986186

* 本文件所在目录为包，不是ros的工作空间；而且缺少一个原作者自定义的一个消息包

* 代码分析: https://blog.csdn.net/jiajiading/article/details/102776697

# file function
### imageProjection
receive cloud and project cloud to pseudo-image.

### featureAssociation
extract features and registrate(associate) to calculate frame-frame transformation

### mapOptmization
optimization using local map