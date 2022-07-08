# Week2Agsignment
## Requirement  
pakename `wk2Assignment_3`
*  launch folder: contains launch files
*  scripts folder: contains your python code
* urdf folder: contains the model files describing your robot
* srv folder: contains your custom ROS services • msg folder: contains your custom ROS messages 
* CMakeLists.txt: list of cmake rules for compilation
* Package.xml: Package information and dependencies
### 1. Urdf xacro.py  
The tutorials can be found in [here](https://www.yuque.com/yulinlin-rf5a0/qfbvb9/xyctsx#E6cgE)
### 2. Service
1.  Service HomingSignal.srv: 指定docking station，面对的朝向 发出信息"My wk2Bot reaches the charging station located at (xx, xx)"   
2.  SetBugBehaviour.srv: 指定机器人移动速度  
## 3. Bug1 and Bug2  
name : `Bug1.py`  
name : `Bug2.py` 
并实现 client.py 选择模式
client.py实现选择算法bug1或bug2，在bug12中判断传的msg是否为true再决定要不要调用  
##  4.GoToPoint.py and followWall.py
go_to_point_switch和wall_follower_switch改srv的类型  
## 5.wk2AssignmentWorld.world
建世界,bug1 algorithm is better than Bug2 algorithm
