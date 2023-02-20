># APJfile
## 获取固件
### 1.从`https://firmware.ardupilot.org/Plane/`下载对应的稳定版本和与飞控类型匹配的固件，应该需要梯子。[Ardupilot固件官网](https://firmware.ardupilot.org/Plane/)
### 2.在`http://www.nufeichuiyun.com/?page_id=121`看课时一与课时三，学会git和编译器的一些常用命令（其实不用记，问题不大）。[怒飞垂云](http://www.nufeichuiyun.com/?page_id=121)
##  ![Ardupilot](https://firmware.ardupilot.org/Tools/Logos/ArduPilot-Cleaned-Transparent.png)

# 控制的任务
## 获取视觉处理得到的投航点（`LI doing`）
## 侦察航线写入
### 1.从`MissionPlanner`获取侦察航线，`Home坐标`为已知量
### 2.侦察后的投靶点从视觉处理得到
## 投靶航线写入（`看代码`）运用了`相对坐标`
### 1.单个点逐个写入，再上传整条航线（需要相对坐标转GPS坐标）（有PPT的原理图）
### 2.根据当前模式来判断是否切入了投靶航线以及是否结束


# 学习
https://ardupilot.org/dev/docs/sitl-simulator-software-in-the-loop.html
https://ardupilot.org/dev/docs/ros.html
https://ardupilot.org/dev/docs/where-to-get-the-code.html
