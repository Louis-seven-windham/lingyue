文件解释

一、1-10均为RobotArm的代码（机械臂）

1、ping.py：查询工作状态，读取舵机的工作状态 

2、read_write.py：从舵机内存控制表里读出数据和写数据到舵机内存控制表

3、read.py：从舵机内存控制表里读出数据

4、reg_write.py：异步写数据到舵机内存控制表

5、sync_read_write.py：同步向舵机内存控制表中读数据和写数据

6、sync_read.py：同步读取舵机内存控制表中的数据

7、sync_write.py：同步将数据写入舵机内存控制表

8、three_Inverse_kinematics.py：三连杆机械臂逆运动学算法，已知末端关节的位置和姿态（与X轴的夹角）求三个关节旋转的角度。

9、wheel.py：循环将数据写入舵机内存控制表中

10、write.py：将数据写入舵机内存控制表中

二、其他代码分别涉及颜色、面部、手势识别等计算机视觉

11.ColorDetection.py: 颜色识别

12.DangerSignRecognition.py: 危险信号识别

13.HandGesture.py: 手势识别

14.RoadSignRecognition: 巡线（路线识别）

15.YOLO.py: yolo算法（图像或视频中快速准确地识别和定位多个物体）
