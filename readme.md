
#### 数据集(Solomon)
    - 第一行：问题名称
    - 第五行：车辆信息(车辆数、capacity)
    - 从第十行开始：
        index    x coordinate     y coordinate   demand   earliest arrival   latest arrival    service time



#### vrppd
1. 车辆数    容量     速度
2. index  横坐标(x)   纵坐标(y)   需求量    最早到达时间    最晚到达时间   服务时间   pickup顺序    delivery顺序

    - 从仓位开始，index=0 
    - customers的index:1,2,3,....
    - 仓库:
        - 需求
        - 最早到达时间
        - 服务时间
        - pickup顺序
        - delivery顺序
        
      均为0
    - pickup顺序、delivery顺序对应的是index
      
